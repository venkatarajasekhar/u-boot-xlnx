#
# (C) Copyright 2010,2011 Nvidia Corporation.
#
# (C) Copyright 2000-2008
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# SPDX-License-Identifier:	GPL-2.0+
#

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-y += cpu.o
else
obj-$(CONFIG_CMD_ENTERRCM) += cmd_enterrcm.o
endif

obj-y += ap.o
obj-y += board.o
obj-y += cache.o
obj-y += clock.o
obj-y += lowlevel_init.o
obj-y += pinmux-common.o
obj-y += powergate.o
obj-y += xusb-padctl.o
obj-$(CONFIG_DISPLAY_CPUINFO) += sys_info.o
obj-$(CONFIG_TEGRA124) += vpr.o

obj-$(CONFIG_TEGRA20) += tegra20/
obj-$(CONFIG_TEGRA30) += tegra30/
obj-$(CONFIG_TEGRA114) += tegra114/
obj-$(CONFIG_TEGRA124) += tegra124/