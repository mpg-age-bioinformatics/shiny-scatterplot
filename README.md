## Cellplot shiny app

This app has been developed to work inside a docker container (Dockerfile file available [here](https://github.com/mpg-age-bioinformatics/shiny)).

To use this app locally you need start the container with:
```bash
docker run --rm -p 3838:3838 --name scatterplot mpgagebioinformatics/shiny-scatterplot
```
Access the app on your browser over [http://localhost:3838/scatterplot](http://localhost:3838/scatterplot).

The container can be stopped and the container removed with:
```bash
docker stop scatterplot && docker rm scatterplot
``` 
Removing the image once you've stopped the container:
```bash
docker rmi scatterplot
```
