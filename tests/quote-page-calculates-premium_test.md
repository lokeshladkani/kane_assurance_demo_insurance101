---
assurance:
  id: t-5
  base: sha256:placeholder-regenerate-with-kane-cli-testmd-author
---
# Quote page calculates a premium

> Prove that submitting valid quote inputs on the quote page returns a calculated premium result.

## Step 1 @verifies ac-3

Open https://shieldlife-insurance.replit.app/quote in a browser and wait for the quote form to render, then assert the form presents fields for calculating an estimated premium.

## Step 2 @verifies ac-3

Fill the quote form with valid representative inputs and submit it, then assert the page displays a calculated premium or quote result.
