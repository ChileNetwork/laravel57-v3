 For Empty repository in a project
 ---------------------------------

If you already have files you can push them using the command line instructions below. 

Command line instructions
--------------------------

Git global setup
----------------

git config --global user.name "Nino77"
git config --global user.email "msotosalgado.77@gmail.com"

Create a new repository
-----------------------

git clone git@gitlab.com:chilenetwork/codigos-pruebas.git
cd codigos-pruebas
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master


Existing folder ()
---------------

cd existing_folder
git init
git remote add origin git@gitlab.com:chilenetwork/codigos-pruebas.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
-----------------------

cd existing_repo
git remote rename origin old-origin
git remote add origin git@gitlab.com:chilenetwork/codigos-pruebas.git
git push -u origin --all
git push -u origin --tags