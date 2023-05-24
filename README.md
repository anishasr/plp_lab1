# Programming Language Project - Lab 1

## History

1) What is the name of your language?
<br>C

2) When/where was it created, and by whom? Was it written to address a particular problem or need? 
<br><br>The programming language C was created in 1972 at Bell Labs by Dennis Ritchie. It was developed for use in building the UNIX operating system. Using C to build UNIX marked a shift from writing operating systems in assembly language, which was a more laborious and inflexible process. C is considered the first 'high-level' language as it abstracts away some of the interactions with a system's hardware, removing some of the low-level interactions from the programmer's scope. 

3) What types of programming is your language primarily used for? 
<br><br>C is used in writing operating systems, such as Unix, Linux, and Microsoft Windows. It is also used to develop compilers, database systems, such as Oracle, kernels, I/O drivers, application software, and software for embedded systems such as IoT devices.  

4) Where will you get information about this language when it's time to start programming in it? 
<br><br>I typically prefer to learn from textbooks and then complete related online tutorials as I'm reading. I found several textbook recommendations such as 'C Programming Lanuage' by Brian W. Kernighan and Dennis Ritchie, who created the language. I'm very interested in the material in the book 'Writing a Simple Operating System -- from Scratch' by Nick Blundell of the University of Birmingham. These programs will likely be too advanced for me in the beginning, but I hope that my final project can be within this domain.

## 'Hello World' Program
 ```c
 #include <stdio.h>

int main()
{
    printf("Hello, World!\n");
    return 0;
}
```

## Guide

1) What did you need to do to install the language? 
<br>I found a very [helpful tutorial](https://code.visualstudio.com/docs/languages/cpp) within Visual Studio Code's official documentation. It walks through the set up of C/C++ for VS Code. 

Step 1: I installed the 'C/C++ extension' on VS Code.

Step 2: Then I had to install a compiler, 'MinGW'. I had to carefully follow the given installation instructions for this step.

Step 3: Once I had installed 'MinGW', I had to add the compiler to my Windows' path by going into Settings > Edit environment variables. Then I had to add the path 'C:\msys64\mingw64\bin'

After this, I was able to run C programs in VS Code.

2) Does this language come with a recommended programming environment? What is it? If not, how did you pick the one that you'll be using? 
<br>I have a Windows laptop and a Mac laptop. I chose to use my Windows device because I was having a hard time running the 'Hello World' program on my Mac. I'm not exactly sure what the specific problem was, but after several attempts I wasn't able to fix the issue. The setup was pretty seamless on my PC.

3) How do you run programs in that language? 
<br>Once the program is written, the file must be saved with the '.c' extension. The code must then be compiled (which is why I had to install MinGW!). The compiler compiles the code and produces an executable file than can be run. That file can be run from command line or an IDE like VS Code. 

4) How do you write comments in your language? 
<br>You use the '//' characters. 

## Sources

<br>https://www.freecodecamp.org/news/what-is-the-c-programming-language-beginner-tutorial/
<br>https://www.w3schools.com/c/c_intro.php
<br>https://code.visualstudio.com/docs/languages/cpp
<br>https://www.msys2.org/
