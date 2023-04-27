# SPDX-License-Identifier: GPL-2.0
# dtb-y += exynos/exynos9820.dtb
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_25.dtbo
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_18.dtbo
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_24.dtbo
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_17.dtbo
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_19.dtbo
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_20.dtbo
# dtbo-y += samsung/exynos9820-beyond0lte_eur_open_22.dtbo

dtb-$(CONFIG_SOC_EXYNOS9810) += \
				exynos9810-crownlte_eur_open_26.dtb \
				exynos9810-star2lte_eur_open_26.dtb \
				exynos9810-starlte_eur_open_26.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
