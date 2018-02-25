obj-m += list_net_devices.o
all: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
