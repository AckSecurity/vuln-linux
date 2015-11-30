# VulnLinux

Learning Linux security

gcc have for default canarie validation. if you want compiler your code without this protection use the flag

-fno-stack-protector 

gcc -g -o vuln_program vuln_program.c -fno-stack-protector 
