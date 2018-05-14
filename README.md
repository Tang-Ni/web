# web
$ ssh-keygen -t rsa -C "youremail@example.com"

$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com 

echo "# web2" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:OMGOR/web2.git
git push -u origin master
