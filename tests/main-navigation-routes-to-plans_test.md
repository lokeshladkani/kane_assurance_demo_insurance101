---
assurance:
  id: t-1
  base: sha256:placeholder-regenerate-with-kane-cli-testmd-author
---
# Main navigation routes to Plans

> Prove that selecting "Plans" in ShieldLife's main navigation routes the visitor to the plans listing page.

## Step 1 @verifies ac-1

Open https://shieldlife-insurance.replit.app/ in a browser and wait for the homepage header to render, then assert the main navigation shows a "Plans" link.

## Step 2

Capture the current browser URL and the visible identity of the loaded homepage before selecting "Plans" from the main navigation.

## Step 3 @verifies ac-1

From the main navigation, open "Plans", then assert the browser shows the plans listing page at `/plans`.
