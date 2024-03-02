<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

QRNG is chip scale implementation of Spooky Manufacturing's [QRNG](https://github.com/Spooky-Manufacturing/QRNG) technology, designed both to generate random numbers for various applications, and to assist in the development of open-source quantum photonics technologies.
### Modules:
The QRNG consists of two modules:
- **External LED Module:** This module is designed to operate using an external light source.
- **Internal LED Module:** This module incorporates an experimental silicon-based LED.

### Light Propagation
In each module, photons are generated when the LED is trigger. These photons travel down a waveguide into a 50:50 beam splitting structure which splits the light into two modes. At the end of each mode, there is an optical trap containing a photodiode which is used to measure the intensity of light along the respective mode. The outputs from these photodiodes are then passed into a comparator which returns a bit.

## How to test

### External LED
The External LED module requires a bare die and/or optical access into the chip. This module is designed to operate using an external light source.

### Internal LED
The Internal LED is highly experimental and requires a break down of the diode gate.

**WARNING:**
To activate the Internal LED, a reverse voltage of up to 6V must be applied to a pin that is TBD (To Be Determined). This reverse voltage is necessary to form the silicon filament inside the CMOS LED, which is used to generate photons. However, this process is inherently destructive and carries significant risks:
- **Irreversible Damage:** Applying the reverse voltage is likely to result in irreversible damage to both the QRNG module and the chip itself
- **Experimental Nature:** The Internal LED module is experimental, and its functionality may not be guaranteed. It should only be attempted by experienced users familiar with the associated risks.

Before attempting to activate the Internal LED module, carefully consider the potential consequences and ensure that proper safety measures are in place.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
