# SPDX-License-Identifier: GPL-2.0-only
snd-intel-sst-core-y := sst.o sst_ipc.o sst_stream.o sst_drv_interface.o sst_loader.o sst_pvt.o
snd-intel-sst-pci-y += sst_pci.o
snd-intel-sst-acpi-y += sst_acpi.o

obj-$(CONFIG_SND_SST_ATOM_HIFI2_PLATFORM) += snd-intel-sst-core.o
obj-$(CONFIG_SND_SST_ATOM_HIFI2_PLATFORM_PCI) += snd-intel-sst-pci.o
obj-$(CONFIG_SND_SST_ATOM_HIFI2_PLATFORM_ACPI) += snd-intel-sst-acpi.o
