<h1>Thunderbolt3方案<h1>

此项目包含Thunderbolt3核心板+底板PCB文件，底板为官方提供的EVM，核心板原理图未整理，两张pcb均已验证可正常使用

<h2>目录<h2>

-Document目录内为部分可公开资料

-HW目录内包含底板参考设计与模块文件

-Firmware目录内包含固件

<h2>固件烧录方法<h2>
此雷电方案固件分为两个部分，分别为SPI Flash内JHL7440固件与CYPD5235内电源固件。SPI Flash内固件可用SPI编程器(如RT809)烧录，CYPD5235固件需要Miniprog3或Miniprog4通过SWD接口烧录

*Tip:Miniprog价格不菲，经实测所有带自动下载的CY8CKIT均可正常烧录未编程OTP的CYPD5235*