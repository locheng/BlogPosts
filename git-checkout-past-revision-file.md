Title: Git: Checkout revisions past
Tags: git|git-checkout
Date: 2012-12-22 21:41:34 -0500 
Author: Denevell

If you want to checkout a file as it was one revision ago on the master branch:

     git checkout master~1 thedir/thefile.txt

I used this to remove an update to a file when amending a commit.

(I hadn't pushed to master, hence the ability to amend without screwing things up.)
