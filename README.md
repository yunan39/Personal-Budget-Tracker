# Personal-Budget-Tracker
SpendWise - Budget Tracker
https://spendwise-budget-tracker-9599c4.netlify.app/
# SpendWise – Personal Budget & Expense Tracker

## Project Description
SpendWise is an interactive web-based personal budgeting application designed to help users manage their finances effectively. Users can input their total monthly budget, log categorized expenses, and view real-time calculations of their total spending, budget utilization percentage, and remaining balance.

---

## Technologies Used
* **HTML5:** Semantic structure and layout of the application interface.
* **CSS3:** Custom styling, responsive design, and visual organization of forms and summary cards.
* **JavaScript (ES6+):** DOM manipulation, event handling, arithmetic calculations, and interactive user feedback.
* **Git & GitHub:** Version control and remote repository hosting.
* **Netlify:** Static web hosting and Continuous Deployment (CI/CD).

---

## GitHub Repository Information
* **Repository URL:** [https://github.com/YOUR_USERNAME/spendwise](https://github.com/YOUR_USERNAME/spendwise)
* **Branch Deployed:** `main`
* **Visibility:** Public

---

## Live Netlify Website URL
* **Live Application:** [https://YOUR-CUSTOM-NAME.netlify.app](https://YOUR-CUSTOM-NAME.netlify.app)

---

## Deployment Process Summary
1. **Deployment Readiness:** Verified that `index.html`, `style.css`, `script.js`, and `README.md` were organized cleanly in the root directory with accurate relative file paths.
2. **GitHub Repository Setup:** Initialized a local Git repository, committed all project files, and pushed them to a public GitHub repository on the `main` branch.
3. **Netlify Hosting Integration:** Connected the GitHub repository to Netlify via **Import an existing project** and deployed the root directory.
4. **Custom Domain Configuration:** Updated the auto-generated Netlify subdomain to a clean, project-specific site name (`YOUR-CUSTOM-NAME.netlify.app`).
5. **Continuous Deployment Verification:** Made a visible UI update locally, pushed the commit to GitHub, and confirmed that Netlify automatically triggered a rebuild and updated the live site.
6. **Production Testing:** Tested the live URL across desktop and mobile views and inspected browser DevTools to ensure zero console or network errors.

---

## Challenges Encountered During Deployment
* **Root Directory Structure:** Ensuring `index.html` resided at the root of the repository rather than inside a nested folder so Netlify could locate and serve the entry point without returning a `404 Page Not Found` error.
* **Case-Sensitive Asset Paths:** Double-checking that all `<link>` and `<script>` references matched exact lowercase filenames (`style.css` and `script.js`), since Netlify's Linux servers enforce strict case sensitivity.

---

## Lessons Learned
* **Automated CI/CD Workflows:** Connecting GitHub directly to Netlify eliminates manual re-uploads—every push to the `main` branch automatically builds and publishes changes to production within seconds.
* **Environment Differences:** Code that works locally on Windows or macOS can break on cloud servers if file paths or casing are inconsistent.
* **Post-Deployment Verification:** Always test the live production link in a fresh browser tab with DevTools open to verify that styles, scripts, and interactive features behave identically to the local build.
