# SauceDemo-Automation-task
there is a new automation task usin Java script and playwright 

1. Installation
Prerequisites:
- Node.js
- npm
- playwright
Steps:
1. Clone or unzip this repository and open the folder.
2. Install dependencies using (npm install)
3. Install browsers using (npx playwright install)
4. Run with   ( npx playwright test --headed )
---------------------------------------------------------------------------
2. foldar structure and overview :-
   - it is in POM design pattern
     tests/ => e2ePurchaseFlow.spec.js
      pages/ =>
loginPage.js
 inventoryPage.js
 cartPage.js
 checkoutPage.js
 orderConfirmationPage.js
data/=> testData.json
playwright.config.js
 package.json
 README.md
----------------------------------------------------------------------------
  Tools and Libs :- 
Playwright (@playwright/test)
JavaScript (ES Modules)
Page Object Model (POM)
HTML Reporter
----------------------------------------------------------------------------
  Assumptions & Limitations
- Environment: Desktop browsers (Chromium, Firefox, WebKit).
- Data: Uses static credentials and hardcoded user info.
- Cross-browser: Enabled by default, can limit to Chromium.
- Network: Requires stable internet.
- Screenshots & Videos: Saved in test-results.
-----------------------------------------------------------------------------
  Summary
• End-to-end coverage of login → item selection → checkout → confirmation.
• Built on Playwright + JavaScript with modular POM.
• Generates HTML reports, screenshots, and videos on failure.


Author: Sara Ismail



