#
# Makefile for the touchscreen drivers.
#

# Each configuration option enables a list of files.
#obj-$(CONFIG_TOUCHPANEL_FOCAL) += focal_common.o
#obj-$(CONFIG_TOUCHPANEL_FOCAL_FT8006) += FT8006/
#obj-$(CONFIG_TOUCHPANEL_FOCAL_FT3518) += ft3518/


obj-$(CONFIG_TOUCHPANEL_FOCAL_FT3518) += ft3518/
obj-$(CONFIG_TOUCHPANEL_FOCAL_FT3658U) += ft3658u/
obj-$(CONFIG_TOUCHPANEL_FOCAL_FT3658U_SPI) += ft3658u_spi/
obj-$(CONFIG_TOUCHPANEL_FOCAL_FT3681) += ft3681/

oplus_bsp_tp_focal_common-y += focal_common.o
obj-$(CONFIG_TOUCHPANEL_FOCAL) += oplus_bsp_tp_focal_common.o
#endif
