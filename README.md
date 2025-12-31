## Reactive Bongo Cat Animation in QMK Firmware 🐱⌨️

It defines:
- `process_record_user`
- `oled_task_user`
Make sure these functions are **not duplicated** elsewhere in your keymap.

You may need to disable features like:
- WPM counter
- RGB Matrix
- RGB Light

Credits:
- bongo frames: https://github.com/nwii/oledbongocat
- bongo sleep frame: https://in.pinterest.com/pin/2181499814087050/

Tested on **Corne split keyboard** with 128x32 OLED display
![demo](demo.gif)
