NEW JERSEY BALINTAWAK — FULL SITE
============================================

PAGES
-----
index.html    — Home
about.html    — About (GM Taboada + Guro Frank bios, mission)
events.html   — Events (upcoming seminar + past event archive)
updates.html  — Updates (news posts)
faqs.html     — FAQs (click-to-expand questions)
contact.html  — Contact (info + form)

styles.css    — all shared styling (brand green: #209D50)
script.js     — mobile nav toggle + auto footer year
images/       — all your real photos, already wired in

CONTACT FORM — IMPORTANT
--------------------------
Plain static sites (GitHub Pages, etc.) can't run server code, so a
contact form has nowhere to submit *to* on its own. Right now the form
is wired to open the visitor's email app via mailto: — it works with
zero setup, but some people find it clunky (it depends on them having
an email client configured).

If you'd rather visitors just click Send and be done, the standard
free fix is a "form backend" service — you paste one line into the
form's action, no account needed to test, free tier for low volume:
  - Formspree (formspree.io) — most popular, easiest
  - Web3Forms (web3forms.com) — no signup needed at all
Say the word if you want this wired in — it's a five-minute change.

HOSTING — NEXT STEP
----------------------
Same plan as before: GitHub Pages (free) + your GoDaddy domain.
When you're ready:
  1. Create a free GitHub account + a new public repo
  2. Upload everything in this folder (keep the images/ folder structure)
  3. Turn on GitHub Pages for the repo (Settings → Pages)
  4. In GoDaddy's DNS settings, point newjerseybalintawak.com at
     GitHub Pages (I'll give you the exact records when you're there)

Just let me know when you want to do this part and I'll walk you
through it step by step.
