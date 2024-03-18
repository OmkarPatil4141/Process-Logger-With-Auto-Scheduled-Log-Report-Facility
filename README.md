# Process-Logger-With-Auto-Scheduled-Log-Report-Facility

Project: Process Monitoring and Log Automation

## Description:

This project involves the creation of an automation script that periodically logs information about running processes, including their name, PID (Process ID), memory usage, and the number of child processes, into a log file. Additionally, the script sends this log file to a specified email address at regular intervals.

## Features:

Process Monitoring: The script continuously monitors the system's running processes and captures relevant information such as process name, PID, memory usage, and the number of child processes.

Logging: Information about the monitored processes is logged into a file along with the current timestamp for reference.

Automation: The script is designed to run periodically, ensuring consistent monitoring of processes and logging of relevant data.

Email Notification: It automatically sends the log file to a specified email address, allowing for remote monitoring and analysis.

## Requirements:

Python 3.x
psutil library (for process management and system monitoring)
SMTP library (for sending emails)

## Installation:

1. Clone the repository to your local machine
2. Install the required Python libraries using pip: psutil, secure-smtplib
3. Navigate to the project directory
4. Run the script


## Disclaimer:
This script is provided as-is without any warranty. Use it at your own risk.
