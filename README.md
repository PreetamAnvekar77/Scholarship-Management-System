# Scholarship-Management-System

The Scholarship Application System is a web application designed to streamline the scholarship application process. It empowers users to submit their scholarship applications conveniently by providing a platform to fill out personal details and upload necessary attachments.

## Features

- **User Authentication:** Users can securely log in to their accounts to access the application system.
- **Personal Details Form:** Applicants can complete a comprehensive personal details form required for the scholarship application.
- **Attachment Upload:** Users can upload essential attachments including passport photos, Aadhar cards, passbooks, income certificates, fee receipts, marksheets, and hostel fee receipts (if applicable).
- **Preview:** Applicants can review their submitted application before final submission to ensure accuracy.
- **Security Measures:** Stringent security measures are implemented to safeguard user data and prevent unauthorized access.

## Technologies Used

- PHP
- MySQL
- HTML
- CSS

## Setup

1. **Clone the Repository:** Clone the repository to your local machine using Git.
2. **Database Setup:** Set up a MySQL database and import the provided SQL schema to create the necessary tables and structure.
3. **Database Configuration:** Update the `connect.php` file with your database credentials to establish a connection between the application and the database.
4. **Web Server Setup:** Place the project files in your web server directory. For instance, if you're using XAMPP, the directory could be `htdocs`.
5. **Government Module Setup:** Within your web server directory, locate the `gov` folder. Place its contents in a folder named `gov` in your web server directory.
6. **Access the Application:** Once everything is set up, access the application through your preferred web browser.

## Usage

### User:

1. **Registration/Login:** If you're a new user, register for an account. Existing users can log in using their credentials.
2. **Fill out Form:** Complete the personal details form and upload the required attachments.
3. **Preview Application:** Review your application details on the preview page to ensure accuracy.
4. **Submit Application:** Once satisfied, submit your application for consideration.

### Government:

- **Admin Access:** Use the provided admin credentials (`username: admin`, `password: admin`) to access the government module.
- **Form Viewing:** View submitted forms for review and processing.
- **Sanction Amount:** Approve applications and sanction the required amount. Tick the green button to signify approval.
- **Deletion:** Delete incorrect or invalid forms by clicking the red delete button.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Note

Please ensure to follow all instructions carefully to set up and use the application effectively.
