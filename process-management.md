Linux Learning Log Summary

Topic: Process Management

What I Learned

* A process is a program that is currently running.
* Every process has a unique Process ID (PID).
* Linux provides commands to view, pause, resume and stop processes.

Commands Learned            Command	Purpose
ps	                         Shows running processes
ps -ef	                     Shows detailed information about all running processes
top	                         Displays a live view of system processes and resource usage
sleep	                       Pauses a process for a specified amount of time
&	                           Runs a command in the background
jobs	                       Shows background jobs in the current terminal
Ctrl + Z	                   Suspends (pauses) the current process
bg	                         Resumes a suspended process in the background
fg	                         Brings a background process back to the foreground
kill PID	                   Politely stops a process
kill -9 PID	                 Forcefully stops a process if it won’t stop

Key Concepts

* Process: A program that is currently running.
* PID: A unique number assigned to each running process.
* Foreground process: Uses the terminal until it finishes or is stopped.
* Background process: Runs while allowing you to continue using the terminal.


Challenges

* Understanding the difference between a running process (sleep) and a suspended process (Ctrl + Z).
* Learning when to use kill versus kill -9.


Result
* I can view running processes.
* I can monitor system activity.
* I can pause, resume and stop processes.
* I understand how to manage background and foreground jobs.

