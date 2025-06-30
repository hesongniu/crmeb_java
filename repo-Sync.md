git remote add upstream git@github.com:crmeb/crmeb_java.git

git fetch upstream

git checkout master

git merge upstream/master

git add .

git commit -m "remark"

git push origin master