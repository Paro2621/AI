# DL query
## Simple queries
`isConnectedTo value room_corridor`
`isConnectedTo min 2 Room`
`hasRoom value room_minibar`
`contains value room_showroom`

## Sanity check
`Room and Floor`			    -> empty
`not (isConnectedTo some Room)`	-> no room must be here

# SPARQL Query
```
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
SELECT ?subject ?object
    WHERE { ?subject rdfs:subClassOf ?object }
```
