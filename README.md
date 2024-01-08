command lines for updating folder:

go to local copy of this repository, if not get it with "git clone".
get token on github (only valid for certain amount of time)

cd "local-copy"
git remote set-url aldhr https://aldhr:TOKEN@github.com/aldhr/aldhr.github.io.git
git fetch aldhr
git add . 
git commit -m "upload all files for webpage"
git push aldhr



