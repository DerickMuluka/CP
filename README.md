# CarePulse — Smart, Modern Healthcare Appointment Management

**CarePulse** is a dynamic, intuitively designed platform built with **Next.js**, **TypeScript**, **Tailwind CSS**, and powered by **Appwrite**, that empowers both patients and administrators to manage medical appointments effortlessly—complete with **SMS confirmations**, performance monitoring via **Sentry**, and scalable file storage.

---

## ⭐ Why CarePulse Stands Out

- **Patient-Centric Experience**  
  Patients can seamlessly register, schedule, or reschedule appointments with a few clicks.

- **Efficient Admin Controls**  
  Admins can view, confirm, or cancel appointments with ease—and trigger notifications instantly.

- **Automated SMS Alerts**  
  Powered by Twilio integration, users receive real-time SMS confirmations for their appointments.

- **Robust Backend with Appwrite**  
  Secure data storage, user authentication, and API endpoints are handled efficiently through Appwrite.

- **Responsive & Accessible**  
  Built with Tailwind CSS and UI components from ShadCN, CarePulse provides a consistent and mobile-friendly interface across devices.

- **Performance & Stability Tracking**  
  Integrated with Sentry to monitor errors and ensure top-tier reliability.

---

##  Quick Start Guide

Follow these steps to get CarePulse running on your local environment:

```bash
# Clone the repository
git clone https://github.com/DerickMuluka/carepulse.git
cd carepulse

# Install dependencies
npm install

# Copy environment file and provide your credentials
cp .env.local.example .env.local
# → Populate Appwrite, Twilio, Sentry, and other API keys in .env.local

# Run the development server
npm run dev
