# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_NVME_CORE)			+= nvme-core.o
obj-$(CONFIG_BLK_DEV_NVME)		+= nvme.o
obj-$(CONFIG_NVME_FABRICS)		+= nvme-fabrics.o
obj-$(CONFIG_NVME_RDMA)			+= nvme-rdma.o
obj-$(CONFIG_NVME_FC)			+= nvme-fc.o
obj-$(CONFIG_NVME_LPM_BACKUP)		+= nvme-lpm.o

nvme-core-y				:= core.o
nvme-core-$(CONFIG_NVM)			+= lightnvm.o

nvme-y					+= pci.o

nvme-fabrics-y				+= fabrics.o

nvme-rdma-y				+= rdma.o

nvme-fc-y				+= fc.o

nvme-lpm-y				+= pci-lpm.o
