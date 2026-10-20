Course: BS in Data Science and Applications — IIT Madras
Course / Project Code: BS042001P
Student Name: Nikita Neethi
Student ID: 25f2006342
Project Status: Initial repository setup

1. Purpose of This Repository

This repository will contain the code, notebooks, experiments, documentation, and other deliverables developed for the Introduction to Deep Learning and GenAI project.

The repository is intended to keep the project organised, reproducible, easy to review, and straightforward for the instructor to evaluate.

2. Mandatory Repository Setup

- Keep the repository private unless the instructor explicitly asks for public access.
- Invite the instructor as a collaborator and confirm that the invitation has been accepted.
- Maintain a clear README.md and a consistent folder structure.
- Do not commit passwords, API keys, access tokens, private credentials, or other sensitive information.
- Do not upload large datasets or files unless they are permitted by the project instructions.

3. Branching Strategy

Use Git branches to separate ongoing work from the stable version of the project.

- main — stable, reviewed work.
- dev — integration branch for ongoing development, if needed.
- feature/<short-description> — a focused feature, experiment, or task.
- fix/<short-description> — a bug fix or correction.

Suggested workflow

1. Create a feature branch from dev (or main if no dev branch is being used).
2. Make small, focused changes and commit them regularly.
3. Test the changes before merging.
4. Merge completed work into the integration branch.
5. Keep main in a stable, presentable state.

For a small solo project, using main plus feature branches is sufficient; do not create unnecessary branches.

4. Code and Notebook Guidelines

- Use clear, descriptive names for files, functions, variables, and notebooks.
- Prefer small functions and modular, reusable code.
- Add comments where the reasoning or implementation is not obvious.
- Keep notebooks organised into logical sections with Markdown headings.
- Include a short explanation of the objective, approach, results, and conclusions in each notebook.
- Set random seeds where appropriate so experiments can be reproduced.
- Avoid committing notebook outputs or generated files that are unnecessarily large.
- Keep dependencies documented, for example in requirements.txt, when applicable.
- Never hard-code secrets or machine-specific absolute file paths.

5. Data and File Handling

- Keep data loading and preprocessing steps reproducible.
- Document each dataset's source, purpose, and any licence or usage restrictions.
- Do not commit confidential, personal, or restricted data.
- If a dataset is too large for GitHub or the project rules prohibit uploading it, document how authorised users can obtain it instead.
- Separate raw data from processed data when both are used.

6. Suggested Repository Structure

introduction-to-dl-genai-project/
├── README.md
├── .gitignore
├── requirements.txt
├── scripts/
│   └── .gitkeep
├── notebooks/
│   └── .gitkeep
├── data/
│   └── .gitkeep
├── models/
│   └── .gitkeep
├── reports/
│   └── .gitkeep
└── docs/
    └── .gitkeep

Folder descriptions

- scripts/ — reusable Python scripts and utilities.
- notebooks/ — Jupyter notebooks for exploration, training, evaluation, and experiments.
- data/ — datasets or instructions for obtaining them, subject to course rules.
- models/ — model artefacts, if permitted and reasonably sized.
- reports/ — results, plots, and project reports.
- docs/ — additional documentation and project notes.
- requirements.txt — Python dependencies, when applicable.
- .gitignore — files and folders that Git should not track.

Git does not track empty folders. The .gitkeep files above are placeholders and can be removed when real files are added.

7. Best Practices

- Make changes in small, understandable steps.
- Run relevant checks or experiments before committing.
- Keep the repository structure consistent throughout the project.
- Update this README when the project scope, setup, or workflow changes.
- Document important design decisions and experiment results.
- Review the repository before submission to ensure that required files are present and secrets or restricted data are absent.

8. Commit Message Guidelines

Write commit messages that describe the change clearly and concisely.

Good examples

docs: add initial project README
feat: add data preprocessing script
feat: add baseline model notebook
fix: handle missing feature values
test: add preprocessing checks
refactor: simplify evaluation function

Use the prefixes consistently where practical:

- feat: — new functionality or experiment.
- fix: — bug fix.
- docs: — documentation changes.
- test: — tests or validation.
- refactor: — code restructuring without changing intended behaviour.
- chore: — maintenance and configuration.

Avoid vague messages such as update, changes, or final.

9. Recommended Workflow

1. Set up: create the private repository, README, and folder structure.
2. Plan: record the project objective, scope, and tasks.
3. Prepare data: document data sources and implement preprocessing.
4. Experiment: build and compare suitable baseline approaches.
5. Develop: implement the selected deep learning or GenAI approach.
6. Evaluate: record metrics, observations, limitations, and relevant comparisons.
7. Document: update notebooks and the README with reproducible instructions.
8. Review and submit: verify that all required deliverables are present and the instructor has access.

10. Evaluation Readiness Checklist

Before submission, check the requirements specified by the instructor and course portal. The following is a general readiness checklist, not a substitute for the official grading rubric.

- [ ] Repository is private and instructor access is configured.
- [ ] README explains the project and how to navigate the repository.
- [ ] Code and notebooks are organised and understandable.
- [ ] Data sources and preprocessing steps are documented.
- [ ] Experiments can be reproduced as far as practical.
- [ ] Results and evaluation methods are explained.
- [ ] Limitations and conclusions are documented.
- [ ] No secrets, credentials, or prohibited data are committed.
- [ ] Required deliverables and submission instructions have been checked.

11. Final Note

This repository currently contains the initial project structure. Project-specific code, notebooks, datasets, experiments, and results will be added as the work progresses.

# Dl-gen-ai-project# Dl-gen-ai-project
