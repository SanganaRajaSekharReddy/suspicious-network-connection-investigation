# Suspicious Network Connection Investigation

## Project Overview
This beginner SOC Analyst project focuses on investigating active network connections on a Windows computer using Command Prompt (CMD).

## Objectives
- Identify active network connections.
- Understand IP addresses and port numbers.
- Find established connections.
- Identify processes using Process IDs (PIDs).
- Learn basic network investigation techniques.

## Tools Used
- Windows Command Prompt (CMD)
- Windows Tasklist
- Netstat

## Commands Used

### 1. View Network Connections
```cmd
netstat -ano
```

### 2. View Established Connections
```cmd
netstat -ano | findstr ESTABLISHED
```

### 3. Identify a Process Using Its PID
Replace `26432` with the actual PID you want to investigate.

```cmd
tasklist /FI "PID eq 26432"
```

### 4. Findings
- Reviewed active network connections.
- Examined established connections.
- Practiced identifying processes using PIDs.
- Learned that unknown IP addresses require further investigation before being classified as suspicious.

## Conclusion
This project helped me understand basic Windows network connections and practice an important SOC Analyst investigation technique.

## Disclaimer
This investigation was performed on my own Windows computer for educational purposes. An unfamiliar IP address does not automatically indicate malicious activity.
