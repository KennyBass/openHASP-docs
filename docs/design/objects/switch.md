# Switch
**obj:`switch`**

![lv_switch](./images/lv_ex_switch_1.png)

| Property   | Value      | Default | Description
|------------|------------|---------|---------------
| val        | [bool][2]  | 0       | `1` = on, `0` = off
| bg_color10 | [color][1] | 0       | changes indicator color
| bg_color20 | [color][1] | 0       | changes knob color
| radius20   | [int16][9]      | depends<BR>on theme | changes knob corner radius (also see [radius](#common-properties))

???+ example "Example `jsonl`"
    ```json linenums="1"
    {"page":1,"id":4,"obj":"switch","x":125,"y":145,"w":105,"h":55,"radius":15}
    ```
Events generated by switch are similar to the ones generate by the _toggle_ buttons.

   
[1]: ../../data-types/#colors
[2]: ../../data-types/#boolean
[3]: ../../../configuration/gpio/#groupid
[4]: ../../styling/#general
[5]: ../../styling/#image
[6]: ../../styling/#value
[7]: ../../styling/#line
[8]: ../../styling/#scale
[9]: ../../data-types/#integer
[10]: ../../data-types/#string
[11]: ../../data-types/#json-object
[12]: ../../styling/
[13]: ../../styling/#padding-and-margin
[14]: ../../styling/#text
[15]: ../../data-types/#variables
[16]: https://lvgl.io/tools/imageconverter
[17]: ../../../integrations/home-assistant/sampl_conf/#using-tags
[18]: ../../styling/#parts