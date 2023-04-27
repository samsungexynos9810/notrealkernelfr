# SPDX-License-Identifier: GPL-2.0
# dtbo-y += samsung/exynos9820-d1_eur_open_21.dtbo
# dtbo-y += samsung/exynos9820-d1_eur_open_22.dtbo
# dtbo-y += samsung/exynos9820-d1_eur_open_19.dtbo
# dtbo-y += samsung/exynos9820-d1_eur_open_18.dtbo
# dtbo-y += samsung/exynos9820-d1_eur_open_23.dtbo
# dtb-y += exynos/exynos9825.dtb

dtb-$(CONFIG_SOC_EXYNOS9810) += \
				exynos/exynos9810-crownlte_eur_open_26.dtb \
				exynos/exynos9810-star2lte_eur_open_26.dtb \
				exynos/exynos9810-starlte_eur_open_26.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
