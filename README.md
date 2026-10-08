# Launchkit: Resume Analyzer

Launchkit helps students check their resume before applying for a job. Many students get rejected without knowing why, so this tool shows what to fix.

## What it does
1. **Resume:** upload a PDF, DOCX, or TXT file, or paste your resume text.
2. **Company:** add the company name and, if you have it, the job description.
3. **Role:** pick your target role (Full Stack, Frontend, Backend, Cloud/DevOps, Data Analyst, or ML/AI).
4. **Your plan:** get a match score, a list of found and missing skills, a resume checklist, a 7-day preparation plan, and practice interview questions.

## How it works
The analysis is **keyword based**. The tool reads your resume text and checks it against the skills usually needed for the chosen role. It does not use an AI model, so treat the result as a checklist, not a final verdict.

Your resume is read inside your browser and is never uploaded anywhere.

## Built with
HTML, CSS, and JavaScript in a single file. PDF and DOCX reading uses the pdf.js and mammoth libraries.

## Run it
Download `index.html` and open it in any browser. No installation needed.

## Live demo
https://darshpreetkaur95-sys.github.io/launchkit-resume-analyzer/
