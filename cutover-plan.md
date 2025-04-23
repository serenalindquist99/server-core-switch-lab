# 🔁 Switch Cutover Plan

## Phase 1: Pre-Migration Checklist
- [x] Backup all switch configs
- [x] Document port mappings (before/after)
- [x] Notify all stakeholders

## Phase 2: Go/No-Go Criteria
- Configuration loaded and validated
- Interfaces tested for connectivity
- Redundancy and STP functioning

## Phase 3: Migration Steps
1. Disconnect old switch
2. Connect uplinks to new switch
3. Restore config to new switch
4. Test VLAN and ACL behavior

## Phase 4: Post-Cutover Validation
- Ping gateway and VLAN interfaces
- Review logs and CPU/memory
- Final confirmation from end-users

