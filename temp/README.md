# docops-juanjo

## Create static site
Execute the following command
```
docker run --rm --volume="$PWD:/app" -it tw-mkdocs-img:latest mkdocs build && ( cd .. && cp -r docops-juanjo/site docs )
```
