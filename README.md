# Shell Scripting with AWS EC2, Bash & Git

## Objective
To learn cloud setup, shell scripting, automation, and monitoring of EC2 instances using Bash and Git.

## Day 1: Environment Setup & Monitoring Script

### Task 1: Launch EC2 Instance
- Launch a free-tier Ubuntu EC2 instance on AWS.
- Connect to the instance using SSH or AWS CLI.

### Task 2: Install Required Tools
Install Git using the following commands:

```bash
sudo apt update
sudo apt install git -y
```

### Task 3: Initialize Git Repository
Create a project directory and initialize Git:

```bash
mkdir shell-assignment
cd shell-assignment
git init
```

### Task 4: Create EC2 Monitoring Script
Create a shell script named `monitor.sh` to display:
- Running services
- CPU usage
- Memory usage
- Disk usage

### Task 5: Push Code to Repository
Create a GitHub repository and push the monitoring script to GitHub.

## Day 2: Automation & Logging

### Task 6: Log Monitoring Output
Save the monitoring output to a log file:

```bash
./monitor.sh >> monitor_logs.txt
```

### Task 7: Enhance Monitoring Script
Format the monitoring output clearly for better readability.

### Task 8: Schedule Automation Using Cron
Schedule `monitor.sh` to run daily using the crontab scheduler.

### Task 9: Version Control Updates
Commit and push all changes to the GitHub repository.

## Technologies Used
- AWS EC2
- Ubuntu Linux
- Bash Shell Scripting
- Git
- GitHub
- Cron

## Project Files
- `monitor.sh` – EC2 monitoring script.
- `monitor_logs.txt` – Monitoring output log.
- `README.md` – Project documentation.

