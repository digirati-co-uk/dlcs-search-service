# dlcs-search-service
Search service for IIIF Content Search and annotation indexing.

Initially, a placeholder for us to gather use cases as issues, and scope the requirements.

## MVP

* Ingest:
  * W3C Web Annotations from Elucidate
  * Full text from Starsky
* Indexing:
  * text as strings: must fully support non-Roman character sets and languages.
  * creator: required by IIIF Content Search
  * motivation: required by IIIF Content Search
  * date: required by IIIF Content Search
  * body URIs, e.g. IDA topic URIs (potentially with some granularity)
* APIs:
  * IIIF Content Search 1.0
  * Iris
  * ? Standard Elasticsearch query syntax IN, W3C or OA annotation lists OUT
  * ? bulk ingest, e.g. from PostgreSQL (for a mass ingest of an Elucidate instance), or from S3 (for Starsky).
  
  
## Non-functonal requirements

* Elasticsearch
* Python 3.x
* Well-documented
* 100% test coverage (might as well do this as TDD from the start)
* maintainable by more than one developer (no SPOFs).


