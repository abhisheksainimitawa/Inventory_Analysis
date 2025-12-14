# Inventory Analysis Project

## Overview
This project focuses on analyzing and optimizing inventory, purchase, and sales data. The main analysis is conducted in the `solution.ipynb` notebook, which includes various sections such as data preprocessing, demand forecasting, ABC analysis, EOQ calculation, reorder point analysis, lead time analysis, stock aging analysis, and inventory optimization.

## Files
- `solution.ipynb`: Contains the main analysis and optimization code for inventory, purchase, and sales data.

## How to Run the Notebook Locally

1. **Install Python**  
   Ensure you have Python 3.8+ installed. You can download it from [python.org](https://www.python.org/downloads/).

2. **Install Required Libraries**  
   Open a terminal and run the following command:
   ```
   pip install pandas numpy matplotlib seaborn prophet jupyter
   ```

3. **Download the Data Files**  
   Place the necessary CSV files in the same folder as the notebook:
   - 2017PurchasePricesDec.csv
   - BegInvFINAL12312016.csv
   - EndInvFINAL12312016.csv
   - InvoicePurchases12312016.csv
   - PurchasesFINAL12312016.csv
   - SalesFINAL12312016.csv

4. **Open the Notebook**  
   In the terminal, navigate to the project folder and run:
   ```
   jupyter notebook
   ```
   Then open `solution.ipynb` in your browser.

5. **Run All Cells**  
   In Jupyter, click "Cell" > "Run All" to execute the notebook.

6. **View Results**  
   The plots and analysis will appear below each code cell.

## Key Insights
- The analysis identifies top-selling products and forecasts future demand.
- ABC analysis categorizes products based on sales revenue, helping prioritize inventory management.
- EOQ and ROP calculations optimize order quantities and timing.
- Lead time analysis highlights vendors and products with long lead times, indicating areas for improvement.
- Stock aging analysis reveals slow-moving inventory, guiding decisions on markdowns or liquidation.

This project aims to enhance inventory management practices through data-driven insights and optimizations.





---
layout: default
---

# Pull Request Guidelines

## Core Principles

- **Code Quality Obsessed** - Every line matters for production stability
- **Clean Code** - Readable code reduces bugs and maintenance costs
- **Type Safety** - Catch errors at compile time, not in production
- **Broken Window Policy** - Fix small issues before they become big problems

## 1. Before You Code

- **Keep it small** - Large PRs are harder to review, more likely to have bugs, and slower to merge. One logical change only.
- **Create proper branch** - `author/type/description` helps teammates know who's working on what (e.g., `john/fix/login-bug`)

## 2. Writing Commits

`type: description` (max 50 chars) - Clear history helps with debugging and rollbacks
- **feat:** `feat: add email auth` - New features
- **fix:** `fix: resolve timeout` - Bug fixes  
- **chore:** `chore: update dependencies` - Maintenance tasks
- **refactor:** `refactor: improve API performance` - Code improvements
- **docs:** `docs: update API guide` - Documentation changes
- **test:** `test: add login automated tests` - Adding automated tests
- Use imperative mood: "Add" not "Added"

## 3. Creating Your PR

**Title:** Clear, specific description tells reviewers exactly what changed
- Good: "Add email login functionality" 
- Bad: "Update login stuff"

**Description:** Complete the entire [PR template](https://github.com/jalantechnologies/boilerplate-mern/blob/main/.github/pull_request_template.md) - this is your documentation for future developers
- **Why** this change is needed - Context prevents future bugs and confusion
- **API/Database changes** - Critical for deployment planning (even if "None")
- **Screenshots** - Visual proof reduces back-and-forth questions
- **Testing** - Shows you've verified the change works

**Meta Information:** Set proper PR metadata for tracking and organization
- **Assignee:** Assign to yourself - You own this change
- **Labels:** Use appropriate labels (feature, bug, documentation, etc.) - Helps with filtering and metrics

> **⚠️ Incomplete descriptions = rejected PRs** - Poor documentation leads to production issues

## 4. Before Requesting Review

> **MANDATORY self-review checklist - Catches 90% of issues before wasting reviewer time:**

- [ ] **Line-by-line code review** - Pretend you're reviewing someone else's code
- [ ] **Test your changes** - Verify your work AND ensure it doesn't break existing related functionality. Broken code in review wastes everyone's time
- [ ] **Complete PR template** - Missing context leads to poor review quality
- [ ] **Record Loom video** - Explains business impact and saves review meeting time
- [ ] **Add automated tests** (backend PRs) - Prevents regressions and builds confidence
- [ ] **Clean up** - Debug code, console.log, and comments make code unprofessional
- [ ] **All previous feedback addressed** - Ignoring feedback damages team relationships

## 5. Timeline

Give reviewers 24 hours - Quality review takes time. Follow up if blocking other work.

---

*Remember: PRs are permanent documentation. Write them for the developer who will debug this code at 2 AM in 6 months.*
