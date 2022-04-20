# Welcome to search-companion

search-companion.org is working on open source tools to help technical people to interact with the open source search engine Solr ([https://solr.apache.org/](https://solr.apache.org/)).
The functionality is based on apache camel ([https://camel.apache.org/](https://camel.apache.org/)) application. 
The search-companion components are deployed in an apache karaf container ([https://karaf.apache.org/](https://karaf.apache.org/)) via "search-companion" karaf features.

- The docker image of the karaf container is available on [https://hub.docker.com/repository/docker/searchcompanion/karaf](https://hub.docker.com/repository/docker/searchcompanion/karaf).
- The karaf features xml is available on [https://mvn.search-companion.org/mvnrepo/companion/org/search-companion/companion-karaf-features/0.8.0/companion-karaf-features-0.8.0-features.xml/](https://mvn.search-companion.org/mvnrepo/companion/org/search-companion/companion-karaf-features/0.8.0/companion-karaf-features-0.8.0-features.xml/)
- The karaf distro is available on [https://mvn.search-companion.org/mvnrepo/companion/org/search-companion/companion-karaf/0.8.0/companion-karaf-0.8.0.tar.gz/](https://mvn.search-companion.org/mvnrepo/companion/org/search-companion/companion-karaf/0.8.0/companion-karaf-0.8.0.tar.gz/)

### Quick start demo
The easiest way to see the search-companion functionality in action, is to run the searchcompanion/karaf docker container in an example "docker compose" network with a zoo/solr ensemble and an example db.
See the companion-demo README page ([https://github.com/search-companion/companion/tree/main/companion-demo](https://github.com/search-companion/companion/tree/main/companion-demo))

### search-companion features

- data-import: alternative and robust solution to replace the deprecated solr dataimporthandler that imports data from a datasource into solr

### search-companion source code on GitHub

[https://github.com/search-companion/companion](https://github.com/search-companion/companion)

### Contact

This page is under constructions.
Please contact us via [email](mailto:info@search-companion.org) to get answers to your enquiries.
