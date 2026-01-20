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
<img width="1223" height="697" alt="image" src="https://github.com/user-attachments/assets/cdeea908-8913-4179-b9c5-14124e284c4d" />
<img width="989" height="484" alt="image" src="https://github.com/user-attachments/assets/7d50d7b0-eeec-4ff5-b05a-40159de19f3f" />
<img width="777" height="332" alt="image" src="https://github.com/user-attachments/assets/1ac1be12-248b-4e80-9d8c-f8ef117ee9fb" />


### [3] 📋 Task / Story
<img width="1212" height="767" alt="image" src="https://github.com/user-attachments/assets/d2606057-a6af-4ffe-ab12-f665e4c05ae8" />


### [4] 📄 Documentation
<img width="762" height="576" alt="image" src="https://github.com/user-attachments/assets/0d7dffd6-19f0-4d1f-b580-62fea91de4eb" />


### Ask a Question / Dicussions
<img width="1188" height="922" alt="image" src="https://github.com/user-attachments/assets/c99f65ed-df59-4d41-b49c-65a9a41861ae" />


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

### 1. Dowload file (**<> Code -> dowload ZIP**) and copy the entire folder to your repo:
<img width="424" height="377" alt="image" src="https://github.com/user-attachments/assets/a3fef3f0-7fb8-4954-979a-4b3a41337797" />

to the **root of your repository**. Make sure the folder structure remains **exactly the same**.

- your-repo-root-folder
    - .github
        - ISSUE_TEMPLATE
            - 01-bug.yml
            - 02-feature.yml
            - 03-task.yml
            - 04-doc.yml
            - config.yml

### 2. Commit and push to your repository:

```bash
git add .github/ISSUE_TEMPLATE
git commit -m "Add issue templates"
git push origin main
```

## Additional Settings

###  Create custom label
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

### Activate the Discussions
In you repo -> Settings > Features > Discussions (check)

### nodify the config.yml for you discussions repo link
Open **config.yml**
modify the url 

blank_issues_enabled: false
contact_links:
- name: 💬 Ask a Question
- **url:  https://github.com/mis-bghmc/your-repo/discussions**
- about: Please use Discussions for questions

