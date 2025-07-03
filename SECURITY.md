# Security Policy

## Supported Versions

We are committed to providing security updates for the following versions of our projects:

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| Latest - 1 | :white_check_mark: |
| Latest - 2 | :white_check_mark: |
| < Latest - 2 | :x: |

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you believe you have found a security vulnerability in any UltraDNS open source project, please report it to us as described below.

### **DO NOT** create a public GitHub issue for security vulnerabilities.

### How to Report

1. **Email us directly** at [ultradnssupport@digicert.com](mailto:ultradnssupport@digicert.com)
2. **Include the following information**:
   - Project name and version
   - Type of vulnerability (e.g., XSS, SQL injection, etc.)
   - Detailed description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact assessment
   - Suggested fix (if any)

### What to Expect

- **Initial Response**: You will receive an acknowledgment within 48 hours
- **Assessment**: Our security team will assess the reported vulnerability
- **Updates**: We will keep you informed of our progress
- **Resolution**: We will work to fix the vulnerability and release an update
- **Credit**: We will credit you in our security advisories (unless you prefer to remain anonymous)

### Responsible Disclosure Timeline

- **Day 0**: Vulnerability reported
- **Day 1-2**: Initial assessment and acknowledgment
- **Day 3-7**: Investigation and fix development
- **Day 8-14**: Testing and validation
- **Day 15-21**: Release of security update
- **Day 22**: Public disclosure (if applicable)

*Note: Timeline may vary depending on the severity and complexity of the vulnerability.*

## Security Best Practices

### For Contributors

- Follow secure coding practices
- Review code for potential security issues
- Use security-focused linting tools
- Keep dependencies updated
- Validate all inputs
- Use HTTPS for all external communications
- Implement proper authentication and authorization

### For Users

- Keep software updated to the latest version
- Use strong, unique passwords
- Enable two-factor authentication when available
- Monitor for security advisories
- Report suspicious activity immediately
- Follow the principle of least privilege

## Security Features

Our projects implement various security measures:

- **Input Validation**: All user inputs are validated and sanitized
- **Authentication**: Secure authentication mechanisms
- **Authorization**: Role-based access control
- **Encryption**: Data encryption in transit and at rest
- **Logging**: Comprehensive security event logging
- **Monitoring**: Continuous security monitoring

## Security Updates

Security updates are released as:

- **Critical**: Immediate release (0-24 hours)
- **High**: Within 7 days
- **Medium**: Within 30 days
- **Low**: Within 90 days

## Contact Information

- **General Support**: [ultradnssupport@digicert.com](mailto:ultradnssupport@digicert.com)
- **Emergency Contact**: Available through our support channels

## Disclosure Policy

We follow responsible disclosure practices:

1. **Private Disclosure**: Vulnerabilities are kept private until fixed
2. **Coordinated Release**: Security updates are released with appropriate advisories
3. **Public Disclosure**: After fixes are available, we may publicly disclose details
4. **Credit**: Contributors are credited unless they prefer anonymity

## Compliance

Our security practices align with:
- OWASP guidelines
- Industry best practices
- Relevant compliance standards
- Security frameworks
