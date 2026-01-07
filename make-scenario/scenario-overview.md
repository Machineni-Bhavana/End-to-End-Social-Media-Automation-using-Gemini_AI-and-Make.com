# Make.com Scenario Overview

## Scenario Name
Social Media Automation

## Purpose
This scenario automates the creation and posting of social media content
based on project or skill links provided in Google Sheets.

## Trigger
- Google Sheets: Watch when a new row is added

## Workflow Steps
1. A new content link is added to Google Sheets
2. Gemini AI summarizes the content
3. Router splits the workflow by platform
4. Gemini AI generates platform-specific content:
   - LinkedIn (professional tone)
   - Telegram (concise and engaging)
5. Content is posted automatically

## Scheduling
- Scenario runs every 15 minutes using Make scheduler

## Outcome
Reduces manual effort and ensures consistent social media posting
for student projects and learning updates.
