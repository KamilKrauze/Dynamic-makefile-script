## The Bash Script

This is a bash script that basically writes an entire makefile for you for the GCC or G++ compiler. You only require to run the script inside of the terminal of your linux distro.

**NOTE: ** This script has been written and tested in Ubuntu OS, I do not know if it will run properly on other distros.

### Instructions

1. Place the script inside of your C/C++ project folder for it to work.
2. Run the script in the terminal
```markdown
$ bash ./createMake.sh <optional argument>

2.1. You can enter something for the optional argument like `gcc` or `g++`. If it is not entered then script will ask for a valid input either way.
#### Example

$ bash ./createMake.sh gcc

$ bash ./createMake.sh g++
```
