### node-dhcp
---
https://github.com/infusion/node-dhcp


```js
// tests/segbuffer.test.js
var should = require('should');
var SeqBuffer = require('../lib/seqbuffer.js');

describe('Segbuffer', function() {

  it('should init correctly', function() {
    
    var sb = new SeqBuffer;
    sb._data.length.should.be.equal(1500);
    var sb = new SeqBuffer(null, 20);
    sb._r.should.be.equal(0);
    sb._w.should.be.equal(0);
    sb._data.compare(new Buffer(20).fill(0)).should.be.equal(0);
  });
  
  it();
  
  
});

```

```
```

```
```


