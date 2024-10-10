ortfolio on GitLab/GitHub: Electronic Mailbox Notification System
1. Individual Learning Goal and Reflection (50%):
Learning Goal:
"My learning goal was to independently build an electronic mailbox notification system using the ESP8266 microcontroller that sends email notifications when mail is detected. I aimed to improve my skills in hardware-software integration, troubleshoot issues, and enhance my knowledge of communication protocols."

Reflection:
"Working on this project alone, I faced many challenges, especially around connecting the ESP8266 to the Wi-Fi network and sending secure emails using the Gmail SMTP server. I learned how to solve connection issues, integrate sensors with microcontrollers, and debug my own code. The project tested my patience and problem-solving skills, but I gained confidence in my ability to work independently. I now understand the importance of persistence and research in successfully completing complex projects."

2. DIY Problem Definition – 5WH (Who, What, Where, When, Why, How):
Who:
Homeowners, apartment dwellers, office workers, and anyone who regularly receives physical mail and is often unsure when mail has been delivered.

What:
The inconvenience of not knowing when important mail is received, which can result in delayed responses to time-sensitive documents or missed opportunities.

Where:
This issue affects users with physical mailboxes in residential areas, apartment complexes, and office buildings.

When:
The problem arises when users forget to check their mailbox or cannot check it regularly, especially when expecting important documents.

Why:
Missing out on time-sensitive letters or important documents can have negative consequences. A real-time notification system ensures that users are informed the moment their mail is delivered.

How:
By developing a smart notification system using the ESP8266, the problem of not knowing when mail arrives can be solved with an automatic email alert.

3. Products for the "Empathize and Define" Phase (at least 2):
Product 1: User Persona
"The user for this system is a busy professional or a senior citizen who receives important letters and doesn't have time or ability to frequently check their mailbox. This user values efficiency and convenience. They may already use technology for daily tasks and would appreciate the ability to manage their physical mail remotely."

Product 2: Empathy Map

Says:
"I often forget to check my mailbox, and it’s a hassle to walk there just to find it empty."
Thinks:
"There should be an easier way to know when I’ve received important mail."
Does:
"Checks the mailbox once or twice a week but sometimes misses urgent letters."
Feels:
"Frustrated when mail delivery is delayed or when they forget to check the mailbox."
4. Product for the "Ideate" Phase (at least 1):
Idea Generation:
Brainstorming solutions included sending push notifications, SMS alerts, or email alerts when mail is detected. After reviewing several options, I decided to use email notifications as they are simple, effective, and accessible to most users. I explored using different sensors like magnetic reed switches and ultrasonic sensors, and ultimately chose the ultrasonic sensor due to its accuracy in detecting the presence of mail in the mailbox.
5. Business Canvas Model:
Key Partners:
Suppliers of electronic components (ESP8266, sensors), software platforms (libraries and APIs), and email service providers.

Key Activities:
Developing the notification system, integrating hardware and software, testing, and ensuring secure communication.

Value Proposition:
A simple, reliable system that automatically informs users via email when mail arrives in their mailbox. The system is affordable and easy to set up.

Customer Segments:
Homeowners, renters, businesses, and elderly individuals who receive physical mail and need timely notifications.

Customer Relationships:
Offering user-friendly setup instructions and reliable technical support.

Key Resources:
ESP8266 microcontroller, ultrasonic sensor, secure email server, Wi-Fi connectivity, and the software used for notifications.

Channels:
Online marketplaces, tech blogs, and DIY communities for promoting and selling the system.

Cost Structure:
Cost of components, server maintenance for email notifications, potential advertising and outreach.

Revenue Streams:
Selling the system as a product, offering premium features (e.g., app integration), or creating a subscription-based service.

6. Go Viral Post for Blog:
Title:
"Never Miss a Letter Again: How I Built a Smart Mailbox Notification System with ESP8266"

Content:
"Mail is still an important part of our lives, but how often do we forget to check the mailbox? To solve this, I built a DIY mailbox notification system that sends an email when mail is delivered. Using an ESP8266 microcontroller and ultrasonic sensor, this system is easy to set up and ensures you never miss important letters again. Follow my journey and learn how you can build your own smart mailbox notification system, step by step!"

7. Overview of the Technical Solution:
Hardware:

ESP8266 Wi-Fi microcontroller
Ultrasonic sensor to detect mail inside the mailbox
Power source
Software:

Arduino IDE to program the ESP8266
Code using the ESP-Mail-Client library to send email alerts
Base64 encoding for secure authentication
Activity Diagram:
Diagram the workflow from the moment mail is detected by the sensor to sending an email notification using the ESP8266.

Use-Case Diagram:
Diagram showing the interaction between the user and the system, including the user receiving the mail notification, checking the mailbox, and system resetting.

