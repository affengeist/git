# Standard reminders for a git commit

Put this file in your home directory, delete the Markdown extension .md and make it a dotfile (.gitmessage).

## Title

Summary, imperative, start upper case, don't end with a period
No more than 50 chars.

## Blank line

 Remember blank line between title and body.
#

## Body

Explain *what* and *why* (not *how*). Include task ID (Jira issue).
Wrap at 72 chars. 

At the end: Include Co-authored-by for all contributors. 
Include at least one empty line before it. Format: 
Co-authored-by: name <user@user.foo.bar.com>

##  How to Write a Git Commit Message:

See this [Link](https://chris.beams.io/posts/git-commit/)

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

Example:
    
    Feat: Add garbage collector 
    Fix: Removed brain from user (Fixes #22) 

(Fixes #22) will link GitLab issues automatically and will close the issue


## Available Gitlab Issue keywords
 
- Close, Closes, Closed, Closing, close, closes, closed, closing
- Fix, Fixes, Fixed, Fixing, fix, fixes, fixed, fixing
- Resolve, Resolves, Resolved, Resolving, resolve, resolves, resolved, resolving
- Implement, Implements, Implemented, Implementing, implement, implements, implemented, implementing 

See [documentation](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)

## Git commit types:

- Feat: a new feature is introduced with the changes
- Fix: a bug fix has occurred
- Chore: changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
- Refactor: refactored code that neither fixes a bug nor adds a feature
- Docs: updates to documentation such as a the README or other markdown files
- Style: changes that do not affect the meaning of the code, likely related to code formatting
- Test: including new or correcting previous tests
- Perf: performance improvements
- Ci: continuous integration related
- Build:  changes that affect the build system or external dependencies
- Revert: reverts a previous commit 
