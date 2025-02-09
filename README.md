# HOW TO USE SHELL (Start)

This is a recreation of the Unix Shell.
Enter a command you want to be run and hit enter. The format is typically [command] [argument1] [argument2] and so on.

It will present errors if a command is inputed wrong or fails.

This shell supports the following built in commands:

cd - No argument will print the current directory, 1 argument will move the user into the given directory. This can take no arguments or one.
dir - No argument prints the content of the current directory. 1 argument will print the content of that directory. This can take no arguments or one.
pause - pauses the shell until enter is pressed.
environ - no arguments, prints all the environment variables. These are variables the shell has access to whenever and can be used by any program.
help - displays this document with the more functionality.
clr - no arguments, clears the console output.
echo - prints out the line you typed, excluding 'echo'.
quit/exit - quit the shell.

This shell also supports all external commands found in Unix Shell and the /bin folder. Examples are ls, hexdump, gcc, and so on.

This shell supports input and output redirection. '<' is used for input redirection, and '>' or '>>' is used for output redirection. 
Using '>' will overwrite whatever is in the output, while '>>' will append to the end of whatever is in the output. 
These change stdin and stdout to whatever is given for the executing process. ex: [command] > [file], [command] >> [file2], [file] < [command]

This shell also supports piping, which is another form of redirection. Piping is used in a similar way with regular input and output redirection, using the pipe symbol '|' between commands. Piping takes the output of one command and uses it as input to for the next command. ex: [command1] | [command2]

This shell also supports commands running in the background. To do this, include an ampersand '&' at the end of a command. This allows you to immediately return back to the shell to run more commands. Your process will run in the background.


