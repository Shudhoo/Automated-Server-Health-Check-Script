# Automated System Health Check Script

A shell script designed to automate system health monitoring and reporting on CentOS systems.

## Features
- Monitors:
  - CPU usage
  - Memory usage
  - Disk space
  - System uptime
  - Active services
  - Logs for errors and failed login attempts
- Logs results to a file for easy access.
- Sends email notifications (optional).
- Supports automation using `cron` jobs.

## Requirements
- CentOS or similar Linux distribution.
- Basic shell scripting environment (e.g., Bash).
- `mail` utility for email notifications (if enabled).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/system-health-check.git
   cd system-health-check
