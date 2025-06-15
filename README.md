# Classroom

<p align="center">
  <img alt="logo" src="./public/favicon.ico" width="100">
</p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/> 
  <img alt="Firebase" src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase"/> 
  <img alt="TailwindCSS" src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img alt="Chart.js" src="https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white"/>
</p>

## Overview

Classroom is a modern web application built with React and Firebase that helps students and teachers manage their online learning experience effectively. The platform provides a comprehensive suite of tools for attendance tracking, assignment management, and class organization.

## Features

### For Teachers
- Create and manage assignments with due dates
- Share class links and important announcements
- Monitor student submissions
- Track student attendance
- Create and manage class events

### For Students
- Track attendance with visual analytics
- Manage assignments and deadlines
- Access class materials and announcements
- Submit assignments
- Organize tasks with Kanban-style Todo list

## Tech Stack

- **Frontend**: React.js with React Router for navigation
- **Styling**: TailwindCSS for modern, responsive design
- **Backend**: Firebase (Authentication, Firestore, Storage)
- **Charts**: Chart.js for data visualization
- **State Management**: React Context API
- **Build Tools**: Webpack with CRACO configuration

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Firebase account

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/classroom.git
cd classroom
```

2. Install dependencies:
```bash
npm install
```

3. Create a Firebase project and add your configuration in `src/firebase/config.js`

4. Start the development server:
```bash
npm start
```

## Usage Guide

### For Teachers
1. Navigate to the Profile tab and toggle your status to "Teacher"
2. Add your email in the profile section
3. Create assignments in the Classroom tab
4. Share class links and events through the Home tab
5. Monitor student submissions and attendance

### For Students
1. Update your profile with teacher emails
2. Track attendance using the bar chart
3. Use the Todo list for task management
4. Check the Classroom tab for assignments and announcements
5. Submit assignments before due dates

## Screenshots

<div align="center">
  <img src="./screenshots/Screenshot from 2021-05-26 23-00-12.png" alt="Dashboard View" width="45%"/>
  <img src="./screenshots/Screenshot from 2021-05-26 23-00-19.png" alt="Classroom View" width="45%"/>
</div>




