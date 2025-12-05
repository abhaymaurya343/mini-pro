R.R.I.M.T. Event Registration System 
A modern, responsive event registration web application for R.R.I.M.T. (Lucknow, Uttar
Pradesh) with real-time database integration. 
🌟 Features 
Event Management: View upcoming events with details (date, time, venue, category)
Student Registration: Easy registration form for students to sign up for events
Admin Panel: Secure admin dashboard to manage events and view registrations
Dark Mode: Toggle between light and dark themes
Real-time Database: Connected to Supabase for instant data synchronization
Export Data: Download registrations as CSV file
Responsive Design: Works seamlessly on desktop, tablet, and mobile 
🛠️ Tech Stack 
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript
Database: Supabase (PostgreSQL)
Authentication: Simple password-based admin access
Hosting: Netlify (deployment-ready) 
📊 Database Tables 
Events Table 
id - Unique identifier
name - Event name
date - Event date
time - Event time
venue - Event location
category - Type (Technical, Cultural, Sports, Workshop, Seminar, Other)
created_at - Timestamp 
Registrations Table 
id - Unique identifier
name - Student name
email - Student email
phone - Phone number
branch - Department/Branch
year - Academic year
event - Event name
registered_at - Registration timestamp
created_at - Timestamp🚀 Local Development 
Clone or download the project
Open index.html in a web browser
That’s it! No build process needed. 
🌐 Deployment to Netlify 
See the Deployment Guide for detailed instructions. 
Quick Deploy: 1. Go to https://app.netlify.com/drop 2. Drag and drop the project folder 3.
Done! 🎉 
🔑 Admin Access 
Password: rrimt2025
Access the admin panel from the “Admin Panel” tab 
🎨 Customization 
Change Branding 
Edit line 289 in index.html: ```html 
Your Institution Name 
 ### Change Admin Password
Edit line 39 in `index.html`:

const ADMIN_PASSWORD = ‘your-new-password’; ``` 
Modify Branches 
Edit lines 394-404 in index.html to add/remove branches. 
📱 Browser Support 
✅ Chrome (recommended)
✅ Firefox
✅ Safari
✅ Edge
✅ Mobile browsers 
📄 License 
Free to use for educational institutions.🤝 Support 
For issues or questions, check the browser console (F12) for error messages. 
 Built with ❤️ for R.R.I.M.T
