# ⚠️ Incident Response SOP - Switch Outage

## When to Escalate:
- Loss of uplink or multiple VLANs
- ACLs not applying correctly
- Config mismatch with running vs. startup

## Steps to Triage:
1. Check LED indicators on device
2. Console into switch or SSH (if reachable)
3. `show running-config` and `show interface status`
4. Review syslog and STP errors

## Rollback Plan
1. Power down new switch
2. Plug in original switch
3. Restore old configuration from backup
