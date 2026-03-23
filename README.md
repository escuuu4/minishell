# Minishell - Unix Shell Implementation in C

## Overview
This project consists of the implementation of a Unix shell written in C as part of an Operating Systems project.

The shell supports execution of external commands, pipes, redirections, background processes and internal commands.

## Features
- Command execution
- Pipes (|)
- Input/Output redirection (<, >)
- Background execution (&)
- Internal commands (cd, umask, limit, set)
- Environment variables
- Signal handling (SIGINT)
- Process management using fork, exec and wait
- File descriptor management using dup2

## Architecture
The shell parses the user input into commands, creates processes using fork(),
connects pipes between processes, handles redirections with dup2(),
and executes commands using execve().

## Technologies
- C
- Unix/Linux
- System calls: fork, execve, wait, pipe, dup2, signal
- Makefile

## Note
Due to academic licensing restrictions, the source code cannot be publicly shared.
The project can be demonstrated or explained upon request.
