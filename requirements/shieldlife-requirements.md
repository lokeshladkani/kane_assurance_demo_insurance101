# ShieldLife Insurance Web App — Requirements

Target application: https://shieldlife-insurance.replit.app/

## Overview

ShieldLife is an online life/health/travel insurance web app. Visitors can browse insurance
plans (Term, Whole Life, Health, Travel), get a premium quote, sign up / log in, view plan
detail pages, and reach the company through direct contact info or a contact form. This
document defines the use-cases and acceptance criteria that the assurance suite must cover for
the public-facing site.

## Use Case 1: Primary navigation

As a visitor, I want to use the main navigation to reach the key sections of the site, so that
I can find the information relevant to me.

- AC-1.1: The main navigation exposes links to "Home" and "Plans" at minimum.
- AC-1.2: Selecting "Plans" navigates to the plans listing page (`/plans`).
- AC-1.3: Selecting "Contact" (or equivalent) navigates to the contact page (`/contact`).

## Use Case 2: Plan discovery

As a visitor evaluating coverage options, I want to browse the available insurance plans, so
that I can compare them before requesting a quote.

- AC-2.1: The plans page (`/plans`) lists individual named plans, including at least one term
  life plan (e.g. "TermShield Pro") and one family/whole-life plan (e.g. "FamilyCare Complete"
  or "PremiumLife Elite").
- AC-2.2: Selecting a specific plan navigates to a plan detail page describing that plan's
  coverage and benefits.
- AC-2.3: The plan detail page displays the plan's key benefits (e.g. low premiums, whole life
  option, premium waiver on disability).

## Use Case 3: Get a quote

As a prospective customer, I want to request a premium quote for a plan, so that I can decide
whether to purchase coverage.

- AC-3.1: The quote page (`/quote`) presents a form to calculate an estimated premium.
- AC-3.2: Submitting valid quote inputs displays a calculated premium/result to the visitor.

## Use Case 4: Account access

As a returning visitor, I want to log in to my account, so that I can view or manage my
policies.

- AC-4.1: The login page (`/login`) presents email and password fields.
- AC-4.2: Submitting the login form with an invalid email/password combination shows an
  "Invalid email or password" error message without navigating away.

## Use Case 5: Contact & support visibility

As a visitor, I want to see a direct support contact channel without filling a form, so that I
can reach out through my preferred channel.

- AC-5.1: The site displays a direct support email address (support@shieldlife.com), either on
  the contact page or in the site footer.
- AC-5.2: The contact page (`/contact`) is reachable from the main site and loads without error.

## Use Case 6: Claims information

As a policyholder, I want to find information about filing or checking a claim, so that I know
how to proceed if I need to make one.

- AC-6.1: The claims page (`/claims`) or claims-status page (`/claims-status`) is reachable from
  the site and describes the claims process or lets a visitor check claim status.
