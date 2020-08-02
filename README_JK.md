- Edit the keymap file `keyboards/kyria/keymaps/jkrasnay/keymap.c`
- Run `bin/qmk compile -kb kyria -km jkrasnay` to build the firmware
-

To flash, you need the QMK Toolbox gui app installed. Run the app and
specify `/Users/john/ws/qmk_firmware/kyria_rev1_jkrasnay.hex` and select
`atmega32u4` (it remembers these settings on subsequent uses).

Press the reset button on the side of the master keyboard and click the
Flash button in QMK Toolbox WITHIN EIGHT SECONDS.
