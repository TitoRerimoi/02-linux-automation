# Hardening Decisions

1. Created dedicated service accounts for kk-api, kk-payments and kk-logs.
2. Assigned non-login shells to all service accounts.
3. Applied least-privilege permissions to application directories.
4. Used ACLs to manage shared access to log directories.
5. Enabled UFW and restricted inbound access.
6. Managed services through systemd.
7. Enabled journal persistence.
8. Configured log rotation to prevent excessive disk usage.
9. Added health monitoring output for service visibility.

These controls improve security, maintainability and operational visibility.
