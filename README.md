 # linux
#how to pull file(s) from github.com
git pull origin master
#how to upload files to github.com
#1, add (mark) files you wish to upload,
git add file.txt #use wildcard for all files
#2, commit changes
git commit -m "any messages here"
#3 set remote url, run once
git remote add origin https://github.com/renyiwu/anyrepository.git
#4, push (upload) files
git push -u origin master
