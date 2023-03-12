# NOW-issues

NOW - No Opportunity Wasted

  

## 1.  Introduction
    

NOW is an application that can be used both by organizations/companies and users. On this app companies can post advertisements for volunteering jobs/events, on which students can apply for volunteering jobs and achieve a certain number of points. Companies can choose which user is going to be accepted or rejected based on the user’s profile information and the company organization can also keep a record of the personal information of its users (completed jobs, scored points, acceptance rate). Moreover, users can check the status of their applications for volunteering. Additionally, users that are logged in on the NOW app can track the history of points scored in the ongoing year and in the years before. Points scored in volunteering jobs and events users can use to acquire certain benefits, however, the main idea of the points scored are for the students that are interested in applying for a scholarship, jobs, and other opportunities for career.

  

## 2.  Features
    

The features that NOW includes are following:

-   Student can login and register and be verified (student)
    
-   Organization can accept invitation and login (organization)
    

  

-   Create, update, delete an opportunity (organization)
    
-   Choose an opportunity, see details, share link and apply (student)
    

  

-   Complete profile, connect with Linkedin and download PDF (student)
    
-   See active and completed opportunities (student)
    

  

-   Approve or reject students for created opportunity (organization)
    
-   See list of students and their performance (organization)
    

  

## 3.  User interface
    
Wireframes can be seen on a link: https://balsamiq.cloud/s4a5j6m/payzzo7
-   Landing page (organization and student)
    
-   Registration page (organization and student)
    
-   Login page (organization and student)
    
-   Onboarding page (student)
    
-   Opportunity page (student and organization)
    
-   My Engagements (student)
    
-   Portfolio page (student)
    
-   Student application page (organization)
    
-   Creating opportunity (organization)
    
-   Student list (organization)
    

  

## 4.  Functionality
    

### 4.1. Landing page (organization and student) [#1](https://github.com/Cerka24/NOW-issues/issues/1)

Starting with a landing page that can be accessed by both students and the organization is designed to simplify the way students/organizations work and collaborate with others. Our app offers a clean and simple user interface, making it easy to navigate and get the job done efficiently and effectively.

However, depending on the user's status (student or organization), there will be two different ways to become a member of NOW. When accessing the landing page, there will be a short description for everyone willing to post jobs or tasks for students, which will lead them to a registration form exclusively created for organizations. Students, on the other hand, will need to go through a registration form if they are using the app for the first time, or a login page if they are frequent users. Both the register page and the login page can be accessed through buttons on the landing page.

With the minimalist look and functions of the site, we have achieved that regardless of whether users are beginners or experts, they can easily complete their account settings.

Whether organization is looking for students to complete tasks or a student is seeking job opportunities, our web app can simplify and enhance that experience.

  
  

### 4.2. Registration and login page (organization and student)

The registration page is a crucial step in creating a user account on our platform. It's important to us that the registration process is as seamless and user-friendly as possible. Therefore, we have designed our registration page to be used only once by each user and ask only for essential information needed to create the account.

In addition to the user's name, email, and password, we have also included a phone number field on the registration form. This additional information serves as an extra layer of protection to keep user data safe. We use this information for verification purposes.

After the user has filled in the required information and closes the registration form, they will receive a code number through a SMS message. This code number needs to be entered in the input field that will appear on the page to complete the registration process. This verification process ensures that only the registered user can access their account, adding an extra layer of security to their personal data.

Once the user has successfully created their account, they will be able to log in to our platform through the login form. The login form requires an email and password already created through the registration form. If the user does not have an account and uses the login form, the system will automatically redirect them to the registration page, ensuring that every user has a registered account.

  

### 4.3. Onboarding page (student)

Onboarding page represents a form that needs to be filled out by a student in order to apply for a volunteering job. This page includes fields such as short bio and list of certificates, where students need to write their short description about themselves and the achievements that they obtained during their academic career. University year and chosen organization represents two dropdown menus and students are also required to upload their photo, write their GPA and then to paste a link from their LinkedIn account.

  

### 4.4. Opportunity page (pages:feed, details, modals: create opportunity and apply for) (student and organization)

Opportunity page enables students to search for new volunteering jobs/events. On this page companies could make new advertisements for the job (with description and requirements). Window for adding new advertisements contains several fields: title, open until, description and requierments. The navigation part of this page for companies include: opportunities, all my students and logout.

When students are applying for a job/event students can submit their motivational letter in a new window. This window includes a submit button.

  

### 4.5. My Work page (student)

The Work page is accessed only by a student. Besides displaying the list of all opportunities which were applied for by a student, it also provides a view of the status of every application, no matter whether it was accepted or rejected by an organization. In short, this page shows the history of all opportunities for which the student sent the applications to the organizations.

The tabular form of the past applications includes:

-   the name of the opportunity
    
-   the name of the organization that posted it
    
-   the date when the application was created
    
-   the number of points collected
    
-   the status of the opportunity
    

  
  

### 4.6. Portfolio page (student)

The Portfolio page is sort of like a profile page for the student, which can be viewed by other students and an organization as well. The page provides the ability to overview the student's personal information and also displays his/her previous works.

The personal information of the student includes:

-   an image
    
-   the university he/she attends
    
-   the summary that highlights their personality or work experience
    
-   the number of points they earned volunteering that year
    
-   the total amount of points earned calculated from the time they created their account
    

We are planning on scratching some of this data from their LinkedIn profile, allowing our users to have better experience and enter less data manually. Users will on the registration provide us with the link to their LinkedIn.

  

The tabular form for the previous works consists of the components:

-   the name of the opportunity
    
-   the name of the organization that posted the opportunity
    
-   the date of finishing the opportunity
    
-   the number of points earned
    
-   in which academic year it happened
    

  

An option to download the student info is provided as well, which can be used in a similar context as a CV to earn scholarships.

  

### 4.7. Opportunity details (+ student application modal) (organization)

Opportunity details view from the organization’s side will be a preview format of what organization has published.

This content will include:

-   cover page designed image
    
-   title
    
-   how much time is left
    
-   description
    
-   requirements
    
-   date posted
    
-   organization
    

We will allow users to delete and edit their published content. Apart from created content here will be displayed a table with all submitted applications on which users will have to answer by rejecting or accepting.

Columns for that table will be:

-   ID
    
-   Student full name
    
-   Date and time of application
    
-   Student email
    
-   Status
    
-   Button which leads to details
    

That button will lead to modal which includes:

-   Student name
    
-   ID
    
-   Their application text
    
-   A link to their portfolio
    
-   Buttons: reject, accept, decide later
    

### 4.8. Student list (organization)

Student list is another page on organization’s side. There they can see a table in which are all students that are a part of their organization. The goal is to allow user’s see student’s performance.

In that table there will be following columns:

-   ID
    
-   Full name
    
-   Date joined
    
-   Email
    
-   Acceptance rate
    
-   Number of completed jobs
    
-   Points
    

## 5.  Technical requirements
    

NOW application is developed using:

-   Backend - Java, Spring framework and PostgreSQL
    
-   Frontend - Angular
    

  

## 6.  Out of scope
    

### The admin page
    

The admin panel which provides more control to the owner of the platform will enable administrators of an application to manage its configurations, settings, content, features, and carry out oversight functions critical for business. Logging in as an administrator to the platform allows an overview of the state of the platform, and not only technical and administrative tasks, but also handling of business-related issues such as helping users solve the problems, monitor the member accounts, etc. The admin is able to see (view/create/delete) all the users (students and organizations) and keep track of all opportunities posted on the app. He/She is provided with control of the content posted on the app to maintain the quality of the platform.

  

### Non-responsive UI design
    

The current UI design is not responsive. For the time being the app will not be automatically adaptive at a code-level for different screen sizes which will not offer the best user-friendly experience on smaller resolutions.

  

### Filtering jobs
    

An organization is able to require an application for the job only from certain students by using a filtering option. For example, the organization needs some designing job to be done, and by choosing a design option through the filter, the opportunity will be shown only to students who are registered to the platform as a designer.

  

### Integrated chat
    

Communication after a candidate is selected is done via email since a student's email will be visible to an organization that is providing the opportunity. Therefore, communication is not a part of the app right now since any chat inside our app is out of scope.
