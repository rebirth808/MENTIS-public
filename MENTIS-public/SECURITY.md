# Security Policy

MENTIS is designed around human-controlled automation and safe developer workflows.

## Reporting security issues

Please do not open public issues for sensitive vulnerabilities.

For now, report concerns privately to the repository owner.

## Security principles

- No API keys in source control
- No personal memory in public repositories
- No local `.env` files in public repositories
- No destructive command execution without confirmation
- No hidden tool execution
- No credential theft
- No unauthorized access
- No malware behavior
- No unsafe defaults

## Public repository scope

This public repository contains documentation only.

It intentionally excludes:

- implementation code
- private logs
- local configuration
- API credentials
- personal memory
- generated artifacts
- unreleased automation scripts

## Future source release checks

Before implementation code is published, it should pass:

- secret scan
- dependency review
- destructive command review
- test pass
- documentation review
- license review
- privacy review
