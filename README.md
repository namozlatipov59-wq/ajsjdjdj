# SOMONIYON VPN

SOMONIYON VPN is an educational software project focused on
learning Linux server administration, backend development,
VPN service management, Telegram bot development and web
application deployment.

## Project Goals

The project is being developed as an educational and
experimental infrastructure project.

Main goals:

- Learn Linux server administration
- Learn VPS deployment and SSH
- Learn backend development
- Learn database management
- Learn Telegram Bot API integration
- Learn web application development
- Learn VPN service management
- Learn monitoring and account management
- Learn secure server configuration

## Architecture

The planned architecture is:

Telegram Bot
        |
        v
     Backend
        |
        v
    Database
        |
        +------ Website
        |
        +------ VPN Infrastructure

## Components

### Telegram Bot

The Telegram bot provides:

- User registration
- Language selection
- Account information
- VPN subscription management
- Trial subscription
- Subscription status

### Web Application

The website provides:

- User account dashboard
- Subscription plans
- VPN status
- Account management
- Multilingual interface

### Backend

The backend provides:

- User management
- Subscription management
- Expiration tracking
- VPN status management
- REST-style HTTP endpoints

## Technology

Current technologies include:

- Python
- SQLite
- HTML
- CSS
- JavaScript
- Telegram Bot API
- Linux / Termux development environment

## Subscription Model

The educational prototype currently contains:

| Plan | Duration |
|---|---:|
| Free Trial | 3 days |
| 1 Month | 30 days |
| 3 Months | 90 days |
| 6 Months | 180 days |
| 1 Year | 365 days |

## Educational Purpose

This project is primarily intended for learning and
experimentation with:

- Linux
- VPS infrastructure
- Networking
- Backend development
- Database systems
- Web development
- Automation
- Server monitoring

## Current Status

The project is under active development.

Current components:

- Telegram bot prototype
- Web interface
- Python backend
- SQLite database
- Account system
- Subscription expiration system

Future work:

- Real VPS deployment
- Xray/VLESS integration
- Automated VPN account provisioning
- Automated expiration handling
- Monitoring
- Android client

## Security

No passwords, API tokens, private keys or other secrets
should be stored in this repository.

## License

This project is currently provided for educational and
experimental purposes.
