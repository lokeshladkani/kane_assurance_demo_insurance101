---
assurance:
  id: t-3
  base: sha256:placeholder-regenerate-with-kane-cli-testmd-author
---
# Plans page lists named plans

> Prove that the plans page presents the required named insurance plans for comparison.

## Step 1 @verifies ac-2

Open https://shieldlife-insurance.replit.app/plans in a browser and wait for the plans listing to render, then assert the page lists "TermShield Pro" and "FamilyCare Complete" (or "PremiumLife Elite") as named plans.

## Step 2

Capture the current browser URL and the visible identity of the loaded plans page before selecting a specific plan.
