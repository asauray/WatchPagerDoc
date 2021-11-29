---
title: "Watchpager Documentation"
date: 2019-03-26T08:47:11+01:00
draft: false
---

# PagerDuty + ***WatchPager*** Integration Benefits

* Receive notifications on your Apple Watch regardless of other notification settings.
* Complete view of the incident on your Apple Watch, with abilities to perform all actions.
* View incidents in your complications.

# How it Works
* The applications asks to you authenticate with PagerDuty in order to retrieve an API token. ***The token is not store on our server for security reasons.***
* The backend application retrieves data about your PagerDuty account. This includes: ***Id, Name, Summary and Email***.
* The application registers a webhook on your behalf. This webhook calls our backend application which sends notifications to your Apple Watch. 
* Any time the Apple Watch receives a notification, it updates the data in the App and the active complication.

# Requirements
* This integration is intended for Apple Watch users only.
* ***WatchPager integration require the permission to create webhooks. If you do not have this role, this application will show you a screen to help you fix the problem. Please reach out to an Admin or Account Owner within your organization to configure the integration. You may also ask an Admin to create a webhook on your behalf, pointing to the URL showed in the application configuration screen.***

# Support
If you need help with this integration, please contact ***support@watchpager.sauray.net*** ***.

# Integration Walkthrough

# How to install
Search for WatchPager on the App Store
# How to Uninstall
Please send an email to support@watchpager.sauray.net with your PagerDuty email***. We will delete any data related to the WatchPager integration. This includes:
* The webhook initially created when you registered on the App.
* Any data stored on your PagerDuty account
