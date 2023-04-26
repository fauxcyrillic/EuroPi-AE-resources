# EuroPi-AE-resources

Various EuroPi files/scripts adjusted for AE compatibility. Use Thonny to replace the versions on your EuroPi Pico with these.

---

These files generally solve quirks related to AE modular's 0-5v standard, which causes problems with a few of the contributor scripts and the calibration process.

I recommend doing a 'precision' calibration if required, using a multimeter to measure voltage in 1v steps from 1 to 5v. The quick calibration may fail.

Also included here is a custom version of the main europi.py file which incorporates a TW-themed boot image.

The Hardware folder contains gerbers for the PCB and frontpanel, plus pick & place file and BOM. I used JLCPCB to manufacture mine. The PCB uses a fair amount of SMT including the op-amps, so they aren't the cheapest boards (about £40 for 5) but it saves a lot of space.
