# DL query
## Simple queries
`isConnectedTo value room_2`
`isConnectedTo min 2 Room`
`hasRoom value room_6`
`contains value room_3`
`{room_1} and canPass value room_5` -> check if two rooms are reachable

## Sanity check
`Room and Floor`			        -> empty
`not (isConnectedTo some Room)`	    -> no room must be here

