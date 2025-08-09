# n8n + Twilio WhatsApp Integration

## Project Overview

This project integrates Twilio WhatsApp messaging with n8n workflow automation to enable:

- Receiving WhatsApp messages via a webhook trigger in n8n
- Extracting commands, file/folder names, and related details from incoming messages
- Searching for files or folders in Google Drive (or other storage), retrieving their IDs and MIME types
- Sending automated replies through Twilio based on command execution
- Modular command execution nodes designed for folders, with planned extension for files

## Features

- Reliable webhook integration for Twilio WhatsApp
- Command parsing and data extraction logic
- Dynamic search and metadata retrieval functionality
- Automated reply messages using Twilio node
- Resilient design with extensible command nodes

## Current Limitations

- Accessing outputs from non-immediately previous nodes in the n8n workflow has been a challenging area and remains a work in progress.

## How to Use

1. Configure your Twilio credentials securely in n8n.
2. Import the workflow into your n8n instance.
3. Adjust any placeholders to fit your environment.
4. Activate the webhook and test by sending WhatsApp messages.

## Contribution

Contributions, suggestions, and feedback are welcome!

---

### Note

This README was crafted with assistance from ChatGPT, but the content and experience reflect the genuine work on this project.

