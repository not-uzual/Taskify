# Taskify

Simple task management app to create, organize, and complete tasks.

> Live Site: https://taskify-mytask.vercel.app/

---

## Product Overview

Taskify is built with:

- Frontend: React + Vite
- Backend: Node.js + Express
- Database: MongoDB
- Authentication: JWT in secure HTTP-only cookies

Core flow:

1. Create account or log in.
2. Add tasks with title, description, and category.
3. View and filter tasks by category.
4. Mark tasks done or delete tasks.

---

## Setup (Frontend Contributors)

> Contributors only need frontend setup. No local backend setup required.

### Prerequisites

- Node.js 18+
- npm

### 1. Install

```bash
cd frontend
npm install
```

### 2. Environment

Create `frontend/.env`:

```env
VITE_API_BASE_URL=https://taskify-5pi3.onrender.com
```

Use the backend URL provided by the maintainer if it changes.

### 3. Run

```bash
cd frontend
npm run dev
```

Open: http://localhost:5173

---

## Contribute

Frontend contributions are welcome (UI polish, UX improvements, accessibility, and small features).

### How To Contribute

1. Fork this repository.
2. Create a branch from `main`.
3. Make changes in `frontend/` only.
4. Add backend URL in `frontend/.env` and test locally.
5. Before pushing your branch, sync with upstream `main` (fetch + rebase/merge).
6. Open a Pull Request with:
- Clear summary
- Screenshots for UI changes
- Testing steps

### Suggested Frontend Areas

- Better form validation and feedback
- Responsive improvements
- Accessibility improvements
- Better loading, empty, and error states
- Reusable UI components

### Contribution Rules

- Keep existing visual style consistent.
- Keep PRs focused and small.
- Do not commit secrets or real env values.
- Update README when setup/behavior changes.

