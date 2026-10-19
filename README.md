# campus-hub

campus events platform: admins publish events, students register for them.

## features

- student and admin sign up / sign in (jwt, bcrypt)
- admins create, edit and delete events and see registrations per event
- students browse events and register

## stack

react 18 + vite · recoil · tailwind css · framer motion · express · mongodb (mongoose) · zod · nodemailer

## run locally

needs node 20.6+.

```bash
cd backend && npm install && cp .env.example .env && node --env-file=.env index.js
cd frontend && npm install && npm run dev
```

## env

copy `backend/.env.example` to `backend/.env` and set `MONGODB_URI`.
