Update from Remote Master Branch:

```
git fetch upstream
git merge upstream/master
git push
git checkout cilium-ubuntu-20-04
git merge master
```
check changes
```
git push
```


Create Docker Image and push:
```
make docker-image
docker login
make docker-image-publish
```