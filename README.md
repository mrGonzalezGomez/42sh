# 42sh Project

## Overview
The 42sh project is an advanced Unix shell based on the TCSH shell, written in C. The project is a collaborative effort aimed at building a robust and feature-complete shell. The project emphasizes stability and reliability over the sheer number of features.

## Project Details

- **Project Name:** 42sh
- **Language:** C
- **Members:** pereto-axel, EmilioEpitech, alpha0344, vincbct34 and myself
- **Compilation:** The project is compiled using a Makefile that includes the rules: `re`, `clean`, and `fclean`.
- **Authorized Functions:** All functions from the standard C library (libC) and the ncurses library are permitted.

## Deliverables

- **Source Files:** All necessary source files must be included in the delivery, excluding unnecessary files such as binaries, temporary files, and object files.
- **Bonus Files:** Any bonus files, including a potential specific Makefile, should be placed in a directory named `bonus`.
- **Error Handling:** Error messages should be written to the error output, and the program should exit with the same error code as TCSH.

## Features

### Mandatory Features
The shell should include the following features:
- **Inhibitors:** Implement inhibitors like `''`.
- **Globbing:** Support for globbing patterns such as `*`, `?`, and `[ ]`.
- **Job Control:** Implement job control features such as `&`, `fg`, and `bg`.
- **Variables:** Support both local and environmental variables.
- **Special Variables:** Implement special variables such as `term`, `precmd`, `cwdcmd`, `cwd`, and `ignoreof`.
- **History:** Command history with `!`.
- **Aliases:** Support for command aliases, e.g., `alias ls "ls --color"`.
- **Line Edition:** Features like multiline editing, dynamic rebinding, and auto-completion.

## Development Guidelines

- **Group Collaboration:** Ensure effective collaboration and communication within the team. Each member should be able to understand and potentially complete the tasks of other members if necessary.
- **Workload Distribution:** Distribute the workload intelligently to handle unforeseen circumstances such as a team member falling sick.
- **Unit Tests:** Write unit tests alongside feature development to maintain the stability of the project as it grows.
- **Version Control:** Utilize Git for version control. Commit changes frequently and be familiar with navigating previous revisions and using branches.

## Compilation and Execution

To compile the project, use the provided Makefile with the following commands:

```sh
make        # Compile the project
make re     # Recompile the project
make clean  # Remove object files
make fclean # Remove object files and binaries
```

Execute the shell using:

```sh
./42sh
```

## Error Handling
All error messages should be directed to the error output, and the shell should exit with the appropriate error code, consistent with TCSH behavior.

## Conclusion
The 42sh project aims to create a fully functional Unix shell with a strong emphasis on stability and reliability. By following the development guidelines and focusing on the mandatory features, your team will deliver a robust and efficient shell. Additional features and bonuses are encouraged as long as they maintain the overall coherence and stability of the project.
