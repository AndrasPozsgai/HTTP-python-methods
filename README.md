# HTTP-python-methods
Method of json.data getting


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

#with request
##install requeat ex. on ubuntu $pip install reqest
```import requests

        r = requests.get('url')

        print r.json()    
```
