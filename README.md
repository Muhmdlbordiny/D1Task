A Git repository is a version control system that helps developers track changes in their code over time. It is especially useful for front-end developers working on projects with HTML, CSS, and JavaScript. Here's how it helps:
🔍 Purpose of a Git Repository
Version Control
Git keeps a history of all changes made to a project. You can:
Revert to previous versions.
Compare changes over time.
Identify when and why changes were made.
Explain the difference between tracked and untracked files in Git, and why might untracked files cause issues in a front-end project?
🔍 Tracked vs. Untracked Files
Tracked Files
These are files that Git is actively monitoring.

They have been added to the repository using git add.

Tracked files fall into one of three states:

Unmodified (no changes since last commit)

Modified (changes made but not yet committed)

Staged (ready to be committed)

🛠 Example:
If you run git add index.html, Git begins tracking index.html.

❌ Untracked Files
Files that exist in your project directory but have never been added to Git.

Git completely ignores them until you explicitly add them.

They show up when you run git status.

🛠 Example:
You create a new file dark-mode.js
🔍 Benefits of Viewing Project History
1. 🔁 Track and Revert Changes
See exactly what changed, when, and who made the change.

Useful for reverting specific changes if:

A new layout breaks the design.

A JS update causes unexpected bugs.

Example: You notice the navbar broke after a recent commit — Git lets you roll back to the version where it worked.
Helps new team members or your future self understand:
Why a feature or style was added or removed.
The reasoning behind code structure or naming.
- What is the role of GitHub in relation to a local Git repository
- , and how does hosting a project on GitHub Pages add value for a front-end developer?
- ✅ Local Git Repository
Lives on your machine.

Lets you:

Track changes (git commit)

Create branches

Revert or compare changes

It’s private by default and not shared unless you push it elsewhere.

🌐 GitHub
A cloud-based hosting platform for Git repositories.

Allows you to:

Push local code online with git push

Collaborate with others via pull requests

Track issues, discussions, and project boards

Use CI/CD tools and automation

