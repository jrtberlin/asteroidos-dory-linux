dvb-as102-objs := as102_drv.o as102_fw.o as10x_cmd.o as10x_cmd_stream.o \
		  as102_usb_drv.o as10x_cmd_cfg.o

obj-$(CONFIG_BACKPORT_DVB_AS102) += dvb-as102.o

ccflags-y += -I$(backport_srctree)/drivers/media/dvb-core
ccflags-y += -I$(backport_srctree)/drivers/media/dvb-frontends
