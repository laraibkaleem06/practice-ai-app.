# 🎓 Scholar Match
### AI-Powered Scholarship Discovery and Eligibility Assistant

**Team Name:** Vectors  
**Project Category:** Education Technology (EdTech)  
**Project Type:** AI-Powered Web Application

**Team Members:**
- Alishba Kamran
- Laraib Kaleem
- Maryam Fareed

---

## 1. Project Overview

Scholar Match is a web application designed to help students discover scholarship opportunities that may match their academic background, financial circumstances, and educational goals.

Many students miss scholarship opportunities because they are unaware of available programs, struggle to understand eligibility requirements, or have difficulty finding accurate information about deadlines and required documents.

Scholar Match brings scholarship information into one accessible platform. Students can enter relevant details to explore potentially suitable opportunities, review eligibility criteria, identify required documents, and receive assistance drafting scholarship application essays or emails where AI writing assistance is implemented.

Our mission is to make scholarship information easier to access and help students make informed decisions about financing their education.

## 2. Problem Statement

Access to higher education can be challenging for students facing financial constraints. Although government organizations, universities, and educational institutions offer scholarships and financial assistance, students often struggle to identify opportunities that fit their circumstances.

Key problems include:

- **Lack of awareness:** Students may not know which scholarships are available to them.
- **Confusing eligibility criteria:** Academic requirements, financial need, residency rules, and other conditions can be difficult to interpret.
- **Missed deadlines:** Information is spread across different websites and announcements, making deadlines harder to track.
- **Unclear document requirements:** Students may not know which documents to prepare.
- **Application-writing difficulties:** Students may need help writing scholarship essays, personal statements, and formal emails.
- **Limited guidance:** Students without access to educational counsellors may find the application process difficult to navigate.

Consequently, students may miss opportunities for financial assistance simply because they cannot easily find or understand the relevant information.

## 3. Our Solution

Scholar Match provides a centralized platform to help students discover potentially suitable scholarships based on their academic profile and relevant personal circumstances.

Students can provide information such as academic marks or CGPA, city, degree program, educational level, and approximate household income. The application compares the profile with the scholarship information available in its dataset and presents potentially relevant opportunities.

For each scholarship, the application can display available eligibility information, required documents, deadlines, and official source links. Where AI assistance is implemented, it can also help students understand requirements and draft application essays or emails.

### How It Works

1. **Enter a profile:** Provide the academic and other information requested by the application.
2. **Discover scholarships:** The application compares the profile with its available scholarship dataset.
3. **Review eligibility:** Check which criteria appear to match and which details need verification.
4. **Check requirements:** Review available information about documents, deadlines, and application procedures.
5. **Get writing assistance:** If enabled, use AI to generate a draft essay or application email based on information provided.
6. **Verify and apply:** Visit the official source to confirm the latest details and submit an application through the scholarship provider.

Scholar Match offers preliminary guidance; it does not guarantee eligibility or scholarship approval.

## 4. Key Features

Include only features that are implemented and working in the submitted version of the application.

- **Personalized scholarship matching:** Compares student details against available scholarship criteria.
- **Centralized scholarship information:** Organizes scholarship opportunities in one place.
- **Eligibility guidance:** Helps explain criteria and identify requirements that need checking.
- **Deadline information:** Displays deadlines when they are available in the dataset.
- **Document checklist:** Lists documents specified by the relevant scholarship, where this information is available.
- **AI-powered application assistance:** Can draft essays, personal statements, or formal emails if AI integration is implemented.
- **Scholarship search:** Helps students explore available opportunities.
- **Accessible web interface:** Aims to make scholarship discovery straightforward for students.

## 5. Technology Stack

Update this section to reflect the technologies actually used in the project.

| Technology | Purpose |
|---|---|
| Python | Application logic, if used |
| Streamlit | Web interface, if used |
| Pandas | Processing scholarship data, if used |
| AI API / Large Language Model | Natural-language assistance and draft generation, if integrated |
| CSV or JSON | Storing scholarship records, if used |
| Git | Tracking code changes |
| GitHub | Hosting and collaborating on source code |
| Hosting platform | Publishing the application online |

### AI Integration

If an AI API is integrated, it can help explain scholarship requirements, summarize supplied information, or draft application text. Scholarship matching should rely on the curated scholarship data and explicit eligibility rules wherever possible, rather than asking an AI model to invent scholarship details.

AI-generated content must be reviewed by the student. API keys must be stored securely and must never be committed to a public repository.

## 6. How Scholarship Matching Works

The application can compare a student's profile with scholarship criteria such as:

- Academic marks or CGPA.
- Educational level and degree program.
- City, province, or residency requirements.
- Household income or financial need.
- Admission or enrollment status.
- Other scholarship-specific requirements.

The matching process identifies opportunities that appear relevant based on the information available. If a required detail is missing, the application should mark it as unknown rather than assuming the student qualifies.

A match is not an official eligibility decision. Scholarship providers make final decisions.

## 7. How to Run the Project Locally

The following instructions apply to a Python and Streamlit version. Adjust them if the project uses a different framework or entry-point filename.

### Prerequisites

- Python 3
- Visual Studio Code or another code editor
- Git (needed to clone the repository)

### Step 1: Clone the Repository

Replace the placeholder with the actual GitHub repository URL:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd scholar-match
```

### Step 2: Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Or in Windows Command Prompt:

```bat
.venv\Scripts\activate.bat
```

### Step 3: Install Dependencies

If the repository includes `requirements.txt`, run:

```bash
python -m pip install -r requirements.txt
```

For a basic Streamlit project, the file might contain:

```text
streamlit
pandas
```

Keep only dependencies the project actually uses, and add any required AI SDK if applicable.

### Step 4: Configure AI Secrets (If Required)

If the application uses an external AI API, configure its key using the secret name expected by the code. For Streamlit, a local `.streamlit/secrets.toml` file may be used.

Example only:

```toml
AI_API_KEY = "YOUR_API_KEY_HERE"
```

Replace the variable name with the one your code expects. Do not commit real API keys, passwords, or private credentials to GitHub. If the app does not use an external AI API, skip this step.

### Step 5: Run the Application

For a Streamlit app whose main file is `app.py`:

```bash
streamlit run app.py
```

Open the local address shown in the terminal (usually `http://localhost:8501`) in your browser.

## 8. Deployment

The app can be deployed using a hosting platform compatible with the framework used by the project.

For a Streamlit application, Streamlit Community Cloud is one option:

1. Push the project code to GitHub.
2. Ensure the repository includes the required files and `requirements.txt`.
3. Connect the repository to Streamlit Community Cloud.
4. Select the correct branch and application entry-point file.
5. Configure any required API secrets in the platform's settings.
6. Deploy and open the public URL.
7. Test the app in a private/incognito browser window.

**Live Application:** Add the deployed application URL here.  
**GitHub Repository:** Add the repository URL here.

Deployment should only be described as complete after the public link has been tested.

## 9. Scholarship Data and Sources

The usefulness of Scholar Match depends on the quality and accuracy of its scholarship dataset.

Potential official sources for research include:

- Higher Education Commission of Pakistan (HEC): https://www.hec.gov.pk/
- Punjab Educational Endowment Fund (PEEF): https://peef.org.pk/
- University scholarship and financial-aid offices.
- Official scholarship program announcements and application portals.

These are starting points for research, not confirmation that every program is currently open or available to every student.

For each scholarship included in the application, record as much of the following as possible:

- Scholarship name and provider.
- Official source URL.
- Eligibility criteria.
- Academic and financial requirements.
- Required documents.
- Official deadline, if announced.
- Application procedure.
- Date the information was last checked.

Verify information against official sources because deadlines and requirements can change. Add the actual pages used to build the dataset before submission.

## 10. Limitations

- **Limited dataset:** The application can only match students against scholarships included in its dataset.
- **Potentially outdated information:** Deadlines, eligibility requirements, and funding availability may change.
- **Preliminary matching:** A match does not guarantee eligibility, selection, or funding.
- **Incomplete profiles:** Missing or inaccurate student information may affect results.
- **AI limitations:** AI-generated drafts may contain errors or unsuitable wording and should be reviewed and personalized.
- **Document-processing limitations:** If document upload or text extraction is implemented, unclear scans, handwriting, or unusual formatting may be processed incorrectly.
- **Internet/API dependency:** AI features using an external API may depend on connectivity, service availability, usage limits, and costs.
- **Privacy considerations:** Student profiles and academic/financial documents should be handled securely and not retained or shared unnecessarily.

## 11. Future Improvements

Potential future improvements include:

- Expanding the database with more verified scholarships.
- Adding deadline reminders and application tracking.
- Supporting Urdu and other regional languages.
- Improving extraction of information from uploaded academic documents.
- Adding filters for degree programs, locations, and financial requirements.
- Allowing students to save scholarships to a personal dashboard.
- Explaining missing eligibility information more clearly.
- Establishing a reliable process for regularly verifying scholarship records.
- Strengthening privacy and document-security controls.

## 12. Project Impact

Scholar Match aims to make scholarship information easier to find, reduce confusion during the search process, and help students prepare applications more effectively.

By combining structured scholarship information, eligibility-based matching, and—where implemented—AI-assisted writing, the project seeks to reduce the information gap between students and available educational funding.

**Our goal:** Help students spend less time searching for opportunities and more time preparing to pursue them.

## 13. Team

**Team Vectors**

- Alishba Kamran
- Laraib Kaleem
- Maryam Fareed

**Project:** Scholar Match  
**Category:** Education Technology  
**Mission:** Making scholarship discovery simpler, clearer, and more accessible.

---

*Built by Team Vectors for the DITE Hackathon 2026–27.*
