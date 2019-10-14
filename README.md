# Base64
Preprocessing of Base64 data

We have data in base64 coded binary format (in .h5 file). Our aim is to decode the binary file to json, open up the nested data structure. Furthermore, for our polygons, we want to calculate a median value for the geographic co-ordinates. As result, we get a sparse DataFrame matrix. 

This is an example of data preprocessing. These code functions you might find valuable: 

- flatten nested structure
- decode Base64 to JSON
- calculating median in polygon, from a lat-long pairs
