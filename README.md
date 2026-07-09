# Hanumanji Monitor

Continuous subdomain drift detection + nuclei scanning workflow for bug bounty targets.

## What it does
- Every 5 days at 06:00 UTC, scans 10 targets with subfinder
- Diffs against baseline `previous.txt`
- Runs nuclei on NEW alive subdomains
- Alerts to Slack on new attack surface + findings

## Targets monitored
apple, google, microsoft, meta, facebook, x, bing, paypal, openai (x2)

## Framework
Full recon framework is at [suvendu-dash/hanumanji-recon](https://github.com/suvendu-dash/hanumanji-recon) (private).
