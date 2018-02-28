---
title: Python 
taxonomy:
    category: docs
---

! [vsdConnect Python 3 on github](https://github.com/SICASFoundation/vsdConnect)


This library implements a client for the REST API of the virtualskeleton framework which is used by the Sicasl Medical Image Repository (www.smir.ch). It supports authentication, general queries, and specific requests such as image upload/download, object linking and right management. Examples are provided in the examples directory. Please use 'demo.smir.ch' for testing purposes.

## Module documentation
-[http://sicasfoundation.github.io/vsdConnect/](http://sicasfoundation.github.io/vsdConnect/)

## What is in this module
- Pyhton 3
- usage of **requests** package instead of urllib2
- usage of **pathlib** instead of os.path
- usage of **PyJWT** for jwt.io authentication [PyJWT](https://github.com/jpadilla/pyjwt)
- introduction of API classes using **jsonmodels**

### How do I get set up? ###
1. clone the repo

`git clone https://github.com/SICASFoundation/vsdConnect`

2. Install the package with dependencies

`pip install vsdConnect`

or

`python setup.py install`

or, if you want to edit the source:

`pip install --editable vsdConnect`


### Problems

* The server response is very slow if you have 50+ folders. VSD-connect makes a request to the server for each folder. Therefore, I will be slow if you have a lot of folders and use the folder methods. You should then use the getRequest function and create your APIFolder object locally.

## Get Started

This code connects to the demo server and retrieves an object

```python
from vsdConnect import connect
from vsdConnect import models

## Connect to demo.smir.ch
api = connect.VSDConnecter()

# an available object id from the demo and define the selfurl
vsd_id = 38
selfUrl = 'https://demo.smir.ch/api/objects/{0}' . format(vsd_id)

# create the APIObject and get it from the server
obj  = models.APIObject(selfUrl=selfUrl).get(api)

# display the object infos (json)
print(obj.show())
```

to download the object's file add this line

```python
obj.download(api)
```