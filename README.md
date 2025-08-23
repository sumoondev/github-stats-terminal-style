# 📊 GitHub Stats – Terminal Style

A dynamic GitHub stats card that looks like a **terminal window** 🖥️.  
This generates an SVG with your GitHub activity and updates automatically using GitHub Actions.

![GitHub Stats – Terminal Style](https://raw.githubusercontent.com/sumoondev/github-stats-terminal-style/main/github_stats.svg)

---

## 🚀 Setup

1. Fork or use this repo as a **template**.
2. Go to **Settings → Secrets and variables → Actions → New repository secret** and add:
   - `GH_TOKEN` → Your [GitHub Personal Access Token](https://github.com/settings/tokens) with `repo` & `read:user` scopes.
3. Commit changes. GitHub Actions will run and generate `github_stats.svg` at the root of your repo.

4. Use the SVG in your profile README:

   ```markdown
   ![GitHub Stats – Terminal Style](https://raw.githubusercontent.com/USERNAME/github-stats-terminal-style/main/github_stats.svg)
   ```

---

## 📝 Credits

* Original project by [**yogeshwaran01**](https://github.com/yogeshwaran01/github-stats-terminal-style)
* Modified & adapted by [**sumoondev**](https://github.com/sumoondev)

---

## 📄 License

This project follows the same license as the [original repository](https://github.com/yogeshwaran01/github-stats-terminal-style).

```
