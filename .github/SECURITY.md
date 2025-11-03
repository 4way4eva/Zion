# Security Policy

## Reporting Security Issues

If you discover a security vulnerability in the Zion repository, please report it by emailing the repository owner or creating a private security advisory on GitHub.

**Please do not report security vulnerabilities through public GitHub issues.**

## Security Features Enabled

This repository has the following security features enabled:

- ✅ **Dependabot alerts**: Automatically notifies of vulnerabilities in dependencies
- ✅ **Code scanning (CodeQL)**: Automatically scans code for security vulnerabilities
- ✅ **Secret scanning**: Automatically detects committed secrets
- ✅ **Push protection**: Prevents accidental commits of secrets

## Supported Versions

As this is an active development repository, security updates are applied to the main branch.

| Branch | Supported          |
| ------ | ------------------ |
| main   | :white_check_mark: |
| other  | :x:                |

## Security Best Practices

When contributing to this repository:

1. Never commit secrets, API keys, or credentials
2. Use Git LFS for large binary files (already configured in `.gitattributes`)
3. Keep dependencies up to date
4. Follow the code review process (CODEOWNERS)
5. Ensure all CI checks pass before merging
