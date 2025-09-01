# System Notification Generator (Python)

## Overview
Built a Python script that generates realistic system notifications with:
- UUID Case IDs
- Real-time timestamps
- Randomized HTTP status codes
- Persistent logging to file

Extended the project with Gmail SMTP integration to deliver messages via Verizon's SMS gateway, simulating real-world IT monitoring alerts.

## Features
- Generates structured system messages
- Appends each run to a log file
- Sends SMS notifications to Verizon numbers via email-to-SMS
- Easily customizable for other carriers (AT&T, T-Mobile, etc.)

## Example Output
System Notice: Verification Required
Case ID: e308cbb1-6811-4ca8-b681-aecf7a481f64
Timestamp: 2025-09-01 10:43:38
Status: SUCCESS [Code 200]
