# AI Job Application Automation
An AI-powered workflow that automates tailoring job applications.

Instead of manually spending 1–2 hours researching every company, tailoring my resume, rewriting it, creating a cover letter, organizing documents, and tracking applications, I built a workflow that automates most of the process.

# Architecture
Job URL
   │
   ▼
Apify
Extract job description
   │
   ▼
Claude
Evaluate company
Score opportunity
Choose best resume
   │
   ▼
Claude
Tailor resume
   │
   ▼
ChatGPT
Improve wording & readability
   │
   ▼
Claude + ChatGPT
Generate cover letter
   │
   ▼
Google Docs
Create documents
   │
   ▼
Airtable
Track application

# Tech Stack
• Make
• Airtable
• Claude API
• OpenAI API
• Apify API
• Google Docs API
• HTTP modules
• JSON parsing

# Features
✓ One-click application workflow
✓ Job description extraction
✓ Company evaluation
✓ Resume scoring
✓ Resume version selection
✓ Resume tailoring
✓ Cover letter generation
✓ Google Docs generation
✓ Airtable tracking

## Why I Built It
Tailoring every application manually often took 1–2 hours.
Rather than improving prompts over and over, I wanted to automate the entire workflow while keeping the output personalized.
This became my first end-to-end AI automation project.
