# Software Testing Tools

## Project
Webhook Ingestion & Retry Mechanism Hub

## Purpose
Software testing was performed using Jira to identify, track, fix, and retest defects in the webhook system.

## Bug Tracking
Six bugs were created in Jira to represent different issues in the system.

### Bugs Identified
- BUG49-1 – Webhook payload is not recorded after ingestion
- BUG49-2 – Failed webhook is not retried with exponential backoff
- BUG49-3 – Failed webhook is not moved to dead-letter queue
- BUG49-4 – Delivery status and retry attempts are not displayed
- BUG49-5 – Unauthorized access to webhook payload is possible
- BUG49-6 – Webhook delivery fails when invalid payload is received

## Testing Process

The testing process followed these steps:

1. Identify a software defect.
2. Create the bug in Jira.
3. Fix the identified issue.
4. Move the bug to the appropriate status.
5. Retest the issue.
6. Mark the bug as Done after successful retesting.

## Evidence

The screenshots below show the Jira bug tracking and testing process.

### Screenshot 1 – Jira Bug Tracker

Shows the six identified bugs in the Jira Bug Tracker.

### Screenshot 2 – Bug Retest and Completion

Shows a bug moved to the Done column after the issue was fixed and retested.
