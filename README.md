# E3372h
## HiLink e3372h library


### Summary
```
Huawei E3372h hilink client
```

### Install
```
pip install xmltodict
pip install requests
```

### Usage
```python
from e3372h import Client
c = Client()
if c.is_hilink():
    print c.basic_info().productfamily
```

### License
```
Copyright (C) 2016 Denis A. Fedorov

This software may be modified and distributed under the terms
of the MIT license.  See the LICENSE file for details.
```
