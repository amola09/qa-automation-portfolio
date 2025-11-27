# qa-automation-portfolio

Live CI Results:
- Cypress: https://github.com/yourusername/qa-automation-portfolio/actions/workflows/cypress.yml
- Playwright: https://github.com/yourusername/qa-automation-portfolio/actions/workflows/playwright.yml

## Tools & Frameworks
| Tool          | Version   | Status |
|---------------|---------|--------|
| Cypress       | v13.15+ | Passing |
| Playwright    | v1.47+  | Passing |
| Javascript/TypeScript | Latest  | Used |
| GitHub Actions| Full CI/CD | Running |

## Quick Run Locally
```bash
# Cypress
cd cypress && npm install && npx cypress open

# Playwright
cd playwright && npm install && npx playwright test

# View reports
npx playwright show-report
