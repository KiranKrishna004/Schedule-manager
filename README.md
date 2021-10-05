# Schedule-manager
Building AI course project

## Summary

This AI project works as an assistant that reads e-mails and automatically schedules meetings in the google calender along with providing meeting links and other relevant information.


## Background

If your inbox quickly fills with meeting requests managing scheduling and booking of these meetings can quickly become a chore. Having an agentive AI program that reads my e-mail correspondence, automatically schedules meetings in my online calendar, creates Teams/Skype links and collects documents, agendas and other important information and invites other participants would help me with my work efficiency.


## How is it used?

The program takes it's form as a plug in for e-mail and calendar applications. When installed and given access to the user's inbox and calendar it looks through previous e-mail correspondence and calendar bookings to learn about it's user. When a new e-mail message arrives it tries to determine whether it should class the message as a booking request and schedule an appointment or if it should ignore it. The same goes for outgoing messages. When it finds something that it thinks should result in a calendar booking it asks the user whether it should do so or not. After a while it will have learned enough to be able to operate more or less autonomously requiring less and less interaction from the user.


## Data sources and AI methods

The data used comes from either an already existing dataset or data collected from the user. The data is used to build a model for classifying a message as a booking request or not, and to extract important information about the booking such as day and time, agenda, participants and document attatchments that should be included in the booking.
The main source of data will be e-mails.
AI methods that could be used are Natural Language Processing methods such as Term Frequency Inverse Document Frequency that can classify messages based on the words in them and identify important sections of the message that contains informations such as dates and times, participants and agendas.


## Challenges

The biggest challenge would be to get users to trust the system. The technology for classifying texts and extracting information have been around for quite a while and have been used for many applications. As long as the AI program is only used for managing calendars and not unintentionally/intentionally leaking the data that has been acquired from the email's of the user's devices.

The AI program should not be used in sensitive or classified contexts such as for doctors appointments or if the information containd in the user's e-mails could contain sensitive or classified information.


## What's next?

The skills needed to create the AI program are data science/AI development, application development for the e-mail/calendar platforms and interaction design for the sysem-user interaction.
