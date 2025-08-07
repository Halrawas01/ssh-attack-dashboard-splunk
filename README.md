# ssh-attack-dashboard-splunk
Visual dashboard built in Splunk to detect SSH brute-force attacks
# SSH Attack Detection Dashboard (Splunk)

This is a simple dashboard built in Splunk to detect failed SSH login attempts, which can indicate brute-force attacks.

## What it shows
- A bar chart of failed SSH login counts per IP address
- Data filtered over the last 24 hours

## File included
- `ssh_dashboard.json`: JSON export of the Splunk dashboard

## How to use
1. Open Splunk
2. Go to Dashboards > Import > Upload this JSON file
3. View the failed login attempts visually

## Built for
Splunk lab practice / Cybersecurity analytics
