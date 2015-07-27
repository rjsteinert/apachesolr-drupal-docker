ApacheSolr Docker for Drupal
==============

Docker image for ApacheSolr for Drupal search.


To use:
```sh
git clone git@github.com:rjsteinert/pantheon-solr-drupal-docker.git
cd apachesolr-drupal-docker

docker build -t pantheon-solr-drupal-docker .
docker run -it -p 8983:8983 -t pantheon-solr-drupal-docker
```
