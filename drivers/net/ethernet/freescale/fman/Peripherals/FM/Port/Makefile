#
# Makefile for the Freescale Ethernet controllers
#
EXTRA_CFLAGS           += -DVERSION=\"\"
#
#Include netcomm SW specific definitions
include $(srctree)/drivers/net/ethernet/freescale/fman/ncsw_config.mk

NCSW_FM_INC = $(srctree)/drivers/net/ethernet/freescale/fman/Peripherals/FM/inc

EXTRA_CFLAGS += -I$(NCSW_FM_INC)

obj-y		+= fsl-ncsw-Pcd.o

fsl-ncsw-Pcd-objs	:=   fm_port.o fm_port_im.o fman_port.o
