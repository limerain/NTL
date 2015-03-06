#
# Makefile for the linux nmfs routines.
#
#
# 가나다라마바사아자차카타파하

obj-y += nmm.o
obj-y += nmfs.o

file-mmu-y := file-nommu.o
file-mmu-$(CONFIG_MMU) := file-mmu.o
nmfs-objs += inode.o $(file-mmu-y)
