# FullStack

* Bulk Email Sending: The application will enable the sending of a large number of emails to different users.

* Billing: There may be a billing component in the application, indicating that the service of sending emails may not be free.

* User Accounts: The application will require user authentication and user account management.


## The user will interact with the feedback collection application. The steps are as follows:

* Authentication: Users will sign in or sign up using Google OAuth, simplifying the authentication process.

* Payment: After signing in, users will be prompted to add money to their account or make a payment. The application will use a credit-based system, where users purchase credits that allow them to send a specific number of emails.

* Campaign/Survey Creation: Once the user has paid, they can create a new campaign or survey. They will enter a list of emails to whom they want to send the survey. The user here represents a product owner or startup owner who wants to collect feedback from their application users.

* Email Sending: The application will send an email with a feedback link to all the specified email addresses. The recipients can click on the link to provide feedback.

* Feedback Collection: The application will collect the feedback provided by the recipients of the email surveys.

* Report Generation: The collected feedback will be tabulated and summarized into a report, allowing the user to gain insights into their application's feedback and user opinions.

### Technologies

 * Authentication: Google OAuth will be used for user authentication. The backend server will be implemented using Express, and user information will be stored in a MongoDB database. The authentication process will be simplified using the Passport.js library.

* Payments: Stripe, a third-party service, will be used for handling payment transactions. Instead of directly handling credit card numbers, Stripe will handle the billing process. The payment information will be recorded in the MongoDB database.

* Campaign/Survey Creation: React and Redux will be used for creating the campaign or survey forms. Redux Form will handle the form functionality.

* Email Sending: A third-party email provider will be integrated into the application to handle sending emails to the specified email addresses. The integration process for email handling will be a significant part of the development.

* Feedback Collection: Feedback given by users in response to the email surveys will be recorded and stored. The combination of the email provider, Express backend, and MongoDB database will be used for handling feedback data.

* Report Generation: MongoDB will be utilized to store feedback data, and when users want to view the feedback, React and Redux will be used to present the data in the form of a report.

Learning FullStack with [Udemy](https://www.udemy.com/course/node-with-react-fullstack-web-development/)
