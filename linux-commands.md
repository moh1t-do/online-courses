# Linux command bootcamp

> Section 1: Course Walkthrough

> Section 2: Introduction 

	Kernel: does the key operation of acessing the computer hardware.
	Shell: exposes the functionatalies of the kernel.
	Terminal: interface for the end user for the commands to run on the shell.

> Section 3: Command Basics

	command -option arguments
	date, cal, man (useful gets the manual of the command)

> Section 4: Getting Help

	man, help
	which, where 

> Section 5: Navigation 

	ls, cd, absolute, relative path

> Section 6: Creating Files and Folders

	touch, file, mkdir

> Section 7: Nano

	replace commands

> Section 8: Deleting, Copying and Moving

	rm, mv, cp

> Section 9: Shortcut and History

> Section 10: Working wih Files

	less, cat, tac, rev, head, tail, wc, sort

> Section 11: Redirections

	redirect output to a file, use the greater than operator >.
	standard input from a file, use the less than operator <.
	redirect standard error, use the 2>

> Section 12: Piping

	connecting commands, uses the pipe | operator.
	tr (translate)
	tee

> Section 13: Pathname expansion

	wildcards (*) everything, (?) single character, [] range, [^] negation, {} brace expansion (cool stuff)
	nesting braces, arithmatic expansion $(())
	single quote vs double quote, variables
	command subsitution

> Section 14: Finding Things

	locate (looks into the stored file entry), find (looks for all the files hence slower), by size, user, timestamp, 
	times mtime, atime, ctime (MAC) boredom
	logical operator: and or not
	find w/ exec (difficult) (when you want to execute in a serial fashion)
	xargs (take standard input and convert to arguments)

> Section 15: Grep

	search within files
	compatible with regex and extended regex (use -E, syntax changes)
	piping to grep

> Section 16: Permission Basics

	total 10 bits
	file type, owner, group, world
	read, write, execute

> Section 17: Altering Permissions

	chmod, user(u), group(g), others(o), all(a), +(grant permission), -(revoke permission), =(set permission and remove others)
	symbolic and octal notation
	su (substitute user)
	chown, use : to create a group
	groups, addgroup (to create a group), adduser (to add user to a group)

> Section 18: The Environment

	parameter expansion
	shell variables, env variables (use export), user defined varibles
	customising prompt
	alias

> Section 19: Writing your own commands

	shebangs #!bin/bash, #!bin/zsh (to specify the correct shell to execute)
	adding path

> Section 20: Cron

	crontab -e, Scheduled tasks
	minute, hour, day, month, day of the week command
