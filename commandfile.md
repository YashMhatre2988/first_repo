git --version
git config --global user.name "yash"
git config --global user.email "yash@gmail.com"
git init
git add .
git commit -m "index.html"
git diff --cached
git restore --staged .
git restore .
git status
git log -p -2
git log --pretty=oneline
git log --grep="first commit" 

# git remote reposetry commands 
(it requires github login)
create repo 
copy path

#in VS 
git remote add origin https://github.com/YashMhatre2988/first_repo.git
git branch -M main
git push -u origin main