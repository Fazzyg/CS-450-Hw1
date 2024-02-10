# CS-450-Hw1 Fayez Ghosein

# Functionality
The shell parses the input command line into a structured representation that adheres to the syntax rules specified in the assignment, including sequences and nested commands. It then will exxecute the commands given by the user in accordance to the parsed structure.
# Features
Custom Prompt ("S2024$"): Implemented to match assignment specifications.
Command Execution: Support for executing basic Unix commands and advanced command structures using ",", ";", and "()" operators.
Redirections: Implemented code to handle input ("<") and output (">", ">>") redirections more effectively.
Pipes: Improved piping mechanism to chain commands seamlessly.
Background Execution: Augmented to support running commands in the background using "&".
Command Lists: Upgraded to execute a list of commands separated by ";" with proper handling of command execution order.
Parenthesis Handling: Integrated ability to execute commands within parentheses with precedence, allowing for complex command structures.
Error Detection: Added functionality to identify and reject illegal command lines.
# Commands
EXEC: Basic command execution.
BACK: Background command execution.
REDIR: Redirection of input/output.
LIST: Sequential command execution.
PIPE: Piping command output between commands.
#Parsing and Execution
The shell's parsing mechanism now includes advanced error checking to ensure that the syntax of the command line meets the specified requirements, rejecting commands that do not conform.

Compilation
To compile the shell use the following command in the terminal:
Make Clean
-Make
-Make Qemu
.Then the specified prompt "S2024$" will appear in the terminal
