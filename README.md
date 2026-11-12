# lab_8010diadapter
I designed this DI box, which mounts directly onto the back of a Genelec 8010, for use during synthesizer development and workshops. It supports both line-level and Eurorack-level signals and includes a ground-lift function, helping to prevent damage to your speakers while you’re testing synthesizers. I have now made it open-source.

<img src="https://github.com/kevinkewang/lab_8010diadapter/blob/main/images/IMG_2983.jpg" width="60%" alt="8010 DI adapter">

## Main features:
* The rotary switch offers four settings: Mute, -38dB (for Eurorack-level signals), -20dB, and Pass-through.
* When the rotary switch is set to "Mute," the indicator light can show the presence of a signal.
* The "Ground Lift" switch allows for the disconnection of the ground line, which can help eliminate noise in certain scenarios.
* A 10K:600 transformer is used for isolation, providing protection for your speakers.

## Schematics
**The component values in the PDF may be incorrect; please refer to the BOM table instead.**
https://github.com/kevinkewang/lab_8010diadapter/blob/main/hardware_design/circuit.pdf

## PCB
<img src="https://github.com/kevinkewang/lab_8010diadapter/blob/main/images/pcb.png" width="60%" alt="8010 DI adapter">

## Bill of materials
| Designator       | Qty | Value               | Description                     | Mouser Part No.                              |
|------------------|-----|---------------------|---------------------------------|----------------------------------------------|
| **PTH parts**    |     |                     |                                 |                                              |
| T1               | 1   | 10K:600             | audio transformer               |                                              |
| SW1              | 1   | ALPHA-SR1712F-0204  | rotary switch                   | 105-SR1712F-24NS                             |
| SW2              | 1   |                     | switch                          |                                              |
| J1               | 1   | 3.5mm Jack WQP518MA | Thonkiconn – 3.5mm Jack Sockets | https://www.thonk.co.uk/shop/thonkiconn/     |
| X1               | 1   | Neutrik XLR Jack    | Neutrik NC3MAAV                 | 568-NC3MAAV                                  |
| LED1             | 1   | Kingbright WP937EGW | RED/GREEN DIFFUSED 2-LEAD       | 604-WP937EGW                                 |
| C1               | 1   | 10uF ±10% 63V       | Film Capacitor                  | 871-B32522C106K                              |
| C2               | 1   | 10nF ±5% 50V        | Through-hole MLCC capacitor     | 594-K103J20C0GF5TH5                          |
| R1               | 1   | 620 Ohms            | 1/4W Through-Hole Resistor      | Resistor for LED                             |
| R4               | 1   | 51 Ohms             | 1/4W Through-Hole Resistor      | Resistor for Ground Lift                     |
| R5, R6           | 1   | 9.1kΩ               | 1/4W Through-Hole Resistor      | −38dB T-pad attenuation                      |
| R7               | 1   | 1kΩ                 | 1/4W Through-Hole Resistor      | −38dB T-pad attenuation                      |
| R8, R9           | 1   | 4.02kΩ              | 1/4W Through-Hole Resistor      | −20dB T-pad attenuation                      |
| R10              | 1   | 10kΩ                | 1/4W Through-Hole Resistor      | −20dB T-pad attenuation                      |
| **Mount parts**  |     |                     |                                 |                                              |
| nylon spacer     | 4   | M4 x 8mm x 1mm      |                                 |                                              |
| nylon spacer     | 4   | 4.2mm x 7mm x 5mm   |                                 |                                              |
| screw            | 4   | M4 x 16mm           |                                 |                                              |


## License
**The lab_8010diadapter project is made available under a CC-BY-NC-SA-3.0 license.**

If you want to make a few cases for your own use, go ahead and make them. If you're a synth studio and want to use them for product testing/demonstration etc, that's also welcome as long as it doesn't involve selling these directly. **Please do not make and sell these in bulk.**

## Links
Official website:  https://bitiworkshop.com/

Purchase here: https://store.bitiworkshop.com/



