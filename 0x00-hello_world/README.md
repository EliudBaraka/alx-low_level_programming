gcc -E $CFILE -o c -  a script that runs a C file through the preprocessor and save the result into another file.

gcc -c $CFILE -  a script that compiles a C file but does not link.

gcc -S $CFILE - a script that generates the assembly code of a C code and save it in an output file.

gcc $CFILE -o cisfuni - a script that compiles a C file and creates an executable named cisfun.

gcc -S -masm=intel $CFILE - a script that generates the assembly code (Intel syntax) of a C code and save it in an output file.


