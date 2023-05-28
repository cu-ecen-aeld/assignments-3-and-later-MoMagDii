# Simply expanded variables
# ARCH:=$(shell arch)
# CWD:=$(shell pwd) 
# OS:=$(shell uname) 
# Recursively Expanded Variables 
all :
	$(CC) $(CFLAGS) $(INCLUDES) $(OBJS) writer.c -o writer $(TARGET) $(LDFLAGS)

CROSS_COMPILE :
	aarch64-none-linux-gnu-gcc writer.c -o writer

clean :
	rm -f writer
