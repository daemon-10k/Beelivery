# Beelivery by Kwasong 🐝

**_Skip the Line, Save Your Time._**

![Beelivery Status](https://img.shields.io/badge/status-MVP%20Launched-brightgreen)
![Tech Stack](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-blue)
![Backend](https://img.shields.io/badge/backend-Google%20Apps%20Script-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

Beelivery is a hyper-local food delivery service designed to solve the unique logistical challenges at the Binus University @ Alam Sutera campus. This project is the Minimum Viable Product (MVP) developed for the "Entrepreneurship: Market Validation" course.

### The Problem

The Binus @ Alam Sutera campus is a 20-floor vertical campus with thousands of students, crowded elevators, and canteens located on the lower floors. With only 20-minute breaks between classes, students and staff face a significant time crunch, often having to choose between getting food and being on time for their next class. This results in stress, skipped meals, and reduced productivity.

### Our Solution

Beelivery is a web-based platform that allows users to order food from any on-campus canteen and have it delivered directly to their classroom, desk, or a designated meeting point. Our model leverages a team of on-site student runners who can navigate the building's layout with maximum efficiency, bypassing the main elevator traffic.

We offer a fast, affordable, and reliable service that gives Binusians back their break time.

### Tech Stack

This MVP is built to be lean, scalable, and extremely low-cost, using a serverless architecture.

- **Frontend:** A responsive, mobile-first web app built with vanilla **HTML, CSS, and JavaScript**.
- **Backend:** A robust backend powered by **Google Apps Script**, which handles order processing and notifications.
- **Database:** **Google Sheets** is used as a simple, effective, and free database for both menu items and incoming orders.
- **Team Operations:** Real-time order dispatching and team coordination are managed via automated notifications to a private **Discord** server.

### How It Works

1.  **Browse & Select:** The user accesses our web app via a QR code and browses the menus of various campus canteens.
2.  **Order & Customize:** They add up to 3 items to a multi-vendor cart and choose their preferred delivery speed.
3.  **Submit:** The user submits their details (name, location), and the order is sent to our Google Apps Script backend.
4.  **Automated Dispatch:** The script logs the order in our Google Sheet and instantly sends a "New Order" notification to the Beelivery team's Discord channel.
5.  **Fast Delivery:** An available runner claims the job, picks up the food, and delivers it directly to the customer.

### The Team

* **Aurelia Faren** - _Chief Operational Officer (COO)_
* **Seraphim Ruben Udjung** - _Chief Technology Officer (CTO)_
* **Stefani Gifta Ganda** - _Chief Executive Officer (CEO)_
* **Frederick Nicholas Su** - _Chief Finance Officer (CFO)_
* **Wilbert** - _Chief Marketing Officer (CMO)_

### License

This project is licensed under the MIT License.
