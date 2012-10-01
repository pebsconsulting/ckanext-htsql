# ckanext-htsql

An extension that enables HTSQL queries for the new datastore in CKAN. This extension adds an API endpoint `datastore_search_htsql` that allows HSQML queries on the datastore. Because of restrictions with the sql endpoint, not all HTSQL queries are possible.

[Documentation for the datastore](http://docs.ckan.org/en/latest/datastore.html)

# installation

You need CKAN and the new datastore enabled for this plugin to work. To install this extension, follow the instructions in the [CKAN documentation on extensions](http://docs.ckan.org/en/latest/extensions.html). 

The basic steps are:

* Install the plugin by running `pip install ckanext-htsql`
* Enable the plugin in CKAN by adding `ckan.plugins = htsql` to your `.ini` file