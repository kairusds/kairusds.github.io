---
title: "Adding require() support on ES Modules"
published: true
---

I just got this from the official NodeJS documentations page so yeah.
I don't know how to write blogs so I'll just post the code here:

```javascript
import { createRequire } from "module";
const require = createRequire(import.meta.url);

const path = require("path");
```

And now you should be able to require any CommonJS modules even
from an ES module (.mjs) or TypeScript. Enjoy!

[Source](https://nodejs.org/api/module.html#module_module_createrequire_filename)
