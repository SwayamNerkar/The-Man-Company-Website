The Career Company - Web Application Welcome to The Career Company, a career guidance and mentorship platform. This project provides an interactive web application to connect mentors and candidates, schedule sessions, and explore various services.

🚀 Features Landing Page (home.html):

Overview of services like placements, career development, and mentorship.

Newsletter signup option.

Candidate Registration (candi.html):

Form for candidates to join and register for career support.

Mentor Registration (login.html):

Mentor form with local storage integration to save mentor data.

Mentor Profiles (mentor-profile.html):

Displays dynamic mentor profiles using data stored from mentor submissions.

Booking option to schedule a session with a mentor.

Booking System (book.html):

Book time slots with mentors.

Confirmation Page (succ.html):

Displays booking confirmation message.

Responsive & Modern UI:

Designed with HTML5, CSS3, and Font Awesome Icons for clean and professional design.

🛠️ Technologies Used HTML5 – Structure and content

CSS3 – Styling and layout

JavaScript (script.js) – Form handling, data storage, and dynamic rendering of mentors

Font Awesome – Icons for social media and UI elements

LocalStorage API – To store mentor information persistently

📂 Project Structure bash Copy Edit . ├── home.html # Landing page ├── candi.html # Candidate registration form ├── login.html # Mentor registration form ├── mentor-profile.html # Mentor profiles display ├── candi-profile.html # Additional mentor listing (backup) ├── book.html # Booking page ├── succ.html # Booking success page ├── script.js # Core JavaScript logic for form submission ⚙️ How It Works Mentor Form:

Mentor details are collected from login.html and saved to localStorage via script.js.

Profile Display:

mentor-profile.html dynamically loads all mentors from localStorage and shows them.

Booking:

Candidates can choose available slots from book.html and confirm booking.

🔧 How to Run Locally Clone this repository:

bash Copy Edit git clone Open home.html in any modern browser.

You can test mentor registration and booking features offline as they use localStorage.

🌟 Future Improvements Add backend with database for persistent data.

Include email notifications for bookings.

Improve form validation and security.

Make the UI fully mobile responsive with modern CSS frameworks (e.g., TailwindCSS or Bootstrap).
