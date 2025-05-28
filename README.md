# HealthAI Assistant

HealthAI Assistant is a smart web-based healthcare platform designed to enhance medical accessibility by providing AI-powered symptom analysis, digital health record management, and online doctor consultations. The system is tailored to the Indian healthcare ecosystem and supports patients, doctors, and administrators with role-specific dashboards.

## 🏥 Features

- 🤖 **AI Symptom Checker** – Get instant health insights based on user input.
- 👨‍⚕️ **Doctor Discovery** – Search for certified Indian doctors by specialty, location, or rating.
- 📅 **Online Appointments** – Real-time booking and schedule management.
- 📁 **Digital Health Records** – Secure storage and easy access for medical history.
- 👤 **Role-Based Dashboards** – Separate views for Patients, Doctors, and Admins.

## 🚀 Technology Stack

### Frontend
- React.js
- TypeScript
- Tailwind CSS
- Shadcn UI
- Lucide React (icons)

### Backend & Database
- Supabase (authentication and real-time DB)
- PostgreSQL

### Tools & Libraries
- Vite
- Date-fns

## 🔧 Development Process

1. **Planning** – Defined roles and features
2. **Design** – UI mockups using Figma
3. **Development** – Modular coding in React
4. **Integration** – Connected frontend to Supabase
5. **Testing** – Functional, performance, and security tests
6. **Deployment** – Hosted mobile-friendly web application

## ✅ Testing & Validation

- Unit Testing for components
- Integration Testing of frontend-backend
- Security Testing for data privacy
- Performance Testing (< 2s load time)
- User Acceptance Testing with feedback implementation

## 📊 Market Analysis & Future Scope

- **Market Size**: Indian telemedicine market projected to reach $5.5B by 2025
- **Planned Features**:
  - Video consultations
  - Mobile app (React Native/Flutter)
  - Wearable device integration
  - E-prescriptions
  - Multilingual support

## ⚠️ Challenges Faced

- Role-based authentication
- Avoiding double bookings
- Ensuring secure data handling
- Creating responsive UI across devices

## 💡 Key Learnings

- Supabase simplifies backend setup
- TypeScript enhances code quality
- Iterative development speeds up issue resolution

## 📂 Database Schema

| Table       | Description                          |
|-------------|--------------------------------------|
| `users`     | Login credentials and roles          |
| `profiles`  | Personal and contact information     |
| `appointments` | Scheduling details                 |
| `symptoms`  | User inputs and AI-generated output  |

## 🔌 API Endpoints

- `POST /auth/signup`
- `POST /auth/login`
- `POST /appointments/book`
- `POST /symptom/analyze`

## 🔗 Project Repository

[GitHub – HealthAI Assistant](https://github.com/sruthibasineni/symptom-scribe-gemini-guide/tree/ccfaaa13f6943640e3583f860be6aac3d6ec864f)

 
