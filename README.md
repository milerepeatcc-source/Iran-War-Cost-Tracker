# Comprehensive Cost & Tax Tracker 🇺🇸

A lightweight, standalone web widget that calculates the live personal financial impact of U.S. federal spending and macroeconomic energy shocks. 

This project was built to provide transparency on how geopolitical events—specifically those tracked by [Iran Cost Ticker](https://iran-cost-ticker.com/) and the [Watson Institute's Costs of War Project](https://iranwarcost.watson.brown.edu/)—impact the everyday American taxpayer through both direct taxation and indirect inflation at the gas pump.

## 🌟 Features

* **Live Federal Spending Ticker:** Tracks the estimated total U.S. taxpayer spending in real-time.
* **Live Macro Fuel Burden Ticker:** Displays the cumulative billions of dollars in added fuel costs shouldered by the U.S. economy.
* **Progressive Tax Engine:** Users input their Adjusted Gross Income (AGI) and Filing Status (Single or Jointly). The app runs this through the official 2025 IRS progressive tax brackets to calculate their highly specific share of the federal budget.
* **Household Gas Premium:** Calculates the rolling average out-of-pocket cost paid per U.S. household at the pump due to global oil supply disruptions.
* **Total Personal Impact:** A unified dashboard that sums the user's direct tax burden and indirect household gas premium into one real-time personal cost.
* **Zero Dependencies:** 100% vanilla HTML, CSS, and JavaScript. No backend, no databases, no external libraries.

## 🚀 How to Use / Hosting

Because this is a static, single-file application (`index.html`), it is incredibly easy to host and share.

1.  **Run Locally:** Simply download or clone this repository and double-click `index.html` to open it in any modern web browser.
2.  **Host for Free:** You can deploy this instantly using free static hosting services:
    * **[GitHub Pages](https://pages.github.com/):** Go to your repository settings, navigate to "Pages," and set the source to your `main` branch.
    * **[Netlify](https://www.netlify.com/) / [Vercel](https://vercel.com/):** Drag and drop the folder containing `index.html` into their web dashboard for an instant live URL.
3.  **Embed on a Website:** Copy the code and paste it into a "Custom HTML" block on WordPress, Squarespace, Wix, or standard HTML sites.

## 🛠 Project History & Development Process

This project was built iteratively using an AI-assisted development workflow. Here is a summary of the development chat and version history:

* **v1 - The Baseline:** The project started as a request to build a static tax receipt calculator inspired by `represent.us`, mapping personal taxes to the `iran-cost-ticker.com` data.
* **v2 - Going Live:** Added JavaScript `setInterval` logic to create rolling tickers. The math was updated to calculate a user's micro-percentage of the overall $6.5 Trillion U.S. Federal Budget against the live spending rate.
* **v3 - Adding Macroeconomic Data:** Integrated research from Brown University's Watson Institute to account for indirect economic costs (gas premiums). Initial versions included user inputs for weekly gas consumption, which was later refined to display exact household averages to reduce user friction.
* **v4 - The Unified Dashboard:** Redesigned the UI/UX to clearly separate **Direct Tax Burden** from **Indirect Gas Costs**. Moved national macroeconomic data to the top and added a bottom-line **Total Estimated Personal Impact** section that sums both metrics dynamically.
* **v5 - Progressive Tax Brackets:** Completely replaced the initial flat 12% tax estimate with a dynamic script utilizing official 2025 IRS progressive tax brackets and standard deductions. Added a filing status selector for pinpoint accuracy.

## 📊 Data Sources & Methodology

Proper credit and attribution for the data models used in this calculator belong to the following organizations:

* **Federal Spending Data:** Baseline spending estimates and ticker methodology are sourced from [Iran Cost Ticker](https://iran-cost-ticker.com/).
* **Gas & Macroeconomic Data:** Fuel burden estimates, household averages, and macroeconomic inflation data are sourced from the [Costs of War Project at Brown University's Watson Institute](https://iranwarcost.watson.brown.edu/). 
* **Tax Calculation:** Personal tax burden is calculated dynamically by running the user's AGI and filing status through the official 2025 IRS standard deductions and progressive marginal tax brackets. This estimated total tax is then measured against a $6.5 Trillion U.S. Federal Budget benchmark.

## 🤖 AI Disclosure

The code, UI design, and mathematical scripting for this project were generated collaboratively using **Google's Gemini** Large Language Model. The AI was prompted to structure the math, write the vanilla HTML/CSS/JS, and design the responsive layout based on publicly available ticker methodologies.

## ⚠️ Disclaimer

This tool is for **educational and informational purposes only**. The figures presented are estimates based on macroeconomic models, historical federal budget ratios, and estimated bracket scaling. It does not represent exact financial advice or exact IRS tax routing. 
