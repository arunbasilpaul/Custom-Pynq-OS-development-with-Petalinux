# Custom-Pynq-OS-develpment-with-Petalinux
## The project is to run the TVM deploy_classification.py inference on the custom development board TE0802 developed by Trenz Electronics

TVM works on the Pynq Driver. Since there is no Operating System for the TE0802 board, an Operating System has to be created from scratch with the source files from Trenz Electronics based on a Pynq Linux driver.

Why TE0802 Zynq Ultrascale+ Board:
- 1Gb DDR memory for future projects
- Multiple peripherals
- Cost around 335€

Softwares and their versions:
- Ubuntu 18.04.5
- Vivado with Vitis 2019.2
- PetaLinux 2019.2 (It is better to have the same version as Vivado)
- TVM
- Python with Anaconda 3.8
- Balena Etcher (To format the SD crad and clone the new OS)

Design Flow:
The steps involved are dependent on the previous step and provide insights or?and source files for the next step:
  ![design_flow](https://github.com/arunbasilpaul/Custom-Pynq-OS-develpment-with-Petalinux/assets/171144888/ff7f2bb6-3422-481e-b4f1-174b4e3b1d1d)
