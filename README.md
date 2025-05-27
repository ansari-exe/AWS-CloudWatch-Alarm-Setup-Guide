# AWS CloudWatch Alarm Setup Guide

This repository contains a step-by-step guide for setting up AWS CloudWatch Alarms along with EC2 instance configuration, Load Balancer, Auto Scaling Group, and SNS notifications.

## Overview

This project outlines the process to:
- Launch an EC2 instance and its template
- Create a Load Balancer and Target Group
- Set up an Auto Scaling Group
- Create CloudWatch Alarms
- Configure SNS for alert notifications
- Monitor CPU utilization via CloudWatch Metrics

## Steps Covered

1. **Launch an EC2 instance**
2. **Create a launch template for EC2**
3. **Create a Load Balancer**
4. **Create a Target Group for EC2**
5. **Set up an Auto Scaling Group**
6. **Verify the Auto Scaling Group state**
7. **Create a CloudWatch Alarm for CPU Utilization**
8. **Configure SNS topic and subscribe for notifications**
9. **Monitor CPU utilization from CloudWatch Metrics**

## Prerequisites

- AWS account
- IAM user with necessary permissions
- EC2 key pair
- Basic knowledge of AWS services like EC2, ELB, Auto Scaling, and CloudWatch

## Folder Structure

