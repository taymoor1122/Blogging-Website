# Blogging Website

This is a demo blogging website project for Git and GitHub CI/CD workflow practice.

---

## 🚀 Project Structure

- `src/` – source code folder
- `styles/` – CSS/styles folder
- `.github/workflows/` – GitHub Actions workflows

---

## 🌿 Branching Strategy

- `develop`: Main development branch
- `feature/*`: For new features (e.g., homepage)
- `release/v1.0`: For production-ready release

---

## 🔁 GitHub Actions Workflows

### ✅ pr-validation.yaml
- Validates all pull requests to `develop`

### ✅ build-and-test.yaml
- Runs on push/PR to `develop`
- Tests on Node.js 16 and 18

---

## 🧪 Test Command

```bash
npm test
