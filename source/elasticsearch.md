# Elasticsearch

## simple query

```bash
curl -X GET "http://localhost:9200/_search?pretty"
```

## remove all data

```bash
curl -X DELETE "http://localhost:9200/*"
```

## create index and type

```bash
curl -X PUT "http://localhost:9200/<IndexName>/<TypeName>"
```

