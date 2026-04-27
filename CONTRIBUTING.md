# 🤝 Contributing to Fan Plane Reactor

Thank you for your interest in contributing to this project! Whether you want to improve the design, share a remix, fix a bug in the documentation, or suggest a new feature, all contributions are welcome.

---

## 📋 Table of Contents

- [What Contributions Are Welcome](#what-contributions-are-welcome)
- [How to Contribute](#how-to-contribute)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Reporting Issues](#reporting-issues)
- [Code of Conduct](#code-of-conduct)

---

## ✅ What Contributions Are Welcome

This is a hardware / maker project, so contributions can take many forms:

### 🛠️ Design & CAD
- Improvements or optimisations to the existing 3D-printed parts (reactor body, motor adaptor, support).
- Alternative part designs (e.g., different motor mounts, larger/smaller reactor variants).
- New accessories or add-ons (e.g., LED ring, decorative nozzle, stand variants).

### ⚡ Electronics
- Alternative wiring diagrams or circuit improvements.
- Suggestions for additional speed control methods (e.g., PWM controller, encoder).
- Power supply or efficiency improvements.

### 📝 Documentation
- Fixing typos, grammar, or unclear instructions in the README or other docs.
- Adding build photos, renders, or step-by-step assembly guides.
- Translating the documentation into another language.

### 🐛 Bug Reports & Issues
- Reporting fitment problems with the 3D-printed parts.
- Pointing out errors in the wiring diagrams or BOM.
- Suggesting improvements to the build instructions.

---

## 🚀 How to Contribute

### 1. Fork the repository

Click the **Fork** button at the top-right of the repository page to create your own copy.

### 2. Clone your fork

```bash
git clone https://github.com/<your-username>/fan-plane-reactor.git
cd fan-plane-reactor
```

### 3. Create a new branch

Use a descriptive branch name that summarises your change:

```bash
git checkout -b feat/improved-motor-mount
# or
git checkout -b fix/bom-unit-prices
# or
git checkout -b docs/assembly-guide
```

### 4. Make your changes

- For **CAD changes**: Export the modified file in both `.f3d` (Fusion 360) and `.step` formats and place them in the appropriate `CAD *` folder.
- For **documentation changes**: Edit the relevant `.md` file directly.
- For **electronics changes**: Update or add wiring diagrams and reference them in the README.

### 5. Commit your changes

Write a clear, concise commit message:

```bash
git add .
git commit -m "feat: add LED ring mount to reactor body"
```

### 6. Push and open a Pull Request

```bash
git push origin feat/improved-motor-mount
```

Then open a Pull Request on GitHub against the `main` branch. Fill in the PR template and describe:
- **What** you changed.
- **Why** you changed it.
- Any **known limitations** or things still to do.

---

## 🔍 Submitting a Pull Request

To keep things consistent and easy to review, please follow these guidelines:

- Keep pull requests focused on a single topic. Separate unrelated changes into separate PRs.
- Include before/after photos or renders when modifying CAD files — this makes it much easier to review.
- Update the `README.md` if your change affects assembly steps, the BOM, or the wiring.
- Make sure file names follow the existing naming convention (lowercase, spaces allowed, matching folder).

---

## 🐛 Reporting Issues

If you find a problem, please [open an issue](../../issues/new) and include:

- A clear description of the problem.
- Steps to reproduce it (e.g., "When printing the motor adaptor at 0.2 mm layer height, the shaft hole is too tight").
- Photos, screenshots, or measurements if relevant.
- Your printer / slicer settings if the issue is print-related.

---

## 🌟 Sharing Your Build

Have you built this project? We'd love to see it! You can:

- Open an issue with the label **"Show and Tell"** and share your photos.
- Link to your build in the issue or in a comment.

---

## 📜 Code of Conduct

This project follows a simple rule: **be respectful and constructive**. Everyone is welcome regardless of experience level. If you are new to maker projects, hardware, or GitHub — don't hesitate to ask questions in the issues.

---

Thank you for helping make this project better! 🚀
