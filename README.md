# VulnLinux

Learning Linux security. I'm using ubuntu 15.04 for all my test

If your ubuntu is 64bit and you want compiler 32bit code. You have to add -m32 flag and install libc6-dev-i386 package.

gcc have for default canarie validation. if you want compiler your code without this protection use the flag

-fno-stack-protector 

gcc -g -o vuln_program vuln_program.c -fno-stack-protector 
