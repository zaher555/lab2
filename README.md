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
![IMAGE!](https://images.unsplash.com/photo-1721804979141-fe6c884b690b?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwyNHx8fGVufDB8fHx8fA%3D%3D)

