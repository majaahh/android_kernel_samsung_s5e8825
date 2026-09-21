# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_SEC_A25X_PROJECT) += \
    a25x/a25x_eur_open_w00_r00.dtbo \
    a25x/a25x_eur_open_w00_r01.dtbo \
    a25x/a25x_eur_open_w00_r02.dtbo \
    a25x/a25x_eur_open_w00_r04.dtbo \
    a25x/a25x_eur_open_w00_r05.dtbo

targets += dtbs
always-y := $(dtbo-y)

dtbs: $(addprefix $(obj)/, $(dtbo-y))

clean-files := *.dtbo*
