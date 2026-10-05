*This project has been created as part of the 42 curriculum by gdero and ngharian*

# minishell

## Description

A simplified recreation of a Unix shell (such as Bash), built in C as a duo project from the
42 curriculum. The goal is to understand how a shell parses, interprets, and executes commands
by implementing core shell behavior from scratch.

## Features

- Command parsing, including quotes and special characters.
- Pipes and I/O redirections (`|`, `<`, `>`, `>>`).
- Environment variable handling and expansion.
- Built-in commands: `cd`, `echo`, `pwd`, `export`, `unset`, `env`, `exit`.
- Signal handling (Ctrl+C, Ctrl+D, Ctrl+\\).
- Process management via fork/exec.

## Usage

```bash
make
./minishell
```
