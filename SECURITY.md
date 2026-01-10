# Security Policy

## Supported Versions

The following versions of CortexMail are currently being supported with security updates:

| Version | Supported          |
| ------- | ------------------ |
| v2.0.2-Cortex    | :white_check_mark: |
| v2.0.0-Cortex    | :white_check_mark: |
| v1.1.0    | :x:                |

## Reporting a Vulnerability

We take the security of CortexMail seriously. If you believe you have found a security vulnerability, please report it to us responsibly.

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please send an email to **apiwish.boon@gmail.com**.

Please include the following information in your report:
- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full details of the steps of reproduce (e.g., HTTP request payloads, screenshots, etc.)
- Any potential impact of the vulnerability.

We will acknowledge receipt of your vulnerability report within 48 hours and strive to provide a fix or mitigation as soon as possible.

## Security Best Practices

To keep your CortexMail installation secure, please follow these best practices:

1.  **Use App Passwords**: Never use your primary account password for IMAP/SMTP. Use service-specific App Passwords (e.g., [Gmail App Passwords](https://myaccount.google.com/apppasswords)).
2.  **Environment Variables**: Keep your `.env` file secure and never commit it to version control. It is git-ignored by default in this repository.
3.  **Keep Dependencies Updated**: Regularly run `pip install -r requirements.txt --upgrade` to ensure you have the latest security patches for your dependencies.
