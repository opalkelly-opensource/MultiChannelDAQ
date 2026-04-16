The MultiChannelDAQ example app is a composite demonstration instrument that provides an 8 channel signal generator, and oscilloscope using the [XEM8320 ](https://opalkelly.com/products/xem8320/) and [SZG-MULTIDAQ](https://docs.opalkelly.com/syzygy-peripherals/szg-multidaq/).

## Compatibility

The MultiChannelDAQ app is compatible with the following FPGA module and peripheral combinations:

* XEM8320
  * [SZG-MULTIDAQ](https://docs.opalkelly.com/syzygy-peripherals/szg-multidaq/) - Note that this peripheral must be attached at Port D.

## Usage

The signal generator controls the output of the 8 channel DAC, and the oscilloscope captures and displays the input from up to 8 signal channels sampled by the ADC.

### Signal Generator

* Enable or disable any of the output channels with the corresponding switch.
* Set the frequency of the sinusoidal output signal for each channel.

### Oscilloscope

* Select the number of channels to sample with the ADC and display on the chart.

## Version History

* 1.0.0 (released 2026-04-14)
  * Initial release