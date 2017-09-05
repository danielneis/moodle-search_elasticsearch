Elasticsearch Search Engine for Moodle
---------------------------------------

This plugin was iscontinued. 
--------------------
There is more a complete plugin at https://moodle.org/plugins/search_elastic
-------------------

A plugin to use ElasticSearch as Moodle Global Search engine.
It should be compatible with version 2.3.3 of ElasticSearch.

Install
-------

* You will need Moodle 3.1 or later
* Put these files at moodle/search/engine/elasticsearch/
 * You can git clone
 * or download the latest version from https://github.com/danielneis/moodle-search_elasticsearch/archive/master.zip
* Log in your Moodle as Admin and go to "Notifications" page
* Follow the instructions to install the plugin

Usage
-----

You must go to the Administration block > Site administration > Advanced features and enable global search.
Then Administration block > Site administration > Plugins > Search > Manage global search and change the engine to elasticsearch.
If you elasticsearch is running on localhost:9200 you are all set, if not, go to Administration block > Site administration > Plugins > Search > Elasticsearch and set the hostname accordingly.

Now you can add the "Global Search" block and start using it after the first index scheduled taks is executed.

Dev Info
--------

Please, report issues at: https://github.com/danielneis/moodle-search_elasticsearch/issues

Feel free to send pull requests at: https://github.com/danielneis/moodle-search_elasticsearch/pulls

[![Build Status](https://travis-ci.org/danielneis/moodle-search_elasticsearch.svg)](https://travis-ci.org/danielneis/moodle-search_elasticsearch)
