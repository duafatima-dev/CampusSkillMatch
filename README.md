# CampusSkillMatch
Campus Skill Match is a web-based system that connects university students with projects based on their skills. Students can register, add their skills, browse available projects, and apply to ones that match their skillset. Admins can post projects and manage all data
>Technologies Used
Technology     Purpose
HTML/CSS       Frontend pages and styling
PHP            Backend logic and database connection
MySQL          Database
XAMPP          Local server (Apache + MySQL)
>Database Tables
Table          Purpose
Student        Stores registered student accounts
Skill          Catalog of all available skills
Project        Projects posted by students or admin
Student_Skills Links students to their skills with level
Application    Tracks which student applied to which project
Admin          Admin login credentials
>File Structure
campusskillmatchsys/
├── index.html          → Homepage
├── login.php           → Student & Admin login
├── register.php        → Student registration
├── dashboard.php       → Student dashboard
├── skills.php          → Add/remove skills
├── browse.php          → Browse & apply to projects
├── applications.php    → View application status
├── admin-dashboard.php → Admin homepage
├── post-project.php    → Admin posts new project
├── manage-data.php     → Admin manages students & projects
├── logout.php          → Destroys session and logs out
├── db.php              → Database connection
└── style.css           → Stylesheet
