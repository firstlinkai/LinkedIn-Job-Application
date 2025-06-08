# LinkedIn-Job-Application
End-to-End Job Application Automation — Powered by AI and No-Code

An AI-powered system that fully automates the job application process—from job discovery to resume submission—built using n8n, ChatGPT (OpenAI), Google Sheets, and RSS.app.

Here’s how the system works step-by-step:

🔁 Automated Job Discovery
Using RSS.app, custom job feeds from LinkedIn are generated based on specific keywords and locations. These feeds are monitored in n8n, which triggers the workflow at scheduled intervals.

📥 Extracting Job Details
The system retrieves job listings and fetches additional information—such as company name, job description, and benefits—via an HTTP request node.

🤖 AI-Powered Parsing and Analysis
Using OpenAI’s GPT-4, the HTML content of each job post is summarized into structured data.
Another AI model then evaluates each job against the candidate’s resume and assigns a compatibility score.

📝 Custom Cover Letter Generation
A separate AI model crafts a tailored cover letter for every job post based on the resume and job description.

📊 Centralized Job Tracking
All extracted information—job details, rating, and cover letter—is logged into Google Sheets, ensuring a complete and organized application record.
