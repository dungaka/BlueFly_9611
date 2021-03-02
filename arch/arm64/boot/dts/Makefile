# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos9610.dtb
dtbo-$(CONFIG_EXYNOS9611_A51) += \
	samsung/exynos9611-a51_eur_open_03.dtbo \
	samsung/exynos9611-a51_eur_open_00.dtbo \
	samsung/exynos9611-a51_eur_open_01.dtbo \
	samsung/exynos9611-a51_eur_open_07.dtbo

dtbo-$(CONFIG_EXYNOS9611_M31) += \
	samsung/exynos9611-m31_eur_open_00.dtbo \
	samsung/exynos9611-m31_eur_open_01.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
