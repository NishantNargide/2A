git config --global user.name "Nishant Nargide"
git config --global user.email "nargidenishant@gmail.com"
mkdir exam
git init
ls -a
git status
git add file1.md
git commit -m "initial commit"
git log
git add file2.md
git commit -m "2nd commit"
git log
// repository commands //
git branch dev
git branch
git checkout dev
git checkout -b merge/multiply
git add file3.md
git commit -m "3rd commit"
git checkout dev
git merge merge/multiply
git log
git merge dev