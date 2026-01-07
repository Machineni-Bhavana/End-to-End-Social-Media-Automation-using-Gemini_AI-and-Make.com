## End-to-End Social Media Automation using Gemini AI & Make.com
 

## Overview
This project automates social media content creation and posting using Make.com.
It watches content links from Google Sheets, summarizes them using Google Gemini AI,
and publishes platform-specific posts to LinkedIn and Telegram.

## Tech Stack
- Make.com (Automation & Orchestration)
- Google Sheets (Trigger source)
- Google Gemini AI (Content generation)
- Telegram Bot API
- LinkedIn integration

## Workflow Summary
1. New row added in Google Sheets
2. Gemini AI summarizes content
3. Router splits flow by platform
4. Platform-specific prompts generate posts
5. Content is published automatically

## Make.com Scenario
Screenshots of the automation workflow are available in:
make-scenario/scenario-screenshots


## Future Improvements
- Add approval step before posting
- Integrate post-performance analytics
- Extend automation to Twitter/X and Instagram
- Add error handling and alert notifications

## Resume Summary
Designed and implemented an AI-powered social media automation workflow
using Make.com, Google Sheets, and Gemini AI to generate and publish
platform-optimized content automatically.
