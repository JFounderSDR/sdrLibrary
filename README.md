# sdrLibrary
sdrLibrary包含了编译项目所需要的第三方库和运行时库。<br>

编译环境分为两种PetaLinux2015.4、jLinux如下：<br>
jLinux编译环境:<br>
* 编译器：arm-linux-gnueabihf-gcc，arm-linux-gnueabihf-g++<br>
* 编译器版本：gcc version 6.5.0 (Linaro GCC 6.5-2018.12)<br>
* 目标平台：ARMv7_CortexA9<br>

PetaLinux2015.4编译环境：
* 编译器：arm-xilinx-linux-gnueabi-gcc，arm-xilinx-linux-gnueabi-g++<br>
* 编译器版本：gcc version 4.9.2 (Sourcery CodeBench Lite 2015.05-17)<br>
* 目标平台：ARMv7_CortexA9<br>

两个版本的第三方库：<br>
* ace_tao，版本：ACE+TAO-2.0a<br>
* boost, 版本：1.69.0<br>
* tiny1xml，版本：1<br>

两个版本的运行时库：<br>
* runtime_env, 本项目编译所依赖的其他动态库。
