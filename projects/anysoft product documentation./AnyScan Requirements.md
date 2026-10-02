
# AnyScan Requirements

Before deploying or using AnyScan, ensure that the required system, hardware, network, account, and provider configurations are in place.

Meeting these requirements helps support reliable document capture and secure upload.

## System Requirements

AnyScan requires:

* Windows 10 or Windows 11
* 64-bit operating system recommended
* At least 4 GB RAM
* 8 GB RAM recommended for optimal performance
* Sufficient disk space for temporary scan processing
* A supported web browser for portal access

Supported browsers should be kept up to date.

## Hardware Requirements

AnyScan requires:

* A TWAIN-compatible scanner
* Properly installed scanner drivers
* USB or network connectivity to the scanning device

If the scanner is not detected, verify that the scanner driver is installed correctly and that the device is supported.

## Network Requirements

A stable internet connection is required for:

* User authentication
* Multi-Factor Authentication, if enabled
* Uploading scanned documents
* Communication with configured providers

Recommended network configuration includes:

* Reliable broadband connectivity
* Firewall configuration that allows required secure outbound connections

Network interruptions may result in failed uploads.

## Account and Access Requirements

Users must:

* Have an active AnySoft account
* Be assigned the appropriate role and permissions
* Have access to at least one linked provider or workflow
* Complete Multi-Factor Authentication if required

Users without the appropriate permissions may not see available providers or destinations.

## Provider Configuration Requirements

Before scanning to a cloud destination:

* A supported provider must be linked in the Portal.
* Provider authentication must be valid.
* Required provider permissions must be configured.
* At least one destination must be available to the user.

If a provider or destination is not configured correctly, scan-to-cloud functionality may not be available.

## Security Requirements

AnyScan relies on security controls such as:

* Encrypted communication
* Role-based access control
* Secure authentication methods
* Multi-Factor Authentication or SSO, where configured

## Verification Checklist

Before deployment, confirm:

* [ ] Supported Windows version installed
* [ ] Scanner connected and tested
* [ ] Scanner drivers installed and working
* [ ] Stable internet connection available
* [ ] Required outbound network access configured
* [ ] User account is active
* [ ] Correct user role and permissions assigned
* [ ] Multi-Factor Authentication configured where required
* [ ] Provider successfully linked
* [ ] Provider authentication is valid
* [ ] Required provider permissions are configured
* [ ] At least one destination is available

Completing this checklist helps identify configuration problems before users begin scanning documents.

## Related Articles

* [AnyScan Overview](overview.md)
* [How AnyScan Works](how-anyscan-works.md)
* Linking Providers and Integrations
* Managing Provider Permissions
* Installing the Windows Agent
