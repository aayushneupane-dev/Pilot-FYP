# 🚗 FlexRide

> **Rent. Drive. Earn.**

**FlexRide** is a modern, responsive vehicle rental platform designed for drivers and delivery partners who want to earn through ride-sharing, food delivery, courier, and parcel services without owning a vehicle.

Whether you're driving for Pathao, InDrive, Foodmandu, or working independently, FlexRide helps you choose a suitable vehicle and begin your journey.

---

## ✨ Features

### 🚙 Vehicle Rental

* Browse available rental vehicles
* Choose vehicles based on your work requirements
* Filter vehicles by:

  * Food & Parcel Delivery
  * Ride-Sharing
  * All Vehicles
* View vehicle descriptions, types, and daily rental prices

### 📝 Interactive Booking System

* Select a vehicle directly from the vehicle directory
* Open an interactive booking modal
* Enter rental duration
* Automatic rental price calculation
* View the total rental cost before proceeding
* Close the booking modal by clicking the close button or outside the modal

### 💳 Payment Selection

Choose your preferred digital payment method:

* eSewa
* Khalti

The selected payment method is used when proceeding with the booking payment flow.

### ⭐ Driver Reviews

* View existing driver reviews
* Display driver ratings using stars
* View rental statistics and rating summaries
* Submit your own review
* Select the rented vehicle
* Choose a rating
* Add your experience
* Dynamically publish new reviews using JavaScript

### 📰 Blog & Driver Insights

* Featured article about maximizing earnings
* Tips for choosing the right vehicle
* Information about digital payments
* Additional articles about:

  * Payments
  * Vehicle maintenance
  * Driver safety

### 🔐 Authentication Pages

* User Sign Up page
* User Login page
* Email and password fields
* Driving service selection during registration
* Basic client-side form handling
* Redirect to the login page after successful sign-up

### 📱 Responsive Design

The project includes responsive layouts for different screen sizes and adapts navigation, filters, forms, and content for smaller devices.

---

## 📄 Pages

| Page             | Description                                                                                   |
| ---------------- | --------------------------------------------------------------------------------------------- |
| 🏠 `index.html`  | Homepage, vehicle selection, filters, booking modal, price calculation, and payment selection |
| 📰 `blog.html`   | Driver insights, featured articles, and platform updates                                      |
| ⭐ `reviews.html` | Driver reviews, ratings, statistics, and review submission                                    |
| 🔐 `login.html`  | User login form                                                                               |
| ✍️ `signup.html` | User registration form                                                                        |

---

## 📸 Preview

> Add screenshots of your project here.

```text
Homepage
Vehicle Selection & Filtering
Booking Modal
Payment Selection
Driver Reviews
Blog & Insights
Login Page
Sign Up Page
```

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (Vanilla JS)

No frameworks or external dependencies are required.

---

## 📂 Project Structure

```text
FlexRide/
│
├── index.html
├── blog.html
├── reviews.html
├── login.html
├── signup.html
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/flexride.git
```

### 2. Open the project

Simply open `index.html` in your preferred web browser.

No installation or dependencies are required.

---

## 🚙 Available Vehicles

The platform includes multiple vehicle options for different types of work:

| Vehicle                | Type       | Work Category              |
| ---------------------- | ---------- | -------------------------- |
| City Scooter 125cc     | Scooter    | Food & Parcel Delivery     |
| Sedan Comfort          | Sedan      | Ride-Sharing               |
| Standard Commuter Bike | Motorcycle | Multi-Purpose              |
| Compact Van 1.5T       | Van        | Delivery & Parcel Services |
| Luxury SUV             | SUV        | Ride-Sharing               |

Vehicle cards include rental details and daily pricing, and users can select a vehicle to begin the booking process.

---

## 🔎 Vehicle Filtering

Users can filter available vehicles based on their work type:

1. **All Vehicles** — Displays every available vehicle.
2. **Food / Parcel Delivery** — Displays vehicles suitable for delivery work.
3. **Ride-Sharing** — Displays vehicles suitable for passenger ride-sharing.

The filtering functionality is handled dynamically with JavaScript.

---

## 💰 Dynamic Rental Price Calculator

When a user selects a vehicle:

1. The booking modal opens.
2. The selected vehicle is automatically displayed.
3. The rental duration is set.
4. The total rental cost updates automatically.

### Calculation

```text
Total Rental Cost = Daily Rental Price × Number of Rental Days
```

---

## 💳 Payment Methods

FlexRide currently provides payment method selection for:

* 🟢 eSewa
* 🟣 Khalti

After selecting a payment method and submitting the booking form, the project displays a payment initiation message.

> **Note:** This project currently demonstrates the payment flow on the frontend. A real payment gateway is not yet integrated.

---

## ⭐ Reviews System

The Reviews page allows users to:

1. View driver ratings and rental statistics.
2. Read existing driver experiences.
3. Enter their full name.
4. Add their driving platform and location.
5. Select the rented vehicle.
6. Choose a rating.
7. Write their experience.
8. Publish the review dynamically.

New reviews are added to the reviews section using JavaScript.

---

## 📰 Blog Section

The Blog page provides information and tips for FlexRide drivers, including:

* How to maximize daily earnings
* Working during peak demand hours
* Choosing the right vehicle for the job
* Digital payment options
* Vehicle maintenance
* Driver safety in rain and heavy traffic

---

## 🔐 Authentication

### Sign Up

Users can create an account by entering:

* Full Name
* Email Address
* Primary Driving Service
* Password

Available service options include:

* Pathao Driver / Courier
* InDrive Driver
* Foodmandu Delivery
* Independent / Other

### Login

Users can log in using:

* Email Address
* Password
* Remember Me option

> **Note:** Authentication is currently handled as a frontend demonstration and does not use a backend database.

---

## 🌟 Key Features

* Responsive Layout
* Modern Glassmorphism Navigation
* Vehicle Category Filtering
* Interactive Vehicle Cards
* Booking Modal
* Dynamic Price Calculator
* eSewa Payment Selection
* Khalti Payment Selection
* Driver Reviews
* Dynamic Review Submission
* Blog & Driver Insights
* Login Page
* Sign Up Page
* Form Validation
* Smooth Hover Effects and Transitions
* Mobile-Friendly Design
* Lightweight and Framework-Free

---

## 📱 Responsive Design

FlexRide is optimized for:

* 💻 Desktop
* 🖥️ Laptop
* 📱 Mobile
* 📲 Tablet

The layout adjusts navigation, forms, filters, cards, and content for smaller screens.

---

## 🔮 Future Enhancements

* Backend Integration
* Secure User Authentication
* Database for Users and Bookings
* Real eSewa Payment Gateway Integration
* Real Khalti Payment Gateway Integration
* Vehicle Availability Tracking
* Admin Dashboard
* Booking History
* Email Confirmation
* Password Recovery System
* Vehicle Images
* Search Functionality
* GPS Tracking
* Driver Rating System with Persistent Storage
* Online Booking Management

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Make your changes.
4. Commit your changes.
5. Push to your branch.
6. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aayush**

Frontend Developer | Backend Enthusiast |  UI/UX Creator | Robotics Enthusiast

---

## ⭐ Show Your Support

If you like this project, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and motivates future improvements.

---

<p align="center">
  <b>🚗 FlexRide — Helping Drivers Earn Without Owning a Vehicle.</b>
</p>
