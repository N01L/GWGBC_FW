# GWGBC_FW

I, MAKHO, DO NOT MAINTAIN THIS DEVICE OR THE FIRMWARE. I AM ONLY HOSTING A GITHUB REPO WITH THE HISTORICAL FIRMWARE RELEASES FROM FUNNYPLAYING. Please [reach out to funnyplaying directly](https://funnyplaying.com/pages/contact-us) if you have any bug reports or feature requests not listed below or otherwise need any assistance with the device. I do not provide support for this hardware and I will not respond to any requests. I do not have source code for these firmware files. All are pre-compiled and encrypted. 

WARNING: Ensure you use v1.1 firmware if you have a v1.1 hardware based device. Your console will not boot cartridges if you flash the wrong firmware and will be unusuable until you reflash with the correct firmware. 

Overview of the device itself via my video on the v1.0 hardware:

[![Funnyplaying GWGBC -- FPGA BASED GAME BOY COLOR](https://img.youtube.com/vi/T4LSHpKfPGs/0.jpg)](https://www.youtube.com/watch?v=T4LSHpKfPGs)

To proceed to firmware files, select either [HW v1.0](HWv1_0/) or [HW v1.1](HWv1_1/) based on the hardware you have (below). Note that "v1.11" devices use the same firmware as "v1.1" devices. You may also **click** the image that matches the device you have. Note the version number in the top right corner. 

[![HW v1.0](./media/v1.0_Front.jpg)](HWv1_0/)

[![HW v1.1](./media/v1.1_Front.jpg)](HWv1_1/)

I've made lots of feature requests of funnyplaying and they've implemented at least some. They're still working out the kinks. Here is a short list of things that *have already been requested and acknowledged by funnyplaying*:
* LUTs for display accurate color correction (planned for future FW)
* More pixel grid modes; feature parity with their Game Boy Color Q5 laminated backlight kit (planned for future FW)
* Lower minimum speaker volume[^1]
* SD Card support
  * Flashing flashcarts (e.g. to replace burnmaster)
  * system updates
  * save states
  * and you know why. 
* Game Boy Advance support
* IR functionality
* AA battery support (really, guys?)
* faster charging

Funnyplaying has mentioned some of these features in a way that sounds like they're trying to add to the next FW revision (pixel grid modes). From the inception of the device, Funnyplaying has planned IR function but since several revisions of retail boards have shipped without the requisite hardware, I wouldn't hold my breath. I'd treat the rest of these features like that too. Other features they want to add not just to the device but to their backlight kits too (like LUTs) and I expect them to show up there first. 

In this short term, I expect two re-releases of this device, one in DMG form-factor and another in MGB form-factor. The internal hardware, support, and features will be identical to this version, only the shape of the boards will be different for install in the respective shells. Likely the devices will use the same firmware as well. 

While SD Card support and Game Boy Advance functionality are both planned features, I would not expect either until a full hardware refresh happens in probably two to three years, given funnyplaying's track record with promises and deliveries.

[^1]: So this console is so authentic, the amp makes a noticeable buzzing noise that sounds eerily similar to the CPU sound leaks on actual CGBs. Funnyplaying intentionally gimps the minimum volume levels to mask this. It's not the same noise, just similar in nature and likely caused by a similar defect in hardware design. Upon further investigation of the issue, the amp appears to be locked at max volume always and then volume control is achieved by adjusting the audio levels output by the FPGA itself. This is likely why the console buzzes, even when muted. 
