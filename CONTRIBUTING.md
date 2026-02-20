# 🤝 Contributing to Night-Stack

Thank you for your interest in contributing to **Night-Stack** — a green-first hacker-inspired theme ecosystem.

We welcome contributions of all kinds, including:

- New theme variants
- Stack-specific syntax tuning
- Semantic highlighting improvements
- Eye-strain optimizations
- UI coverage fixes (terminal, sidebar, activity bar, etc.)
- Bug fixes & contrast adjustments

---

## 🛠 Development Setup

### 1️⃣ Fork the Repository

Click **Fork** on GitHub to create your copy.

---

### 2️⃣ Clone Your Fork

```bash
git clone https://github.com/<your-username>/night-stack.git
cd night-stack
```

---

### 3️⃣ Install Dependencies (if applicable)

```bash
npm install
```

---

### 4️⃣ Run Extension Development Host

Open the repo in VS Code and press:

`F5`

This launches a new Extension Development Host window for testing themes.

---

## 🌿 Branching Strategy

Please create feature branches for all contributions.

Examples:

```bash
git checkout -b feature/theme-react
git checkout -b fix/contrast-terminal
git checkout -b enhancement/semantic-python
```

❌ Do NOT commit directly to `main`.

All changes must go through Pull Requests.

---

## 🎨 Theme Contribution Guidelines

When submitting or modifying themes:

### Must Cover Full IDE

Themes should style:

- Editor
- Terminal
- Activity Bar
- Sidebar
- Status Bar
- Tabs
- Panels
- Title Bar
- Notifications

---

### Color Philosophy

Night-Stack follows a **green-first identity**:

- Green = Primary color
- Red = Secondary (errors/diffs)
- Neon allowed only in hacker variants
- Eye-friendly palettes required for soft themes

Avoid excessive neon usage in non-hacker themes.

---

## 🧪 Testing Checklist

Before submitting a PR, verify:

- Theme loads correctly
- Semantic highlighting works
- Multiple languages tested
- Git diff colors readable
- Terminal ANSI palette visible
- No eye-strain neon conflicts
- Sidebar & activity bar styled

---

## 📦 Pull Request Process

1️⃣ Fork the repository  
2️⃣ Create a feature branch  
3️⃣ Commit your changes  

```bash
git commit -m "feat: add rust theme variant"
```

4️⃣ Push to your fork

```bash
git push origin feature/theme-rust
```

5️⃣ Open a Pull Request to `main`

---

## 🔒 Branch Protection

The `main` branch is protected:

- Direct pushes are disabled
- Pull Requests are required
- Maintainer approval is required before merge

This ensures stability and quality control.

---

## 👑 Maintainers

Maintainers are responsible for:

- Reviewing Pull Requests
- Approving merges
- Managing releases
- Ensuring theme consistency

If you’re interested in becoming a maintainer, open a discussion.

---

## 🐛 Reporting Issues

You can report:

- Contrast problems
- Accessibility issues
- Language syntax gaps
- Terminal visibility problems

Use the **Issues** tab on GitHub.

---

## 💡 Suggesting New Themes

When proposing new variants, include:

- Theme name
- Target stack/language
- Palette preview (hex colors)
- Eye-strain classification (neon vs soft)

---

## 📜 License

By contributing to Night-Stack, you agree that your contributions will be licensed under the **MIT License**.

---

## 🌙 Night-Stack Philosophy

Night-Stack is built on three pillars:

- Hacker aesthetic roots
- Green-first identity
- Developer eye comfort

Every contribution should respect these principles.

---

Thank you for helping grow Night-Stack 🚀