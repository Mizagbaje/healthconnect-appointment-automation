# HealthConnect — Healthcare Appointment Automation

A no-code workflow automation project that streamlines appointment request handling and patient email communication using Google Forms, Google Sheets, Zapier, and Gmail.

## 📌 Project Overview

HealthConnect is a healthcare administration automation prototype built to reduce repetitive manual tasks involved in receiving appointment requests, notifying staff, and communicating appointment decisions to patients.

The project uses two separate Zapier workflows to automate new appointment notifications and appointment status updates.

## 🎯 Problem Statement

Manually managing appointment requests and communicating decisions to patients can create repetitive administrative work, delays, and inconsistent follow-up.

HealthConnect demonstrates how no-code automation can connect everyday applications to make this process more efficient.

## 🎯 Project Objectives

- Collect appointment requests through an online form.
- Store submitted information in Google Sheets.
- Notify staff when a new appointment request is received.
- Send patients an email confirming receipt of their request.
- Track appointment statuses as Pending, Approved, or Declined.
- Send patients email notifications when their status changes to Approved or Declined.

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Google Forms | Collect appointment request information |
| Google Sheets | Store appointment responses and track statuses |
| Zapier | Connect applications and automate workflows |
| Gmail | Send staff notifications and patient emails |

## ⚙️ Workflow 1: New Appointment Requests

1. A patient submits the appointment request form.
2. Google Forms records the response in Google Sheets.
3. Zapier detects the new spreadsheet row.
4. Gmail sends an email notification to staff.
5. Gmail sends a confirmation email to the patient.

**Outcome:** Staff receive a notification, and the patient receives confirmation that the request was received.

## ⚙️ Workflow 2: Appointment Status Notifications

1. Staff updates the Appointment Status field in Google Sheets.
2. Zapier detects changes to the configured status column.
3. A Zapier filter allows the workflow to continue when the status is Approved or Declined.
4. Gmail sends the corresponding status update to the patient's email address.

**Outcome:** Patients receive an email informing them of the recorded appointment decision.

The workflows were configured and tested separately.

## 📋 Appointment Statuses

- **Pending:** The request is awaiting a decision.
- **Approved:** Staff have approved the request.
- **Declined:** Staff have declined the request.

An email confirming receipt of an appointment request does not mean the appointment has been booked.

## 🧪 Testing and Validation

The following scenarios were tested during development:

- New appointment submissions and spreadsheet recording.
- Staff notification emails.
- Patient confirmation emails.
- Approved status email notifications.
- Declined status email notifications.

Fictional patient information was used for testing.

## 💡 Skills Demonstrated

- No-code workflow automation
- Trigger and action configuration
- Conditional filtering with Zapier
- Dynamic field mapping
- Google Forms and Google Sheets integration
- Gmail automation
- Workflow testing and troubleshooting
- Process documentation

## 📸 Project Screenshots

### 1. Appointment Request Form

![Appointment Request Form](screenshots/Appointment%20Form.png)

### 2. Google Sheets Appointment Responses

![Google Sheets Appointment Responses](screenshots/Google%20Sheet%20Response.png)

### 3. Example Patient Confirmation Email

![Example Patient Confirmation Email](screenshots/Example%20Email%20Confirmation.jpeg)

### 4. New Appointment Workflow

![New Appointment Workflow](screenshots/The%20New%20Appointment%20Workflow.png)

### 5. Appointment Status Change Workflow

![Appointment Status Change Workflow](screenshots/The%20Status%20Change%20Workflow%20with%20the%20approved%20and%20declined%20filter.png)

## 🚀 Future Improvements

Potential enhancements include:

- A staff-facing appointment management dashboard.
- Appointment availability and scheduling checks.
- Automated appointment reminders.
- Error monitoring and duplicate-notification prevention.
- Stronger privacy, security, and access controls.

## 🔒 Privacy and Intended Use

HealthConnect is an educational prototype, not a production-ready healthcare system. Demonstrations should use fictional patient information. Before using real patient data, appropriate privacy, security, access-control, and healthcare compliance requirements must be assessed.

## 👩‍💻 Author

Created as a hands-on project to develop practical no-code automation and process improvement skills.

