Hello World Program based on leason 1 and 2 on asmtutor.com
Written by daniel Dreyer for CMSC 313 8:30AM class
compile with: nasm -f elf32 -g -F dwarf -o myProgram.o myProgram.asm
link and load with:  ld -m elf_i386 -o myProgram myProgram.o
run: ./myProgram 
