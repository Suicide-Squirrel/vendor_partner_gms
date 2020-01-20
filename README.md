# vendor_gapps
Android 10 ARM64 GAPPS

To build your GAPPS in your rom simply include:

vendor/partner_gms/products/gms.mk

into your device makefile.

e.g:

$(call inherit-product-if-exists, vendor/partner_gms/products/gms.mk)

or

-include vendor/partner_gms/products/gms.mk
