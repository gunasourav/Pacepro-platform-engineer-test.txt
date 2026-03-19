# PacerPro Platform Engineer Test

Monitoring and auto-remediation solution for slow `/apidata` response times.

## Overview

- Query finds `responsetime > 3s`
- Alert fires on 0 results
- Webhook triggers Lambda

## Part 1 - Sumo Logic

- Reboots EC2 via `reboot_instances`
- Logs to CloudWatch
- Publishes SNS notification

## Part 2 - Lambda

- Provisions EC2, SNS, Lambda, IAM
- Least-privilege IAM policies
- Lambda Function URL for webhook

## Part 3 - Terraform

## Recordings

- Part 1: https://drive.google.com/drive/folders/1MJsgs-biPpD8dlDmMKLDPUyTzSUvhmcg?usp=drive_link
- Part 2: https://drive.google.com/drive/folders/1MJsgs-biPpD8dlDmMKLDPUyTzSUvhmcg?usp=drive_link
- Part 3: https://drive.google.com/drive/folders/1MJsgs-biPpD8dlDmMKLDPUyTzSUvhmcg?usp=drive_link
