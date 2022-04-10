# ASR6601 Getting Started Guide

Video tutorial : [https://youtu.be/ULMnPckZp1M](https://youtu.be/ol-VPjXlCgc)

![alt text](https://github.com/akarsh98/ASR6601-getting-started-guide/blob/main/Images/8.JPG)

In this project, we have with us a different kind of LoRa module. The name of the module that we are talking about is ASR6601. It is similar to any other LoRa module that we use normally but the difference is that it has a microcontroller on chip and does not require any additional microcontroller to be added to it for its operation. The module is a SoC loaded with Cortex microcontroller from ARM which makes it a perfect fit for projects where we require some compact and small in size LoRa devices. With other type of LoRa modules that are already in the market, we first needed to connect them to some microcontroller and after that, we had to upload the code to the microcontroller and then the device was seen as ready to use. This process was a bit cumbersome and sometimes made smaller tasks tedious That's why this module can be a good alternative for traditionally available modules.

![alt text](https://github.com/akarsh98/ASR6601-getting-started-guide/blob/main/Images/1.JPG)

What we are going to do with the ASR6601 is that we will be flashing some basic code in it which is nothing but a code to check if our module is working fine or not. For loading the code in our device we will need a programmer because the that is not onboard. So we will be using a J-Link Programmer from Segger. We will do some simple connections between the programmer and the ASR6601 and connect them both with the PC. In this way, we will be done on the Hardware front.

![alt text](https://github.com/akarsh98/ASR6601-getting-started-guide/blob/main/Images/2.JPG)

After doing the Hardware stuff, we need to upload the code to our device. For that we will be using Keil uVision Software. So we need to install that as well. Apart from that, we will require two additional things which are:-
1) GNU ARM Embedded Toolchain
2) Software Development Kit (present in this repository)

After completing the downloading and installation of these softwares, we are good to go and complete the uploading of our code. As the code gets compiled and uploaded to the board, we will be displayed some details on the screen which will show that the code was uploaded succesfully or not.So in this way, we will be done with our first project on ASR6601. We can use this board to make many more different projects that we used to make using LoRa.

![alt text](https://github.com/akarsh98/ASR6601-getting-started-guide/blob/main/Images/jlccb1.JPG)

You must check out [JLCPCB](https://jlcpcb.com/aka) for ordering PCBs online for cheap!

You can also get good quality SMT Assemblies from [JLCPCB](https://jlcpcb.com/aka) with Assembly Prices starting at an 8$ setup fee and $0.0017 assembly fee per joint. You will get a discount on shipping on your first order. You just need to upload your Gerber, BOM&CPL files to get an instant quote on PCB, components, and assembly. A DFM analysis is generated after you order the boards, allowing you to spot potential mistakes before it goes into production. You can also track order status in real-time and can get your products in your hands as fast as one week.
