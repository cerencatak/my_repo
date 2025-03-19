📌 GMT211 - Git/GitHub Tutorial
This project demonstrates the usage of Git and GitHub, including essential Git commands, local vs. GitHub workflows, encountered challenges.

🛠 Git Commands Used
bash
Kopyala
Düzenle
git init             # Initialize a new repository  
git clone <repo>     # Clone an existing repository  
git add .            # Stage all changes  
git commit -m "msg"  # Commit changes with a message  
git push origin master # Push commits to GitHub  
git pull origin master # Fetch the latest updates  
git branch <name>    # Create a new branch  
git checkout <name>  # Switch to a branch  
git merge <name>     # Merge branches  
🔄 Local vs. GitHub Workflow
\begin{table}[]
\begin{tabular}{lllll}
local Workflow                    & GitHub Workflow                     &  &  &  \\
Changes are made locally.         & Changes are pushed online.          &  &  &  \\
Commits are stored on the device. & Commits are backed up remotely.     &  &  &  \\
No collaboration unless pushed.   & Enables teamwork via pull requests. &  &  & 
\end{tabular}
\end{table}
⚠️ Challenges & Solutions
Authentication errors → Fixed by configuring SSH keys.
Merge conflicts → Resolved using git merge and manual edits.
Forgotten commits → Improved commit strategy with git log.
✅ Commit Strategy
After implementing key features.
Before pulling updates to prevent conflicts.
After fixing issues for version control.
🤖 AI Assistance
Used ChatGPT for troubleshooting errors.
Learned best Git practices and conflict resolution.
📖 Resources
Git Documentation
GitHub Guides

