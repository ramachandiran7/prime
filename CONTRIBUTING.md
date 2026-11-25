# Contributing to KodeKloud 100 Days of DevOps

Welcome! 🎉 Thank you for helping make this a better resource for everyone following the KodeKloud Engineer 100 Days of DevOps challenge.

---

## 📋 How You Can Contribute

- **Fix a command or value** that did not work in your lab.
- **Add a missing issue and fix** to a day's *Common Issues & Fixes* table.
- **Improve a solution** with a clearer or safer way to do the task.
- **Improve the documentation**: typos, wording, helpful links.
- **Raise an issue** for a bug, a question or a suggestion.

---

## 📝 Contribution Process

1. **Fork the repository** with the **Fork** button at the top right.

2. **Clone your fork**
   ```sh
   git clone https://github.com/<your-username>/kodekloud-100-days-devops.git
   cd kodekloud-100-days-devops
   ```

3. **Create a branch**
   ```sh
   git checkout -b fix-day-12-firewall-step
   ```

4. **Make your changes** and follow the [folder structure](#-folder-structure) and [day file format](#-day-file-format) below.

5. **Commit and push**
   ```sh
   git add .
   git commit -m "Fix firewall step in Day 12"
   git push origin fix-day-12-firewall-step
   ```

6. **Open a pull request** from your fork: click **Compare & pull request**, describe what you changed and why, and reference any related issue.

---

## 📂 Folder Structure

- One folder per day: `DAY01/`, `DAY02/` ... `DAY100/` (two digits, so they sort correctly).
- One task file per folder: `task-<number>-<short-title>.md`.
- Screenshots go in `DAYxx/screenshots/` and are named `dayxx.png`.

```
DAY01/
  task-1-create-a-user-with-a-non-interactive-shell.md
  screenshots/
    day01.png
DAY02/
  task-2-create-a-temporary-user-with-an-expiry-date.md
  screenshots/
```

---

## 🧩 Day File Format

Keep every day file in this order so problems and fixes are easy to find:

```
# Day NN: Title
## 📌 Task
## 🔁 Values to change before you run
## ✅ Solution (copy and paste)
## 🧪 Verification
## 🛠️ Common Issues & Fixes
## 📸 Screenshot
```

---

## ✅ Pull Request Guidelines

- **Follow the folder structure** and day file format above.
- **Keep PRs focused:** one PR per day or per topic.
- **Test your change** in a real lab and say so in the PR description.
- **Never include passwords, tokens or private keys.** Use placeholders such as `<PASSWORD>`.
- **No plagiarism:** submit your own work or credit your sources.
- **Be respectful:** communicate politely and constructively.

---

## 🛡️ Code of Conduct

This project follows the [Code of Conduct](./CODE_OF_CONDUCT.md), based on the [Contributor Covenant](https://www.contributor-covenant.org/version/2/0/code_of_conduct/). Please be respectful and inclusive.

---

## 💬 Need Help?

- Open an [issue](../../issues) for questions, suggestions or bug reports.
- Check existing issues before opening a new one.

Happy learning and contributing! 🚀
