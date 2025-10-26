# CS/IT Laboratory Scheduler - Static Version

This is a static HTML version of the CS/IT Laboratory Scheduler application, designed to be hosted on GitHub Pages or any static web hosting service.

## Features

- **Dashboard**: View today's schedules and announcements
- **Schedule Management**: Create and view laboratory schedules
- **Faculty Management**: Add and manage faculty members
- **Announcements**: Create and view announcements
- **Responsive Design**: Works on desktop and mobile devices

## File Structure

```
static-cils/
├── index.html                 # Main landing page
├── login.html                 # Login page
├── dashboard.html             # Faculty dashboard
├── create-schedule.html       # Create new schedule
├── view-schedules.html        # View all schedules
├── create-announcement.html   # Create announcements
├── faculty-management.html   # View faculty list
├── add-faculty.html          # Add new faculty
├── styles.css                # Main stylesheet
├── login.css                 # Login page styles
├── script.js                 # Main JavaScript
├── sidebars.js               # Sidebar functionality
├── assets/
│   └── Scitech logo.png      # Logo image
└── data/
    ├── schedules.json        # Sample schedule data
    ├── announcements.json    # Sample announcement data
    ├── faculty.json         # Sample faculty data
    └── course_codes.json    # Sample course data
```

## Demo Data

The application includes sample data for demonstration purposes:

- **Schedules**: Various class schedules for CS and IT programs
- **Faculty**: Sample faculty members with different subjects
- **Announcements**: Sample announcements about laboratory rules and updates
- **Course Codes**: Available courses for CS and IT programs

## How to Use

1. **Open `index.html`** in a web browser to view the public dashboard
2. **Click "LOGIN"** to access the faculty portal
3. **Navigate through the sidebar** to access different features:
   - Home: View today's schedules
   - Create Schedule: Add new laboratory schedules
   - View Schedules: See all weekly schedules
   - Create Announcement: Post new announcements
   - Faculty Management: Manage faculty members

## Features in Detail

### Dashboard
- Displays today's laboratory schedules
- Shows current time and date
- Lists recent announcements
- Displays laboratory rules

### Schedule Management
- Create schedules for classes or events
- Set repeat days for recurring schedules
- Assign faculty to schedules
- View schedules by day of the week

### Faculty Management
- Add new faculty members
- Edit existing faculty information
- View faculty list with contact details
- Assign subjects to faculty

### Announcements
- Create announcements with text and images
- View announcements on the dashboard
- Track announcement dates and authors

## Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Bootstrap 5.3.3, Custom CSS
- **Icons**: LineIcons 4.0
- **Fonts**: Google Fonts (Montserrat, Roboto)
- **Data**: JSON files for sample data
- **Responsive**: Mobile-friendly design

## Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Deployment

This static version can be deployed to:

- **GitHub Pages**: Upload the entire `static-cils` folder to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Import the folder as a static site
- **Any Web Server**: Upload files to any web hosting service

## Notes

- This is a **demo version** - no actual data is saved
- All forms show success messages but don't persist data
- The application simulates a real laboratory scheduling system
- Perfect for showcasing the UI/UX design and functionality

## Original Application

This static version is based on a PHP/MySQL laboratory scheduling system for Manila Central University's CS/IT department.

## License

This project is for educational and demonstration purposes.
