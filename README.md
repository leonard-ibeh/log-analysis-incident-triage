# Linux SSH Log Analysis (Junior SOC Project)


## Overview
THis project demonstrates basic Security Operations Center(SOC) skills by analyzing logs to detect and assess failed SSH login attempts.

## Objective
- Monitor authentication logs
- Identify failed SSH login attempts
- Determine severity and recommend actions

## Tools & Environment
- Ubuntu Linux (VirtualBox VM)
- Native Linux log files(/var/log/auth.log)
- Command-line utilities (grep,awk,wc)

## Findings
- Detected multiple failed SSH authentication attempts
- Activity classified as low-severity, likely automated scanning
- No successful compromise observed

## Recommendations
- Continuous monitoring of authentication logs
- Implement brute-force protection (e.g., fail2ban)
- Enforce strong authentication policies

## Skills Demonstrated
- Log analysis
- Incident indentification
- Security monitoring 
- Linux command-line proficiency
