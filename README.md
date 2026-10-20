# Want To See My ~~Lease~~ CV?

## Docker
> docker run  -dp 8080:8080 spideropl/cv

## Docker Compose
> wget https://raw.githubusercontent.com/spidero/cv/main/docker-compose.yaml;
> docker compose up -d
 
## Kubernetes 
> kubectl apply -f https://raw.githubusercontent.com/spidero/cv/main/k8s-piotr-skwarna-cv.yaml

## Azure
Live: https://azure.skwarna.eu/

Every push to `master` in [spidero/homepage](https://github.com/spidero/homepage) is deployed automatically to Azure Static Web Apps by GitHub Actions ([workflow](https://github.com/spidero/homepage/blob/master/.github/workflows/azure-static-web-apps-ashy-bay-0b0d2f003.yml)). Pull requests get their own preview environment, which is removed when the PR is closed.
