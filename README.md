# Super-linter-Github-Actions
Getting Started with Github Actions by creating super linter

This section follows <www.youtube.com/watch?v=mFFXuXjVgkU>

## [Github Actions](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions)

Github Actions is a CI/CD tool to automate a project's build, test and deploy pipeline.
* GitHub Actions **workflow** is triggered when an **event** occurs in your repository, such as a pull request being opened or an issue being created.
* Github Workflow contains one or more **jobs** which can run in sequential order or in parallel
* Each of these jobs is run in its own **runner** (either VM or docker container) and has one or more **steps**.
* Each **step** either runs a custom script(defined by user based on usecase) or runs an **action**
* **Action** is a reusable extension that simplifies the workflow.

## [Github Workflows](https://docs.github.com/en/actions/about-github-actions/understanding-github-actions#workflows)

* A workflow is a configurable automated process that will run one or more jobs.
* Defined by a YAML file.
* Workflows are defined in the .github/workflows directory in a repository.
* A repository can have multiple workflows, each which can perform a different set of tasks

## [Github Secrets](https://docs.github.com/en/actions/security-for-github-actions/security-guides/using-secrets-in-github-actions)

Github Secrets should host all the secret API keys or other secret variables needed for the code execution. Github Workflow needs Github secret key which is accessed in workflow .yml file.
