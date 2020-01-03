# GitLab
This repo is created for studying git. Anyone can do anything to it.
## 2019-12-31
I use sourcetree to initialize it with command "git flow", but I don't know what happened.  
Now I create a branch called "feature/Feature0". It acts like a normal branch with a tag or something, which makes me confused.  
Now I add some special rules in .gitignore. The files in my local disks are:*Test/File0.txt, Test/File1.txt* But only *Test/File1.txt* is tracked. That means the order of the ignore rules matters. For more details, see [.gitignore](.gitignore)
## 2020-01-03
Add a file in Test/ChildFolder, with a file named "A.txt".  
.gitginore also changed. It shows that "!Test/*.txt" only matches the txt files in "Test/", instead of all txt files both in "Test/" and in "Test/ChildFolder".  
Now I add a new line directly on github through website. Will the Pull.bat run correctly?
