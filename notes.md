 499  cd Git-harjoitukset/
  500  ls
  501  ls -l
  502  ls -la
  503  git init
  504  ls -la
  505  ls -la .git
  506  ls -la .git/
  507  git status
  508  touch mallitiedosto
  509  git status
  510  git add mallitiedosto
  511  git status
  512  git status
  513  .
  514  git add .
  515  git status
  516  git commit -m "Initial commit, add mallitiedosto"
  517  git log
  518  git staus
  519  git status
  520  git diff
  521  git reset --hard
  522  git reflog
  523  gitk
  524  status
  525  git status
  526  git branch -M main
  527  git remote add origin https://github.com/jasmiinv/git-tests.git
  528  git remote -v
  529  git push origin main
  530  git push -u origin main
  531  git branch dev
  532  git branch
  533  git checkout dev
  534  git status
  535  touch toinen-tiedosto
  536  git status
  537  git add .
  538  git commit -m "fix mallitiedosto, add toinen-tiedosto"
  539  git status
  540  git checkout main
  541  git merge dev
  542  git diff dev
  543  git checkout -b dev-ville
  544  git status
  545  git add .
  546  git commit -m "rm mallitiedosto, update toinen-tiedosto"
  547  git status
  548  git checkout main
  549  git status
  550  git add .
  551  git commit -m "update mallitiedosto"
  552  git status
  553  git add .
  554  git commit -m "update toinen-tiedosto"
  555  git merge dev-ville
  556  git status
  557  cat
  558  cat toinen-tiedosto
  559  git status
  560  git add toinen-tiedosto
  561  git status
  562  git add mallitiedosto
  563  git status
  564  git commit -m "merged dev-ville to main"
  565  git history
  566  git log
  567  git push origin dev
  568  git push origin -all
  569  git push origin --all
  570  git checkout dev
  571  git pull origin dev
  572  git loggit log
  573  git log | clip
  574  git checkout main
  575  git log | clip
  576  git log
  577  git history
  578  git reflog
  579  history
  580  git add .
  581  git init
  582  git add .
  583  git commit -m "Some exercises with teacher"
  584  git push
  585  touch notes.md
