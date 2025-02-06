//q1 
git checkout test
git rm file.txt 
git commit -m "test remove file.txt"
git push test

//q2
git stash // save changes temp
git checkout test 
git stash apply // save it if you try it and it works 
git checkout -m main //force change branch 


//q3
git tag  // list all tags
git tag -n  //list tag + commit messages
//q4
git tag -d v1  //delete local
git push --delete origin v1  // delete remotely on github web

![cat_imag_readmeLab2](https://github.com/AbdAllahSayed11/versionControlLab2/blob/test/cat.jpeg?raw=true)
