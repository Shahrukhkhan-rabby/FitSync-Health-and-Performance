# FitSync Health and Performance - Gym Class Scheduling and Membership Management System

## Project Overview

FitSync is a full-featured Gym Class Scheduling and Membership Management System designed to streamline gym operations by organizing classes, trainers, and trainees with clear role-based access and robust business logic. The platform supports three user roles: **Admin**, **Trainer**, and **Trainee**, each with distinct responsibilities and permissions. FitSync ensures smooth scheduling, efficient class capacity management, and secure authentication for all users.

---

## Relation Diagram

![Relation Diagram](https://raw.githubusercontent.com/Shahrukhkhan-rabby/FitSync-Health-and-Performance/main/assets/relation-diagram.png)
<!-- If your diagram is hosted elsewhere, update the link above. If you don't have an image, use any free diagram tool (dbdiagram.io, draw.io), export as PNG/JPG, and upload in the repo. -->

---

## Technology Stack

- **Frontend:** Next.js (React), TypeScript, Tailwind CSS
- **Backend:** Express.js, TypeScript
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JWT (JSON Web Token)
- **Deployment:** Vercel / Heroku
- **State Management:** Redux Toolkit
- **Other:** Framer Motion, React Three Fiber, Lucide Icons

---

## Deployment

- **Live Server:** [https://fitsyncserver.vercel.app](https://fitsyncserver.vercel.app) <!-- Replace with your actual deployed server URL -->
- **Live Client:** [https://fitsyncclient.vercel.app/](https://fitsyncclient.vercel.app/) <!-- Replace with your actual deployed client URL -->

---

## Business Rules

- **Admins:** Max 5 classes per day, assign trainers, manage users.
- **Trainers:** Conduct assigned classes only, view schedules.
- **Trainees:** Book schedules (max 10 per class), manage own profile.
- **Schedule:** Each class lasts 2 hours.
- **Authentication:** JWT-based, role-based access.
- **Error Handling:** Unauthorized access, validation errors, booking/scheduling limit errors.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For any queries, contact [shahrukhkhan3418198@gmail.com](mailto:shahrukhkhan3418198@gmail.com)