# Digital load
This is a digital load circuit, project is WIP.
Intended features are:
- USB type-C connector with USB-2.0 supply (5V 500mA)
- Oled display to show current setting (and maybe other stuff)
- Encoder wheel to change current value
- Ability to stack several circuit (only one with screen, encoder, and usb supply) which will communicate through I2C and share the load (to reach higher current load)
- Maximum current and voltage are to be determined, current will probably be on the order of 1 to 5 amps max, ~1uA min
- Several sense resistors to increase dynamic range.
- USB serial interface, maybe to control from computer and read measured current points, this would allow to specify curve for the load for instance, if there's a use for it.

# Screenshots

![Render of the WIP board (top)](https://user-images.githubusercontent.com/6578006/164995171-83aff471-13d9-422e-bfa7-a72b0c995981.jpg)

![Render of the WIP board (perspective)](https://user-images.githubusercontent.com/6578006/164995175-26a30472-c773-4804-bde0-5d0d12f0daee.jpg)

