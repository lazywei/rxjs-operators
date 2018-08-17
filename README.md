RxJS operators wrapper
===

## Why ?

From RxJS 6, import path for operators is
```
const {filter} = require('rxjs/operators');
```

However, for some resolution system, relative import path might not be supported. We export the operators as a flatten module to handle such case
```
const {filter} = require('rxjs-operators');
```
