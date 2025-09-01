## How to run it

1. Clone this repo:
   ```bash
   git clone https://github.com/karimharbb/Auth-BackEnd.git
   cd Auth-BackEnd
   ```
2. Install dependencies:

   ```
   npm install
   ```

3. Start the app:

   ```
   npm run start:dev
   ```

4. Run Mongodb

5. CREATE env File :

```
MONGO_URL = ""
JWT_SECRET = "Secret"
PORT = PORT
FRONTEND_URL = http://localhost:5173

```

---

# React Authentication Demo

Hey This is a small authentication demo I built as part of an interview task.  
The idea is simple: **sign up, sign in, and access a protected page** only if you’re logged in.

---

## What it does

- Let’s you **create an account** (sign up).
- You can **log in** with your account.
- If login is successful, a **JWT access token** is stored in `localStorage`.
- That token is used to check if you’re allowed to see protected pages.
- If you’re not logged in, you get redirected back to the signin page.

Basically—it mimics the core of how most modern apps handle authentication.

---

## Tech Choices

I kept it lightweight and modern:

- **Nestjs + TypeScript** → fast, clean setup.
- **Mongodb** → for Database.
- **JWT Authentication** → token-based auth like you’d see in real apps

---
