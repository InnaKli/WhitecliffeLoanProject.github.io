---
layout: post
title: Project Planning
date: 2023-07-24 
author: <author_id>
tags: [Project Planning,  ]
---
## Project Planning

### Project stakeholders:

1. Educational institution/ Client: The Art School Photo Media Department that has requested the development of digital department’s resources rental system for school students.

2. Team developing the system: The team responsible for developing digital resources. They consist of developers, designer, tester, project manager and BA who will be responsible for organization, development and implementation of the product.

3. Students: The primary users of digital rental system. They are Whitecliffe Art School students who will access web applications to rent photo/media equipment.

4. Art School staff: The teachers who will maintain department rental inventory, authorize rental request, rent equipment and process equipment returns and return state evaluation.

5. Administrators: The individuals responsible for managing the rental database, rental system and ensuring its smooth operation.

6. Content Creators: The team members responsible for creating database of the rental equipment (posting equipment photos, description, qr codes and etc.)

7. Quality Assurance member: The team member who is responsible for testing the web application and the rental database to identify and fix any bugs, errors, or usability issues. They ensure that the developed resources meet the specified requirements and provide a smooth user experience.

## Project Scope

#### Release 1 main business process is:

Allow users to login with their Whitecliffe credential (student/teacher ID and their password) into the application, using AzureID authentication. Users will not need to create a separate username and a password for this application.

Separate users’ permission levels will be set up. Only administrators will have full access to the system.

#### Business processes for release 2 are:

A comprehensive rental equipment database will be created based on MySQL with AzureSQL.

Advanced search functionality developed, that will allow users to search equipment by name, serial number, description, location.

#### Business processes for release 3 are:

Booking application established and connected to students, teachers accounts and the rental database.

The rental duration is set as 2 weeks period, with extension possible on demand by student or teacher, editing rental status.

## Business requirements.

#### Streamlined Equipment Rental Process:

Develop a digital platform that simplifies the equipment rental process, enabling students to request equipment loans and staff to approve and manage these requests more efficiently.

#### Enhanced Data Analytics:

Implement a data analytics feature that provides insights into popular equipment, frequent renters, and peak rental periods. This information will aid decision-making and resource allocation.

#### Reduction of Manual Paperwork:

Create a system that eliminates the need for manual paperwork by allowing digital rental request submissions and approvals.

#### Remote Rental Extension:

Enable students to remotely extend or renew their equipment rentals without the need for in-person visits to teachers, enhancing convenience for both students and staff.

#### Centralized Inventory Management:

Establish a unified online inventory database that offers a comprehensive view of available equipment, reducing the risk of double-bookings and conflicts.

#### Comprehensive Rental History:

Develop a student rental database that maintains a record of rental history, aiding staff in tracking past transactions and enforcing rental policies.

#### Secure Authentication:

Integrate Azure AD authentication to ensure secure access for users while maintaining ease of use.

## User Requirements

#### Student-Friendly Interface:

Develop a user interface that is intuitive and easy for students to navigate, enabling them to submit rental requests seamlessly.

#### Transparent Rental Process:

Provide clear visibility into the rental process, allowing students to track the status of their requests and view rental history.

#### Timely Approvals and Notifications:

Ensure that rental requests are processed promptly, and users receive notifications about approval status and equipment availability.

#### Intuitive Equipment Search:

Enable students to search for specific equipment types, view availability, and make informed rental decisions.

#### User-Friendly Rental Extension:

Design a straightforward process for extending or renewing rentals, allowing users to manage their equipment usage efficiently.

#### Accessible Inventory Information:

Provide detailed equipment information, including specifications and conditions, to help users make informed rental choices.

#### Secure and Convenient Login:

Implement Azure AD authentication for secure login and easy access to the system without the need to remember additional credentials.

#### Seamless Communication:

Enable users to communicate with staff regarding rental inquiries, extensions, and returns within the platform.

## Functional requirements.

#### User Registration and Authentication:

Users shall be able to create accounts to access the web application.  The application shall authenticate user credentials to ensure secure access.

#### Role-Based Access Control:

The application shall implement different access levels for administrators, teachers, and students.  Administrators shall have full control and access rights to all functionalities.  Teachers shall have access rights to add, modify, and manage rental items.  Students shall have restricted access rights limited to browsing available rentals and submitting rental requests.

#### Equipment Rental Process:

Students shall be able to browse available equipment and submit rental requests based on their needs and desired timeframes.  Teachers shall be able to review and approve/deny rental requests from students.  The system shall provide real-time tracking of equipment availability and rental statuses.

#### Data Analytics:

The application shall generate reports and insights on popular equipment, frequent renters, and peak rental periods for analysis.  Administrators shall have access to the generated reports to aid decision-making and resource allocation.

#### Renewal and Extension:

Students shall have the option to request rental extensions or renewals through the system.  Teachers shall be able to review and approve/deny rental extension requests.

#### Centralized Inventory Database:

The system shall maintain a centralized online inventory database containing comprehensive information about available equipment.  Teachers shall be able to add, modify, and update equipment details in the inventory.

#### Student Rental Database:

The system shall maintain a student rental database that records each student's rental history, past requests, and equipment return conditions.

#### Azure AD Authentication:

The application shall integrate Azure AD authentication to ensure secure access to the system.

#### User-Friendly Interface:

The user interface shall be intuitive and user-friendly, catering to both students and staff.

#### Communication Platform:

The system shall provide a communication platform for users to interact with staff regarding rental inquiries, extensions, and returns.

#### Testing and Quality Assurance:

The application shall undergo thorough testing by the Quality Assurance team to identify and rectify any bugs, errors, or usability issues.

## Non-functional requirements.

#### Performance:

The system shall have a response time of less than 2 seconds for user actions, ensuring a smooth and responsive user experience.

The system shall support concurrent user access, with the ability to handle at least 100 simultaneous users without performance degradation.

#### Security:

User passwords shall be securely stored using hashing algorithms and encryption techniques.

Data transmission between users and the system shall be encrypted using HTTPS protocols to ensure data privacy.

The system shall implement role-based access control to prevent unauthorized access to sensitive functionalities.

#### Usability:

The user interface shall be intuitive and user-friendly, requiring minimal training for users to navigate and perform tasks.

The system shall provide clear and concise error messages to guide users in case of incorrect inputs or system errors.

#### Scalability:

The system architecture shall be designed to accommodate future growth, allowing for easy scalability as the number of users and equipment items increases.

#### Availability:

The system shall have a minimum uptime of 99.5%, with planned maintenance and updates communicated to users in advance.

#### Reliability:

The system shall have automated data backups performed daily to ensure data integrity and recovery in case of system failures.

#### Compatibility:

The system shall be compatible with modern web browsers, including Chrome, Firefox, Safari, and Edge, ensuring accessibility for a wide range of users.

#### Accessibility:

The system shall adhere to web accessibility standards (WCAG 2.0), providing features that make it usable by individuals with disabilities.

#### Documentation:

Comprehensive user manuals and documentation shall be provided to assist users, administrators, and staff in understanding system functionalities and processes.

#### Compliance:

The system shall comply with relevant data protection and privacy regulations, such as GDPR, to ensure the security and privacy of user data.

#### Maintenance:

The system shall be designed with modular components to facilitate easy maintenance and updates without disrupting overall system functionality.

![Desktop View](/assets/img/GanttChart.jpg){: width="972" height="589" }
_Our Gantt Chart_





