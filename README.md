# Villa des Luquettes

Villa familiale avec piscine dans la belle campagne provençale de la Cadière-d'Azur idéale pour 2 familles (220m2, 7 chambres, 14 couchages) - 1542F Chemin des Luquettes, La Cadière-d'Azur


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


