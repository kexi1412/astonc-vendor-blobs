# astonc vendor crypto blobs (private)

Vendor ELF files needed by the AERA / OrangeFox recovery ramdisk on
OnePlus Ace 3 (astonc, PJE110, SM8550) for FBE decryption.

Source: extracted from the working OrangeFox recovery image
(orangefox-opace3-android16-rkbkosp.img). Every file's SHA256 matches the
device tree's config/crypto-inputs.json manifest (36/36), so this is the
same ROM-derived asset set the OrangeFox bring-up was validated against.

Layout mirrors the ramdisk destination (/vendor/...); the build copies this
tree over recovery/root/vendor/ before packaging.

These are OEM/QTI proprietary binaries. Keep this repository private.
