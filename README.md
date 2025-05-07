1.Linking to Github repository with merged branches : https://github.com/sudheshna-30/ass-3-git
2.After creating the feature/update-styling branch 
![Screenshot (7)](https://github.com/user-attachments/assets/65a963cc-e139-4648-846e-6342bdbf0389)
3.Created another feature/add-content branch 
![Screenshot (8)](https://github.com/user-attachments/assets/591e9939-b9f0-4eae-811c-6448149acc0f)
4.conflict arises after making changes in both branches 
![Screenshot (9)](https://github.com/user-attachments/assets/3a1fc3f2-ac06-4fea-805c-8b8b88a650c8)
5.Resolved the conflicts. ![Screenshot (10)](https://github.com/user-attachments/assets/01ee1d0d-de44-494b-a840-c16007f167ec)
6.We can see after solving the conflicts in github theere will be no conflicts.![Screenshot (11)](https://github.com/user-attachments/assets/a1534387-73eb-409f-8cc1-bd1ef81a66db)
7.Merging and taking the pull request after solving the conflict.
![Screenshot (13)](https://github.com/user-attachments/assets/2788e0d1-c696-40a0-ba87-3c1e3c1a7dc0)

Assignment - 4
Husky is a tool that let you easily manage git hooks in the project.Git hooks are scripts that run automatically on certain git events such as commit,push, or merge.
With husky we can automatically run linters and fromatters before commits.
enforce commit message rules using tools commitlint prevent bad code or fomatting from being committed to the repository.
Husky improves code quality and consistency by ensuring that important checks run before code is pushed or merged.
Example Git hooks with husky:
pre-commit:run linters/formatters on staged files.
commit-msg:validate commit message format.
pre-push:Run tests before pushing code.

ESLint : Eslint is a popular open-source javascript linter that analyzes your code to find and fix problems according to defined rules.It helps enforce consistent code style and catch bugs or bad practices before runtime.
key features:
1.Detects syntax errors,unused variables,and code smells.
2.supports custom rules and plugin integration.
3.works with most editors via extensions.
4.can automatically fix common issues with the fix flag.
Es Lint is commonly run before commits(husky+lint-staged) or CI workflows to ensure code quality.
Prettier Config: Prettier is an opinionated code formatter that automatically formats your code to ensure a consistent style across the project,regradless of who writes it. 1.consistent formatting across the team
2.easy integration with vscode,git hooks(husky),and ci tools.
3.reduces formatting-related code review comments.
