#
# Makefile for the sensor drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_SENSORS_SSP)		+= ssp_dev.o ssp_i2c.o ssp_data.o ssp_sysfs.o\
						ssp_input.o ssp_firmware.o ssp_debug.o
obj-$(CONFIG_SENSORS_SYSFS)		+= sensors_core.o

obj-$(CONFIG_IIO)			+= ssp_iio_ring.o ssp_iio_trigger.o

obj-$(CONFIG_SENSORS_SSP_ICM20610)	+= factory/accel_icm20610.o factory/gyro_icm20610.o
obj-$(CONFIG_SENSORS_SSP_MPU6500)	+= factory/accel_mpu6500.o factory/gyro_mpu6500.o
obj-$(CONFIG_SENSORS_SSP_BMI058)	+= factory/accel_bmi058.o factory/gyro_bmi058.o
obj-$(CONFIG_SENSORS_SSP_YAS532)	+= factory/magnetic_yas532.o
obj-$(CONFIG_SENSORS_SSP_AK09911)	+= factory/magnetic_ak09911.o

obj-$(CONFIG_SENSORS_SSP_CM3320)	+= factory/light_cm3320.o
obj-$(CONFIG_SENSORS_SSP_MAX88920)	+= factory/prox_max88920.o factory/gesture_max88920.o
obj-$(CONFIG_SENSORS_SSP_MAX88921)	+= factory/light_max88921.o factory/prox_max88920.o\
					factory/gesture_max88922.o
obj-$(CONFIG_SENSORS_SSP_TMG399X)	+= factory/light_tmg399x.o factory/prox_tmg399x.o factory/gesture_tmg399x.o
obj-$(CONFIG_SENSORS_SSP_BMP182)	+= factory/pressure_bmp182.o
obj-$(CONFIG_SENSORS_SSP_LPS25H)	+= factory/pressure_lps25h.o
obj-$(CONFIG_SENSORS_SSP_SHTC1)		+= factory/temphumidity_shtc1.o

obj-$(CONFIG_SENSORS_SSP_STM32F401)	+= factory/mcu_stm32f401.o

obj-$(CONFIG_SENSORS_SSP_MOBEAM)	 += factory/barcode_emul_tmg3992.o

obj-$(CONFIG_SENSORS_SSP_SENSORHUB)	+= ssp_sensorhub.o ssp_misc.o
obj-$(CONFIG_SENSORS_MAX86900) += max86900.o
obj-$(CONFIG_SENSORS_MAX86902) += max86902.o
obj-$(CONFIG_SENSORS_MAX_NOTCHFILTER) += max_notchfilter/
obj-$(CONFIG_SENSORS_ADPD142)  += adpd142.o

obj-$(CONFIG_SENSORS_SSP_BBD)           += ssp_bbd.o factory/mcu_bcm4773.o
obj-$(CONFIG_SENSORS_SSP_BBD)           += bbdpl/
