Custom Linux Shell in C++ 🖥️

This project is a simple custom shell (command interpreter) written in C++ that can execute Linux commands, support redirection (> / <), and handle basic piping (|).
It works similar to Bash for simple command execution.

Features ✨
Feature	Description
Execute basic commands	ls, cat, touch, echo, mkdir, rmdir, ps aux etc.
Input/Output Redirection	Uses < and > to redirect input/output
Piping Support	Supports commands connected by `
Interactive Prompt	Shows Custom Shell> for every command
Exit	Type exit to leave the shell
Demo Screenshots 📸
Example	Description
ls, mkdir, rmdir	Basic command execution
echo "Hello" > file.txt	Output redirection
cat file.txt	Display file contents
ps aux	Process listing

(Add screenshots here in GitHub by uploading them into /screenshots folder)

How to Run the project 🔧
g++ init.cpp
./a.out

Tech Stack Used

C++

Linux System Calls (fork, execvp, waitpid, open, dup2)

GCC Compiler

Folder Structure
.
├── init.cpp          # main shell source file
├── README.md         # documentation
└── screenshots/      # screenshots (optional)

Future Enhancements 🚀

Support background execution (&)

Maintain command history

Add autocomplete using TAB

Add job control (fg / bg / jobs / kill)
