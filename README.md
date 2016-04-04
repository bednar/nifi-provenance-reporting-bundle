# nifi-elasticsearch-reporting-bundle

NiFi Elasticsearch reporting tasks.

## Table of Contents

- [Installation](#installation)
- [Tasks](#tasks)
- [Todo](#todo)

## Installation

```sh
$ mvn clean package
$ cp nifi-elasticsearch-reporting-nar/target/nifi-elasticsearch-reporting-nar-0.0.1-SNAPSHOT.nar $NIFI_HOME/lib
$ nifi restart
```

## Tasks

### ElasticsearchProvenanceReporter

Reporting task to write provenance events to an Elasticsearch index.

![](elasticsearch_provenance_reporter_properties.png)

## Todo

- Use state management API to keep track of the most recent event indexed by ElasticsearchProvenanceReporter.

## License

Copyright (c) 2016 Joey Frazee. nifi-elasticsearch-reporting-bundle is released under the Apache License Version 2.0.
