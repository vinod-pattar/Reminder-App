# Reminder App

The **Reminder App** is a no-code solution designed to automate email reminders for upcoming events. Built using Tally Forms, Pabbly Connect, and Gmail, it allows users to effortlessly manage reminders without writing a single line of code.  

## Features

- **Event Creation**: Users can add event details using a simple Tally Form.
- **Automated Emails**: Sends email reminders automatically before the event date.
- **Customizable Timing**: Choose when to send reminders (e.g., days or hours before the event).
- **No-Code Setup**: Built using Tally Forms for input, Pabbly Connect for workflow automation, and Gmail for email delivery.

## How It Works

1. **Fill the Form**: Enter event details (e.g., event name, date, time, email) through the Tally Form.
2. **Automated Workflow**: Pabbly Connect processes the form data and schedules an email reminder.
3. **Receive Reminders**: Gmail sends a personalized reminder email to the specified address before the event.

## Use Cases

### 1. **Personal Event Reminders**
   - **Scenario**: You want to remember an upcoming friend's birthday.
   - **Steps**:  
      - Fill out the form with the friend's name, birthday date, and your email.  
      - Receive an email reminder two days before their birthday.

### 2. **Work Deadlines**
   - **Scenario**: You're managing multiple work deadlines and need reminders for each.  
   - **Steps**:  
      - Enter each task's deadline in the Tally Form.  
      - Set reminders to be sent a day before the deadlines.

### 3. **Appointment Reminders**
   - **Scenario**: You have a doctor's appointment next week.  
   - **Steps**:  
      - Use the form to set the date, time, and your email.  
      - Receive a reminder email a few hours before the appointment.

## Setup Instructions

Since this app leverages no-code tools, there is no local setup required. Follow the steps below to configure and use:

1. **Tally Form**  
   - Create a Tally Form to collect event details.  
   - Fields to include: Event Name, Date, Time, Email Address, Reminder Timing.

2. **Pabbly Connect**  
   - Create a workflow in Pabbly Connect:  
      - Trigger: Tally Form Submission.  
      - Action: Gmail to send reminder emails.

3. **Gmail**  
   - Connect your Gmail account to Pabbly Connect.  
   - Use dynamic fields to personalize the email content.

## Limitations

- Requires active Gmail and Pabbly Connect subscriptions.
- Relies on Tally Forms for data collection.

## Future Improvements

- Add SMS reminders.
- Support for recurring events.
- Integrate with calendars (Google Calendar, Outlook).

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with your enhancements or fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
