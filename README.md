<div align="center">
  <br />
    <a href="https://doc-connect-alaht.vercel.app/" target="_blank">
      <img src="https://github.com/Vishnuvarun077/DocConnect/blob/f26cc8e1293d8c3ba11c5acd56d77327614ec16b/Project_banner.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  </div>

  <h3 align="center">Doc Connect - A Healthcare Management System</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🚀 [Deployment](#deployment)

## <a name="introduction">🤖 Introduction</a>

Doc Connect is a healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors. It features administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Appwrite
- TypeScript
- TailwindCSS
- ShadCN
- Twilio

## <a name="features">🔋 Features</a>

👉 **Register as a Patient**: Users can sign up and create a personal profile.

👉 **Book Appointments**: Patients can schedule multiple appointments with doctors at their convenience.

👉 **Admin Management**: Administrators can efficiently view and handle all scheduled appointments.

👉 **Appointment Confirmation**: Admins can confirm and set appointment times.

👉 **Cancel Appointments**: Administrators can cancel any appointment as needed.

👉 **SMS Notifications**: Patients receive SMS notifications to confirm their appointment details.

👉 **Responsive Design**: The application works seamlessly on all device types and screen sizes.

👉 **File Uploads**: Users can upload and store files securely within the app.

👉 **Performance Monitoring**: The application uses Sentry to monitor and track its performance.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/Vishnuvarun077/DocConnect.git
cd DocConnect
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="deployment">🚀 Deployment</a>

The application is deployed on Vercel. You can access the live version of Doc Connect at the following link:

[Doc Connect Live](https://doc-connect-alaht.vercel.app)

To deploy your own version of the application, follow these steps:

1. Sign up for a Vercel account if you don't have one.
2. Connect your GitHub repository to Vercel.
3. Configure the environment variables in the Vercel dashboard.
4. Deploy your application with a single click!

For more details on deploying with Vercel, check out the [Vercel Documentation](https://vercel.com/docs).
