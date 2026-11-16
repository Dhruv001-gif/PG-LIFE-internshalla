# 🏠 PG Life - Student Accommodation Web Application

**PG Life** is a full-stack web application developed as the capstone project for the **Web Development Training** by [Internshala Trainings](https://trainings.internshala.com/). The platform simplifies the process of finding, comparing, and shortlisting Paying Guest (PG) accommodations for college students and working professionals across major Indian cities.

---

## ✨ Key Features

* **City-Based Search:** Search for PG accommodations across major cities (Delhi, Mumbai, Bengaluru, Hyderabad) using the search bar or quick-select city cards.
* **Filtering & Sorting:** Filter listings by gender preference (Male, Female, Unisex) and sort properties by rent (highest/lowest) or user ratings.
* **User Authentication:** Secure sign-up and login modals powered by PHP sessions and AJAX for seamless page interactions without reloads.
* **Interactive Wishlist (Interested Properties):** Logged-in users can mark PGs as "Interested" via heart icons and view live interest counts.
* **User Dashboard:** Personalized profile page displaying user details and a saved list of all marked/interested properties.
* **Detailed Property View:** Comprehensive listing pages featuring image carousels, monthly rent, available amenities (Wi-Fi, AC, Laundry, Food, etc.), cleanliness/food/safety ratings, and student testimonials.
* **Responsive Design:** Fully mobile-friendly interface built with Bootstrap 5.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript, AJAX, ReactJS
* **Backend:** PHP
* **Database:** MySQL (managed via phpMyAdmin)
* **Local Server Environment:** XAMPP / WAMP

---

## 📂 Project Structure

```text
pglife/
├── api/                  # Backend PHP endpoints (login, signup, toggle_interest)
├── css/                  # Custom stylesheets
├── img/                  # City thumbnails, property photos, and amenity icons
├── includes/             # Reusable PHP components (header, footer, database connection)
├── js/                   # Frontend JavaScript and AJAX scripts
├── index.php             # Home page with city search
├── property_list.php     # City-specific PG listings with filters
├── property_detail.php   # Detailed view of a single PG accommodation
├── dashboard.php         # User profile and saved properties
└── logout.php            # Session termination script
```

---

## ⚙️ How to Run Locally

Follow these steps to set up and run the project on your local machine:

1. **Install XAMPP:** Download and install [XAMPP](https://apachefriends.org) on your computer.
2. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/[Your-Username]/[Your-Repo-Name].git
   ```
3. **Move Project Files:** Copy the project folder into the `htdocs` directory inside your XAMPP installation folder (e.g., `C:\xampp\htdocs\pglife`).
4. **Start Services:** Open the XAMPP Control Panel and start **Apache** and **MySQL**.
5. **Set Up the Database:**
   * Open your browser and go to `http://localhost/phpmyadmin`.
   * Create a new database named `pglife`.
   * Click on the **Import** tab and upload the `.sql` database file included in this repository.
6. **Launch the App:** Open your browser and visit `http://localhost/pglife/index.php`.

---

## 👨‍💻 Author

* **[Your Full Name]**
* GitHub: [@Your-Username](https://github.com)
* LinkedIn: [Your LinkedIn Profile](https://linkedin.com)

---

## 🙏 Acknowledgements

* Built under the guidance of **Internshala Trainings** as part of the 8-week Full Stack Web Development certification program.

