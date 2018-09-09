# chromecast-scanner

scan your local network for chromecast devices and return the
first found.

### Usage
```javascript
const scanner = require('chromecast-scanner');

scanner((err, service) => {
  console.log(
    'chromecast %s running on: %s',
    service.name,
    service.data
  );
});
```

### Installation

```bash
npm install chromecast-scanner
```

## License
MIT
