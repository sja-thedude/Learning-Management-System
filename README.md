## 📘 Learning-Management-System (LMS)

A modern Learning Management System built with Laravel (Backend) and Vite (Frontend). Designed to showcase role-based access, CRUD operations, and scalable architecture.


🚀 Core Features (Phase 1 – MVP)
	•	👩‍🏫 User Roles: Admin, Teacher, Student
	•	📚 Course Management: Course creation, editing, and publishing
	•	🎓 Enrollment: Students can enroll and access their courses
	•	📝 Quizzes & Assignments: Basic evaluation system


🔮 Future Expansion (Phase 2 – Advanced)
	•	📹 Live Classes: Integration with Zoom/Google Meet
	•	📜 Certificates: Auto-generated course completion certificates
	•	💳 Subscription Payments: Stripe/PayPal integration
	•	🏆 Gamification: Badges, leaderboards, XP points


🛠️ Tech Stack
	•	Backend: Laravel 12 (PHP 8.2)
	•	Frontend: Vite, Blade + Alpine.js
	•	Database: MySQL / PostgreSQL
	•	Authentication: Laravel Breeze (role-based auth)
	•	Future APIs: REST & possibly GraphQL

📂 Project Structure
	•	app/Models → User, Course, Enrollment, Quiz
	•	resources/views → Blade templates (frontend)
	•	routes/web.php → Web routes
	•	routes/api.php → API endpoints (future mobile app support)

▶️ Getting Started

```
git clone https://github.com/sja-thedude/LMS.git
cd LMS
composer install
npm install
npm run dev
php artisan migrate
php artisan serve
```