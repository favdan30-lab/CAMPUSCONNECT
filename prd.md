PRODUCT REQUIREMENTS DOCUMENT (PRD)
CAMPUSCONNECT
Centralized Campus Information System
Institution: Babcock University, Ilishan-Remo, Nigeria
Course: BU-209 
Assignment: Week 4
Project Type: University-wide Information Management System

1. PROJECT OVERVIEW
- Introduction
CampusConnect is a proposed centralized information platform designed to improve communication within Babcock University. It aims to bring important university announcements, academic updates, departmental notices and event information into one accessible location.
Currently, information may be distributed through different channels, including WhatsApp groups, university websites, noticeboards and word of mouth. This can make it difficult for members of the university community to find accurate and relevant updates.
- Product Vision and Objectives
The vision is to create a reliable platform that connects the university community through organized and verified information.
Its main objectives are to:
- Centralize university announcements.
- Improve access to relevant information.
- Reduce the circulation of unverified updates.
- Make announcements searchable and organized.
- Restrict publishing to authorized personnel.
- Preserve previous announcements for reference.

2. PROBLEM STATEMENT
University information is essential for academic and administrative activities. However, distributing announcements across multiple communication channels may cause students, lecturers and administrators to miss important updates or struggle to identify accurate information.
Messages can also become outdated, duplicated or distorted as they circulate through informal channels.
CampusConnect proposes a centralized platform where authorized university administrators and departmental representatives can publish information, while students, lecturers and administrators can access relevant announcements.
The actual extent of this problem at Babcock University will be established through surveys, interviews and observations.

3. TARGET USERS AND STAKEHOLDERS
CampusConnect will serve the entire Babcock University community.
- Students: Access university announcements, academic updates, deadlines and events.
- Lecturers: Access relevant academic and departmental information.
- Administrators: Access information related to university operations.
- University Administrators: Manage official announcements and publishing permissions.
- Authorized Departmental Representatives: Publish relevant departmental updates.
Only university administrators and specifically authorized departmental representatives will have permission to publish announcements. Other users will have viewing access according to their roles.

4. PROPOSED SOLUTION AND CORE FEATURES
CampusConnect will be a responsive web-based platform with the following features:
1. User Authentication: Secure account access for registered users.
2. Role-Based Access Control: Different permissions for students, lecturers, administrators and authorized publishers.
3. Announcement Management: Authorized personnel can create, edit and withdraw announcements.
4. Categories: Information organized into academic, departmental, administrative, examination, event and general announcements.
5. Audience Targeting: Announcements can target the entire university, specific schools, departments or academic levels.
6. Search and Filtering: Users can locate announcements by keywords and categories.
7. Source Identification: Every announcement displays its publisher and publication date.
8. Archiving: Expired and withdrawn announcements are retained according to the archive policy.

5. FUNCTIONAL REQUIREMENTS
ID| System Requirement
FR-01| Users shall be able to log in securely.
FR-02| The system shall assign roles and permissions.
FR-03| Only authorized publishers shall create announcements.
FR-04| Publishers shall edit and withdraw announcements.
FR-05| Users shall view published announcements.
FR-06| Users shall search and filter announcements.
FR-07| Publishers shall select announcement categories and target audiences.
FR-08| Announcements shall display their source and publication date.
FR-09| The system shall support expiry and archiving.
FR-10| Administrators shall manage authorized publisher accounts.

6. NON-FUNCTIONAL REQUIREMENTS
- Security: Protect user information and restrict publishing operations.
- Performance: Load announcements efficiently under normal conditions.
- Reliability: Maintain consistent access to published information.
- Scalability: Support increasing users and announcements.
- Usability: Provide a simple and accessible interface.
- Compatibility: Support mobile devices, tablets and desktop browsers.
- Privacy: Collect and protect only necessary personal information.
- Maintainability: Allow future modifications and improvements.

7. MINIMUM VIABLE PRODUCT (MVP)
The first version will focus on essential features required to establish a functional information platform.
Included features:
- User authentication.
- Role-based access control.
- Announcement creation and management.
- Centralized announcement feed.
- Categories and audience targeting.
- Search and filtering.
- Publisher identification.
- Announcement expiry and archiving.

8. BACKEND AND DATA REQUIREMENTS
The backend will manage authentication, permissions, announcement storage and information retrieval.
Proposed Data Entities
Entity| Main Data
Users| User ID, name, email, password hash, role ID, department ID
Roles| Role ID, role name, permissions
Departments| Department ID, name, school ID
Announcements| ID, title, content, publisher ID, category ID, dates, status
Categories| Category ID, name, description
Notifications| Notification ID, user ID, announcement ID, status
Backend Responsibilities
The backend must authenticate users, enforce publishing permissions, store and retrieve announcements, apply audience restrictions, manage categories and maintain records of important publishing activities.
The database structure and architecture will be finalized after evaluating the requirements. No programming language or framework is selected at this stage.

9. USER FLOW
Student/Lecturer/Administrator:
1. Open CampusConnect and log in.
2. The system identifies the user's role and relevant department.
3. View relevant published announcements.
4. Search or filter information.
5. Open announcements to view full details.
Authorized Publisher:
1. Log in using an authorized account.
2. Create an announcement.
3. Enter its title and content.
4. Select a category and intended audience.
5. Publish according to the approved publishing process.
6. Edit or withdraw the announcement when necessary.

10. SUCCESS METRICS
The platform's effectiveness will be evaluated through:
- Number of active users.
- Number of announcements published.
- Percentage of intended users reached.
- Time required to locate announcements.
- Number of active authorized publishers.
- User satisfaction ratings.
- Successful announcement searches.
Specific targets will be established after baseline research and usability testing.

11. RISKS AND CONSTRAINTS
Risk| Proposed Mitigation
False information| Verify and authorize publishers.
Unauthorized publishing| Enforce role-based permissions.
Low user adoption| Improve usability through user feedback.
Outdated announcements| Implement expiry and archiving.
Information overload| Use categories and audience targeting.
Data security threats| Apply secure authentication and access controls.
Limited institutional cooperation| Obtain appropriate university authorization.
Poor connectivity| Optimize the platform for low-bandwidth access.
Institutional cooperation will be important before the platform can operate as an official university information source.

12. RESEARCH AND VALIDATION
Research will be conducted to establish the communication challenges experienced within Babcock University.
The methods will include:
- Student Surveys: Gather information about current announcement channels and difficulties accessing updates.
- Staff Interviews: Understand how lecturers, administrators and departmental representatives distribute information.
- Platform Observation: Examine existing websites, student portals, messaging groups and noticeboards.
The findings will be used to validate the problem, identify user needs and prioritize features.
Actual survey results, interview summaries, participant numbers and supporting evidence must be added after the research is completed.

13. USER STORIES
- As a student, I want to receive verified campus information so that i can stay updated on important events and announcements.
- As a student, I want to report fake news or misleading information so that other students are not misinformed.
- As a student, I want to receive notifications about important campus updates so that i do not miss useful information.
- As a lecturer or staff member, I want t share important academic information so that students can reeive reliable updates on time.
- As an admin, I want to review and verify information before it is published so that only accurate and trusted information is shared on CAMPUSCONNECT.

14. FUTURE IMPROVEMENTS
Future versions may include push notifications, email alerts, personalized feeds, calendar integration, advanced analytics, mobile applications and improved moderation workflows.
These improvements will depend on user feedback and institutional requirements.

15. CONCLUSION
CampusConnect proposes a centralized approach to distributing and managing information within Babcock University. Through organized announcements, controlled publishing permissions and efficient information retrieval, the platform aims to improve communication among students, lecturers and administrators.
The initial version will focus on authentication, announcement management, categorization, audience targeting and search functionality. Its development will be guided by actual research to ensure that it addresses a genuine university-wide problem.

