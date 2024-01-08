command lines for updating folder:

go to local copy of this repository, if not get it with "git clone".
get token on github (only valid for certain amount of time)

1. cd "local-copy"
2. git remote set-url aldhr https://aldhr:TOKEN@github.com/aldhr/aldhr.github.io.git
3. git fetch aldhr
4. git add . 
5. git commit -m "upload all files for webpage"
6. git push aldhr



