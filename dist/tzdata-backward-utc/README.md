
## Synopsis

This is (a portion of) the [IANA TZ database](https://www.iana.org/time-zones), represented as JSON. Use this module in combination with [timezonecomplete](https://www.npmjs.com/package/timezonecomplete).

This module contains all zones of IANA TZ database file 'backward' that are old synonyms for Etc/UTC or Etc/GMT.

This module has peer dependency tzdata-etcetera, because the data in this module has links to zones in those modules.

## TZ Database Version

2016g

## Use

In Node.JS, to get at the JSON data, simply do:

```javascript
var jsonData = require('tzdata-backward-utc');
```

In a browser, use the [bundled UMD module](./tzdata-backward-utc.js):

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>tzdata-backward-utc example</title>
    <script src="./tzdata-backward-utc.js"></script>
    <script>
        function onLoad() {
            var data = tzdataBackwardUtc;
        }
    </script>
</head>
<body onLoad="onLoad()">
</body>
</html>
```

## License

MIT

## Zones in This Module

GMT+0, GMT-0, GMT0, Greenwich, UCT, UTC, Universal