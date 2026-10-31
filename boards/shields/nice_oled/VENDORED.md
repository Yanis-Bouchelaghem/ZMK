# Vendored: zmk-nice-oled

Copied from https://github.com/mctechnology17/zmk-nice-oled at commit
`46f824abb2bd41f1287c5c68abd14122af6042a3` (`boards/shields/nice_oled`, MIT, see `LICENSE`).
Font `.ttf` sources and the symlinked README were not copied (not needed to build).

Local changes:
- `assets/balloon.c`: stock ZMK nice!view balloon art (MIT, ZMK contributors), cropped to 124x68.
- `Kconfig.defconfig`, `CMakeLists.txt`, `widgets/animation.c`: new option
  `CONFIG_NICE_OLED_WIDGET_STATIC_IMAGE_PERIPHERAL_BALLOON` to show it on the peripheral.
