# tmp

cd /tmp
  886  mkdir base
  887  cd base
  888  git clone https://github.com/pavmash97/tmp.git .
  889  git status
  890  git add --all
  891  git status
  892  git commit -m "git init"
  893  git config user.email "pavmash97@gmail.com"
  894  git config user.name "pavmash97"
  895  git commit -m "git init"
  896  git push origin master
  897  git add --all
  898  git status
  899  git commit -m "session 2"
  900  git push origin master
  901  cd /tmp/base/
  902  git add --all
  903  git status
  904  git commit -m "session 3"
  905  git push origin master
  906  git add --all
  907  git status
  908  git log
  909  git commit --amend -m "session 3"
  910  git push -f origin master
  911  history > /tmp/xxx.txt
