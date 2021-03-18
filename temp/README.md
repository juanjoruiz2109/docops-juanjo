# docops-juanjo

## Create static site
1. Change directory to the tw-mkdocs folder

2. Execute the following command
```
docker run --rm --volume="$PWD:/app" -it tw-mkdocs-img:latest mkdocs build && ( cd .. && cp -r docops-juanjo/site docs )
```
