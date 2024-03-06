# Homework_Pastel

# Problem 1_a is finally done!

# Problem 1_b is finally done

# Problem 1_c is finally done!

# Problem 1_d is finally done!

# Problem 2 is done.

# Problem 2a is done!

# Problem 2_b is done!

# Problem 2_c is done!

# Problem 3 is done!!!!

# HomeWork 3 problem 1 is done!!

# Homework 3 problem 2 is done!!


# # Question: 

## What is the difference between shell and bash?


### “shell” is a broad term that refers to any program that provides a command-line interface, “Bash” is a specific type of shell that is widely used in Unix/Linux systems.


# Exercise 1:


## What is your home directory? What files/folders exist in your home directory? Navigate to it and then navigate back to your notes.

### $ echo $HOME (/c/Users/cmpas) cd -

# Exercise 2:

## Where does the following command 'cd' take you? How does it work?

### The cd command takes you to your current directory. Depending on the amount of slashes '/' it will move that many in the current directory.

# Exercise 3:

## Read the manual page of ls. What does the a flag do? What does the l flag do?

### The -a flag in ls stands for "all" and displays hidden files as well. The -l flag provides a detailed listing, showing additional information

# Exercise 4:

## Create a new file with touch command. for instance touch myfile.txt. Run stat myfile.txt what information do you get?


### I get information about the file such as the size, permissions, owner, and timestamps

# Exercise 5:

## Run ls and from there list select a file. Now run ‘ls -l’ to display the details of the files, showing that it has been created or updated. what information does it give you regarding the myfile.txt and your selected file.


### 'Homework 3.Rmd', Homework_Pastel_Data_413.Rproj myfile.txt, README.md. 

# Exercise 6:


## Add the following line This line is my first line to myfile.txt. Then run cat myfile.txt to show the line is added.

### echo "This line is my first line" >>
myfile.txt

### cat myfile.txt This line is my first line


# Exercise 7:

### touch myfile.txt, ls -l myfile.txt

### -rw-r--r-- 1 cmpas 197609 27 Mar  4 22:35 myfile.txt


## Run touch myfile.txt then run ls -l myfile.txt does the “timestep” for the file myfile.txt is updated? Show the output. Note: Another common use of the touch command is to update the timestamps of an existing file.
