# Kiosk confirmation page

Shown after a patient submits the JotForm check-in form. Displays a green
checkmark and "Information Submitted Successfully", with buttons for
Español, Português, Русский, Türkçe, Oʻzbekcha and العربية. After a short
countdown it returns to the form so the kiosk resets.

## Setup
1. In `index.html`, replace `YOUR_FORM_ID` (two places) with the form link.
2. Settings → Pages → Deploy from a branch → `main` / root.
3. In JotForm: Settings → Thank You Page → Redirect to an external link →
   `https://<username>.github.io/kiosk-confirmation/`

Timer lengths and translations are in the Settings section at the top of the script.
