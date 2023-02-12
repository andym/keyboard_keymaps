- The "AlexDaigre" keymap is more sane then the default : https://imgur.com/a/k95XQlP

- https://config.qmk.fm/#/preonic/rev3_drop/LAYOUT_ortho_5x12
    - Downloaded a json file.
    - This will also build a .bin you can flash using the "qmk toolbox" if you want.
- Turn downloaded configurator json into keymap: `qmk json2c /Users/andym/projects/keyboard_keymaps/preonic/andym.json -o ./keyboards/preonic/keymaps/andym/keymap.c`
- Build with `qmk compile -kb preonic/rev3_drop -km andym`
- Flash with : `qmk flash ./preonic_rev3_drop_andym.bin`
