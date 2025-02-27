# Docmost Setup Guide
Setup guide for Docmost server &amp; client using docker.

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
