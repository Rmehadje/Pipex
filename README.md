# Pipex

**Pipex** is a 42 project that aims to introduce students to inter-process communication and Unix pipes. The goal is to reproduce the behavior of the shell pipe (`|`), which allows the output of one command to be used as the input for another. The project involves creating a program that connects multiple processes, enabling them to communicate with each other through pipes.

## Features

- 🖥️ **Command Chaining**: Connects the output of one command to the input of another using pipes.
- 🔗 **Process Communication**: Implements inter-process communication, allowing commands to run in separate processes.
- 💻 **Input/Output Redirection**: Redirects file input and output to simulate shell behavior.
- 📜 **Error Handling**: Gracefully handles errors such as missing files or invalid commands.
  
## Functionality

The program will behave like this:
```
/pipex infile "cmd1" "cmd2" outfile
```
## USAGE:
1. **Clone the Repository**
```
  git clone https://github.com/Rmehadje/pipex.git
```
2. **Accessing the cloned Repository**
```
   cd pipex
```
3. **Compile and run the project**
```
make re
```
## ACKNOWLEDGEMENT 
I would like to thank 42 and the community for the help and support to give me an opportunity to work on this project.
