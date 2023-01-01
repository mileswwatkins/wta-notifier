# WTA Notifier

Send an SMS when new [Washington Trails Association "work parties"](https://www.wta.org/volunteer/schedule/) become available. This service is useful because these volunteer slots typically fill up quickly, and WTA lacks a built-in notification system.

This repository is a shell that just contains a GitHub Actions workflow YML. This GitHub Actions workflow executes on a daily schedule, and uses Twilio SMS to notify the user.
