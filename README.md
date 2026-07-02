# AI Job Application Automation

An end-to-end AI workflow that transforms a job posting URL into tailored application documents using multiple LLMs, APIs, and workflow automation.
Built while transitioning from 7+ years in Real Estate sales into SaaS Sales.

---

## Architecture

![AI Automation Pipeline](pipeline.png)

The workflow starts with a job posting URL and automatically extracts the job description, evaluates the opportunity, selects the most appropriate resume version, generates a tailored resume and cover letter, publishes both documents to Google Docs, and tracks every application in Airtable.

## Tech Stack
### Platforms
- Make
- Airtable
- Google Docs
### AI Models
- Claude
- ChatGPT
### APIs
- Claude API
- OpenAI API
- Apify API
- Google Docs API
### Workflow
- HTTP Modules
- JSON Parsing

## Features
- Job description extraction
- Company and role evaluation
- Resume version selection
- AI tailored resume generation
- AI tailored cover letter generation
- Google Docs publishing
- Airtable tracking
- End to end workflow automation

## Why I Built It
Tailoring every application manually often took 1–2 hours.
Rather than improving prompts over and over, I wanted to automate the entire workflow while keeping the output personalized.
This became my first end-to-end AI automation project.

## Results
- Reduced manual application time from 1–2 hours to a few minutes
- Automated 8 stages of the application workflow
- Uses Claude for evaluation and document generation, with ChatGPT as a quality control and language refinement layer.
- Generates application documents automatically
- Keeps every application organized in Airtable

## Future Improvements
- Apollo API integration
- Clay enrichment
- HubSpot CRM synchronization
- Automated LinkedIn outreach
- Contact discovery
- AI generated personalized emails
- n8n version of the workflow
- Multi-agent architecture with specialized LLMs
