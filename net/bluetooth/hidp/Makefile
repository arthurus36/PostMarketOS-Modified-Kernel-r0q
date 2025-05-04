# SPDX-License-Identifier: GPL-2.0-only
#
# Makefile for the Linux Bluetooth HIDP layer
#

# Object files
obj-$(CONFIG_BT_HIDP) += hidp.o

# Source files
hidp-objs := core.o sock.o

# More Flags Obviously
KCFLAGS += -Wall -Wextra -Wunused -Wstrict-prototypes -Wno-trigraphs
KCFLAGS += -Wdeclaration-after-statement -Werror-implicit-function-declaration
KCFLAGS += -Wno-format-security
KCFLAGS += -Wvla
KCFLAGS += -Wno-int-to-pointer-cast
KCFLAGS += -Wno-pointer-to-int-cast
KCFLAGS += -Wno-address-of-packed-member
KCFLAGS += -Wno-format-nonliteral
KCFLAGS += -Wframe-larger-than=2048
KCFLAGS += -Wno-maybe-uninitialized
KCFLAGS += -Wno-array-bounds
KCFLAGS += -Wno-format-zero-length
KCFLAGS += -Wno-missing-field-initializers
KCFLAGS += -Wno-missing-include-dirs
KCFLAGS += -Wno-pointer-sign
KCFLAGS += -Wno-sign-compare
KCFLAGS += -Wno-unused-parameter
KCFLAGS += -Wno-unused-variable
