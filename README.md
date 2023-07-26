# Linux Server Security Checker

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)

## Description

The Linux Server Security Checker is a Python script designed to help you check the security status of your CentOS Linux server. It performs various checks to identify potential security issues, such as CPU usage, system load, network traffic, recently modified files, established network connections, scheduled tasks, and more. Additionally, it can verify common system commands for potential modifications.

## Features

- Check CPU usage, system load, and network traffic
- Identify recently modified files within a specified number of days
- Detect established network connections and identify foreign IP addresses
- Check for common system command modifications
- Identify suspicious commands in bash history
- Check scheduled tasks and cron jobs
- Detect potential hijacked library files

## Usage

1. Clone the repository:

```bash
git clone https://github.com/moonshineDX/EmergencyResponse.git
cd EmergencyResponse
pip install -r requirements.txt
