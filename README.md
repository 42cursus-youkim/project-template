# project-template

generic team project template so i don't have to copy-paste everything again

korean versions have `ko-` prefix, remove them or others before using

## Features

- [Clang-Format](https://clang.llvm.org/docs/ClangFormatStyleOptions.html)

- [Issue Forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms)

- [Codeowners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

- [Project Board Automation](https://github.com/marketplace/actions/project-beta-automations)

## How to use

### Labels

1. [export labels](https://gist.github.com/MoOx/93c2853fee760f42d97f)
2. [import labels](https://gist.github.com/Isaddo/7efebcb673a0957b9c6f07cd14826ea4)

### set up CODEOWNERS

Add members to [CODEOWNERS](.github/CODEOWNERS)

### set up project board automation

1. create repository secret named `PERSONAL_ACCESS_TOKEN`, with [org:write permission](https://github.com/marketplace/actions/project-beta-automations#gh-app-auth)
2. create following kanban board structure on project beta. (or change [script](.github/workflows/project_board.yml))

```
🗃️ Triage
💡 Todo
🚧 In Progress
✅ Done
```

1. change `project_id` on `env` section to that of `<project_id>` of project board.
