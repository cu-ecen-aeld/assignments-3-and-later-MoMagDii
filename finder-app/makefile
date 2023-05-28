# Simply expanded variables
# ARCH:=$(shell arch)
# CWD:=$(shell pwd) 
# OS:=$(shell uname) 
# Recursively Expanded Variables 
ifndef CROSS_COMPILE
override CROSS_COMPILE=aarch64-none-linux-gnu-
endif
CFLAGS = -g -Wall  

write:
	$(CROSS_COMPILE)gcc $(CFLAGS) -o writer writer.c

clean:
	rm -f writer

all:
	$(CROSS_COMPILE)gcc $(CFLAGS) -o writer writer.c


