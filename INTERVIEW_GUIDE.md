# Interview Guide: DevOps Practical (GitHub Actions)

Use this guide to ask the candidate questions and evaluate their hands-on DevOps skills.

---

## 📌 Task Overview

> Simulate a CI/CD pipeline using GitHub Actions to:
> - Trigger on every push
> - Print current date
> - Run a dummy test
> - "Deploy" by copying files into a `deploy/` folder

---

## ✅ Evaluation Checklist

### Git & GitHub
- Can they clone the repo?
- Can they make a change and push?

### GitHub Actions
- Can they read and explain the `main.yml` file?
- Do they understand each step?
- Can they debug if workflow fails?

### Bonus (If they finish early)
- Add a GitHub Secret called `MY_API_KEY` and echo it in the workflow.
- Create a new branch, push a change, and make a Pull Request.
- Talk through how they'd change this to deploy to AWS, Netlify, or Azure.

---

## ❓ Questions to Ask

1. What does each step in the workflow do?
2. What are the benefits of using GitHub Actions?
3. How would you handle test failures in real-world pipelines?
4. What would you monitor in a real deployment?
5. Can you explain what CI and CD mean?

---

## 🔚 Done?

When done, ask her to:
- Show the workflow run in the **Actions tab**
- Show the `deploy/` folder is created by the job
- Push the final changes
