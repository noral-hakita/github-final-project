# Contributing to github-final-project

First off, thank you for taking the time to contribute! This project is a specialized calculator designed to determine simple interest based on the core formula:

**Simple Interest** = $p \times t \times r$

### Key Variables:
* **p** = Principal amount
* **t** = Time period in years
* **r** = Annual rate of interest

---

## 🛠️ How Can I Help?

### 1. Bug Reports & Accuracy
Accuracy is the most important part of this project. If the calculator is not outputting the correct `p * t * r` result:
* Open an **Issue** in this repository.
* Clearly state the input values used for **p**, **t**, and **r**.
* Show the incorrect output vs. the expected output.

### 2. Feature Enhancements
We welcome ideas to make this calculator better! Examples include:
* Adding input validation (preventing negative numbers).
* Improving the User Interface (UI).
* Adding "Total Amount" calculation ($p + \text{interest}$).

### 3. Documentation
Found a typo? Is the `README.md` confusing? Pull requests for documentation improvements are always appreciated.

---

## 🚀 Development Workflow

1. **Fork** the project to your own GitHub account.
2. **Clone** the repo to your local machine.
3. **Create a Branch** for your changes:  
   `git checkout -b fix/calculation-logic`
4. **Verify the Formula**: Ensure any changes to the logic strictly follow the project requirement:  
   `simple interest = p * t * r`
5. **Commit** your changes with a clear message:  
   `git commit -m 'Fix interest calculation precision'`
6. **Push** to your fork and **Open a Pull Request**.



---

## 📝 Code Standards

* **Variable Consistency:** Always use `p`, `t`, and `r` for the calculation logic to remain consistent with the project's documentation.
* **Clean Code:** Keep the logic simple and readable.
* **Comments:** If you add a new function, include a brief comment explaining what it does.

---

## ⚖️ Code of Conduct
By contributing, you agree to keep discussions respectful and collaborative. Let's build a helpful tool together!
