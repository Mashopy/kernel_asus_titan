ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2/msm_vb2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/camera
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
obj-$(CONFIG_MSMB_CAMERA) += cci/ io/ csiphy/ csid/ actuator/ eeprom/ ois/ flash/ ir_led/ ir_cut/ 
ifdef CONFIG_MACH_ASUS_ZE620KL
obj-$(CONFIG_MSMB_CAMERA) += laser_led/
obj-$(CONFIG_MSMB_CAMERA) += ois-onsemi/
obj-$(CONFIG_MSM_CAMERA_SENSOR) += fac_camera.o
endif
ifdef CONFIG_MACH_ASUS_ZE554KL
obj-$(CONFIG_MSMB_CAMERA) += laser_led/
obj-$(CONFIG_MSMB_CAMERA) += ois-onsemi_ZE554KL/
obj-$(CONFIG_MSM_CAMERA_SENSOR) += fac_camera_ZE554KL.o
endif
obj-$(CONFIG_MSM_CAMERA_SENSOR) += msm_sensor_init.o msm_sensor_driver.o msm_sensor.o 
