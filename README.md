# 🌟 Last Stargazer Badge

Display the username of the **last person who starred your repository** with this dynamic GitHub Action!  
Let visitors engage with your project while adding a fun interactive touch.

![Last Stargazer](https://img.shields.io/badge/Last%20Stargazer-NathanCordeiro-brightgreen?style=flat-square)

## 🚀 How it Works

Whenever someone stars your repository, this GitHub Action automatically updates your `README.md` with a badge displaying their username. Give it a try by starring this repository and seeing your name appear above!

## 🛠️ Setup Instructions

To add the **Last Stargazer Badge** to your repository:

1. **Add the workflow file:**
   - Copy the file `.github/workflows/last-stargazer.yml` into your repository.

2. **Insert the badge in your README:**
   - Add the following markdown to your `README.md`:

     ```markdown
     ![Last Stargazer](https://img.shields.io/badge/Last%20Stargazer-NathanCordeiro-brightgreen?style=flat-square)
     ```

3. **Update repository permissions:**
   - Go to your repository settings.
   - Navigate to `Actions > General` and set **Workflow permissions** to:
     - `Read and write permissions`.

4. **Push your changes to the `main` branch**:
   - Once pushed, your GitHub Action will automatically fetch stargazers and update your README!

5. **Star your own repository** (optional):
   - Test it out by starring your repository and watch your username appear as the **Last Stargazer**! 🌟

---

## 👀 Example in Action

This repository uses the badge—star this repo to test it for yourself!  
Your name will appear here:

![Last Stargazer](https://img.shields.io/badge/Last%20Stargazer-NathanCordeiro-brightgreen?style=flat-square)

---

## ⚡ Features
- Updates every time someone stars your repository.
- Customizable badge style using [Shields.io](https://shields.io/).
- Simple and quick to set up!

---

## 📝 Notes
- Ensure your repository has **write permissions** enabled for Actions.
- Badges will not dynamically fetch for forks unless you also set up the workflow in the fork.
- If you change the styling options for the badge (e.g., color, style, etc.) in the GitHub Action YAML file, you will also need to update the README.md

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and adapt it!
