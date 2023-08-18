# VDL WebSite for S3

we use : https://hub.docker.com/r/klakegg/hugo


# creation site

```
docker run --rm -it   -v .:/src   klakegg/hugo:0.101.0-alpine  shell  
hugo:/src$ hugo new site vdl


cp -r ./vdl/ .

docker run --rm -it   -v .:/src   klakegg/hugo:0.101.0-alpine server


git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo new posts/my-first-post.md
```


