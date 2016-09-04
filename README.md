#Trezor Diy Development Board
This is hardware project designed to work with <a href="http://www.waveshare.com/wiki/Core205R">Core205R</a> development board with custom arm STM32F205RGT6.
If anyone needs custom board can be ordered from <a href="http://www.waveshare.com/">Waveshare</a>.

Please be kindly advised that people behind original Trezor hardware wallet on purpose published non-working bootloader code in order to prevent people from building devices on their own.
Please take a look on my forked repository https://github.com/karek314/trezor-mcu which is free of this easter egg.

https://github.com/karek314/trezor-mcu/commit/34a081e032af5fc5d0f006adb6f7bec5c789feb8
Function random32() caused infinite loop preventing device from starting.
