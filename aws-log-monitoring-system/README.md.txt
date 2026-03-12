# AWS Log Monitoring System

This project demonstrates how to monitor EC2 instances using AWS CloudWatch and send alerts using SNS.

## AWS Services Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS

## Project Workflow
EC2 Instance → CloudWatch Metrics → CloudWatch Alarm → SNS → Email Alert

## Features
- Real-time monitoring
- Automated alerts
- CPU stress testing

## Test Command
stress --cpu 2 --timeout 300