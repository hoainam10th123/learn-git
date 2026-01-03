# learn-git
git config

git config --global user.name "hoainam10th"
git config --global user.email "hoainam10th@gmail.com"

git config --local user.name "hoainam10th"
git config --local user.email "hoainam10th@gmail.com"


git status
git init

open git bash: ssh-keygen -t ed25519 -C "hoainam10th@outlook.com.vn"

git clone giturl

git add filename.txt
git add .
git add src/

git commit -m "example"

git log ==> xem toan bo lich su
git log -3 => xem 3 commit gan nhat
git log --author="Aicode" ==> xem commit cua nguoi cu the
git log --oneline   => 1 commit 1 dong

sau khi sua file: 
git add .
git commit -m "thay doi comment"

git remote -v (lien ket giua repo local PC va repo remote tren github)
git remote add origin https://github.com/hoainam10th123/learn-git.git

git push  ==> dua commit tu local repo len remote repo github:
git push -u origin master ==> chi chay lan dau

git branch


Đổi master → main
git branch -m master main
git push -u origin main