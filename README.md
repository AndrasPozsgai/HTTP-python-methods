# HTTP-python-methods
Method of json.data 


*1.)*

   
```import urllib, json

      url = "http://maps.googleapis.com/maps/api/geocode/json?address=googleplex&sensor=false"

      response = urllib.urlopen(url)

      data = json.loads(response.read())

      print data 
```

*2.)*

    
```json_url = urlopen(url)

      data = json.loads(json_url.read())

      print data   
```

*3.)*

# with request
## install request ex. on ubuntu:$pip install request
```import requests

        r = requests.get('url')

        print r.json()    
```
*4.)* 

# Pandas, Data_reader
## head:
 ```import pandas as pd
 
    import pandas_datareader as pdr
 ```

