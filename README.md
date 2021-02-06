# unnamedos
The iso in /dist/x86_64/kernel.iso prints "OK" upon booting.
At the moment, it is written completely in assembly, however there will be some C code
to add extra functions

To execute, start with qemu:

Windows cmd: 

cd [qemu location]

qemu-system-x86_64.exe -cdrom [repo location]\dist\x86_64\kernel.iso

this is the precompiled version.
