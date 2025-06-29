# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	orangepi-cm5-blink-gpio.dtbo \
	orangepi-cm5-cam1.dtbo \
	orangepi-cm5-cam2.dtbo \
	orangepi-cm5-cam3.dtbo \
	orangepi-cm5-cam4.dtbo

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
	README.rockchip-overlays

targets += $(dtbo-y) $(dtbotxt-y)

always-y		:= $(dtbo-y) $(dtbotxt-y)
clean-files		:= *.dtbo