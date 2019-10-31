# Object.fromEntries

Created: Oct 19, 2019 8:08 AM

![](1_aeFzjKB-7Y804GicKxk5Rg-f3ffdb9b-a5ab-48cf-ab11-8177e1e5f779.jpeg)

# Object.entries()
```
    const object1 = {
      a: 'somestring',
      b: 42
    };
    
    for (let [key, value] of Object.entries(object1)) {
      console.log(`${key}: ${value}`);
    }
```
![](1818-60ec8284-3902-4c07-8e1d-6392eeb489c6.png)

# Object.fromEntries()
```
    const entries = [
      ['foo', 'bar'],
      ['baz', 42]
    ]
    
    const obj = Object.fromEntries(entries);
    
    console.log(obj);
```
![](181818-9f71b16b-e21e-4eda-bfc8-ece5881c6ff9.png)

# Browser Support

- Edge를 제외한 대부분의 모던 브라우저에서 지원됨
- 물론 Polyfill 가능(core-js)