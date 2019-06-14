# Introduction
### What is bash
Bash is the shell, or command language interpreter, for the GNU operating system
### what is a Shell
a shell is simply a macro processor that executes commands

### How to write a bash script
We are going to write the following code in our file that is called hello.sh
```
#!/bin/sh
echo "Hello world"
```
The file extension has to be .sh
A bash script must always begin with \#!/bin/sh to signify that the script should run with bash.
\#!/bin/sh is technically called shabang symbol
Before running the program we have to give permission to make it an executable file
run the following 
```
chmod u+x hello.sh
```
Now you can run the file by typing 
```
./hello.sh
```
