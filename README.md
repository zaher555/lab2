- Tell me how to remove them locally and remotely
locally->  git branch -d dev
remote->  git push origin :dev
- Tell me how to checkout another branch without commit changes->
git checkout dev
- Create an annotated tag with tagname (v1.7)->
git tag -a v1.7 -m "Tagging version 1.7"
- Push it to the remote repository->
git push origin v1.7 
- Tell me how to list tags. -> git tag
-Tell me how to delete tag locally and remotely ->  
git push origin --delete v1.7 (remote)
git tag -d v1.7 (locally)
![IMAGE!](https://unsplash.com/photos/a-person-sitting-at-a-table-with-a-laptop-NTisn7FckN4)

