# STM32_e-reader
A modest attempt to build an e-reader using a stm32MP1.


> [!CAUTION]
> THIS IS A WORK IN PROGRESS. HACK AROUND AT YOUR OWN RISK.
> I didn't test the board yet and can't be held responsible for any magic smoke 💨

I'm planning to use the [KOReader](https://github.com/koreader/koreader) on OpenSTLinux for the software side, and a modified [epdiy](https://github.com/vroland/epdiy/) driver board for the hardware.
The first version will be using a ED060XC3 screen with a TMA340 touch screen.

Here is the test board:
![image](https://github.com/user-attachments/assets/17122cc1-8a4d-4769-a7da-7a5c22921c24)
based on these PCBs from [@martinberlin](https://github.com/martinberlin):

* [epdiy-hardware-versions/versions](https://github.com/martinberlin/epdiy-hardware-versions/tree/main/versions)
* [epdiy-hardware-versions/epdiy-v7-raw](https://github.com/martinberlin/epdiy-hardware-versions/tree/main/epdiy-v7-raw)
