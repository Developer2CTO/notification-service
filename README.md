# Notification as a Service
A Spring boot microservice for Notification

## Scope

Most application has a pressing need to send notifcation message(s), emails etc based on the application use cases. This project is an effort to generalize the usecases and create a re-usable microservice. 

### Classification (classifying notification based on)
* Purpose (system update, record update, assignment, require action, etc.)
* Priority (low, medium, high)
* Rule based notifications (When to deliver notificaton, For ex: after few conditions, an escalation email will be sent seperate user lists, the number of levels should be customizable)
* Channel preference (in-app active, in-app passive, email)
* Frequency (real-time, daily, weekly, etc.)
* Display rules (separate vs. combined if user returns after X time)
* User control (what & how I want notifications to get delivered)
* Decision Tree (how to deliver notifications, example how slack does it)

