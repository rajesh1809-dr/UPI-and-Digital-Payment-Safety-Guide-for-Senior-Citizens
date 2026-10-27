# UPI & Digital Payment Safety Guide for Senior Citizens

A beginner-friendly, bilingual (English + Tamil) educational project for senior citizens and family caregivers. This is an awareness prototype only: it does not process payments, collect bank details, or contact emergency services.

## Features
- Large-print, high-contrast responsive website
- English/Tamil language toggle
- Read-aloud support using browser speech synthesis (browser/voice dependent)
- Stop-and-check checklist
- Six fictional scam training samples with safe responses
- Eight-question interactive quiz with feedback
- Emergency reporting guidance and official links
- Weekly WhatsApp-ready safety-tip draft generator
- Printable poster and five-slide workshop deck
- Research, prompt library, verification log, before/after analysis, and demo checklist

## Run locally
No build step or dependencies are required.

1. Download and unzip this repository.
2. Open `index.html` in a modern browser, or serve it locally:
   ```bash
   python -m http.server 8000
   ```
3. Visit `http://localhost:8000`.

## Project structure
```text
.
├── index.html
├── styles.css
├── app.js
├── README.md
├── docs/
│   ├── research-report.md
│   ├── stop-and-check.md
│   ├── scam-training-samples.md
│   ├── large-print-guide.md
│   ├── tamil-guide.md
│   ├── workshop-slides.md
│   ├── quiz-answer-key.md
│   ├── audio-tips.md
│   ├── automation.md
│   ├── prompt-library.md
│   ├── verification-report.md
│   ├── before-after-analysis.md
│   └── final-demo-checklist.md
├── automation/
│   └── weekly-tip-template.md
├── assets/
│   └── poster.svg
└── tests/
    └── manual-test-plan.md
```

## Safety principles
- Never share a UPI PIN, OTP, password, or screen-sharing access with a caller.
- A UPI PIN is used to authorize certain transactions; it is not needed to receive money.
- Verify the recipient and amount before approving a payment.
- If money may have been lost to cyber fraud in India, contact 1930 promptly and report at https://www.cybercrime.gov.in/.
- Use only official contact details from a bank/app's official website or app.
- This guide does not guarantee that every scam can be detected.

## AI tools and academic honesty
The project includes a prompt library and verification template. For your assignment, actually run the research prompts in at least two tools (for example, ChatGPT and Gemini or Perplexity), save screenshots/URLs/date accessed, and record what each tool got wrong or right. Do not claim a tool was used unless you used it. Availability of free tiers and features may change.

## Official source starting points
- RBI: https://www.rbi.org.in/
- RBI Kehta Hai: https://rbikehtahai.rbi.org.in/
- NPCI fraud awareness: https://www.npci.org.in/fraud-awareness
- CERT-In: https://www.cert-in.org.in/
- National Cyber Crime Reporting Portal: https://www.cybercrime.gov.in/

Check the exact page and publication date before submitting. Official pages may move or be updated.

## GitHub
Create a new repository on GitHub, then upload these files or push them with Git:
```bash
git init
git add .
git commit -m "Build UPI senior citizen safety guide"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
Replace the URL with your own repository URL. Never put passwords, API keys, or personal bank information in the repository.
