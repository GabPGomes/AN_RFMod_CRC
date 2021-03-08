# AN_RFMod_CRC
An Application Note made as a college assignment. It explains what is needed to implement a  ASK radio frequency communication, from technology principles to actual hardware and software.\
Here you can find an [Application Note](https://github.com/GabPGomes/AN_RFMod_CRC/blob/main/Application_Note.pdf) (in portuguese) that details the hardware and software used in the protocol. There are also files such as a guide and examples to help using this application.\
Check also [this other repository](https://github.com/GabPGomes/433MHz_RF_Module_STM32F4x) with most of the code used in this application and a deeper explanation about the functions used. The main difference between the two programs is that the AN_RFMod_CRC uses the built-in CRC calculation unit of the STM32F401RE while the other one implements CRC via software. 

It was developed as an assignment for the subject Embedded Systems Programming at Universidade Federal de Minas Gerais - Prof. Ricardo de Oliveira Duarte - Department of Electronic Engineering.
## Guide
1. [Requirements and hardware setup](https://github.com/GabPGomes/AN_RFMod_CRC/wiki/Requirements-and-hardware-setup)
2. [Software configuration using STM32CubeMX](https://github.com/GabPGomes/AN_RFMod_CRC/wiki/Software-configuration-using--STM32CubeMX-(before-SW4STM32-configuration))
3. [Software configuration using SW4STM32](https://github.com/GabPGomes/AN_RFMod_CRC/wiki/Software-configuration-using--SW4STM32-(after-STM32CubeMX-configuration))
4. [RealTerm configuration](https://github.com/GabPGomes/AN_RFMod_CRC/wiki/RealTerm-configuration)

## Examples
[Receiver](https://github.com/GabPGomes/AN_RFMod_CRC/tree/main/examples)\
[Transmitter](https://github.com/GabPGomes/AN_RFMod_CRC/tree/main/examples)
