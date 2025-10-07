
https://github.com/user-attachments/assets/2491d155-da31-4115-b727-67b33f719460
Ecommerce App
A full-stack application with a React Native mobile app, React admin panel, and Node.js + Express backend, using Supabase for database and storage.

Tech Stack
- Backend: Node.js, Express
- Mobile App: React Native
- Admin Panel: React
- Database & Storage: Supabase (PostgreSQL + S3-like storage)

Features
- Mobile app and admin panel connected to Supabase backend.
- Supabase used for storing images and handling database operations.
- Environment variables configured for local development.

Local Setup
- Clone the repository:
    git clone <repository-url>
    cd <repository-folder>
- Install dependencies:
    Backend:
      cd backend
      npm install
    Mobile App:
      cd mobile
      npm install
    Admin Panel:
      cd admin
      npm install

Deployment Notes
- Attempted deploying the backend on Vercel and Render, but free hosting plans do not support TCP connections to the database.
- Video demos are attached showing the admin panel and mobile app in action.

env
NODE_ENV=development
PORT=4000
DATABASE_URL=postgresql://postgres:12345678@db.znvgaluttcijbwcejghc.supabase.co:5432/postgres
JWT_SECRET=dev_super_secret_jwt_key_change_me
JWT_EXPIRES_IN=7d
SUPABASE_URL=https://znvgaluttcijbwcejghc.supabase.co
SUPABASE_SERVICE_ROLE_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InpudmdhbHV0dGNpamJ3Y2VqZ2hjIiwicm9sZSI6InNlcnZpY2Vfcm9sZSIsImlhdCI6MTc1OTY5NjMxNywiZXhwIjoyMDc1MjcyMzE3fQ.J7mwuc5RARV3hCwKJWo4i7VLOKhUc-R4bcNQYsff7Aw
SUPABASE_PUBLIC_URL=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InpudmdhbHV0dGNpamJ3Y2VqZ2hjIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTk2OTYzMTcsImV4cCI6MjA3NTI3MjMxN30.iJVXU31DaUtmFm8iBeA-tlM7zkeDMAtW2cD_mA_zlIs
SUPABASE_BUCKET=interview


https://github.com/user-attachments/assets/1daa3b41-8aa6-4681-ba6d-3f39ee3d6fc9
https://github.com/user-attachments/assets/e3eb01ed-8ee3-4348-ada2-ac0a996fe33a




