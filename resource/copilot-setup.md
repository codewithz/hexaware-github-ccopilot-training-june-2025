
# 🤖 Setting Up GitHub Copilot in VS Code and IntelliJ IDEA

## 📋 Prerequisites

Before getting started, ensure you have:
- ✅ A GitHub account with Copilot enabled or trial activated
- ✅ Internet access
- ✅ Installed:
  - [Visual Studio Code](https://code.visualstudio.com/)
  - [IntelliJ IDEA](https://www.jetbrains.com/idea/) (Community or Ultimate)

---

## ⚙️ Step 1: Enable Copilot on GitHub

1. Go to [GitHub Copilot Settings](https://github.com/settings/copilot)
2. Sign in and activate your Copilot subscription (if not done already)
3. Enable Copilot for:
   - Your personal account
   - Selected or all repositories
4. Configure optional preferences like:
   - Enable suggestions in specific languages
   - Filter code with matching public code

---

## 💻 Step 2: Setup GitHub Copilot in **VS Code**

### 🔌 1. Install GitHub Copilot Plugin

- Open VS Code
- Go to Extensions (`Ctrl+Shift+X`)
- Search for: `GitHub Copilot`
- Click **Install**

Alternatively:
```bash
code --install-extension GitHub.copilot
```

---

### 🔐 2. Sign In to GitHub

- After installation, Copilot will prompt you to **sign in**
- This opens a GitHub login page in your browser
- Authorize GitHub Copilot

---

### ✅ 3. Verify It Works

- Open any code file (e.g., `.ts`, `.js`, `.java`)
- Type a comment like:  
  `// function to calculate factorial`
- Copilot suggests a function
- Press `Tab` to accept, or `Esc` to reject

---

### 💬 (Optional) Install Copilot Chat Extension

- Search: `GitHub Copilot Chat` in extensions
- Install and sign in (available for Pro/Business plans)
- Use `Ctrl+I` or Chat sidebar to ask Copilot questions

---

### ⌨️ VS Code Shortcuts

| Action | Shortcut |
|--------|----------|
| Accept Suggestion | `Tab` |
| Reject Suggestion | `Esc` |
| Next Suggestion | `Ctrl + ]` |
| Open Copilot Chat | `Ctrl + I` |

---

## 🧠 Step 3: Setup GitHub Copilot in **IntelliJ IDEA**

### 🧩 1. Install Copilot Plugin

- Go to: `File → Settings → Plugins`
- Search: `GitHub Copilot`
- Click **Install** and **Restart IDE**

---

### 🔐 2. Sign In to GitHub

- After restart, a prompt appears to sign in
- Authorize via GitHub in your browser
- Once complete, Copilot is ready to use

---

### ✅ 3. Use Copilot in Your Editor

- Open any supported file
- Type a comment or function signature
- Wait for gray suggestions
- Press `Tab` to accept

---

### ⌨️ IntelliJ Shortcuts

| Action | Shortcut |
|--------|----------|
| Accept Suggestion | `Tab` |
| Trigger Suggestion | `Ctrl + Space` |
| Reject Suggestion | `Esc` |

---

## 🧪 Test It

Try typing the following in either IDE:
```ts
// function to reverse a string
```

You should see Copilot generate the corresponding function.

---

## 📚 References

- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [Copilot for VS Code](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [Copilot for JetBrains](https://plugins.jetbrains.com/plugin/17718-github-copilot)
