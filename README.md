# git-and-github-setup For All laptop 
1.  Install git -->https://git-scm.com/install/windows <br>
2.  add your config into git <br>
3.  open git bash into computer <br>
4.  paste below CMD: <br>
git config --global --unset user.name <br>
git config --global --unset user.email <br>
git config --global user.name "chintan123-a" <br>
git config --global user.email "chintanbhalala13@gmail.com" <br>
5. check your git config (paste below cmd into gitbash) <br>
git config --list <br>
6.  check your  email and username in given output <br>
7.  create a project folder into computer (ex. News-Website) <br>
8.  join your folder with github <br>
9.  go to github website (login first) <br>
10. create a new repo (cheak for new btn into dashboard - green color btn) <br>
11. give a name to repo (ex. news-website) <br>
12. click botton --> create a repo (green botton) <br>
13. find the link that start with --> git remote add origin --> copy that whole line <br>
14. open your vs code --> open terminal (check the menu click the option terminal --> new terminal) --> first check last words (ex. /news- website>) <br>
15. paste the copy link(repo link) -->close the terminal <br>
16. create files, edit files, delete files into your folder <br>
17. open terminal and give below cmd one by one:
    git add . <br>
    git commit -m "give a msg" <br>
    git push origin main (main --> branch name {check your working brach first and after tha t write the branch name}) <br>
18. repeat the cycle <br>
    edit files --> git add . --> git commit -m "give a msg" --> git push origin main --> edit files <br>
    # 🛠️ Git & GitHub Setup Guide (For All Laptops)

A foolproof, step-by-step guide to installing Git, configuring your identity, and pushing your local projects to GitHub.

---

## 📌 Step 1: Initial Git Installation & Setup
*This is a one-time setup for your computer.*

1. **Download & Install Git:** Go to [git-scm.com/install/windows](https://git-scm.com/install/windows) and install the software.
2. **Open Git Bash:** Search for **Git Bash** on your computer and open it.
3. **Configure your Identity:** Clear any old configurations and set up your active GitHub username and email by running these commands line-by-line:
   ```bash
   git config --global --unset user.name
   git config --global --unset user.email
   git config --global user.name "chintan123-a"
   git config --global user.email "chintanbhalala13@gmail.com"
