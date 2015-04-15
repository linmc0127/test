# test

# before create a new repository in github
#!/bin/sh
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/linmc0127/test.git
git push -u origin master


