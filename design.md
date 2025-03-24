# Zookeeper Design

The overall design for the program will be an extension of the work done in the previous module 4 project. With the major change being how names for the animals are created. Currently the names are stored in a array and are randomly selected. This will be changed to a dictionary where the key is the animal type and the value is a vector of names for that animal type.

- The Parser.h file will be updated to include a new function that will read in the names for the animals from a file.