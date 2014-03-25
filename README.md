# Enonic OSGi Bundles

This project build OSGi wrappers of some libraries we use here at Enonic. The following libraries are OSGi wrapped:

* JDom 2.x (org.jdom/jdom2)
* JHLabs Filters 2.x (com.jhlabs/filters)
* Saxon HE 9.x (net.sf.saxon/Saxon-HE)
* AttoParser 1.3 (org.attoparser/attoparser)
* Elasticsearch 1.0.1 (org.elasticsearch/elasticsearch)

## Building

To install all libraries locally (in your own local Maven repositroy):

    ./gradlew clean install

If you want to deploy all libraries in Enonic's remote repository:

    ./gradlew clean publish
