# CopyCat
Steps To Git--
1.Always pull before anything make sure you are in the master branch
to get to master branch type git checkout master once you are in master
pull from master repo git pull
2.When you are up to date with master you can now make changes make sure
you are making changes while in your branch(git checkout "your branch name")
3.After you make changes the sequence of commands are git add .
git commit -m "message explainging the changes you have made in that push"
if it is the first time you are pushing with that branch you have to set it up
as an upstream to do so type git push -u origin "branch name" if the branch
has already been set up as an upstream you can simply type git push

Congrats you pushed to your branch

Once youve pushed to your branch and you want to merge them with the master brach
you have to send a pull request through the website from there the owner of the
repo will accept or decline the pull request