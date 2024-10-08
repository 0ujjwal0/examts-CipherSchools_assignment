
# **Examts - A Test Environment Platform**

## **Overview**

The Test Environment Platform is a comprehensive solution designed for creating, managing, and conducting online tests. It allows users to create tests, answer questions, and submit their responses while ensuring a seamless and user-friendly experience. The platform is built with modern web technologies and is equipped with various features like test instructions, time management, and post-test result notifications.

## **Features**

- **User Authentication**: Secure login and registration for users.
- **Test Creation**: Admins can create tests with a set of questions, options, and marks allocation.
- **Real-time Test Management**: Users can start, navigate, and submit tests with features like marking questions for review and time tracking.
- **Video Preview and Monitoring**: Users have a video preview option for added security and monitoring during the test.
- **Responsive Design**: The platform is fully responsive, ensuring a seamless experience across different devices.
- **Automated Grading**: A cron job automatically grades submissions, calculates marks, and notifies users via email.
- **Test Instructions**: Clear guidelines and instructions provided before starting the test.
- **Full-Screen Mode**: Tests are conducted in full-screen mode to prevent distractions and ensure focus.
- **Submission and Results**: Users receive their results via email after the test is graded.

## **Real Time Email**
![email](https://github.com/0ujjwal0/examts-CipherSchools_assignment/blob/main/frontend/public/email%20screenshot.png)

## **Project Technologies**

- **Frontend**: Built with React.js, it provides a dynamic and responsive user interface.
- **Backend**: Developed with Node.js and Express, it handles API requests, authentication, and data management.
- **Database**: MongoDB is used for data storage, ensuring scalability and flexibility.
- **Email Notifications**: Nodemailer and Pug are used for sending beautifully designed emails.

## **Getting Started**

### **Prerequisites**

- **Node.js**: Ensure you have Node.js installed on your system.
you just need node as everything else had been already set up for you!!

### **Installation**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/0ujjwal0/examts-CipherSchools_assignment.git
   ```

2. **Install dependencies**:
   ```bash
   cd frontend
   npm i
   npm start
   ```
   open a new terminal or split terminal
   ```bash
   cd backend
   npm i
   npm start
   ```

3. **Set up environment variables**:
   .env file is already added as the environment variable.
4. **To see the API documentation**:
   after running the project go to this link-> http://localhost:5000/api-docs

## **Usage**

1. **Login or Register**: Users must log in or register to access the platform.
2. **Start a Test**: Navigate to the test page, review instructions, and begin the test.
3. **Answer Questions**: Select answers, mark questions for review, and submit the test when done.
4. **Receive Results**: Users will receive their test results via email after grading.

## **Contributing**

We welcome contributions from the community. If you find a bug or have a feature request, please create an issue or submit a pull request.


## **Contact**

For any queries or support, feel free to contact us at ujjwalsangwan2003@example.com.
