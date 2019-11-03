# Automation-Operation
This script used to test connection and check the log for servers
Users: Operation guys in Apac
Version:1.0.0


Language: Powershell

.Description
This is a script used to schedule generating the server log report. and will using the function which out of this script.
.Parameter Computername
Servers list 
.example
ps c:\users\jacob\desktop\script -file c:\users\jacob\desktop\hostlist.txt

need following function:
1:Check the connection status(import external function)
2:Write a function to filter the log, security, system error, power events. and then have a good format to html
3:Write a task/job, import the function, have html report, good title, then using send mail command
4:error action
