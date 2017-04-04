# phase-0-gps-1
GPS 1.1


501  mkdir gps-1-1 *made gps dir*
  502  cd gps-1-1 *go to dir*
  503  git clone https://github.com/JWKyle/phase-0-gps-1.git  *cloned repo from github*
  504  ls *list dir*
  505  cd phase-0-gps-1 *enter cloned dir*
  506  touch awesome_page.md *created document locally within dir*
  507  git add awesome_page.md *staged file*
  508  git commit -m "Add file" *saves and creates a message for the file that's staged*
  509  git push origin master *Pushes data to the original Github repo*
  510  git checkout -b add-command-log *creates and moves to the new branch*
  511  subl readme.md *opens the markdown in sublime*
  512  history *shows terminal history*