# AppointMe Solo

**A powerful, client-side appointment booking application designed for single service providers like tutors, therapists, hairdressers, and consultants. Manage your schedule effortlessly, even offline!**

AppointMe Solo is a single HTML file application that runs entirely in your web browser. All data is stored locally using IndexedDB, ensuring privacy and full offline functionality. No backend, no subscriptions, no internet required after the initial download.

## ✨ Features

**Core Functionality:**
*   **Service Management:** Define services offered with name, duration, and price.
*   **Visual Calendar:** Intuitive calendar interface to view and manage available slots.
    *   Month, Week, and Day views.
*   **Appointment Booking:** Easily book appointments with client details (name, contact), selected service, date/time, and notes.
*   **Appointment Viewing:** Quickly see daily, weekly, or monthly appointment schedules.

**Advanced Features:**
*   **Recurring Availability:** Set your standard working hours and days to define bookable slots.
*   **Appointment Status:** Mark appointments as Booked, Confirmed, Completed, or Cancelled.
*   **Client Contact List:** Manage a list of your clients.
*   **Client Appointment History:** View a complete history of appointments for each client.
*   **Simple Reminders:** Get desktop notifications (via Notification API) for upcoming appointments if the app is open.
*   **Data Export:** Export your appointment list to CSV or ICS (iCalendar) format.

**Technical Highlights:**
*   **Offline First:** Fully operational without an internet connection.
*   **Data Privacy:** All data (services, clients, appointments) is stored locally in your browser's IndexedDB. Nothing is sent to a server.
*   **Single File Application:** The entire app is contained within a single HTML file.
*   **Responsive Design:** Adapts to different screen sizes (desktop, tablet, mobile).
*   **Light/Dark Themes:** Switch between light and dark mode for user comfort.
*   **Accessibility:** Designed with WCAG 2.1 AA guidelines in mind.
*   **Modern UI/UX:** Clean, professional, and futuristic calendar interface.

## 🚀 How to Use

1.  **Download:** Get the `appointme_solo.html` (or whatever you named it) file.
2.  **Open:** Open the HTML file in any modern web browser (Chrome, Firefox, Edge, Safari).
3.  **Start Managing:**
    *   Go to **Services** to define what you offer.
    *   Go to **Settings** to set your recurring availability.
    *   Go to **Clients** to add your clients (or add them on-the-fly when booking).
    *   Use the **Calendar** to book and manage appointments.

## 💾 Data Storage

All application data, including your services, client list, and appointments, is stored in your web browser's **IndexedDB**. This means:
*   **Data is local to that specific browser on that specific device.** If you open the app in a different browser or on a different computer, the data will not be there.
*   **Clearing browser data/cache can delete your AppointMe Solo data.** Be cautious when clearing site data for the domain you are using to access the file (e.g., `file:///`).
*   **Use the Export feature regularly** to back up your appointment data.

## 🛠️ Technology Stack

*   **HTML5**
*   **CSS3** (with CSS Variables for theming)
*   **Vanilla JavaScript (ES6+)**
*   **IndexedDB** for client-side storage
*   **Notification API** for reminders

## 🤝 Contributing

While this is a solo project, suggestions and feedback are welcome! If you find a bug or have an idea for a new feature, feel free to open an issue.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details (if you create one, otherwise state it here).
*If you don't have a LICENSE.md, you can just state: Licensed under the MIT License.*

## 👨‍💻 Author

Created with ❤️ by **Yasin Ullah Pakistani**.
