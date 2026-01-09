git diff is used to comapre the same file with two version

--- : means your previous commit id code
+++ : means your current staged code

1: git add 'file name'
2: git diff --staged

<!-- ******* stash ********** -->
git stash : current work goes into a seprate area(like locked room)
git stash pop : take from separate area to put into working  directory


if you have multiple stashed file then use:
git stash apply "stash@{0}" : give the id of stshed file

<!-- ******************* -->
