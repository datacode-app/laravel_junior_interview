### Project Description: **Real-Time Notification System**

#### Overview
Develop a simple web application where users can receive real-time notifications. These notifications could simulate alerts that users might need to see immediately, such as system warnings, news alerts, or custom messages from an admin panel.

#### Core Features
1. **User Authentication**:Simple login and registration.
   
2. **Real-Time Notifications**: Authenticated users should receive real-time notifications. These can be triggered via a simple admin interface or a command line command. Use Laravel Echo with Pusher (or Laravel WebSockets for a server-based approach) to broadcast notifications to users.

3. **Notification Display**: On the client side, use Flutter, Vue.js, or another lightweight JavaScript framework/library integrated with Laravel to listen for notifications and display them to the user dynamically, without page reloads.

4. **Notification Management**: Create a simple notification interface. This could be accessible only by users with admin roles.

#### Advanced Features (Optional)
- **Notification History**: Store notifications in the database and allow users to view a history of their notifications.
- **User Preferences**: Let users opt in or out of certain types of notifications.

#### Technologies
- **Backend**: Laravel for the application logic, handling authentication, and web socket events.

Frontend**: Use Flutter or Blade for the layout combined with Alpine.js or Vue.js for reactive components to display notifications in real time.
- **Websockets**: Utilize Laravel Echo with Pusher or Laravel WebSockets to handle real-time broadcasting.
- **Database**: MySQL or SQLite to store user and notification data, if implementing notification history or preferences.

#### Evaluation Criteria
- **Functionality**: The system should reliably deliver real-time notifications to users when triggered.
- **Code Quality**: Follow Laravel best practices, with clean, well-organized, and well-documented code.
- **Websockets Integration**: Effective use of WebSockets for real-time communication between the server and clients.
- **UI/UX Design**: While the focus is on the backend and real-time functionality, the user interface for displaying notifications should be intuitive and user-friendly.

#### Deliverables
Candidates should submit the project as a Git repository link containing:
- All source code.
- A README file with setup instructions, including how to configure websockets.
- An explanation of the project's structure and any special instructions for triggering notifications.
- A video or URL to see the functionality 
