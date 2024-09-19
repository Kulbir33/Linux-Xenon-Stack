**Linux-Xenon-Stack**

Linux-Xenon-Stack is a simple and lightweight command-line tool for managing and monitoring various system tasks on Linux-based operating systems.
It provides commands to manage system services, monitor system load and processes, check disk usage, analyze logs, and backup system files.

**Features**
**List active services**

Start/stop specific services
Monitor system load and processes
Display disk usage
Analyze critical system logs
Backup system files

**Installation**
**Clone the repository and make the script executable:**
bash

git clone https://github.com/kulbir33/Linux-Xenon-Stack.git
cd Linux-Xenon-Stack
chmod +x sysopctl.sh

**You can now run sysopctl.sh from your terminal:**

bash
./sysopctl.sh

**To make sysopctl available globally, copy it to /usr/local/bin/:**
bash
sudo cp sysopctl.sh /usr/local/bin/sysopctl

**Usage**
Run the sysopctl command with various subcommands and options:

**Commands**

**sysopctl service list**
List all active services

**sysopctl service start <service-name>**
Start a specified service (e.g., sysopctl service start bluetooth).

**sysopctl service stop <service-name>**
Stop a specified service (e.g., sysopctl service stop bluetooth).

**sysopctl system load**
Display the current system load.

**sysopctl disk usage**
Display disk usage by partition.

**sysopctl process monitor**
Monitor system processes in real-time.

**sysopctl logs analyze**
Analyze critical system logs from the past day.

**sysopctl backup <path>**
Backup system files from the specified path (e.g., sysopctl backup /etc).

**Options**

--help
Display the help message.

--version
Display the current version of the tool.

**Examples**
bash

# List all active services
sysopctl service list

# Start a specific service
sysopctl service start bluetooth

# Display system load
sysopctl system load

# Backup system files
sysopctl backup /etc

**Version**
Current version: v0.1.0
