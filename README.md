📌 Frontend Bug Monitoring – n8n Workflow

This repository contains a sanitized public version of my ongoing automation project built using n8n, Playwright, Google Sheets, and email notifications.

The purpose of this workflow is to automatically:

Run frontend tests

Detect UI bugs

Capture screenshots

Log the results

Notify team members by email

This is an active, work-in-progress project, and several enhancements are planned.

🚀 Project Goal

To automate the QA/bug-detection process for a website using:

n8n (workflow automation)

Playwright (for page interactions & screenshots)

Google Sheets (test logs & history)

Email automation (send bug reports to team)

The final system will:

Run scheduled tests on specific URLs

Identify potential frontend/UI issues

Capture screenshots of the faulty element

Save logs to a Google Sheet

Send an email report containing:

A summary of detected issues

Links to the Google Sheet entries

The screenshot of the bug

🧠 Current Status of the Project (Work in Progress)

Currently, the automation is working as expected for:

✔ Running tests
✔ Collecting metrics
✔ Triggering email notifications
✔ Pushing results into Google Sheets
✔ Capturing screenshots of the full page

🔧 What is still pending?

Right now, Playwright takes full-page screenshots, but the real requirement is:

Capture a screenshot of ONLY the specific element where the bug or error occurs.

Upcoming tasks:

 Detect the exact frontend element that fails

 Take element-level screenshots instead of whole pages

 Save screenshots to storage or DB

 Attach the screenshot directly inside the email

 Improve error-detection logic in Playwright

 Convert the workflow into Docker-ready format

 Improve Google Sheets structuring


This repo will continue to evolve as these improvements are implemented.
