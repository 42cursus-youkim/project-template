# project-template

generic team project template so i don't have to copy-paste everything again

## Features

- [Issue Forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms)

- [Codeowners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

- [Project Board Automation](https://github.com/marketplace/actions/project-beta-automations)

## How to use

### set up CODEOWNERS

Add members to [CODEOWNERS](.github/CODEOWNERS)

### set up project board automation

1. create repository secret named `PERSONAL_ACCESS_TOKEN`, with [following permissions](https://github.com/marketplace/actions/project-beta-automations#gh-app-auth)
2. create following kanban board structure on project beta. (or change [script](.github/workflows/project_board.yml))

```
🗃️ Triage
💡 Todo
🚧 In Progress
✅ Done
```

3. create repository secret named `PROJECT_ID` and value to `<project_id>` of project board.
