---
layout: post
title: Terminal for Beginners
---

The terminal can look quite intimidating for people new to unix like systems such as Linux, however it is a powerful tool that is very useful in day to day.

# What Is The Shell

Simply put, the shell is a program that takes commands from the keyboard and gives them to the operating system to perform. In the old days, it was the only user interface available on a Unix-like system such as Linux. Nowadays, we have graphical user interfaces (GUIs) in addition to command line interfaces (CLIs) such as the shell.

The Terminal is a program called a terminal emulator. This is a program that opens a window and lets you interact with the shell. There are a bunch of different terminal emulators you can use.

# Navigation

The files on a Linux system are arranged in what is called a hierarchical directory structure. This means that they are organized in a tree-like pattern of directories (called folders in other systems), which may contain files and other directories. The first directory in the file system is called the root directory. The root directory contains files and subdirectories, which contain more files and subdirectories and so on and so on.

Most graphical environments today include a file manager program to view and manipulate the contents of the file system.

## pwd

Since a command line interface cannot provide graphic pictures of the file system structure, it must have a different way of representing it. Think of the file system tree as a maze, and you are standing in it. At any given moment, you are located in a single directory. Inside that directory, you can see its files and the pathway to its parent directory and the pathways to the subdirectories of the directory in which you are standing.

The directory you are standing in is called the working directory. To find the name of the working directory, use the pwd command.
When you first log on to a Linux system, the working directory is set to your home directory. To list the files in the working directory, use the ls command.

## cd

To change your working directory (where you are standing in the maze) you use the cd command. To do this, type cd followed by the pathname of the desired working directory. To move one directory up type cd ..
Typing cd in any directory will change the working directory to the home directory

# Manipulating files

## mkdir

The mkdir command makes a new directory. mkdir example would create a new directory named example in the current directory, while mkdir /home/you/Downloads/test would create a new directory named test in your Downloads directory.

## rm

The rm command removes a file. For example, rm example removes the file named example in the current directory and rm /home/you/Downloads/example removes the file named example in the Downloads directory.

## cp

The cp command copies a file from one location to another. For example, cp example /home/you/Downloads copies the file named example in the current directory to /home/you/Downloads.

## mv
The mv command moves a file from one location to another. It works exactly like the cp command above, but moves the file instead of creating a copy. mv can also be used to rename files. For example, mv original renamed moves a file named original in the current directory to a file named renamed in the current directory, effectively renaming it.

# Working With commands

## type

The type command is a shell built in that displays the kind of command the shell will execute, given a particular command name. It works like this:

	type command
where “command” is the name of the command you want to examine.

## man

Most executable programs intended for command line use provide a formal piece of documentation called a manual or man page. A special paging program called man is used to view them. It is used like this:

	man program
where “program” is the name of the command to view.
