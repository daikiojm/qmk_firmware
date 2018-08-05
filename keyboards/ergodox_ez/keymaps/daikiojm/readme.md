# ErgoDox EZ daikiojm Keymap Configuration

## Changelog

* August 7, 2018:
  * create daikiojm keymap.

## How to build

```bash
# in project root
$ docker build -t qmk_firmware .
$ docker run -e keymap=default -e keyboard=ergodox_ez --rm -v (pwd):/qmk:rw qmk_firmware
```
