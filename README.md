# CheckMate

AI-powered requirement validation web service

A web application that compares a requirement document with a submitted project document and automatically determines whether each requirement is Fulfilled, Partially Fulfilled, or Not Fulfilled, along with clear evidence sentences extracted from the submitted document.

---

### What does this project do?

CheckMate analyzes two uploaded documents:
1. Requirement Specification
2. Submission Document (report, implementation description, documentation, etc.)

Using AI-based text comparison, the system detects which requirements are met and presents:
- Requirement status (Fulfilled / Partially Fulfilled / Not Fulfilled)
- Supporting or missing evidence
- Downloadable evaluation results as a .txt file
- A clean and simple web UI for easy interaction

This removes the need for manual cross-checking and enables consistent, objective evaluation.

---

### Why is this project useful?

Many academic and team projects rely on manual checklist evaluation, which is:
- Time-consuming
- Inconsistent across evaluators
- Prone to oversight

CheckMate solves this by providing:
- Automated requirement verification
- Consistent evaluation logic
- Support for multiple document formats (PDF, DOCX, TXT)
- Clear evidence for each decision
- Fast and transparent feedback for teams and instructors

It is especially useful for:
- University team projects
- Open-source development assignments
- Document-based evaluations
- Self-checking before submitting official reports

---

How do I get started?
1. Clone the repository
```
git clone https://github.com/kwon-dohun/oss_teamproject2025
cd oss_teamproject2025
```

2. Run the Frontend
```
cd frontend
npm install
npm run dev
```

3. Run the Backend (Spring Boot)
```
cd checkmate
./gradlew bootRun
```

4. Usage
    1) Access the web UI
    2) Upload a requirement document
    3) Upload a submission document
    4) Receive automatic analysis
    5) Review requirement statuses and evidence
    6) Download the result file if needed

Everything works through a clean and minimal interface.

---

### Where can I get more help?

- Project repository: GitHub Issues & Discussions
- Source code (frontend + backend) for implementation details
- Future documentation will be added in /docs

If you have feature requests, bug reports, or improvement ideas, feel free to open an Issue.

---

### How you handle contributions?

Contributions are welcome.
All collaborators should follow the project workflow:
- Discuss ideas or problems via Issues
- Submit changes via Pull Requests
- Follow the Code of Conduct and Contribution Guidelines
- Use the provided templates for Issues and PRs
- Ensure clarity and testing before requesting a review

This structure ensures transparent and scalable collaboration.

---

### What are the goals of the project?

1. Automate requirement validation to reduce manual work.
2. Provide objective and consistent evaluation results.
3. Support multiple document formats for practical use.
4. Deliver clear explanations and evidence for all decisions.
5. Build a maintainable, extendable open-source project.
6. Serve as a reference for learning proper OSS workflows.

