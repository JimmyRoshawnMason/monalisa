# monalisa
$ docker images  > REPOSITORY  TAG  IMAGE ID CREATED SIZE > monalisa 1.0 c75bebcdd211  4 weeks ago  1.11MB  # Tag the image with OWNER/REPO/IMAGE_NAME $ docker tag c75bebcdd211 docker.HOSTNAME/octocat/octo-app/monalisa:1.0  # Push the image to {% data variables.product.prodname_registry %} $ docker push docker.HOSTNAME/octocat/octo-app/monalisa:1.0
