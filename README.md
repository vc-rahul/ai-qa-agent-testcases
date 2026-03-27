# QA Testcase Generator 🧪

AI Skill that generates **manual QA test cases** from requirement documents such as:

- BRD (Business Requirement Document)
- PRD (Product Requirement Document)
- SRS (Software Requirement Specification)
- User Stories
- Feature Descriptions

The generated output is **Excel-ready** and follows standard QA documentation practices.

---

## 🚀 Features

✅ Requirement analysis using AI  
✅ Generates structured manual test cases  
✅ Covers:
- Positive scenarios
- Negative scenarios
- Edge cases
- Validation checks
- Functional flows
- Error handling

✅ Standardized QA format  
✅ Excel-compatible output  
✅ Works with AI QA agents

---

## 📥 Input

Provide any requirement content:

- BRD
- PRD
- SRS
- Feature specification
- Jira story description

Example:
User should be able to login using email and password.


---

## 📤 Output Format

The skill generates test cases using the following columns:

| Column |
|-------|
| Case ID |
| Case Title |
| Case Description |
| Precondition |
| Test Steps |
| Expected Result |
| Execution Status |
| Comments |

---

## 🧾 Example Output

```json
[
  {
    "Case ID": "TC_001",
    "Case Title": "Valid Login",
    "Case Description": "Verify user login with valid credentials",
    "Precondition": "User account exists",
    "Test Steps": "1. Open login page\n2. Enter email\n3. Enter password\n4. Click login",
    "Expected Result": "User logs in successfully",
    "Execution Status": "",
    "Comments": ""
  }
]