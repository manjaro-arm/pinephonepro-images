# Manjaro ARM Pinephone Pro
[![iso_build](https://github.com/manjaro-arm/pinephonepro-images/workflows/image_build_all/badge.svg)](https://github.com/manjaro-arm/pinephonepro-images/actions)

## description

Release Branch for Manjaro ARM images for the Pinephone Pro

## where can I download an iso?

Images are build and uploaded in a relatively regular interval to [github releases](https://github.com/manjaro-arm/pinephonepro-images/releases)

## sources

- [image profile](https://github.com/manjaro-pinephone/arm-profiles)

## building

1. check out the arm-profiles
2. `sudo buildarmimg -d pinephonepro -e $EDITION`

## Disclaimer

These images have **not** been confirmed to work from the eMMC yet! So flashing it to the eMMC (local storage) is not advised at this time.
