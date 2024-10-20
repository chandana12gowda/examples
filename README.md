 Git Assignment - New Feature Implementation

Overview :
This project demonstrates how to manage changes using Git for a new feature development. 
The following steps were taken to complete the assignment:

1. Configured Git with my name and email.
2. Cloned the project repository from GitHub.
3. Created a new feature branch called `Feature`.
4. Added a new file called `feature_my.txt` to the feature branch.
5. Staged and committed the changes with a relevant commit message.
6. Pushed the new feature branch to the remote repository.
7. Pulled the latest changes from the `main` branch and handled file removals.

Git Commands Used

 1. Configure Git with Name and Email

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git clone https://github.com/chandana12gowda/examples.git
git checkout -b Feature
touch feature_my.txt
git add feature_my.txt
git commit -m "Add new feature implementation"
git push origin Feature
git pull origin main
git rm feature.py
git commit -m "Remove feature.py file"
git push origin Feature
