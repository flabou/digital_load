# Digital load
This is a digital load circuit, project is WIP.
Intended features are:
- USB type-C connector with USB-2.0 supply (5V 500mA)
- Oled display to show current setting (and maybe other stuff)
- Encoder wheel with push-button to change current value
- Ability to connect several circuit (only one with screen, encoder, and usb supply) which will communicate through I2C and share the load (to reach higher current load)
- Several sense resistors to increase dynamic range.
- Maximum current and voltage are to be determined, current will probably be on the order of 1 to 5 amps max, ~1uA min
- USB serial interface, maybe to control from computer and read measured current points, this would allow to specify curve for the load for instance, if there's a use for it.

# Screenshots

![Render of the board (top)](https://user-images.githubusercontent.com/6578006/166560043-6502cc62-ee9e-46e9-b125-2c3724788105.jpg)

![Render of the board (perspective)](https://user-images.githubusercontent.com/6578006/166560036-8f704180-4acc-408f-a2fd-6e55481118e4.jpg)

