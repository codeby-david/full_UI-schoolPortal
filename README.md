
🎓 School Portal Frontend

A modern School Management System designed to streamline administrative tasks, enhance communication, and provide a centralized platform for students, teachers, parents, and administrators. Built using TypeScript, Next.js, and various other libraries to ensure scalability and responsiveness.

✨ Features

For Students

.View personal profiles and academic performance.

.Access course schedules and assignments.

.Track attendance records.

For Teachers

.Manage class schedules and track attendance.

.Assign and grade assignments.

.Communicate with students and parents.

For Administrators

.Manage student and teacher records.

.Perform database operations such as adding or removing users (students, teachers, and parents).

.Post announcements and upcoming school events.

For Parents

.View their child’s academic performance.

.Communicate with teachers for updates and feedback.

🛠️ Tech Stack

.Next.js: Framework for server-rendered React applications with TypeScript support.

.TypeScript: For robust type-checking and enhanced developer experience.

.Tailwind CSS: Utility-first framework for rapid UI design.

.React Hook Form: Simplifies form management and validation.

.Zod: Schema declaration and validation for TypeScript.

.Recharts: For creating visual charts and analytics.

.React Big Calendar: To manage schedules effectively.

.React Calendar: For simpler calendar views and date pickers.

🚀 Getting Started

Prerequisites

Make sure you have the following installed on your system:

Node.js (v18 or higher)
npm or yarn
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/codeby-david/school-portal-frontend.git  
cd school-portal-frontend  
Install dependencies:

bash
Copy
Edit
npm install  
Run the development server:

bash
Copy
Edit
npm run dev  
The application will be available at http://localhost:3000.

📂 Project Structure

graphql

Copy
Edit

school-portal-frontend/  
├── public/             # Static assets  
├── src/  
│   ├── components/     # Reusable UI components  
│   ├── pages/          # Next.js pages  
│   ├── styles/         # Global and component-specific styles  
│   ├── hooks/          # Custom React hooks  
│   ├── utils/          # Utility functions  
│   └── types/          # TypeScript types and interfaces  
├── tailwind.config.js  # Tailwind CSS configuration  
├── tsconfig.json       # TypeScript configuration  
├── package.json        # Dependencies and scripts  
└── README.md           # Project documentation  
