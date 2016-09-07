---
---

## Setup

```javascript
count = 1000 * 1000
range = [];

do {
  range.push(count);
} while(--count);
```

## Tests

- ### Array#forEach

  ```javascript
  range.forEach(function(obj) {
    obj == obj;
  });
  ```

- ### For-Of

  ```javascript
  for (var obj of range) {
    obj == obj;
  }
  ```

- ### For

  ```javascript
  var length = range.length;
  for (var index = 0; index < length; index++) {
    var obj = range[index];
    obj == obj;
  }
  ```
