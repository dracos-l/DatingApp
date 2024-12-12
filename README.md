# Amora: A Matchmaking Web Application

Amora is a web application designed to help users find potential dinner dates at a romantic restaurant setting. This project was collaboratively developed by **Justin Aronwald** and **Logan Dracos**, featuring enhanced matchmaking functionality, an intuitive interface, and several additional features for an engaging user experience.

---

## **Features**

### **Core Functionality**
- **User Authentication & Profiles:**
  - Secure account creation, login, and logout.
  - Public profiles with editable fields for name, gender, year of birth, description, and profile photo.
- **Matching & Preferences:**
  - Users can set gender and age preferences for potential matches.
  - Ability to like or block users.
  - Match suggestions based on mutual preferences.
- **Date Proposals:**
  - Propose dates for specific times with customizable restaurant cuisines.
  - Manage proposals with statuses such as "Accepted," "Rejected," "Ignored," or "Reschedule Requested."
  - Ensures table availability for proposed dates, handling overflow gracefully.

---

### **Additional Features**
1. **Styling Enhancements:**
   - Added polished, professional design elements, including modal windows for interactions.
   - Improved overall user interface and experience for both desktop and mobile users.

2. **Social Integration:**
   - Added a field for Instagram usernames, linking directly to the user’s Instagram account for additional connectivity.

3. **"Surprise Me" Feature:**
   - Randomly navigates to a profile matching both the user’s preferences and the other user’s reciprocal preferences.

4. **Search Results Display:**
   - Shows both search results and users falling within filter ranges side by side for easier comparison.

5. **Compliments:**
   - Users can send quick, pre-generated compliments directly from the homepage without refreshing the screen.
   - Compliments are displayed on profile pages and can be deleted dynamically using the fetch API.
   - Stylishly integrated into the interface for seamless interaction.

6. **Enhanced Proposal Management:**
   - Users can select a restaurant cuisine when making a date proposal.
   - Each restaurant features a set maximum number of tables, ensuring fair availability across multiple locations.
   - Proposals are organized into sections based on their status for clarity.
   - Overflow of proposals is handled efficiently, maintaining a smooth user experience.

---

## **Technologies Used**
- **Backend:** Python, Flask, Flask-SQLAlchemy, MySQL
- **Frontend:** HTML, CSS, JavaScript, Bootstrap, Jinja2
- **API Integration:** Fetch API for dynamic updates and interactions
- **Authentication:** Flask-Login, bcrypt for secure password management


---

## **Contributors**
- **Justin Aronwald**  
- **Logan Dracos**

We welcome feedback and suggestions! Feel free to fork the project or submit issues via GitHub.
