---
home: true
heroImage: /logo.png
actionText: Get Started →
actionLink: /docs/
footer: MIT Licensed • Copyright © 2019-2021 Łukasz Wójcik • Not created, affiliated or endorsed in any way by Blizzard Entertainment
---

### Install

``` bash
npm install blizzapi
```

### Quick start

``` javascript
const BlizzAPI = require('blizzapi');

/**
 * Or using Typescript
 * import { BlizzAPI } from 'blizzapi';
 */

const api = new BlizzAPI({
  region: 'us',
  clientId: 'client id',
  clientSecret: 'client secret'
});

const data = await api.query('/path/to/endpoint');

console.log(data);
``` 
