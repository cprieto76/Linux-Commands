# What Is a Linux Command? 
### (https://kinsta.com/blog/linux-commands/#1-ls-command)
A Linux command is a program or utility that runs on the command line. 
A command line is an interface that accepts lines of text and processes them into instructions for your computer.

- **flag**: is a way we can pass options to the command you run. Most Linux commands have a help page that we can call with the flag `-h`. Most of the time, flags are optional.
- **argument or parameter**: is the input we give to a command so it can run properly. In most cases, the argument is a file path, but it can be anything you type in the terminal.
- You can invoke flags using **hyphens** (-) and **double hyphens** (--), while argument execution depends on the order in which you pass them to the function.

>## 1. ls
> list the contents of the directory

>## 2. alias
> instruct your shell to replace a word with a series of commands.
>Ex: alias ls="ls --color=auto"

>## 3. pwd
> outputs the absolute path of the directory you’re in.  

>## 4. cd  
> switches you to the directory you’re trying to access.  
>Ex: cd Videos  
>Ex: cd /home/kinsta/Documents/Videos

>## 5. cp  
> copy files or directories  
>Ex: cp file_to_copy.txt new_file.txt  
>Ex: cp -r dir_to_copy/ new_copy_dir/  
>the **-r flag** is used to copy directories and their contents recursively

*Remember that in Linux, folders end with a forward slash `(/)`.*
