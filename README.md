# 📌 ISSUES Templates

| Template | Purpose |
|----------|---------|
| 🐛 **Bug Report** (`01-bug.yml`)             | Report reproducible bugs with environment, steps to reproduce, expected vs actual behavior, and optional screenshots/logs. |
| 🚀 **Feature Request** (`02-feature.yml`)    | Suggest new features or improvements, including problem statement, proposed solution, impact, and estimated size. |
| 📋 **Task / Story** (`03-task.yml`)          | Track development or maintenance work with description, acceptance criteria, and affected area/component. |
| 📄 **Documentation Issue** (`04-docs.yml`)    | Report missing, unclear, or incorrect documentation, including page/file location. |
| 💬 **Ask a Question** (`contact_links:`)       | Using the Discussions for questions |


---

### 🖼️ Screenshot

#### Main Option
<img width="848" height="383" alt="image" src="https://github.com/user-attachments/assets/e5ae6750-02c2-43cd-ad4b-b5de503d0cee" />


#### [1] 🐛 Bug Report
<img width="1226" height="717" alt="image" src="https://github.com/user-attachments/assets/0c254523-9f5f-457e-a8b0-5c65eaca0835" />
<img width="978" height="830" alt="image" src="https://github.com/user-attachments/assets/eb976192-9e92-470d-9694-2e6fe4c9ce0e" />
<img width="930" height="465" alt="image" src="https://github.com/user-attachments/assets/efe7c89c-9693-43ec-a48b-cd4ea234a85a" />




### [2] 🚀 Feature Request
<img width="1375" height="1151" alt="image" src="https://github.com/user-attachments/assets/1c6af060-f145-488d-816f-d806d324f89b" />

### [3] 📋 Task / Story
<img width="1396" height="880" alt="image" src="https://github.com/user-attachments/assets/7b1a4597-e196-4884-8d19-9ca06ea9b02b" />

### [4] 📄 Documentation
<img width="1382" height="585" alt="image" src="https://github.com/user-attachments/assets/e49ee429-baa3-415f-aecc-bd938bab6a01" />

### Aska Question / Dicussions
<img width="1306" height="928" alt="image" src="https://github.com/user-attachments/assets/02e1bac1-8eed-4f00-bc93-973228018811" />

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

### 1. Dowload () Copy the entire folder:
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
| `frontend & backend` | Affects both frontend/UI and Affects the backend/server-side.     |
| `API`                | Relates to API endpoints or API work.                             |
| `infra`              | Relates to infrastructure, DevOps, or deployment.                 |

### 3. Activate the Discussions
In you repo -> Settings > Features > Discussions (check)

### 4. Commit and push to your repository:

```bash
git add .github/ISSUE_TEMPLATE
git commit -m "Add issue templates"
git push origin main

