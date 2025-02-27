# Docmost
Docmost is a self-hosted document collaboration and management platform that provides a secure and efficient way to work on and manage your documents alternative to Confluence and Notion. With Docker Compose, deploying and managing Docmost becomes straightforward.  
  
*Originally from [docmost](https://github.com/docmost/docmost) repository*

![Demo GIF](example.gif)

# Setup Guide

## Prerequisite
- [Docker](https://www.docker.com/)
- SMTP server (for example we use gmail service)  
check [this](https://support.google.com/accounts/answer/185833?hl=en#) to get your gmail App Password.

## Installation
- Clone this repository
```bash
git clone https://github.com/aridwan/docmost-setup-guide.git
```

- Configure settings
  - Rename `.env.example` into `.env`, 
  - Change `REPLACE_THIS_WITH_YOUR_EMAIL` to your gmail account
  - Change `REPLACE_THIS_WITH_YOUR_PASSWORD` to your gmail app password generated before

- Run via Docker
```bash
docker-compose up 
```

- Access via browser
Open browser and go to `localhost:3000`
