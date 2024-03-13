The Personalized Email Sender is a Python script that sends personalized emails to recipients listed in a CSV file. It utilizes the yagmail library for sending emails and the pandas library for reading data from a CSV file.

Install the dependencies:

``pip install yagmail pandas``

Set up the env variables:

- Ensure you have set up your Gmail address as the sender (sender).
- Use a Gmail app password as the password for the yagmail SMTP connection.

Prepare your contacts CSV file:

- Create a CSV file named contacts.csv with columns for name and email.
- Populate the CSV file with the names and email addresses of your recipients.

Run the script:

``python personalized_email_sender.py``
