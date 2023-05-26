# Simply expanded variables
# ARCH:=$(shell arch)
# CWD:=$(shell pwd) 
# OS:=$(shell uname) 
# Recursively Expanded Variables 
ifndef CROSS_COMPILE
override CROSS_COMPILE=
endif
CFLAGS = -g -Wall  

write:
	$(CROSS_COMPILE)gcc $(CFLAGS) -o writer writer.c

clean:
	rm -f writer

all:
	rm -f writer
	aarch64-none-linux-gnu-gcc $(CFLAGS) -o writer writer.c

