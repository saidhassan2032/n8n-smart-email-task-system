# Smart Email → ClickUp Task Automation (n8n)

This project automates task creation in ClickUp from incoming emails using n8n.

## Features
- Listens for new emails via Gmail
- Filters actionable emails
- Automatically creates a ClickUp task
- Replies to the original sender with confirmation
- Keeps email and task in sync

## Tools Used
- n8n
- Gmail API
- ClickUp API

## Workflow Overview
1. Gmail Trigger detects a new email
2. Email data is processed and filtered
3. ClickUp task is created
4. Confirmation reply is sent via Gmail

## How to Use
1. Import the workflow JSON into n8n
2. Configure Gmail credentials
3. Configure ClickUp credentials and List ID
4. Activate the workflow

## Notes
- System and newsletter emails should be filtered to avoid auto-replies
- No credentials are stored in the workflow file
