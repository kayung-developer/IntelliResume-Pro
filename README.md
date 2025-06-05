# IntelliResume Pro - AI-Powered Resume Builder

IntelliResume Pro is an advanced web-based resume builder featuring AI-powered suggestions (simulated), multiple templates, version control, and a simulated premium user experience. It's built entirely with HTML, CSS, and Vanilla JavaScript, utilizing Local Storage for data persistence.

**Live Demo:** 



## ✨ Features

**1. Comprehensive Resume Editor:**
*   Sections for:
    *   Personal Information (Name, Job Title, Contact, Links)
    *   Professional Summary/Objective
    *   Work Experience (Job Title, Company, Location, Dates, Description)
    *   Education (Degree, Institution, Location, Dates, Description)
    *   Skills (with optional rating for Creative template)
    *   Projects (Name, Technologies, Description, Link)
    *   Custom Sections (Premium: Title, Content)
*   Dynamic addition/removal of list items (experience, skills, etc.).
*   Input fields update the resume preview in real-time (debounced for performance).

**2. Multiple Templates & Customization:**
*   Choose from:
    *   **Classic Template:** A traditional, professional layout.
    *   **Modern Template (Premium):** A sleek, two-column design.
    *   **Creative Template (Premium):** A stylish, modern layout with visual elements like skill bars.
*   Real-time preview updates as you edit and change templates.
*   **Section Reordering:** Drag-and-drop sections in the "Layout" tab to customize their order in the preview.
*   **Visual Customization (Template-dependent):**
    *   Adjust accent color.
    *   Modify base font size multiplier.

**3. AI Assistant Tools (Simulated & Premium):**
*   **AI Draft Resume from Job Description:** Paste a job description, and the "AI" will attempt to draft a basic resume structure with relevant keywords and a summary.
*   **ATS Keyword Optimizer:** Compares keywords from a job description to your current resume content and suggests missing keywords.
*   **AI Generate Cover Letter:** Creates a basic cover letter template based on your resume and a provided job description.
*   **AI Resume Strength Score:** Provides a simulated score (out of 100) with tips for improvement.
*   **AI Keyword Density Analysis:** Shows the most frequent keywords in your resume.
*   **AI Summary Suggestion:** Offers pre-defined templates for your professional summary.
*   **AI Experience Bullet Suggestions:** Provides templates for crafting achievement-oriented bullet points for your work experience.

**4. Resume Management & Versioning:**
*   **Save & Load Resumes:**
    *   Registered users can save their resumes.
    *   "Free" users can save 1 resume; "Premium" users can save up to 5.
    *   Load previously saved resumes.
*   **New Blank Resume:** Start fresh at any time.
*   **Duplicate Resume:** Easily create a copy of an existing resume.
*   **Version History (Premium):**
    *   Automatically creates a new version with a timestamp and optional note each time a resume is saved.
    *   View the history of saved versions for the current resume.
    *   Revert the current resume to a previous version.
*   **Download Options:**
    *   **PDF:** Uses the browser's print-to-PDF functionality.
    *   **JSON:** Download the raw resume data and settings for backup or future import.

**5. User System (Simulated):**
*   **Login/Register:** A simple username-based system (no passwords for this simulation).
*   **Premium Tier:**
    *   Users can "Upgrade to Premium" (simulated, no actual payment).
    *   Premium status unlocks specific features (marked with a "Premium" tag).
*   User preferences (like dark mode) and resumes are tied to the logged-in user.

**6. UI/UX Enhancements:**
*   **Dark Mode (Premium):** Toggle between light and dark themes for comfortable editing.
*   **Custom Notifications:** Non-blocking, styled notifications for actions like saving, loading, errors, etc.
*   **Responsive Design:** Adapts to different screen sizes (desktop, tablet, mobile).
*   **Sticky Header:** Keeps main navigation accessible.
*   **Clean Tabbed Interface:** Organizes resume editing into logical sections.
*   **Font Awesome Icons:** For improved visual cues.

## 🛠️ Technologies Used

*   **HTML5:** Structure of the application.
*   **CSS3:** Styling, layout, theming (using CSS Variables), and animations.
*   **Vanilla JavaScript (ES6+):** All application logic, DOM manipulation, state management, and feature implementation.
*   **Font Awesome:** For icons.
*   **Google Fonts:** For typography (Roboto, Montserrat).
*   **Local Storage:** Used for:
    *   Storing user account information (simulated).
    *   Storing saved resumes for each user.
    *   Storing global app settings (like dark mode preference) for users and guests.

## 🚀 Setup & Installation

As this is a single-file, frontend-only application:

1.  Download the `intelliresume_pro.html` file (or the full HTML provided in the project).
2.  Open the file directly in a modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3.  No build steps or server required! All functionality runs in your browser.

## 📖 How to Use / Demo Workflow

1.  **Open the `intelliresume_pro.html` file in your browser.**
2.  **(Optional but Recommended) Register/Login:**
    *   Click the "Login/Register" button in the header.
    *   Choose a username and register, or log in if you've registered before.
    *   This allows you to save your work and access premium features (after "upgrading").
3.  **(Optional) Upgrade to Premium:**
    *   Click the "Upgrade to Premium" button in the header.
    *   Confirm the simulated upgrade to unlock all features.
4.  **Fill in Resume Details:**
    *   Navigate through the tabs in the "Resume Editor" panel (Personal, Summary, Experience, Education, Skills, Projects, Custom).
    *   Enter your information in the respective fields.
    *   For sections like Experience, Education, Skills, Projects, and Custom Sections, use the "Add..." button to create new entries.
5.  **Observe Real-Time Preview:**
    *   The "Resume Preview" area on the right will update as you type and make changes.
6.  **Customize Layout & Appearance:**
    *   Go to the "Layout" tab.
    *   **Select Template:** Choose between Classic, Modern (Premium), or Creative (Premium).
    *   **Visual Customizations:** Adjust accent colors and font size multipliers (options vary by template).
    *   **Section Order:** Drag and drop the listed sections to change their order in the resume.
7.  **Utilize AI Tools (Premium):**
    *   Go to the "AI Tools" tab.
    *   Select tools like "Draft Resume from Job Desc.", "ATS Keyword Optimizer", or "Generate Cover Letter". These will typically ask for a job description.
    *   Use "Resume Strength Score" or "Keyword Density Analysis" to get simulated feedback.
    *   The "Summary" and "Experience" tabs also have inline "AI Suggest" buttons for quick content ideas.
8.  **Manage Your Resume:**
    *   Go to the "Manage" tab.
    *   **Name Your Resume:** Update the "Current Resume Name" field.
    *   **Save:** Click "Save Current Resume". You'll be prompted for an optional version note.
    *   **Load:** Click "Load Resume" to open a modal with your saved resumes.
    *   **New Blank Resume:** Clears the editor for a fresh start.
    *   **Version History (Premium):** View past saved versions and revert if needed.
    *   **Download:** Choose to download your resume as a PDF (uses browser print) or as a JSON data file.
9.  **Toggle Dark Mode (Premium):**
    *   Use the Dark Mode button in the header.

## 🌟 Premium Features (Simulated)

The following features are "locked" behind a simulated premium upgrade:

*   **Modern & Creative Templates:** Access to the more advanced resume templates.
*   **Custom Sections Tab:** Ability to add and edit fully custom sections in your resume.
*   **All AI Assistant Tools:** Full access to tools in the "AI Tools" tab (Drafting, Keyword Optimization, Cover Letter Generation, Strength Score, Density Analysis).
*   **AI Summary & Experience Bullet Suggestions:** Inline AI suggestions in the Summary and Experience tabs.
*   **Full Version History Access & Revert:** Ability to view and revert to any saved version of a resume.
*   **Multiple Resume Saves:**
    *   Free users: 1 resume save slot.
    *   Premium users: 5 resume save slots.
*   **Dark Mode:** The ability to switch to a dark editing theme.

## ⚠️ Known Limitations & Simulations

*   **No Backend Server:** All data (user info, resumes, settings) is stored in the browser's Local Storage. This means:
    *   Data is specific to the browser and device you are using.
    *   Data is not synced across different browsers or devices.
    *   Clearing browser data will erase all saved resumes and user information.
*   **AI is Simulated:** The "AI" features are designed to mimic the behavior of AI tools but use pre-defined rules, templates, and simple text processing. **They do not connect to any real external AI APIs (like OpenAI, etc.).**
*   **User Authentication is Simulated:** The login/registration system is basic, stores usernames in Local Storage, and does not involve secure password handling or a real database.
*   **Premium Upgrade is Simulated:** Clicking the "Upgrade" button simulates a premium subscription; no actual payment is processed.
*   **PDF Download Quality:** Relies on the browser's built-in "Print to PDF" functionality, so the output quality and layout fidelity can vary between browsers.
*   **Error Handling:** Basic error handling is in place, but it may not cover all edge cases.

## 🚀 Potential Future Enhancements

*   Additional resume templates.
*   More sophisticated AI simulation logic and a wider variety of suggestions.
*   Option to import resume data from a JSON file.
*   A "quick-fill" or "example" button to populate the resume with sample data.
*   (Major) Integration with a simple backend for real user accounts and cloud-based data storage.
*   (Major) Connection to actual AI APIs for genuine AI-powered content generation (would require API keys and backend infrastructure).

## 📄 License

This project is primarily for demonstration and educational purposes. Feel free to use, modify, and learn from the code. If you adapt it for other purposes, please consider the original structure and intent. No specific open-source license is formally applied, but it's shared in the spirit of open learning.
