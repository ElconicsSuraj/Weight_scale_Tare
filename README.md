# Weight_scale_Tare
# Scale with Tare Button

This Arduino sketch allows you to interface a load cell with an HX711 amplifier and a button for taring the scale. The code utilizes the HX711 library for load cell operations.

## Purpose

The purpose of this code is to read weight measurements from the load cell and display them through the serial monitor. Additionally, a button is implemented to allow for taring the scale (setting the current weight as the zero reference) when pressed.

## Hardware Requirements

- Arduino board
- Load cell with HX711 amplifier
- Button connected to pin 5 (configured as INPUT_PULLUP)
- VCC connected to pin 2 (configured as OUTPUT)

## Setup

1. Connect the load cell and HX711 amplifier to the appropriate pins on your Arduino board.
2. Connect a button to pin 5 (with appropriate debouncing) to act as the tare button.
3. Connect VCC to pin 2 for power control.

## Usage

1. Upload the provided code to your Arduino board.
2. Open the serial monitor to view weight readings.
3. Press the button connected to pin 5 to perform tare operation (reset scale to zero).

Note: The calibration factor may need adjustment based on your load cell's specifications.

## Credits

This code is based on the HX711 library and the Arduino framework.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
