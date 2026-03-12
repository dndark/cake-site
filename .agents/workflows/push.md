---
description: Automated git add, commit, and push with concise English message.
---
# Git Push Workflow

When the user asks to "push" or runs the `/push` command, perform the following steps automatically:

1. Analyze the recent changes to determine an appropriate commit message.
2. Stage all changes in the repository.
   `git add .`
3. Commit the changes using a concise, clear **English** commit message.
   `git commit -m "<your_concise_english_message>"`
4. Push the changes to the remote repository.
   `git push`

// turbo-all
