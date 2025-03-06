This is a new repo called localRepo
<br>
here things reated to git commands are there to add a new repository to git <br>
cmd 1 : to come out of a current directory : cd ..<br>
cmd 2 : to create a new directory : mkdir directory-name   mkdir stands for make directory <br>
cmd 3 : to make a directory your present directory : cd directory-name <br>
the new directory you created wont be a git directory : check by : ls -a <br>
if it doesn't show a git named file than it isn't a git directory <br>
to do so write : git init <br>
to check whether a branch is a main branch or not : git branch <br>
it will most probably be your main branch if it is not then make it by using : git branch main<br>
then add it : git add repo-name / or to add all at once : git add . <br>
then commit by : git commit -m "some comment you wish to add " <br>
to check the current status of the file : git status <br>
to push it : git push origin main --> where origin is the name given to the repository and main is the branch <br>
we can also push by : git push -u origin main --> where -u means that from mow on we will always be pushin all our files in the origin files only  