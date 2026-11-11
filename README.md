# assets

This is a holder repository for adding binary files via releases.

It should not have any actual files in the repo other than this README.md to highlight the files and their purpose, and how to pull them down easily.

## picoboot.bin

Atari boot sector code from [MyPicoDOS](https://github.com/HiassofT/MyPicoDOS), with a small BOOTQ fix ([MyPicoDOS PR 2](https://github.com/HiassofT/MyPicoDOS/pull/2)). Written to an ATR's boot sectors, it makes the disk boot straight into its program when mounted on FujiNet.

- [picoboot.bin](https://github.com/FujiNetWIFI/assets/releases/download/picobin/picoboot.bin)

## fb64.prg

CBM FileBrowser for the Commodore 64, by nbla000: a program launcher that lists a drive's directory and runs the program you pick. Put first on a C64 disk image, it is what FujiNet CONFIG's `LOAD"*",8,1` starts, so the disk boots into a menu of its programs. This is the copy FujiNet's IEC firmware carries in its flash (`data/webui/device_specific/BUILD_IEC/fb64` in fujinet-firmware).

- [fb64.prg](https://github.com/FujiNetWIFI/assets/releases/download/picobin/fb64.prg)
