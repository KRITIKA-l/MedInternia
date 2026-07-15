# Contributing

Thank you for your interest in contributing to MedInternia — especially for GSSoC! Please follow these steps:

1. Fork the repository and create a feature branch from `main`.
2. Read `README.md` and the project setup below.
3. Run the backend and frontend locally:

Backend:
```
cd backend
Copy-Item .env.example .env
# fill values in .env
npm install
npm run build
npm start
```

Frontend:
```
cd frontend
Copy-Item .env.example .env
# fill values in .env
npm install
npm run dev
```

4. Look for issues labeled `good first issue` or `help wanted` and comment that you are working on it.
5. Open a pull request describing your changes and link any related issue.

Maintainers will review and advise. Use `main` as the base for releases.
