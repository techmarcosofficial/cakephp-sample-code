# 🍰 CakePHP Project Structure Overview

This CakePHP-based project follows a modular MVC architecture and includes several custom **Components**, **Controllers**, **Helpers**, and **Models** to handle apartment listings, realtor management, dynamic forms, UI rendering, and more.

---

## 🧩 Components

Reusable service logic used across controllers.

| Component Name           | Description                                                               |
|--------------------------|---------------------------------------------------------------------------|
| `EmailManagerComponent`  | Sends emails using dynamic content and predefined email templates         |
| `ThumbComponent`         | Generates custom thumbnail images from uploaded images                    |

---

## 🧠 Controllers

Manage user requests, business logic, and data coordination.

| Controller Name         | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `ApartmentsController`   | Handles apartment CRUD operations, approval, floor plans, images, e-blasts |
| `RealtorsController`     | Manages realtors, their assigned regions, and related apartments           |

---

## 🛠 Helpers

Custom helpers to simplify view rendering and UI components.

| Helper Name           | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `BreadcrumbHelper`     | Renders breadcrumb navigation                                               |
| `CustomFormHelper`     | Generates forms from an array of inputs and buttons                         |
| `DetailHelper`         | Displays apartment details in a formatted layout                            |
| `FormatterHelper`      | Adds formatting for units, dates, and custom values                         |
| `HeadingHelper`        | Creates section headings dynamically from arrays                            |
| `ListingHelper`        | Manages listings with search and sorting capabilities                       |
| `MapHelper`            | Displays a map with a popup window                                          |
| `SidebarHelper`        | Generates the admin sidebar menu                                            |
| `TopMenuHelper`        | Renders the top navigation menu from array input                            |

---

## 🗂 Models (Tables & Entities)

Represent the data layer and contain business rules.

| Model Name     | Description                          |
|----------------|--------------------------------------|
| `Apartment`     | Represents apartments and their data |
| `User`          | Represents users and their roles     |

---

## 📁 Simplified Directory Structure

