# <pre>                  IT314 - Software Engineering </pre>

#### Name       : Ranpariya Jatin Bharatbhai
#### StudentID  : 202001226
#### Date       : 02-02-2023

----

## Objective:
    Identifying Functional and Non-Functional Requirements

----
## 1. Identify FRs and NFRs
### Functional Requirements
    1. Student and Employee Login (User Login)
        - Borrowing a book and Returning a book
        - Extend return date if no other booking request are made for that particular book
        - Mark a book if it is already borrowed by someone else
        - Borrowing or returning a book require user to login
    
    2. Library Staff Login (Staff Login)
        - Retrieve the list of books that are currently on available in the library
        - View pending borrow requests that need to be finished
        - View the list of pending return requests 
        - Locating a book location on shelf by browsing or searching at the platform
        - View the day to day transaction which is done for analyzing library reach
        
    3. Librarian Login (Admin Login)
        - Create a new record to indicate the borrow of a book
        - Delete the record of the book that is borrowed
        
    4. Non-Members should be able to freely browse the books
    
    5. The user privacy should be maintained in the sense of which book (s)he is borrowing
    
    6. Web application as a final product should handle the concurrent login (or register) requests that are coming from the user and employees
    
    7. System should send the reminder email to registered student when the return date of a book is approaching
    
    8. Student/Employee could see all the book that are available in the library. User also should be able to search the book very fast that (s)he is demanding for which there should be search button
    
### Non-Functional Requirements
    
    1. Authentication - While returning the book system must authorize and validate the user login
    
    2. Scalability - The system will be used by a huge number of employees as well as research scholars, so it must adapt to handle such a high number of users
    
    3. Reliability
        - The database must be kept up to date so that it doesn't display a book as available if it isn't actually available (borrowed but not returned) or show a book as marked as borrowed by a user when that user has already the book
        - This will ensure that the user can only borrow books that are currently available and that they can only be returned if they had borrowed it.
        
    4. Maintainability 
        - The web application should have the capability of modifications and updates so that the technology used does not get outdated too quickly
        - It can be easily updated even if the developer team of the website changes after the deployment of final product
    
    5. Compatibility - The website should be easily accessible through any basic web browser that supports html5 and should be able to run on mobile phone.
    
    6. Usability - The UI of the website should be simple yet elegant so that every type of user can search books and perform other actions easily, without any special training. Option for different language and voice assistant can help in hinderless access.
    
    7. Accuracy - The information that is recorded about the books and the fines that are calculated must be accurate, reliable, and consistent.
    
    8. Credentials of the user should not leak in data breach anyway as it is privacy of concern. 

----
## 2. Identify scope, features and non-functional aspects of the following problem.

### 1. Scope
    - The application's target audience will be the 5% of the world's population who are suffering from hearing loss. 
    - This app would be targeting such people as they are the ones for whom the app is being designed for.
    - Optimizing the application to low latency than can be used for real time application.
    
### 2. Features
    - Low latency to enable real-time use
    - Alerts to user about the incoming sounds
    - The sounds recorded must also be logged properly in readable format
    - The App should alert the users when it recognizes the sounds of critical situations.
    - When a critical emergency is recognised and there is no reaction from the user, notify friends and family.
    - The app should run in the background also.

### 3. Non-Functional aspects
    - The App should alert the user through some vibrations.
    - When travelling, the app should be able to recommend the lanes with the least amount of traffic.
    - Users should be able to send their current position to friends and relatives in case of an emergency via the app.
    - Users should be able to add extra sounds, which the app must be able to identify the user.
    - The latency of the app should be at most 2 seconds.
    
----
