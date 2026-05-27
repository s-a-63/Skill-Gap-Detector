# AI-Powered Career Skill Gap Detector

A sophisticated full-stack career development platform built with the **MERN stack** and **Google Gemini AI**, featuring a high-fidelity UI enhanced using **Lovable**. This application automates the process of identifying professional skill gaps and provides users with a data-driven roadmap to achieve industry readiness.

---

## Key Features

-  **AI Requirement Extraction**  
  Integrated Google Gemini AI to parse unstructured job descriptions into structured technical requirement lists.

-  **Dynamic Skill-Gap Analysis**  
  Interactive dashboard that compares user skills with job requirements and visualizes readiness using progress indicators.

-  **Automated Learning Roadmaps**  
  Generates personalized, phase-based study plans to bridge identified skill gaps.

-  **Predictive Market Valuation**  
  AI-powered Salary Estimator that predicts localized salary ranges (LPA) based on skills and 2026 market trends.

-  **Priority Skill Logic**  
  Gives higher weightage to verified (tested) skills over self-reported skills for more accurate analysis.

-  **Enhanced UI/UX**  
  Modern, responsive interface designed with Lovable for improved user experience.

-  **Secure Authentication**  
  Implements JWT-based authentication with Redux Toolkit for state management and MongoDB for secure data storage.

---

## Tech Stack

### Frontend
- React.js  
- Redux Toolkit  
- React-Bootstrap  
- Axios  
- React-Icons  

### Design
- Lovable (AI-assisted UI/UX)

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB (Atlas)

### AI Integration
- `@google/generative-ai` (Gemini-3-Flash)

### State Management
- Redux (Slice-based architecture)

---

## Getting Started

### 1. Prerequisites

- Node.js (v18 or higher)  
- MongoDB Atlas account  
- Google AI Studio API Key  

---

### 2. Environment Setup

Create a `.env` file inside the **backend** folder:

```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_random_secret_key
GEMINI_API_KEY=your_google_gemini_api_key
```

---

### 3. Installation

#### Install backend dependencies (from root directory)
```bash
npm install
```

#### Install frontend dependencies
```bash
cd frontend
npm install
```

---

### 4. Run the Application

Run both frontend and backend concurrently:

```bash
npm run dev
```

---

## Usage

- **Skill Match:**  
  Select a target role to view compatibility score and missing skills.

- **Job Map:**  
  Paste a job description to let Gemini AI extract requirements and compare with your profile.

- **Salary Estimator:**  
  Get AI-predicted salary range and insights based on your current skill set.

- **Learning Roadmap:**  
  View automatically generated step-by-step phases to improve your skills.

---

## Future Enhancements

- Real-time job market trend analysis  
- Resume parsing and auto skill extraction  
- AI-based interview preparation module  
- Personalized course recommendations  

---

## Key Insight

This platform leverages AI to transform career planning into a data-driven, personalized experience, helping users bridge skill gaps efficiently.
