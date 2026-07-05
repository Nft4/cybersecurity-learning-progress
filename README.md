# Cybersecurity Level 1 Learning Progress

This repository documents my Level 1 cybersecurity training progress across four modules:

1. Programming
2. Operating Systems and Administration
3. Networking, Infrastructure and DevOps
4. Personal and Technical OpSec

The goal is not just to collect courses. The goal is to show evidence: code, notes, screenshots, lab reports, deployment steps, mistakes, fixes, and final checkpoints.

## Current Status

| Module | Focus | Status | Evidence |
|---|---|---:|---|
| Programming | Python, Git, FastAPI, databases, auth, deployment | In progress | `01-programming/` |
| OS Administration | Linux, Windows, hardening, services | Not started | `02-os-admin/` |
| Networking | Mikrotik ISP lab, enterprise lab, VPN, routing/firewalling | Not started | `03-networking/` |
| OpSec | Encryption, basic OpSec case studies, privacy habits | Not started | `04-opsec/` |

## How I Track Progress

I use a local HTML tracker for daily missions, timer sessions, notes, and mini-session checkboxes. This GitHub repo is the public/professional version where I save the proof of work.

Each completed task should include at least one of:

- A short write-up
- Commands used
- Screenshots
- Configuration snippets
- Code
- A problem I faced and how I fixed it
- A final checkpoint explanation in my own words

## Featured Projects

### 1. Python FastAPI Backend

**Goal:** Build and deploy a FastAPI backend with PostgreSQL, JWT authentication, Nginx, systemd, domain name, and SSL.

Folder: `01-programming/fastapi-api-project/`

Planned evidence:

- API routes
- Database models
- JWT login/protected routes
- Deployment notes
- Nginx config notes
- systemd service notes
- HTTPS screenshot

### 2. Linux Hardening Labs

**Goal:** Harden a Linux server with a non-root sudo user, SSH key authentication, 2FA, custom SSH port, firewall rules, and failed-login notifications.

Folder: `02-os-admin/linux/`

Planned evidence:

- User/sudo setup notes
- SSH hardening notes
- UFW or iptables rules
- Failed-login notification script
- Screenshots of tests

### 3. Mikrotik Enterprise Network Lab

**Goal:** Build a simulated company network with Management, HR, and Sales departments, routing, firewall policies, internet access, and router hardening.

Folder: `03-networking/mikrotik-enterprise-lab/`

Important: Do not delete this lab after finishing it. It may need to be reviewed later.

Planned evidence:

- Network diagram
- IP addressing plan
- DHCP/routing notes
- Firewall rules
- Hardening checklist
- Screenshots from Winbox

## Weekly Learning Log

See [`LEARNING_LOG.md`](LEARNING_LOG.md).

## Portfolio Rules

I will keep this repo professional:

- No passwords, tokens, private keys, public IPs, or sensitive screenshots
- No instructions against real targets
- Only authorized labs and local environments
- Clear notes on what I learned and what I still need to improve
