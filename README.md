## SchedPro - Professional Scheduling Platform

### Introduction

**SchedPro** is a modern web application designed to streamline scheduling, appointment management, and time optimization for professionals and teams. The platform enables users to manage their availability, schedule appointments, organize group events, and gain insights through real-time analytics. With its intuitive interface and seamless integration of features such as booking links, recurring events, and time zone management, **SchedPro** helps users stay organized and effectively manage their time.

### Project Type

🛠️ **Fullstack**

### Deployed App

- **Frontend**: https://schedpro.netlify.app/ 🌐
- **Backend**: Firebase Services ☁️  
- **Database**: Firebase Firestore 📊

### Directory Structure

```
schedpro/
├── index.html
├── dashboard.html
├── css/
│   ├── styles.css
│   ├── dashboard.css
├── js/
│   ├── main.js
│   ├── dashboard.js
├── firebase.js
```

### Features

- ✅ **User Authentication**: Sign up and log in using Firebase Authentication.
- 📅 **Appointment Scheduling**: Easily add, edit, and manage appointments.
- 📆 **Availability Management**: Set and update your availability for others to book appointments.
- 👥 **Group Sessions**: Organize and manage group events.
- ♻️ **Recurring Events**: Schedule recurring events for tasks or meetings that occur regularly.
- 🌍 **Timezone Management**: Handle time zone differences for meetings and appointments.
- 📈 **Real-Time Analytics**: Track your meetings, availability rates, and group sessions.
- 🎨 **Customizations**: Adjust settings and preferences for a personalized experience.
- 💳 **Payment Integration**: Manage and process payments for services or bookings.

### Design Decisions or Assumptions

- 📱 **Responsive Design**: Focused on creating a responsive layout to ensure a seamless experience across different devices, including mobile and desktop.
- 🔄 **Real-Time Data**: Utilized Firebase Firestore and Realtime Database for real-time synchronization of data, ensuring up-to-date information on appointments, availability, and more.
- 🗺️ **Simple Navigation**: Implemented a sidebar navigation for easy access to features such as appointments, availability, calendar, and group events.
- 🔒 **Security**: Used Firebase Authentication for secure login and user management.

### Installation & Getting Started

To get started with the **SchedPro** project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/WANI-SHAFIQ/scheduling-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd SchedPro
   ```

3. Open the `index.html` file in your preferred browser to launch the app.

4. **For Firebase Setup**:

   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Copy the Firebase config object and add it to `scripts/app.js`.

5. **Deploy the app** (optional):

   - Install Firebase CLI:

     ```bash
     npm install -g firebase-tools
     ```

   - Log in to Firebase:

     ```bash
     firebase login
     ```

   - Deploy the app:

     ```bash
     firebase deploy
     ```

### Usage

To use **SchedPro**:

1. ✍️ **Sign up or log in** using the interactive login page.
2. 📋 **Manage appointments** by adding and editing them in the **Appointments** section.
3. 🕒 **View and update your availability** to allow others to book appointments.
4. 👥 **Organize group events** and set recurring events as needed.
5. 📊 **Check real-time analytics** and manage customizations from the dashboard.

### Credentials

Test credentials for demo purposes:

- **Email**: testuser@example.com 📧
- **Password**: Test1234 🔑

### APIs Used

- 🔑 **Firebase Authentication**: For user authentication and secure login.
- 📂 **Firebase Firestore**: For storing and retrieving appointment and user data in real-time.
- 🔄 **Firebase Realtime Database**: For real-time updates and synchronization of appointment data.

### Technology Stack

- 🖥️ **Frontend**: HTML, CSS, JavaScript
- ☁️ **Backend**: Firebase Authentication, Firestore, Realtime Database
- 🔄 **Version Control**: GitHub for collaboration and source control
- 🌐 **Hosting**: Firebase Hosting (optional for deploying your app) 

Feel free to adjust the icons as desired!
