# Make Your First PR

Welcome to **Make Your First PR** — a safe and simple project for beginners to make their first open-source contribution! This project allows anyone to add their name and GitHub link to the contributors section, helping you get hands-on experience with Git, GitHub, and basic HTML/CSS.

---

## Project Overview

* Simple HTML & CSS project with dark developer-style theme.
* Banner welcoming contributors with clear instructions.
* Contributors section where each contributor can add their name, email, and GitHub link.
* Fully responsive design for mobile and desktop.
* Great for learning your first pull request and basic collaboration workflow.

---

## Project Structure

```
make-your-first-pr/
│
├── index.html          # Main homepage
├── style.css           # Stylesheet for the project
└── README.md           # Project instructions (this file)
```

---

## Git & GitHub Steps

1. **Fork this repository**

   * Click the **Fork** button on the top-right of the GitHub repo page.

2. **Clone your fork locally**:

   ```bash
   git clone https://github.com/your-username/make-your-first-pr.git
   cd make-your-first-pr
   ```

3. **Add Your Name (HTML Steps)**

   1. Open the `index.html` file.
   2. Find the section called **All Contributors**.
   3. Copy one of the existing contributor cards:

      ```html
      <div class="contributor-card">
        <h3>Contributor Name</h3>
        <p>Email: example@example.com</p>
        <p>
          GitHub: <a href="https://github.com/username" target="_blank">github.com/username</a>
        </p>
      </div>
      ```
   4. Paste it below the other cards.
   5. Replace the name, email, and GitHub link with your own.
   6. Save the file — your info will show up instantly.

4. **Create a new branch**:

   ```bash
   git checkout -b add-your-name
   ```

5. **Stage & commit your changes**:

   ```bash
   git add .
   git commit -m "Added my name to contributors list"
   ```

6. **Push your branch to your fork**:

   ```bash
   git push origin add-your-name
   ```

7. **Open a Pull Request (PR)**

   * Go to your fork on GitHub → click **Compare & Pull Request** → Submit.

---

## Contribution Guidelines

* Always use a **new branch** for your changes.
* Keep your **card format consistent** with existing cards.
* Only add **your own info** — do not modify others’ cards.
* Write a **clear commit message**, e.g., `"Added my name to contributors list"`.
* Be patient while your PR is reviewed. 🎉

---

## License

This project is open source and free to use under the **MIT License**.

---
