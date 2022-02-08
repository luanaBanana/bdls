# Big Data Lab Cluster

Setup for BDLS course.

# How to

* Make sure you got docker and docker-compose installed.
* Change into the hive directory and compose it:

  `cd docker-hive/ && docker-compose up -d`
 
* After having successfully installed hive and the postgresdb you can install hue. make sure to change the directory again:

  `cd ../hue/ && docker-compose up -d`
