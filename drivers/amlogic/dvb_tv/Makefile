#
# Makefile for the DVB driver.
#

obj-$(CONFIG_AM_DVB) += aml.o

aml-objs=aml_dvb.o aml_dmx.o aml_fe.o

obj-$(CONFIG_AM_CI) += amlci/

obj-$(CONFIG_AM_MXL101) += mxl101/

obj-$(CONFIG_AM_AVL6211) += avl6211/

obj-$(CONFIG_AM_SI2168) += si2168/

#obj-$(CONFIG_AM_ITE9133) += ite9133/

obj-$(CONFIG_AM_ITE9173) += ite9173/

obj-$(CONFIG_AM_M6_DEMOD) += amldemod/

obj-$(CONFIG_AM_SI2176) += si2176/
obj-$(CONFIG_AM_SI2196) += si2196/
obj-$(CONFIG_AM_CTC703) += cresta/
obj-$(CONFIG_AM_ATBM8869) += atbm887x/
obj-$(CONFIG_AM_SI2177) += si2177/
obj-$(CONFIG_AM_DIBCOM8096) += dibcom8096/

EXTRA_CFLAGS += -I.