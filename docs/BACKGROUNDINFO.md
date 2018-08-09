# Hospital Notify Background
---
### Notes from Meetings:
## Kim Eshleman
##### Director, Office of Public Health Preparedness and Response at Baltimore City Health Department

**Background:**
The Baltimore City Health Department Office of Public Health Preparedness and Response (OPHPR) among other things runs a State mandated Emergency Operation Center (EOC) during public health emergencies in the city. The purpose of which is to coordinate care between city and state agencies.

**Problem:**
There is a network of care facilities across the city that the EOC must monitor during a state of emergency (Defined as a power outage affecting 20% or more of the city). The current method of collection is labor intensive and unreliable.

**Solution:**
They would like us to build an automated data collection system for recording the operational status of the care facilities

**MVP:**
A sms/voice service that calls/texts each facility, collects responses to a defined set of questions, and updates entries in a google sheet in real time.

This could be accomplished by using twillio and google appscript via SMS or programmable voice: https://www.twilio.com/blog/2018/05/receive-sms-messages-google-sheets-apps-script.html

The google sheet has predefined validations that we will be able to manipulate in order to prioritize which facilities EOC personnel need to contact and which are in normal operation.
