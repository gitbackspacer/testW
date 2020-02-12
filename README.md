Shortcuts
----------

 


git clone https://jitendergithub@bitbucket.org/jitendergithub/ren-seq-t.git

## make sure you have the folders in PWD

git ls-files -co --exclude-standard | grep '\.py$' | xargs git add

git status

git commit -m "added files from SANU2 RENSeq_T and KMER dirs"

##  will ask for password 
git push -u origin master
