Exercise 1
Create a new file called something.md in versioned_dir. Add some text into this file, e.g. copy and paste in the text from this web page.

Use git status to see if Git has seen that you have added the file.

Next, use git add to add this file to Git, and use git status to check that the file is added. Finally, use git commit -a to commit your change, writing a suitable “commit message”. Once committed, use git status to check that there is nothing left to commit, and that the working directory is clean.


Exercise 2 
Edit your file called something.md. Make some changes to the text (e.g. adding some new lines, or changing some words).

Use git status. Does git know that you have changed something.md?

Use git diff. Does git correctly find all of your changes?

Use git diff README.md. Does git know that nothing has changed with README.md?

Use git checkout something.md to revert the file back to the last saved version. Has this correctly restored the old version of the file?

Make some more changes to something.md.

Use git commit -a to commit your changes, ensuring that you write a good commit message. Does git diff now give you no changes? Does git status now show that your working directory is clean?