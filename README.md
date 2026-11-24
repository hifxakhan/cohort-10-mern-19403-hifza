# MERN Notes App

A full-stack Notes Application built with the MERN stack (Node.js, Express, React, MySQL). This project was completed as part of the 10Pearls Shine Program Cohort 10 assignment.

## Features

*   **User Authentication:** Secure signup, login, and JWT-based authorization.
*   **Email Verification (OTP):** Users receive a 6-digit OTP via email to verify their account before logging in.
*   **Notes CRUD:** Users can create, read, update, and delete their own notes.
*   **Rich Text Editor:** Integrated `React Quill` for formatting notes (bold, italic, lists, headers).
*   **Search & Filter:** Instantly filter notes by title on the dashboard.
*   **Export Notes:** Download notes as `.txt` files.
*   **Modern UI:** Beautiful, responsive interface built with Tailwind CSS, featuring a custom dark/light color palette.
*   **Application Logging:** Backend logs HTTP requests, user activities, and errors using `Pino Logger`.
*   **Unit Testing:** Backend API tests written with Mocha, Chai, and Chai-HTTP.

## Tech Stack

**Frontend:**
*   React.js (Vite)
*   React Router DOM (Routing)
*   Tailwind CSS (Styling)
*   Axios (API Requests)
*   React Quill (Rich Text Editor)

**Backend:**
*   Node.js & Express.js
*   MySQL (Clever Cloud Database)
*   JSON Web Tokens (JWT) & Bcrypt (Security)
*   Nodemailer (Email Delivery)
*   Pino & Pino-HTTP (Logging)
*   Mocha & Chai (Testing)



## Developed by
* Hifza Khan

## How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/hifxakhan/cohort-10-mern-19403-hifza.git
cd cohort-10-mern-19403-hifza
