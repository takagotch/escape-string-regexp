### escape-string-regexp
---
https://github.com/sindresorhus/escape-string-regexp

```js
// test.js
import test from 'ava';
import escapeStringRegexp from '.';

test('main', t => {
  t.is(
    escapeStringRegexp('\\ ^ $ * + ? . ( ) | { } [ ] '),
      '\\\\ \\^ \\$ \\* \\+ \\+ \\. \\( \\) \\| \\{ \\} \\[ \\]'
  );
});

test('escapes `-`', t => {
  t.is(
    escapeStringRegext('foo - bar'),
    'foo \\- bar'
  );
});
```

```
```

```
```


