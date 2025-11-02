# HR-Automation-Project-CV-Screening-System
This automation is designed to streamline the job application process by integrating Google Forms, Google Sheets, Gmail, Google Drive, and AI analysis (Google Gemini). It simplifies recruitment by automatically collecting applications, organizing CVs, generating AI-based summaries, and sending instant confirmation emails — making the entire hiring process faster, smarter, and more efficient.

# Where Can This System Be Used?
This automated workflow can be used in many organizations and departments where CVs, forms, or applications are received regularly — for example:

**Hospitals & Medical Colleges** – for staff recruitment (like SRMC)

**Schools, Colleges & Universities** – for teacher and staff hiring

**Corporate HR Departments** – for employee recruitment and onboarding

**IT Companies & Startups** – to manage internship and job applications

**NGOs & Government Offices** – for project-based hiring or form collection

**Training Institutes** – to collect student registrations or trainer applications

**Delivery & Service Businesses** – to hire riders, drivers, or support staff

# Workflow of the System

1. **Application Form** – Collects job application details and CV.
2. **Filter** – Checks if a CV file exists.
3. **Upload file** – Uploads CV to Google Drive (“SRMC CV” folder).
4. **Convert Binary to Json** – Extracts text content from the PDF CV.
5. **Google Gemini Chat Model** – AI engine used for CV analysis.
6. **Using AI Analysis & Rating** – Generates short 3-line CV summary.
7. **Unique ID** – Creates a unique application ID (e.g., SRMC-20251102058).
8. **Merge** – Combines AI summary with unique ID and form data.
9. **Edit Fields** – Prepares final data fields for storage.
10. **Candidate Lists** – Saves candidate data into Google Sheets.
11. **Inform HR New CV Received** – Sends email to HR with candidate details.
12. **Confirmation of CV Submission** – Sends confirmation email to candidate.
13. **Update row in sheet** – Marks “HR Received = Yes” in Google Sheet.
14. **Update row in sheet1** – Marks “Candidate Received = Yes” in Google Sheet.

# Why Use This Workflow

Automates the entire job application process

Saves HR time and reduces manual work

Sends instant confirmation emails to candidates

Notifies HR automatically when a new CV arrives

Uses AI (Google Gemini) to summarize resumes in 3 lines

Stores all data safely in Google Sheets with a unique ID

Uploads and organizes CV files in Google Drive automatically

Ensures error-free and consistent record keeping

Improves candidate experience and SRMC’s professional image

Makes HR review and shortlisting faster and smarter
