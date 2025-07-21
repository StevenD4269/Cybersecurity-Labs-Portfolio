Activity overview

Previously, you learned about Linux and how to communicate with the OS through the shell. You also learned how to use some of the core commands to navigate the Linux file system and read content from files it contains.

These are essential skills. For example, when investigating unauthorized access, you might navigate to and then read a user access report.

In this lab activity, you’ll navigate a Linux file structure, locate files, and read the contents of files. You’ll also need to answer a few multiple-choice questions based on the information contained in these files.

As a security analyst, it’s key that you know how to navigate, manage, and analyze files remotely via a Linux shell without a graphical user interface.

This exemplar is a walkthrough of the previous Qwiklab activity, including detailed instructions and solutions. You may use this exemplar if you were unable to complete the lab and/or you need extra guidance in competing lab tasks. You may also refer to this exemplar to prepare for the graded quiz in this module.

Scenario

In this scenario, you have to locate and analyze the information of certain files located in the /home/analyst directory.

Here’s how you’ll do this: First, you’ll get the information of the current working directory you’re in and display the contents of the directory. Second, you’ll navigate to the reports directory and list the subdirectories it contains. Third, you’ll navigate to the users subdirectory and display the contents of the Q1_added_users.txt file. Finally, you’ll navigate to the logs directory and display the first 10 lines of a file it contains.

To complete these tasks, you'll need to use commands that you've previously learned in this course. Well, it's time to practice what you’ve learned. Let’s do this!

Task 1. Get the current directory information

In this task, you must use the commands you learned about to check the current working directory and list its contents.

Display your working directory.
The command to complete this step:

1
pwd

This will show that your current working directory is your home directory.

1
/home/analyst

2. Display the names of the files and directories in the current working directory.

The command to complete this step:

1
ls

The output should be:

1
logs  projects  reports  temp

Which directory is your current working directory?

Answer: The lab starts with /home/analyst as your current working directory.

How many directories does the current working directory contain?

Answer: The lab starts with four subdirectories in the /home/analystdirectory, namely logs, notes, temp, and reports.

Task 2. Change directory and list the subdirectories

In this task, you must navigate to a new directory and determine the subdirectories it contains.

Navigate to the /home/analyst/reports directory.
The command to complete this step using a relative path:

1
cd reports

Note: The cd command accepts absolute and relative paths. An absolute path includes all the directories from the root of the file system and starts with a /. An alternative is a relative path, which is expressed starting from the current directory and starts without the initial /. The above command uses a relative path.

The command to complete this step using an absolute path:

1
cd /home/analyst/reports

2. Display the files and subdirectories in the /home/analyst/reports directory.

The command to complete this step:

1
ls

The output should be:

1
users

What is the name of the subdirectory in the /home/analyst/reports directory?

Answer: The subdirectory contained in the /home/analyst/reports directory is called users.

Task 3. Locate and read the contents of a file

In this task, you must navigate to a subdirectory and read the contents of a file it contains.

Navigate to the /home/analyst/reports/users directory.
The command to complete this step:

1
cd /home/analyst/reports/users

The above command uses an absolute path. You could also use a relative path as follows:

1
cd users

2. List the files in the current directory.

The command to complete this step:

1
ls

3. Display the contents of the Q1_added_users.txt file.

The command to complete this step:

1
cat Q1_added_users.txt

Note: The cat command prints the contents of a file to the shell. You can specify the file to display using absolute or relative paths.

The same command using an absolute path:

1
cat /home/analyst/reports/users/Q1_added_users.txt

What department does the employee with the username aezra work in?

Answer: The employee with username aezra works in the Human Resources department.

What is the employee_id of the user mreed in the Information Technology department?

Answer: The employee_id of the employee with username mreed in the Information Technology department is 1104.

Task 4. Navigate to a directory and locate a file

In this task, you must navigate to a new directory, locate a file, and examine the contents of the file.

1. Navigate to the /home/analyst/logs directory.

The command to complete this step:

1
cd /home/analyst/logs

2. Display the name of the file it contains.

The command to complete this step:

1
ls

This command will display the following output:

1
server_logs.txt

3. Display the first 10 lines of this file.

The command to complete this step:

1
head server_logs.txt

