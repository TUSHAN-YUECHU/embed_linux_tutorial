

KERNEL_DIR = /home/embedfire/linux4.19

obj-m := led_pdev.o led_pdrv.o

all:modules
modules clean:
	$(MAKE) -C $(KERNEL_DIR) M=$(shell pwd) $@



