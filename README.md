# Bus Booking & Hire Platform — MERN Stack 

**Student:** Niaj Ahmed
**Email:** niajahmd19@gmail.com  
**Course:** Software Development Skills — Full-Stack (MERN)

---

## Project Overview

This repository contains a front-end demonstration and documentation for a bus ticketing and hire web app. The front-end demo is provided for course review and demonstration; the core application logic originates from an example redbus-style project whose authors are credited below.

---

## Live Demo & Video

- **Website Deployment Live link:**  https://redbus.netlify.app/
- **Demo Video (Unlisted YouTube):** https://youtu.be/dmQpiy-wMOE

---

## ReadME — How to run the project

How I ran the project locally (what I did) (Markdown)
## How I ran the project locally (what I did)

> Note: I used a publicly available redBus-style example as the learning source. The instructions below describe how I ran the example project locally for testing and for recording the demo video.

1. Clone the example repository (original project source):
```bash
git clone https://github.com/nitansh11/redbus.git
cd redbus

Install dependencies for both front-end and back-end:

# in one terminal (frontend)
cd front-end-redbus
npm install

# in a separate terminal (backend)
cd ../back-end-redbus
npm install

Create a local .env file for the back-end (based on .env.example) and set required variables such as MONGO_URI and Stripe test keys. Do not commit secrets.

Start the back-end server (Express):

cd back-end-redbus
npm start

Start the front-end (React dev server):

cd ../front-end-redbus
npm start

Open a browser at:

http://localhost:3000

and test the flows (search → view buses → seat selection → booking)
