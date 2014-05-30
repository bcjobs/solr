This core only exists to extract text.  To extract text, execute an HTTP POST to this URL and include a binary file in the request body:

http://localhost:8983/solr/text_extractor/update/extract?extractOnly=true&extractFormat=text&wt=json&indent=true

More info here: http://wiki.apache.org/solr/ExtractingRequestHandler