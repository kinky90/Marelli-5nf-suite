# Marelli-5nf-suite
Marelli 5NF
Need to solder LPT BDM adapter page 125

http://www.rossonex.com/SAAB/Trionic_5.pdf

Making a bootable USB flash drive with MS-DOS

unpack to the root of my archive (unpacked)

open bd32.exe

set the speed with the command Port lpt1 30000

Check read flash command MD 0x0 128

for writing or reading you need to prepare an MCU script

do prepmcp.do command

dumpmcp dump command 123.bin

write command flashmcp 123.bin

123- file name.

recovery dump in the same archive 5NF.bin

For successful recording, throw the jumper as in the photo
