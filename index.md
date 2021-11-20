## The Bash Script

This is a bash script that basically writes an entire makefile for you for the GCC or G++ compiler. You only require to run the script inside of the terminal of your linux distro.

**NOTE: ** This script has been written and tested in Ubuntu OS, I do not know if it will run properly on other distros.

### Instructions

1. Place the script inside of your C/C++ project folder for it to work.
2. Run the script in the terminal
```markdown
$ bash ./createMake.sh <optional argument>
```
2.1. You can enter something for the optional argument like `gcc` or `g++`. If it is not entered then script will ask for a valid input either way.
3. When the makefile is made you get to use 3 different commands.
3.1 `make` - This will create the object files and an executable file called `main` which you can run by using the terminal by typing in `./main`.
3.2 `make clean` - This will remove all the object files and the `main` executable from the project.
3.3 `make rebuild` - This will do the same thing as `make clean`, however it will also run the `make` command.
