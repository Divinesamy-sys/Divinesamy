
# How AnyScan Works

AnyScan enables secure document capture and routing to configured cloud providers or destinations through the local Windows Agent.

It connects local scanning devices with cloud-based storage and workflow systems using authenticated and encrypted communication.

This article explains the main stages involved in processing a scanned document.

## Process Overview

Once setup is complete, AnyScan operates through the following stages:

1. User authentication
2. Provider and destination selection
3. Document capture
4. Secure upload
5. Confirmation and activity logging

## 1. User Authentication

Before scanning, the user must:

* Sign in with valid AnySoft credentials.
* Complete Multi-Factor Authentication (MFA), if enabled.
* Have the appropriate role and permissions.

Authentication verifies the user's identity and determines which providers and workflows are available.

## 2. Provider and Destination Selection

After signing in:

1. The user selects a linked cloud provider.
2. The user selects a configured destination for the scanned document.

Only destinations configured and made available by administrators can be selected.

## 3. Document Capture

AnyScan connects to a TWAIN-compatible scanner installed on the workstation.

During document capture, users can:

* Preview scanned documents
* Adjust scan settings
* Configure resolution
* Scan single or multiple pages

The document is temporarily processed locally before being securely transmitted.

## 4. Secure Upload

After scanning is complete:

1. The document is prepared for transmission.
2. A secure connection is established.
3. The document is uploaded to the selected provider or configured workflow destination.

Data transmission follows the configured security and authentication policies.

## 5. Confirmation and Activity Logging

After a successful upload:

* A confirmation message is displayed.
* The activity is recorded in system logs.
* Administrators can review the event in **Activity Information**.

If the upload fails, an error message is displayed and the user can retry the operation.

## Security Controls

AnyScan supports several security controls, including:

* Role-based access control
* Multi-Factor Authentication, if enabled
* Encrypted data transmission
* Tenant-level data separation

These controls help protect organizational data and restrict access to authorized users.

## Failure Handling

If an issue occurs during scanning or uploading:

1. AnyScan displays an error message.
2. The user can retry the upload.
3. Authentication or provider-related issues must be resolved before the operation can be completed.

For persistent issues, refer to the relevant troubleshooting documentation or contact the system administrator.

## Typical Use Cases

AnyScan can be used for workflows such as:

* Sending scanned invoices to cloud storage
* Uploading signed contracts to shared folders
* Routing scanned forms into document processing workflows
* Secure document submission for remote teams

## Related Articles

* [AnyScan Overview](overview.md)
* [AnyScan Requirements](requirements.md)
* Linking Providers and Integrations
* Managing Provider Permissions
* Viewing Activity Information
