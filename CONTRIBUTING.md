# Contributing to CONTRIBUTORS

First off, thank you for taking the time to contribute! This project is designed specifically for practice.

## Steps to contribute

### 1. Fork the Repository
Click the "Fork" button at the top right of this page to create a copy of this repository in your GitHub account.

### 2. Clone your Fork
Open your terminal and run:
```bash
git clone https://github.com/YOUR_USERNAME/CONTRIBUTORS.git
```
*(Replace `YOUR_USERNAME` with your GitHub username)*

### 3. Create a Branch
Go into the project directory and create a new branch:
```bash
cd CONTRIBUTORS
git checkout -b add-yourname
```

### 4. Add your Profile
1. Navigate to the `contributors/` folder.
2. Create a new file named `your-username.md`.
3. Fill it with some info about yourself. For example:
   ```markdown
   # Your Name
   - GitHub: [@your-username](https://github.com/your-username)
   - Bio: I am learning open source!
   - Favorite Language: JavaScript
   ```

### 5. Commit and Push
```bash
git add contributors/your-username.md
git commit -m "Add your-username to contributors"
git push origin add-yourname
```

### 6. Create a Pull Request
Go to the original repository on GitHub. You should see a "Compare & pull request" button. Click it and submit!

---
Happy coding!
