# ats-friendly-resume-latex
ATS-friendly resume workflow using LaTeX and structured prompts,with template,examples and step-by-step guide for consistent shortlisting 🔹 More technical Generate ATS-compatible resumes using LaTeX,with a clean template,controlled prompts and a repeatable workflow for reliable parsing
ATS Friendly Resume using LaTeX + ChatGPT

Problem

Most resumes are rejected before reaching a human reviewer. The primary reasons are:

- Poor formatting that breaks ATS parsing
- Missing role-specific keywords
- Overdesigned templates with tables,icons or graphics

Solution

This repository provides a structured workflow to convert any resume into a clean, ATS-compatible LaTeX format.
It combines a minimal template, controlled prompt usage and a repeatable process.

---

Who this is for

- MCA,B.Tech or degree freshers
- Candidates from Tier-2 or Tier-3 colleges
- Applicants applying off-campus
- Career switchers with non-traditional backgrounds

---

What this repo includes

- Clean LaTeX resume template (ATS-safe)
- Prompt for structured resume conversion
- Step-by-step workflow
- Example resumes (before and after)

---

Repository Structure

/template
    resume.tex

/prompts
    ats_prompt.txt

/examples
    before.pdf
    after.pdf

README.md

---

Workflow

Step 1: Prepare your data

- Use your existing resume
- Or write details manually:
  - Education
  - Skills
  - Projects
  - Experience

---

Step 2: Generate LaTeX code

- Open ChatGPT
- Paste your resume or details
- Use the prompt from "/prompts/ats_prompt.txt"
- Copy the generated LaTeX code

---

Step 3: Create project in Overleaf

- Create a new blank project
- Delete default code
- Paste your LaTeX code

---

Step 4: Compile

- Click Recompile
- Fix errors if any

---

Step 5: Download

- Export as PDF
- Keep resume length to 1 page (for freshers)

---

Prompt (used in this repo)

Convert the following resume into a clean ATS-friendly LaTeX format.

Requirements:
- Simple structure
- No tables, no graphics
- Clear sections: Education, Skills, Projects, Experience
- Use bullet points with action verbs
- Keep it one page
- Use consistent formatting

Input:
[Paste resume here]

---

Key ATS Guidelines (applied in template)

- No tables or multi-column layouts
- Standard section headings
- Text-based content only
- Consistent bullet formatting
- Keywords aligned with job descriptions

---

Common Mistakes

- Using Canva or design-heavy templates
- Adding icons,images or progress bars
- Writing long paragraphs instead of bullet points
- Missing keywords from job description
- Using inconsistent formatting

---

Results (example)

This approach was tested on entry-level job applications:

- Applications sent: 50
- Shortlisted: 6–10
- Improvement observed after restructuring resume format

Note: Results vary based on skills,projects and role alignment.

---

Important Notes

- This repo focuses on formatting and structure,not fake experience
- ATS optimization improves visibility,it does not guarantee selection
- Content quality still matters more than formatting

---

Future Improvements

- Role-specific keyword sets (DevOps,Full Stack,ML)
- More resume examples
- Error handling guide for LaTeX beginners

---

Contribution

Contributions are welcome:

- Improve template
- Add examples
- Suggest better prompts

---

License

This project is open source and free to use.
