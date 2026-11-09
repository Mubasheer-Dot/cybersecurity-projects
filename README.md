# cybersecurity-projects
# Brute-Force Login Detector

A Python script that reads an authentication log and flags IP addresses
with too many failed logins.

## What it does
- Reads a log file line by line
- Finds "Failed password" entries
- Extracts the source IP address
- Counts failures per IP using a dictionary
- Prints an ALERT for any IP above a chosen threshold

## Usage
find_bruteforce("auth.log", 3)

## Skills used
Python, file handling, dictionaries, log analysis

## Next steps
- Detect failed logins by username
- Parse real Linux /var/log/auth.log files
- Add timestamps to catch rapid-fire attempts
