## About
**Financial Dashboard Project** focuses on developing a financial dashboard with a minimalist user interface that prioritizes the display of account balances. The aim is to create a straightforward, functional tool that meets the client’s need for simplicity and accessibility, without incorporating advanced design elements or responsiveness for mobile devices. 

Account Balances Display: Users need to see a summary of their accounts with clear visuals of available balances.

Background Information Client Needs Simplicity and Accessibility: The financial dashboard must feature a minimalist interface that prioritizes ease of use and displays essential data like account balances clearly and efficiently. The focus is on making the tool accessible to users with limited technical expertise. 

Focus on Desktop Display: The project does not require mobile responsiveness or advanced design elements, as the primary use case involves desktop users. Simplicity is paramount, and the interface should remain clean and functional without unnecessary enhancements.

Core Functionality: The dashboard will display real-time account balances.

The project deployed at the address [https://financial-dashboard-project.onrender.com/](https://financial-dashboard-project.onrender.com/) by using the following technologies:
- **Render.com** - a service that simplifies the deployment process for web applications and takes care of the server configuration process.

## Planning Process
 Users Stories:

User Story 1: Viewing Account Balances
As a user, I want to view my account balances clearly displayed on the dashboard,
so that  I can quickly assess my financial standing across all accounts.
Explanation:
This is about making sure the user can easily see their balances for each account (checking, savings, and investment). The dashboard should be simple and display this information in a way that's easy to read at a glance.

User Story 2: Clear Visuals for Account Information
As a user, I want to see each account's balance and account number clearly presented,
so that the users can easily understand the details of each account without confusion.
Explanation:
The user wants the account information (like balance and account number) to be easy to understand. Each account should be shown separately, so it's clear which account is which.

User Story 3: Total Balance Overview
As a user, I want to see the total balance of all my accounts summarized at the bottom of the page, so that I can understand my total financial position at a glance.
Explanation:
The user wants to know the total balance of all their accounts combined. This total should be shown at the bottom of the page, so they don't have to add it up manually.

User Story 4: Account Summary Navigation
As a user, I want to be able to scroll through and view a summary of my accounts in a minimalist UI, so that I can access the details of my accounts quickly.
Explanation:
The user wants to easily scroll through their accounts and see all the important details quickly. The design should be simple, so it's easy to navigate and find information.



User Story 5: Reliable Data Source
As a user, I want the account balances to be pulled accurately from the JSON file,
so that I can trust the information being displayed is current and correct.
Explanation:
The account balances should be pulled correctly from the JSON file, so the user can trust that what they see is accurate. This is important for building confidence in the dashboard.

User Story 6: Error Handling for Data Issues
As a user, I want to be notified if there is an issue loading my account data from the JSON file, so that the users can be aware of any potential data errors and can contact support.
Explanation:
If there's an issue with loading the account data from the JSON file, the user should get a clear message explaining the problem. This message should help them understand what to do next, like contacting support or trying again later.


 ## Wireframe



## Setup Instructions
Access https://financial-dashboard-project.onrender.com/](https://financial-dashboard-project.onrender.com/ to view our project live.

OR Manual Set-up:
1. Clone the repository.
2. Navigate to the project directory.
3. Run `mvn spring-boot:run` to start the server.
4. Visit `http://localhost:8080` in your browser to view the dashboard.
   

## Features
- Display account balances from a JSON file using a backend API call.
- Minimalist UI with basic functionality of displaying account balance.


## Technologies Used
- Java
- Spring Boot
- JavaScript
- HTML
- JSON for data
- CSS, Bootstrap for styling


