# HealthConnect — Healthcare Appointment Automation

A no-code healthcare appointment workflow built with Google Forms, Google Sheets, Zapier, and Gmail.

## Project Overview

HealthConnect is a learning project designed to streamline appointment request handling and patient communication. It automates the collection of appointment requests, staff email notifications, patient confirmation emails, and email updates when appointment statuses change.

## Problem Statement

Manually handling appointment requests and notifying patients about decisions can create repetitive administrative work and delays in communication.

## Project Objectives

- Collect appointment requests through an online form.
- Store submitted information in Google Sheets.
- Notify staff when a new request is submitted.
- Send patients an email confirming receipt of their request.
- Track appointment statuses as Pending, Approved, or Declined.
- Notify patients by email when their appointment status changes to Approved or Declined.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Google Forms | Collect appointment request information |
| Google Sheets | Store requests and track appointment statuses |
| Zapier | Connect applications and automate workflows |
| Gmail | Send staff notifications and patient emails |

## Workflow 1: New Appointment Requests

1. A patient submits the Google Form.
2. The response is recorded in Google Sheets.
3. Zapier detects the new spreadsheet row.
4. Gmail sends a notification to staff.
5. Gmail sends a confirmation email to the patient.

## Workflow 2: Appointment Status Notifications

1. Staff updates the Appointment Status field in Google Sheets.
2. Zapier monitors the configured status column.
3. A filter allows the workflow to continue when the status is Approved or Declined.
4. Gmail sends an appointment status update to the patient's email address.

The workflow uses separate automation processes for new appointment requests and status updates.

## Appointment Statuses

- **Pending:** The request is awaiting a decision.
- **Approved:** The request has been approved by staff.
- **Declined:** The request has been declined by staff.

An email confirming receipt of a request does not mean the appointment has been booked.

## Testing and Validation

The following were tested during development:

- New appointment submissions and spreadsheet recording.
- Staff notification emails.
- Patient confirmation emails.
- Approval status email notifications.
- Decline status email notifications.

Test submissions using fictional patient information were used to validate the workflows.

## Skills Demonstrated

- No-code workflow automation
- Trigger and action configuration
- Conditional filtering
- Dynamic field mapping
- Google Sheets integration
- Gmail automation
- Workflow testing and troubleshooting

## Future Improvements

Potential enhancements include:

- A staff-facing appointment management dashboard.
- Appointment availability and scheduling checks.
- Automated appointment reminders.
- Error monitoring and duplicate-notification prevention.
- Additional privacy and security controls.

## Privacy and Intended Use

HealthConnect is an educational prototype, not a production-ready healthcare system. Use fictional patient information for demonstrations. Before using real patient data, assess applicable privacy, security, access-control, and healthcare compliance requirements.

## Author

Created as a hands-on project to develop practical no-code automation skills.


## 📸 Project Screenshots

### 1. Appointment Request Form
![Appointment Form](screenshots/Appointment%20Form.png)

### 2. Google Sheets Appointment Responses
![Google Sheet Response](screenshots/Google%20Sheet%20Response.png)

### 3. Example Patient Confirmation Email
![Example Email Confirmation](screenshots/Example%20Email%20Confirmation.jpeg)

### 4. New Appointment Workflow
![New Appointment Workflow](screenshots/The%20New%20Appointment%20Workflow.png)

### 5. Appointment Status Change Workflow
![Status Change Workflow](screenshots/The%20Status%20Change%20Workflow%20with%20the%20approved%20and%20declined%20filter.png)

*Note: This project is an educational automation prototype using sample data. Real patient information should not be used without appropriate privacy, security, and compliance safeguards.*
