# Angular + Elasticsearch Example

This is an example project designed to show how you can use elasticsearch.js with angular.

## Prerequisites

In order to run this example, you will need to have the following installed
  1. [elasticsearch](http://www.elasticsearch.org/guide/en/elasticsearch/guide/current/_installing_elasticsearch.html)
  2. [node.js (with npm)](https://docs.npmjs.com/getting-started/installing-node)

You will also need to configure elasticsearch to accept requests from the browser using [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing). To enable CORS, add the following to elasticsearch's config file. Usually, this file is located near the elasticsearch executable at `config/elasticsearch.yml`.

```yml
http.cors:
  enabled: true
  allow-origin: /https?:\/\/localhost(:[0-9]+)?/
```

## To run the example:
1. Clone this repo locally (or just [download](https://github.com/spalger/elasticsearch-angular-example/archive/master.zip) and unzip it)

  ```sh
  git clone https://github.com/spenceralger/elasticsearch-angular-example.git
  ```

2. Move into the project

  ```sh
  cd elasticsearch-angular-example
  ```

3. Install the node modules

  ```sh
  npm install
  ```

4. Open the index.html file in your browser.

5. Check out the source for [index.html](https://github.com/spenceralger/elasticsearch-angular-example/blob/master/index.html) to see how it works.
