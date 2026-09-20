# Simple CI/CD Pipeline

## Project Overview

Short explanation

## Architecture

[Architecture diagram image]

## CI/CD Flow

Git Push → GitHub Actions → SCP → SSH → EC2 → Nginx → Browser

## Technologies Used

Git
GitHub
GitHub Actions
AWS EC2
Linux
Nginx
SSH
SCP

## How It Works

1. Push code to main
2. GitHub Actions starts
3. Checkout code
4. SCP copies index.html to EC2
5. SSH runs deployment command
6. Nginx serves updated website

## GitHub Secrets

EC2_HOST
EC2_USER
EC2_SSH_KEY_B64

## What I Learned

Short list

## Future Improvements

Docker, testing, rollback, etc.
