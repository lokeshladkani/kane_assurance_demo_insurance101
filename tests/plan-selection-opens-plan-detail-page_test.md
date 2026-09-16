---
assurance:
  id: t-4
  base: sha256:placeholder-regenerate-with-kane-cli-testmd-author
---
# Plan selection opens the plan detail page

> Prove that selecting a specific named plan from the plans listing navigates to a detail page describing that plan's benefits.

## Step 1 @verifies ac-2

Open https://shieldlife-insurance.replit.app/plans in a browser and wait for the plans listing to render, then select "TermShield Pro".

## Step 2 @verifies ac-2

Assert the browser navigates to a plan detail page for "TermShield Pro".

## Step 3 @verifies ac-2

On the plan detail page, assert at least one key benefit (e.g. "Low premiums", "Convertible to whole life", or "Premium waiver on disability") is visible.
