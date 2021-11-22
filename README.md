# minishell
(42 subject) A simple shell made from scratch !

## Table of Content

* [Technologies](#technologies)
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Utility](#utility)
* [Contributing](#contributing)

## Technologies

Project is created with:
* gcc 9.3.0

## Description

The aim of this project is to create an entire shell environment from scratch.\
You have to implement a way to execute other binaries in order to have most of the built-in shell commands (those located in "/bin/").\
I implemented the following features to the shell:
* pipes ("|")
* redirections (">" and "<")
* signals such as SIGINT and SIGQUIT (Ctrl-C and Ctrl-D)
* return values (checkable with "$?")
* cd, echo (with option -e), pwd, export, unset, env, exit (which are not built-in functions !) without any other options than -e on echo
* environment variables

## Installation

Just pull the project !\

## Usage

Classic 42 Makefile:
````sh
make		#compiles everything and create woody_woodpacker binary
make clean	#removes all the .o files
make fclean	#removes all the .o files and the "woody_woodpacker" binary
make re		#cleans everything in the project and compiles everything again
````

Specific to the project:
````sh
./minishell	#make a brand new terminal
exit		#exits the minishell
````

## Utility

I learned a lot about shell and unix during this project and it is quite satisfaying to see that you are able to code an entire shell environment at this stage of your studies (1 year after starting to code)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.