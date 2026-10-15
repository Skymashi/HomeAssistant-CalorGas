# Security reporting

Do not post credentials, session cookies, account identifiers, authenticated portal HTML, `.storage` files or Home Assistant backups in public issues.

Use GitHub's **Security → Report a vulnerability** facility for a private report. If unavailable, open an issue asking the maintainer to enable private reporting, without disclosing the vulnerability itself. Include affected versions and a minimal reproduction using synthetic data.

The integration sends credentials only to the exact MyCalorGas HTTPS origin and stores configuration through Home Assistant. Integration diagnostics omit login material, account IDs and reading values. Home Assistant backups may still contain credentials and should be protected.

Only the latest published release is maintained. Review third-party custom integration code before installing it into Home Assistant.
