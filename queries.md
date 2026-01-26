# Simple queries
isConnectedTo value room_corridor
isConnectedTo min 2 Room
hasRoom value room_minibar
contains value room_showroom

# Sanity check
Room and Floor			-> empty
not (isConnectedTo some Room)	-> no room must be here
