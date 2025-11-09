<<<<<<< HEAD
# Custom_Shell_Imp
Design and Implementation of a Custom Shell Using C++
=======
Custom Shell Project – Assignment 2
Introduction

This project is based on developing a Custom Shell using the C++ programming language as part of my System Programming Assignment 2. A shell is a command-line interface that allows users to interact with the operating system by typing commands. The objective of this project was to design a simple, functional shell that can execute commands, manage processes, handle input and output redirection, and perform command piping. Through this assignment, I learned how operating systems use system calls to execute user commands and how processes are created, managed, and terminated internally.

Project Description

The project folder is named custom_shell_project, and it contains all the files required for the implementation and execution of the shell. The folder structure includes a src directory with all the source code and header files. The files include main.cpp as the entry point, shell.cpp and shell.h for command handling, and jobs.cpp and jobs.h for managing background jobs. The Makefile automates the compilation process and creates an executable file named myshell. The README.md file explains the structure and functionality of the project, while the Ass2.docx report file contains screenshots and explanations of the output.

Features Implemented

The custom shell includes several important features similar to those in Linux terminals. It supports standard Linux commands such as ls, pwd, cd, and echo. It also implements built-in commands like cd, pwd, jobs, fg, and exit. Background process execution is supported using the ampersand symbol (&), allowing multiple commands to run simultaneously. The shell handles input and output redirection using the operators <, >, and >>, enabling users to read from and write to files. It also supports piping, which connects multiple commands together so that the output of one becomes the input of another. Additionally, signal handling for keyboard interrupts such as Ctrl+C and Ctrl+Z has been implemented, along with job control to manage background processes effectively.

Concepts and System Calls Used

This project uses several important Linux system calls that are fundamental to process and command management. These include fork() for creating child processes, execvp() for executing new programs, waitpid() for waiting on child processes, pipe() for setting up communication between commands, dup2() for input and output redirection, and signal() for handling interrupts. Functions like getcwd() and chdir() are used for managing directories. These system calls form the core of shell operations and provide a deep understanding of how command-line interpreters work internally.

Testing and Execution

The project was compiled and executed successfully using the Makefile. After running the executable file named myshell, a command prompt appeared, allowing user inputs. Various commands were tested, such as listing files, changing directories, creating and viewing text files using redirection, and connecting commands through piping. Background jobs were tested using the sleep command followed by the ampersand symbol, and job control commands like jobs and fg were verified. All tests were executed successfully, and the results were captured in screenshots included in the report file.

Learning and Outcome

Working on this Custom Shell project helped me gain practical knowledge about how shells function behind the scenes. I learned how the operating system manages user commands, creates and terminates processes, and performs inter-process communication. This project strengthened my understanding of process management, file descriptors, and system-level programming in C++. It also improved my debugging skills and ability to handle real-time process control. By implementing features like piping, job control, and signal handling, I understood how powerful and complex a command-line shell truly is.

Conclusion

The Custom Shell project was an interesting and insightful experience that deepened my understanding of system programming and operating system concepts. It demonstrated the working of system calls, process creation, and command execution flow in a real-world environment. Building this project gave me confidence in using Linux-based tools and writing efficient C++ programs that interact closely with the operating system. Overall, it was a valuable and educational assignment that enhanced both my technical skills and logical problem-solving abilities.

---




>>>>>>> 3f48e6c (Initial commit - Custom Shell Project by Prakriti Krishna)
