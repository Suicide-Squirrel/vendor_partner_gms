# vendor_gapps
Android 10 ARM64 GAPPS

To build your GAPPS in your rom simply include:

vendor/gapps/common/common-vendor.mk

into your device makefile.

e.g:

$(call inherit-product-if-exists, vendor/gapps/common/common-vendor.mk)

or

-include vendor/gapps/common/common-vendor.mk

