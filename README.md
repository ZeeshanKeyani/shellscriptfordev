````markdown id="k9m2qx"
# 📘 README Update Contribution Guide

<p align="center">
  <a href="https://github.com/DevStrikerTech/datahelm/fork">
    <img src="https://img.shields.io/badge/Fork-Repo-blue?style=for-the-badge&logo=github" />
  </a>
  <a href="https://github.com/DevStrikerTech/datahelm/issues">
    <img src="https://img.shields.io/badge/Issues-Welcome-orange?style=for-the-badge&logo=github" />
  </a>
  <a href="https://github.com/DevStrikerTech/datahelm/pulls">
    <img src="https://img.shields.io/badge/PRs-Open-green?style=for-the-badge&logo=github" />
  </a>
  <img src="https://img.shields.io/badge/Docs-README%20Only-important?style=for-the-badge" />
</p>

---

## 📑 Table of Contents
- [🚀 Objective](#-objective)
- [🔒 Important Rules](#-important-rules)
- [🛠️ Workflow](#️-step-by-step-workflow)
- [🧾 PR Template](#-pr-description-template)
- [✅ Acceptance Criteria](#-acceptance-criteria-checklist)
- [💡 Tips](#-tips-for-a-good-contribution)

---

## 🚀 Objective
Make **minor improvements** to `README.md` such as:
- Fixing grammar or typos  
- Improving formatting  
- Cleaning up sections  
- Fixing broken or outdated links  

⚠️ **Do NOT perform a full rewrite or major restructuring.**

---

## 🔒 Important Rules

- ✅ Work **ONLY** on the `dev` branch  
- ❌ Do **NOT** push directly to `main` or `master`  
- ✅ Only modify `README.md`  
- ✅ Keep changes **small, focused, and clean**

---

## 🛠️ Step-by-Step Workflow

<details>
<summary>📌 Click to expand full workflow</summary>

---

### 1️⃣ Fork the Repository
[![Fork Repo](https://img.shields.io/badge/Fork-Repository-blue?style=for-the-badge&logo=github)](https://github.com/DevStrikerTech/datahelm/fork)

---

### 2️⃣ Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/datahelm.git
cd datahelm
````

---

### 3️⃣ Sync & Checkout `dev` Branch

```bash
git fetch origin
git checkout dev
git pull origin dev
```

---

### 4️⃣ Create a Feature Branch

```bash
git checkout -b docs/readme-small-update
```

---

### 5️⃣ Edit the README

* Open `README.md`
* Apply **small improvements only**
* Keep original meaning intact

---

### 6️⃣ Commit Your Changes

```bash
git add README.md
git commit -m "docs: small README improvements"
```

---

### 7️⃣ Push Your Branch

```bash
git push origin docs/readme-small-update
```

---

### 8️⃣ Open a Pull Request

[![Open Pull Request](https://img.shields.io/badge/Open-PR-green?style=for-the-badge\&logo=github)](https://github.com/DevStrikerTech/datahelm/compare/dev...docs/readme-small-update)

**Set:**

* Base branch → `dev`
* Compare branch → `docs/readme-small-update`

---

</details>

---

## 🧾 PR Description Template

```markdown
## ✅ Changes Made
- Fixed grammar issues  
- Improved formatting in sections  
- Cleaned up minor inconsistencies  

## 📌 Notes
- Only `README.md` was modified  
- No major structural changes were made  
```

---

## ✅ Acceptance Criteria Checklist

* [ ] Only `README.md` is changed
* [ ] Changes are small and meaningful
* [ ] PR targets `dev` branch
* [ ] Grammar and formatting improved
* [ ] No major rewrite

---

## 💡 Tips for a Good Contribution

* Keep it simple and readable
* Avoid unnecessary edits
* Preserve original intent
* Use consistent formatting

---

## 🎯 Goal

Make the README clearer, cleaner, and more professional without changing its core content.

---

<p align="center">
  ✨ Happy Contributing ✨
</p>
```
