# 2048-EKS-CICD


## Create docker image

```bash
# This cli is to create a docker image if you have a dockerhub account
docker build -t "<dockerhub username>/<image_name>:<version>" .

# This cli is to create a docker omage and keep it locally
docker build -t "<image_name>:<version>" .

```


## Utilize built image to create a container

```bash
docker run -itd --name <name_of_container> -p <port_open_on_OS>:<port_open_on_container> <image_name>
```


## Open browser and type in "localhost:<port_open_on_OS>"
