# Kiosk confirmation page

Shown after a patient submits the JotForm check-in form. Displays a green
checkmark and "Information Submitted Successfully", with buttons for
Español, Português, Русский, Türkçe, Oʻzbekcha and العربية. After a short
countdown it returns to the form so the kiosk resets.

## Setup
1. The form link (https://form.jotform.com/221544859310152) is set in `index.html` in two places: the meta refresh and `FORM_URL`.
2. Settings → Pages → Deploy from a branch → `main` / root.
3. In JotForm: Settings → Thank You Page → Redirect to an external link →
   `https://zeronolidge.github.io/kiosk-confirmation/`

Timer lengths and translations are in the Settings section at the top of the script.
