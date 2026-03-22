
#  Filter & Refresh Implementation in Oracle APEX

##  Overview

This project demonstrates how to implement **automatic filtering and refreshing** in an Interactive Report within Oracle APEX by eliminating the need for a manual search button.

The solution enhances user experience by enabling **real-time data updates** based on user selections.

---

##  Key Features

### Automatic Report Filtering

* Implemented using **Dynamic Actions**
* The Interactive Report refreshes automatically when values change in:

  * `P2_GENRE`
  * `P2_AUTHOR`
* Eliminates the need for a manual **Search button**
* Provides real-time data display

---

###  Application Components

* Two **List of Values (LOVs)**:

  * Genre
  * Author
* LOVs are created using **Shared Components**
* These act as filters for the Interactive Report
* Data is sourced from the `BOOKS` table
* <img width="938" height="248" alt="image" src="https://github.com/user-attachments/assets/44e0466e-7e13-450d-b0a3-27a607c697c1" />


---

###  Reset Functionality

* A **Reset button** is added in the Interactive Report’s Action Menu
* Implemented using **Dynamic Actions**:

  * Sets LOV items (`P2_GENRE`, `P2_AUTHOR`) to `NULL`
  * Refreshes the report
* Proper **sequence numbering** ensures correct execution order

---

###  User Interface & Report Management

* Users can dynamically filter data using LOV selections
* No manual submission required
* Supports Interactive Report features:

  * Aggregation
  * Sorting
  * Saved report views
* Includes a **Home Page Dashboard** for analyzing book data

---

##  Technologies Used

* Oracle APEX
* SQL / PL-SQL

---

##  Project Structure

* `app/` → APEX application export (.sql)
* `docs/` → Detailed implementation document
* `db/` → Database schema (optional)

---

##  How to Run

1. Open Oracle APEX
2. Navigate to **App Builder → Import**
3. Upload the SQL file from `app/`
4. Install and run the application

---

##  Key Learnings

* Using Dynamic Actions for real-time UI behavior
* Eliminating unnecessary user interactions
* Enhancing UX in APEX applications
* Managing Interactive Reports effectively

---

##  Author

Rahul Subramanyam
