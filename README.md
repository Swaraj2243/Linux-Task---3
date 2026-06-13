# Linux Task 03 - Process Management, System Monitoring & Basic Shell Scripting

## Objective

The objective of this task is to understand Linux process management, system monitoring, service monitoring, and shell scripting.

## Part A - Process Monitoring

### What is a Process?

A process is a running instance of a program.

### What is a PID?

PID stands for Process Identifier. Every running process has a unique PID.

### Which process is consuming the most CPU?

Observed using top or htop command.

### Which process is consuming the most Memory?

Observed using top or htop command.

## Part B - Process Management

A sleep process was started and identified using ps aux | grep sleep. The process was terminated using kill and kill -9 commands.

## Part C - System Monitoring

Commands used:

free -h
df -h
uptime
uname -a

These commands provide memory, disk usage, uptime, and kernel information.

## Part D - Service Monitoring

Services are background programs that provide important system functions.

Services are important because many Linux features depend on them.

If a critical service stops, users may lose access to network, SSH, or other functionality.

## Part E - Shell Scripting

A shell script named system_report.sh was created to display system information automatically.

## Conclusion

This task improved understanding of Linux process monitoring, system resources, services, and shell scripting automation.
