#
# Makefile for the cgroup-aware proc filesystem routines.
#
obj-m += procg.o

procg-objs := root.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean