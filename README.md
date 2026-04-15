![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg) ![](../../workflows/fpga/badge.svg)

# TinyTapout H DC motor H bridge control

- [Read the documentation for project](docs/info.md)

This project is done to help students understand how to build a Tiny Tapeout circuit from the idea to a manufactured circuit on a real chip.

In this example, we explain the workflow for obtaining the GDS files, starting with the Wokwi template, drawing the logic cronogram, arriving at GitHub, and generating the manufacturing files.

This is a Wokwi tutorial project. All the needed information is in the [info.yaml](info.yaml). Change the `wokwi_id` to the ID of your Wokwi project. You can find the ID in your project's URL; it's the big number after `wokwi.com/projects/`.

The GitHub action will automatically fetch the digital netlist from Wokwi and build the ASIC files.

## Resources

- [FAQ](https://tinytapeout.com/faq/)
- [Digital design lessons](https://tinytapeout.com/digital_design/)
- [Learn how semiconductors work](https://tinytapeout.com/siliwiz/)
- [Join the community](https://tinytapeout.com/discord)
- [Build your design locally](https://www.tinytapeout.com/guides/local-hardening/)
