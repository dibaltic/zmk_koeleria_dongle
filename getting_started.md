1) [Fork this repository](https://github.com/dibaltic/zmk_koeleria_dongle/fork)
2) Enable actions on your fork. (click on the actions tab and enable actions)
3) Edit the `zmk_koeleria_dongle/config/koeleria.keymap` file (See the [ZMK Codes reference](https://zmk.dev/docs/codes))
4) When you push the changes an action will start that builds your firmware. If the action is successful the file will be available from the artifacts within job summary. Check the [ZMK docs](https://zmk.dev/docs/user-setup#installing-the-firmware) if you need more information.

If you'd like to use [nickcoutsos keymap editor](https://nickcoutsos.github.io/keymap-editor/) I've found the hummingbird layout to work with this keyboard in the editor. 
> Note: I have the firmware setup for a nice!nano v2 compatible controller as the dongle. If you opt to use a different MCU for your dongle you will need to change the [build.yaml](https://github.com/dibaltic/zmk_koeleria_dongle/blob/main/build.yaml) dongle board to the board you are intending to use. 
