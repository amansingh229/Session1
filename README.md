Python

- How to check the version : 
python3 —version or python2 --version

- How to import data from a url(jason file)
import pycurl
import requests
import urllib, json
url = 'https://raw.githubusercontent.com/ansymo/msr2013-bug_dataset/master/data/v02/mozilla/bug_status.json'
dresponse = urllib.urlopen(url)
data = json.loads(dresponse.read())

- Important Library
import pycurl
import requests
import urllib, json
import matplotlib.pyplot as plt
import numpy as np



