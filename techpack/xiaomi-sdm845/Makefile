ifeq ($(CONFIG_MACH_XIAOMI_SDM845),y)
obj-y += fingerprint/
obj-y += gps/
obj-$(CONFIG_HALLS)    += halls/
obj-$(CONFIG_NEW_LEDS) += leds/
obj-y += mfd/
obj-$(CONFIG_POWER_SUPPLY) += power_supply/
obj-$(CONFIG_REGULATOR) += regulator/
obj-$(CONFIG_INPUT_TOUCHSCREEN) += touchscreen/
else
ccflags-y := -Wno-unused-function
obj-y := stub.o
endif
