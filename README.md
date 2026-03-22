
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

 <img width="1619" height="392" alt="image" src="https://github.com/user-attachments/assets/68320667-bddc-4674-b531-3734d6504ef4" />



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
##  Application Front End Screenshots 

<img width="959" height="468" alt="image" src="https://github.com/user-attachments/assets/b64f35ea-78bd-4a71-8858-9bd293967291" />
<img width="964" height="407" alt="image" src="https://github.com/user-attachments/assets/bda75439-76b5-41bc-b168-3289065b1606" />
<img width="957" height="496" alt="image" src="https://github.com/user-attachments/assets/467a86c5-011d-4c5f-be0a-2b0bae1b1c6e" />
<img width="1895" height="881" alt="image" src="https://github.com/user-attachments/assets/6da24360-04be-42f8-9dcd-246cc68a7325" />
<img width="1892" height="830" alt="image" src="https://github.com/user-attachments/assets/3e28638c-6a5e-4165-90a9-768bf689ea20" />



---

##  Please go through the Documentation for more technical information
