

### Find your public (external) IP address over https - [https://ipapi.co](https://ipapi.co)

### Shell

```bash
curl 'https://ipapi.co/ip/'
```

### Ruby

```ruby
require 'net/http'
puts Net::HTTP.get(URI('https://ipapi.co/ip/'))
```

### Python

```python
from requests import get   
print get('https://ipapi.co/ip/').text
```

### PHP

```php
echo file_get_contents('https://ipapi.co/ip/')
```

### Node.js

```javascript
var https = require('https');

https.get('https://ipapi.co/ip/', function(resp){
    var body = ''
    resp.on('data', function(data){
        body += data;
    });

    resp.on('end', function(){
        console.log(body);
    });
});
```

### jQuery

```javascript
$.get('https://ipapi.co/ip/', function(data){
  console.log(data)
})
```
