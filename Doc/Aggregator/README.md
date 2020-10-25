# Aggregator/Server

It is the backend server. 

GET on / returns the Web Interface.
POST on / is used for getting toxic spans for a string.

It calls both Detection Components and aggregates their results in order to compute a final result that is returned on the POST request.
