# armcc 编译命令
编译器目录  d:\Keil_v5\ARM\ARMCC\bin <br/>
1 armasm.exe startup_MIMXRT1052.s --cpu cortex-m7' <br/>
2 armcc.exe  main.c --cpu cortex-m7' <br/>
3 armlink.exe   startup_MIMXRT1052.o  main.o   -o Objects/LED-REG.axf  --cpu Cortex-M7  --fpu=SoftVFP --diag_suppress 6314 --strict --scatter ".\MIMXRT1052xxxxx_flexspi_nor.scf" <br/>
<br/>
其中 MIMXRT1052xxxxx_flexspi_nor.scf 文件是keil目录下下载相应CPU之后的文件<br/>
