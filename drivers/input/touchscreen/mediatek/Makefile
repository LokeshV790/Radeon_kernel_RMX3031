subdir-ccflags-y += -Werror
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include
# In case the platform does NOT support this type of sensors
obj-y   +=  mtk_tpd.o
obj-y   +=  tpd_button.o
obj-y   +=  tpd_calibrate.o
obj-y   +=  tpd_debug.o
obj-y   +=  tpd_default.o
obj-y   +=  tpd_misc.o
obj-y   +=  tpd_setting.o
obj-$(CONFIG_TOUCHSCREEN_MTK_SOLOMON)	+=  SOLOMON/
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_touch/
obj-$(CONFIG_TOUCHSCREEN_MTK_GT1151)	+=  GT1151/
obj-$(CONFIG_TOUCHSCREEN_MTK_GT911)	+=  GT911/
obj-$(CONFIG_TOUCHSCREEN_MTK_GSLX680)	+=  gslX680/
obj-$(CONFIG_TOUCHSCREEN_MTK_NT36xxx)	+=  NT36xxx/
obj-$(CONFIG_TOUCHSCREEN_MTK_GT9XX_LM)	+=  GT9XX_LM/
obj-$(CONFIG_TOUCHSCREEN_FT5X26)	+=  FT5X26/
obj-$(CONFIG_TOUCHSCREEN_MTK_GT5688)	+=  GT5688/
obj-$(CONFIG_TOUCHSCREEN_HIMAX_I2C)	+=  hxchipset/
obj-$(CONFIG_TOUCHSCREEN_MTK_FOCALTECH_FHD)	+=  focaltech_fhd_touch/

# Tongxing.Liu@ODM_WT.BSP.Touchscreen.Base,2019/10/04,bringup add for xl and hlt touchscreen mould config.
obj-y      += tp_usb_notifier.o
obj-y      += update_tpfw_notifier.o
obj-$(CONFIG_INPUT_TOUCHSCREEN)      += headset_notifier.o
obj-$(CONFIG_TOUCHSCREEN_NT36xxx_HOSTDL_SPI)	 += NT36525B/
obj-$(CONFIG_TOUCHSCREEN_ILI9881H)	 += ili9881h/
