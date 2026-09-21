# SSH Brute-Force Detection using Splunk

## Overview

This project demonstrates the detection and analysis of repeated SSH authentication attempts using Splunk.

SSH login attempts were generated from Kali Linux against an Ubuntu system. The resulting authentication logs were collected and monitored in Splunk to identify repeated failed login activity.

## Technologies Used

* Kali Linux
* Ubuntu Linux
* SSH
* Splunk
* Splunk Universal Forwarder

## Workflow

```text
Kali Linux
    ↓
SSH Login Attempts
    ↓
Ubuntu Authentication Logs
    ↓
Splunk
    ↓
Log Analysis
    ↓
Brute-Force Pattern Detection
```

## Implementation

* Generated failed SSH login attempts from Kali Linux.
* Performed repeated authentication attempts to simulate brute-force activity.
* Collected Ubuntu SSH authentication logs in Splunk.
* Analyzed repeated login attempts and source information.

## Screenshots

### 1. Failed SSH Login

![Failed SSH Login](screenshots/01-ssh-failed-login.png)

### 2. Authentication Logs in Splunk

![SSH Logs](screenshots/02-ssh-authentication-logs.png)

### 3. Brute-Force Analysis

![Brute Force Analysis](screenshots/03-bruteforce-analysis.png)

## Key Learning

* Linux SSH authentication monitoring
* Splunk log analysis
* Identifying repeated failed login attempts
* Basic brute-force detection
* SOC alert investigation

