# Welcome to search-companion

search-companion.org is working on open source tools to help technical people to interact with the open source search engine Solr (<a href="https://solr.apache.org" target="_blank">https://solr.apache.org</a>).
The functionality is based on apache camel (<a href="https://camel.apache.org" target="_blank">https://camel.apache.org</a>) application.
The search-companion components are deployed in an apache karaf container (<a href="https://karaf.apache.org" target="_blank">https://karaf.apache.org</a>) via "search-companion" karaf features.

- The docker image of the karaf container is available on <a href="https://hub.docker.com/repository/docker/searchcompanion/karaf" target="_blank">docker hub</a>
- The karaf features xml can be found <a href="https://mvn.search-companion.org/mvnrepo/companion/org/search-companion/companion-karaf-features/0.8.0/companion-karaf-features-0.8.0-features.xml/" target="_blank">here</a>
- The karaf distro can be found  <a href="https://mvn.search-companion.org/mvnrepo/companion/org/search-companion/companion-karaf/0.8.0/companion-karaf-0.8.0.tar.gz" target="_blank">here</a>

### Quick start demo
The easiest way to see the search-companion functionality in action, is to run the searchcompanion/karaf docker container in an example "docker compose" network with a zoo/solr ensemble and an example db.
See the companion-demo README page (<a href="https://github.com/search-companion/companion-demo" target="_blank">https://github.com/search-companion/companion-demo</a>)

### search-companion features

- data-import: alternative and robust solution to replace the deprecated solr dataimporthandler that imports data from a datasource into solr
- config-upload: a solution to enable non IT people to load solr config files into zookeeper via a folder watcher (with optional post-processing tasks e.g. spellcheck build)
- querqy-upload: a querqy rules upload routine based on a folder watcher that generates rules for a querqy rewriter from csv files

### search-companion source code on GitHub

<a href="https://github.com/search-companion/companion" target="_blank">https://github.com/search-companion/companion</a>

### Contact

Please contact us via [email](mailto:info@search-companion.org).
We're open to suggestions, enhancements and feedback and welcome all possible participations on this project.
