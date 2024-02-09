CSCI 5828 – Spring 2024 <br>
Homework 3 <br>
Done by: Aaptha Boggaram <br>

ALL GITHUB COMMANDS USED: <br>

git init hw3-git-Aaptha-Boggaram <br>
cd hw3-git-Aaptha-Boggaram <br>
echo "CSCI 5828 – Spring 2024 <br>
Homework 3 <br>
Done by: Aaptha Boggaram <br>" > README.md <br>
git add README.md <br>
git commit -m "commit 0" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 1" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 2" <br>
git checkout (change to hash of commit 0) <br>
git branch bug-fix <br>
git checkout bug-fix <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 3" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 4" <br>
git status <br>
git fetch <br>
git merge master (CAUSES MERGE CONFLICT) <br>
git status (SHOWS CONFLICT) <br>
git add README.md <br>
git commit -m "commit 5" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 6" <br>
git checkout (change to hash of commit 4) <br>
git branch bug-fix-experimental <br>
git checkout bug-fix-experimental <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 7" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 8" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 9" <br>
git checkout master <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 10" <br>
git checkout bug-fix <br>
git status <br>
git fetch <br>
git merge bug-fix-experimental (CAUSES MERGE CONFLICT) <br>
git status (SHOWS CONFLICT) <br>
git add README.md <br>
git commit -m "commit 11" <br>
vim README.md, make changes, :w, :q! <br>
git add README.md <br>
git commit -m "commit 12" <br>
git checkout master <br>
git status <br>
git fetch <br>
git merge bug-fix (CAUSES MERGE CONFLICT) <br>
git add README.md <br>
git commit -m "commit 13" <br>
git checkout master <br>
vim README.md, make changes, :w, :q! <br>


ALL COMMIT MESSAGES USED: <br>

<<<<<<< HEAD
commit 3 -> commit 0 (bug-fix) <br>

commit 4 -> commit 3 (bug-fix) <br>

<<<<<<< HEAD
=======
commit 1 -> commit 0 (master) <br>

commit 2 -> commit 1 (master) <br>
<<<<<<< HEAD

commit 10 -> commit 2 (master) <br>
=======
>>>>>>> master

commit 6 -> merged commit 5 (bug-fix) <br>
=======
commit 7 -> commit 4 (bug-fix-experimental) <br>

commit 8 -> commit 7 (bug-fix-experimental) <br>

commit 9 -> commit 8 (bug-fix-experimental) <br>
>>>>>>> bug-fix-experimental

commit 12 -> merged commit 11 (bug-fix) <br> 
>>>>>>> bug-fix
