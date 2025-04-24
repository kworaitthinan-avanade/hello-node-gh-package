# @kworaitthinan-avanade/hello-node-gh-package

A simple Node.js package published to GitHub Packages that returns a friendly greeting.

---

## 📦 Installation

```bash
npm install @kworaitthinan-avanade/hello-node-gh-package --registry=https://npm.pkg.github.com
```

---

## 🚀 Usage

```js
const hello = require('@kworaitthinan-avanade/hello-node-gh-package');

console.log(hello()); // ➜ "Hello from GitHub Package!"
```

---

## 🧪 Local Development

Clone the repo and run it locally:

```bash
git clone https://github.com/kworaitthinan-avanade/hello-node-gh-package.git
cd hello-node-gh-package
npm install
node test.js
```

---

## 🔄 Publishing to GitHub Packages (via GitHub Actions)

Publishing is automated using GitHub Actions and triggered **when a Git tag is pushed**.

### 🪄 How to Trigger the Publish Workflow:

1. **Commit your changes**

```bash
git add .
git commit -m "Update something"
```

2. **Create and push a version tag (semantic versioning)**

```bash
git tag v1.0.1
git push origin v1.0.1
```

3. ✅ This triggers the `publish.yml` GitHub Actions workflow, which:
   - Sets up Node.js
   - Publishes your package to GitHub Packages automatically

https://github.com/kworaitthinan-avanade/hello-node-gh-package/pkgs/npm/hello-node-gh-package

---

## 📄 License

MIT
