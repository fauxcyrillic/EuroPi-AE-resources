# EuroPi-AE-resources
Various EuroPi files/scripts adjusted for AE compatibility. Use Thonny to replace the versions on your EuroPi Pico with these.

---

These files generally solve quirks related to AE modular's 0-5v standard, which causes problems with a few of the contributor scripts and the calibration process.

I recommend doing a 'precision' calibration if required, using a multimeter to measure voltage in 1v steps from 1 to 5v. The quick calibration may fail.

Also included here is a custom version of the main europi.py file which incorporates a TW-themed boot image.
