---
assurance:
  id: t-6
  base: sha256:placeholder-regenerate-with-kane-cli-testmd-author
---
# Login with invalid credentials shows an error

> Prove that submitting the login form with an invalid email/password combination surfaces an error message instead of navigating away.

## Step 1 @verifies ac-4

Open https://shieldlife-insurance.replit.app/login in a browser and wait for the login form to render, then assert it presents email and password fields.

## Step 2 @verifies ac-4

Submit the login form with an invalid email/password combination, then assert the page displays an "Invalid email or password" error message and remains on the login page.
