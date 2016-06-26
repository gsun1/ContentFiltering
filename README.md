# ContentFiltering

content.py - Contains algorithms using the minkowski distance formula to calculate which locations are most similar to each
other. Based on these "distances", the we are able to give recommendations about where to go based on where someone has
already gone.

chicago.csv - Contains some test data about Chicago. I took 25 popular places in Chicago and rated them 0-5 on a variety of
attributes from family friendliness to the amount of walking required at the location. The first column is the location and
subsequent columns are the ratings in each of the attributes. Locations who recieve similar scores accross attributes are
considered more "similar" than locations who recieve more different ratings.

nyc.csv - Contains the same data as the Chicago csv.

The tables generated by content.py can be used as follows: Suppose we have the Chicago and NYC data. Then we can calculate
how similar different places in the two cities are. For example, the Empire State Building might be similar to the Hancock
Building. Suppose, for example, we have data that says that a user visited the Empire State Building when they were in NYC.
We also know now that our user is now planning on visiting Chicago. It would inform the user then, that they might want to
check out the Hancock Tower.
