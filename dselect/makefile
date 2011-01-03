# -*- make -*-
BASE=..
SUBDIR=dselect

# Bring in the default rules
include ../buildlib/defaults.mak

# DSelect interfacing directory
SOURCE = desc.apt names
TO = $(BUILD)/scripts/dselect
TARGET = program
include $(COPY_H)

# LOCAL = dselect
SOURCE = install.in update.in
TYPE = sh
include $(PODOMAIN_H)
