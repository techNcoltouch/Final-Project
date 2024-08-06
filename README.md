$ git status
On branch contributing
Untracked files:
  (use "git add <file>..." to include in what will be committed)

    contributing_and_editing_this_book/images/gitbook.png

$ git add contributing_and_editing_this_book/images/gitbook.png

$ git commit -m "Added gitbook editor screenshot"
[contributing fe36152] Added gitbook screenshot
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 contributing_and_editing_this_book/images/gitbook.png

$ git push
Counting objects: 11, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 266.37 KiB | 0 bytes/s, done.
Total 5 (delta 1), reused 0 (delta 0)
To git@github.com:miohtama/tutorial.git
   b37ca59..fe36152  contributing -> contributing
