# 📌 ISSUES Templates

| Template | Purpose |
|----------|---------|
| 🐛 **Bug Report** (`01-bug.yml`)             | Report reproducible bugs with environment, steps to reproduce, expected vs actual behavior, and optional screenshots/logs. |
| 🚀 **Feature Request** (`02-feature.yml`)    | Suggest new features or improvements, including problem statement, proposed solution, impact, and estimated size. |
| 📋 **Task / Story** (`03-task.yml`)          | Track development or maintenance work with description, acceptance criteria, and affected area/component. |
| 📄 **Documentation Issue** (`04-docs.yml`)    | Report missing, unclear, or incorrect documentation, including page/file location. |
| 💬 **Ask a Question** (`contact_links:`)       | Using the Discussions for questions |

---

### How to activate the Discussions
In you repo -> Settings > Features > Discussions (check)

--- 

## 💡 Best Practices

- Check existing issues before submitting a new one.
- Be **clear and concise**.
- Include **steps to reproduce** for bugs.
- Add **links, screenshots, or references** where relevant.
- For tasks, clearly define **acceptance criteria**.
- Use the **correct template** to help maintainers triage issues quickly.

---

## ⚡ How to Use
If you want to **reuse these templates in your own repository**, follow these steps:

### 1. Copy the entire folder:
to the **root of your repository**. Make sure the folder structure remains **exactly the same**.
- your-repo-root-folder
    - .github
        - ISSUE_TEMPLATE
            - 01-bug.yml
            - 02-feature.yml
            - 03-task.yml
            - 04-doc.yml
            - config.yml

### 2. Create custom label
| Label                | Meaning / Purpose                                                 |
| -------------------- | ----------------------------------------------------------------- |
| `needs-triage`       | Newly submitted issue that hasn’t been reviewed yet.              |
| `good first issue`   | Tasks suitable for new contributors or beginners.                 |
| `blocked`            | Issue cannot proceed until a dependency is resolved.              |
| `help wanted`        | Maintainers want community assistance.                            |
| `bug`                | Confirms the issue is a bug.                                      |
| `critical`           | Bug that breaks core functionality and needs immediate attention. |
| `high`               | High-severity issue affecting key features.                       |
| `medium`             | Medium-severity or medium-complexity issue.                       |
| `low`                | Low-severity issue or minor/cosmetic problem.                     |
| `enhancement`        | Proposed feature or improvement.                                  |
| `small`              | Small or low-effort task or feature.                              |
| `large`              | Large or complex task, feature, or epic.                          |
| `task`               | General task or user story.                                       |
| `documentation`      | Issue related to documentation or docs updates.                   |
| `frontend`           | Affects the frontend/UI.                                          |
| `backend`            | Affects the backend/server-side.                                  |
| `frontend & backend` | Affects both frontend/UI and backend/server/API & Affects the backend/server-side  |
| `API`                | Relates to API endpoints or API work.                             |
| `infra`              | Relates to infrastructure, DevOps, or deployment.                 |

### 3. Activate the Discussions
In you repo -> Settings > Features > Discussions (check)


### 4. Commit and push to your repository:

```bash
git add .github/ISSUE_TEMPLATE
git commit -m "Add issue templates"
git push origin main


