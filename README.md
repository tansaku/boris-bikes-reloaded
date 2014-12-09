Boris Bikes
====================

###Class - Bike

Responsibilites             | Collaborators
----------------------------|------------------
Be rented                   | User, Station
Be returned                 | User, Station, Van
Be broken                   | User

### Class - User
Responsibilites     | Collaborators
--------------------|------------------------
Rent                |  Bike, Station
Break               |  Bike
Return              |  Bike, Station

### Class - Station 
Responisibilites        |Collaborators
------------------------|------------------
...                     |
...                     |

### Class - Van 
Responisibilites        |Collaborators
------------------------|------------------
Receive                 | Bike, Station, Garage
Eject                   | Bike, Station, Garage
Holding                 | Bike
Move                    | Bike, Station, Garage

### Class - Garage 
Responisibilites        |Collaborators
------------------------|------------------
...                     |
...                     |

