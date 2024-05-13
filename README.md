# boolean-header-file-in-c
A c header file that contains boolean values(true/false)


To run(in ubuntu):
1. Create a folder in the following path: sudo mkdir /usr/local/include
2. If the path already exists navigate to the path: cd /usr/local/include
3. And create a directory(folder): mkdir myheaders  (use sudo to get permission)
4. clone or download the boolean.h file from this repo and paste it in your myheaders folder
5. Add the directory to the compiler's include search path:

For GCC, you can do this by adding the following flag to your compile command:

-I/usr/local/include/myheaders

So, your compile command might look something like this:

gcc -o myprogram myprogram.c -I/usr/local/include/myheaders

This tells the compiler to look for header files in /usr/local/include/myheaders when you include them in your C programs.

6. To access the header file, create any c file and type:
  #include <myheaders/boolean.h>
