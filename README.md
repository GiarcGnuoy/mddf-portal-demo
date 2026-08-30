# MDDF Member Portal — prototype

A working prototype of a member portal for the Maryland Defense Force: volunteer
hours, badge and certification tracks, unit rosters, open billets, and command
briefs.

**Live: https://giarcgnuoy.github.io/mddf-portal-demo/**

## This is a demonstration, not a system

- **Every person, unit, date and record in it is fictional.** No real member data
  is present, and none should ever be entered. Maryland policy MD-POL-205-01
  requires development and test systems to use sanitized, de-identified or
  synthetic data.
- **Nothing leaves your browser.** There is no server and no network call of any
  kind. The demo stores its state in your browser's local storage, so every
  visitor gets their own private copy and nobody can disturb anyone else's.
- **Do not use a real MDDF password.** Two buttons on the sign-in screen fill in
  demo credentials for you. Use the admin account to see the whole thing.

## What is in this repository

One file — `index.html` — the compiled prototype, fully self-contained. It is
built from a separate source repository and copied here; this repository exists
only to publish the page.
