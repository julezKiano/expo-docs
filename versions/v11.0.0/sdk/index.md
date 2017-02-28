---
title: SDK API Reference
old_permalink: /versions/v11.0.0/sdk/index.html
previous___FILE: ./../guides/upgrading-exponent.md
next___FILE: ./amplitude.md
---

The Exponent SDK provides access to system functionality such as contacts, camera, and social login. It is provided by the npm package [exponent](https://www.npmjs.com/package/exponent). Install it by running `npm install --save exponent` in the root directory of the project. Then you can import modules from it in your JavaScript code as follows:

```javascript
import { Contacts } from 'exponent';
```

You can also import all Exponent SDK modules:

```javascript
import * as Exponent from 'exponent';
```

This allows you to write [`Exponent.Contacts.getContactsAsync()`](contacts.html#exponentcontactsgetcontactsasync "Exponent.Contacts.getContactsAsync"), for example.