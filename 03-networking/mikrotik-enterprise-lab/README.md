# Mikrotik Enterprise Network Lab

## Important

Do not delete this lab after finishing it. It may need to be checked later.

## Goal

Build a simulated enterprise network with:

- Management
- HR
- Sales
- Internet router
- Department routers
- Department client VMs
- Controlled routing
- Firewall rules
- Router hardening

## IP Plan

| Department | Subnet |
|---|---|
| Management | 192.168.1.0/24 |
| HR | 192.168.2.0/24 |
| Sales | 192.168.3.0/24 |

## Checklist

- [ ] Create router VMs
- [ ] Create client VMs
- [ ] Configure internet router
- [ ] Configure department routers
- [ ] Set unique LAN pools
- [ ] Verify internet access
- [ ] Add routes between departments
- [ ] Verify client-to-client ping
- [ ] Block YouTube/Facebook
- [ ] Block incoming internet traffic
- [ ] Allow only TCP 443 outbound
- [ ] Apply HR-specific rules
- [ ] Apply Management-specific rules
- [ ] Create new Mikrotik users
- [ ] Delete default users
- [ ] Disable router configuration from LAN
- [ ] Apply sensible hardening rules

## Evidence

- Network diagram:
- Winbox screenshots:
- Firewall rule screenshots:
- Test results:
