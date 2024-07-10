# Open-Web-Repo-for-Upskilling
A web app "Open Web Platform for Upskilling" is a web application connecting tutors offering upskilling services with individuals seeking alternative learning opportunities. 

This innovative platform bridges tutors and learners, facilitating discovery, engagement, and tailored instruction across various domains. Tutors create comprehensive profiles showcasing their expertise, while learners browse and connect based on their learning goals.
The platform incorporates secure payment, communication tools, and user reviews, fostering collaboration and quality assurance. Developed using Spring Boot ReactJS and MongoDB, it prioritizes reliability, scalability, and industry-standard practices, revolutionizing access to quality education and upskilling opportunities.


# AIM:
Master of Computer Applications
To connect learners with tutors for upskilling services through a user-friendly web application.

# OBJECTIVE:
To develop a web application using the Spring Boot framework that connects individuals seeking upskilling services with tutors, providing detailed information on available courses, tutor contact details, learner skill assessment, and availability status.

# SCOPE:
To manage all the tutors data and present the learners with a reliable website to search
necessary listings and courses for their upskilling.
This application is going to include a Streamlined UI Design.
This application will have regular updates via sending notification mail to users registered for specific updates.
This application will incorporate updating only relevant data to the user via the mail.

# Software Requirements:
1. OperatingSystem:
◦ Server: Linux (e.g., Ubuntu, CentOS) or Windows Server.
◦ Development Environment: Windows, macOS, or Linux.
2. Backend:
◦ Java Development Kit (JDK) 8 or later.
◦ Spring Boot framework for Java web development.
◦ Apache Maven or Gradle for build automation.
◦ MongoDB database server.
◦ Additional Security dependencies in Springboot framework
3. Frontend:
◦ Node.js and npm (Node Package Manager) for React development.
◦ React.js library for building the user interface.
◦ Additional libraries and frameworks as needed (e.g., React Router, Redux for
state management).


# Functional Requirements:
1. Tutor Listings: Tutors should create profiles showcasing skills, services offered, availability, contact information, and pricing. Users can search and view tutor listings based on various criteria.Tutor addition is also possible via form
2. Notification System: Users receive updates on newly enrolled members related to their interests via a subscription system. So a system similar to subscribe for a newsletter is built and user gets updated on the new listings automatically.
3. Search and Filter Functionality: Users easily search for tutors and courses using filters like subject, location, availability, and price range. Search results are clear and organized.
4. Enrollment and Booking System: Users can enroll as Tutors and also book sessions with tutors directly through the platform. The system handles enrollment using implementation of e-mail API services
7. Rating System: Users provide feedback and ratings for tutors and courses. Tutors access their ratings and feedback to enhance their services and reputation.
8. Accessibility and Usability: The web app is accessible and user-friendly for all users. It features clear navigation, readable text, intuitive interface design, and responsive layout for various devices.



# User Type 1 (Unregistered Users):
Upon entering the website blocks of tutor listings will be visible . A search option will be available to search and filter these blocks
Tags associated to the skills will be given as a column in the website which also can be used for activation
An alert is ensured to popup asking User’s mail for subscribing to regular Updates.On entry of mail the functionality is implemented and the user receives mail.
# User Type 2 (Registered Users):
All above functionalities will be available to these users also.
Upon entry users will be asked to register tutor listings and all the relevant details by including a web form hyperlink in the website whose information alone will be filled.
This information transforms to blocks of tutor listings via server .
All listings will be updated on refresh in homepage and new user added will be mailed to subscribed users
