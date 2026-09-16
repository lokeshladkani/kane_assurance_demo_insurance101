---
assurance:
  id: t-2
  base: sha256:placeholder-regenerate-with-kane-cli-testmd-author
---
# Main navigation routes to Contact

> Prove that selecting "Contact" in ShieldLife's main navigation routes the visitor to the contact page.

## Step 1 @verifies ac-1

Open https://shieldlife-insurance.replit.app/ in a browser and wait for the homepage header to render, then assert the main navigation exposes a "Contact" link.

## Step 2 @verifies ac-1

From the main navigation, open "Contact", then assert the browser shows the contact page at `/contact`.
