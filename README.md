# Simple Shell

This is a basic UNIX command line interpreter, commonly known as a shell, developed as part of a project requirement.

## Features

- Displays a prompt and waits for the user to type a command.
- The prompt is displayed again each time a command has been executed.
- Command lines are simple, with no semicolons, pipes, redirections, or other advanced features.
- Command lines are made only of one word; no arguments will be passed to programs.
- If an executable cannot be found, an error message is printed, and the prompt is displayed again.
- Handles errors gracefully.
- Handles the "end of file" condition (Ctrl+D).

## Versions

### Simple Shell 0.1

Basic functionality with prompt and simple command execution.

### Simple Shell 0.2

Handles command lines with arguments.

### Simple Shell 0.3

Handles the PATH variable.
Fork is not called if the command doesn’t exist.

### Simple Shell 0.4

Implements the exit built-in, allowing the shell to exit.
Usage: `exit` (No arguments are required).

### Simple Shell 1.0

Implements the env built-in, which prints the current environment.

## How to Contribute

Feel free to contribute to the development of this Simple Shell project by following these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request.
