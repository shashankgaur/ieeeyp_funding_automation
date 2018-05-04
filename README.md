# ieeeyp_funding_automation
IEEE Young Professionals Funding Portal Automations using Google Apps Script
IEEE Young Professionals Funding Portal (http://yp-events.fluidreview.com/) uses fluidreview to approve funding for volunteer events. However, it requires external support to send approved events to the website calendar, provide organizers with external material in attachment to the email and collect survey responses for each event itself.

We use Google Apps Script to achieve that. We push raw data for each approved event to the a google sheet via a parser bot provided by Zapier. In addition, we use SurveyMonkey to maintain the surveys and push the survey responses to a google sheet from Zapier using Zapier itself.

We are in process of building our own Parser bot and Surveymonkey API app to avoid Zapier, but for now Zapier serves as the middleman.

