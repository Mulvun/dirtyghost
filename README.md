# dirtyghost
Linux post exploitation framework designed to assist grey teams in persistence, reconnaissance, privilege escalation and leaving no trace.
https://user-images.githubusercontent.com/74875302/100135963-60257780-2e58-11eb-9783-83a303cc7919.png

Payloads

Function to generate various encoded reverse shells in netcat, bash, python, php, ruby, perl

SudoInject

Function to inject sudo command with wrapper function to run a reverse root shell everytime "sudo" is run for privilege escalataion

lsInject

Function to inject the "ls" command with a wrapper function to run payload everytime "ls" is run for persistence

SSHKeyInject

Function to log keystrokes of a ssh process using strace

Crontab

Function to create cron job that downloads payload from remote server and runs payload every minute for persistence

SysTimer

Function to create systemd timer that downloads and executes payload every 30 seconds for persistence.

GetRoot

Function to try various methods to escalate privileges

Clearlogs

Function to clear logs and make investigation with forensics difficult

MassInfoGrab

Function to grab mass reconaissance/information on system

CheckVM

Function to check if the system is a virtual machine

MemoryExec

Function to execute remote bash script in memory

BanIp

Function to BanIp using iptables
