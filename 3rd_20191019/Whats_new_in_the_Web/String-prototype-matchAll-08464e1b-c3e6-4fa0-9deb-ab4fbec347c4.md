# String.prototype.matchAll

Created: Oct 19, 2019 7:44 AM

![](1_aeFzjKB-7Y804GicKxk5Rg-a1928a5d-11d9-4776-93f8-4a780cd4d5cb.jpeg)

# String.prototype.match

    const str = 'abc/abd/abe';
    
    const reg = /ab(a|d|e)/g
    
    str.metch(reg) // ['abc','abd','ade']

# String.prototype.matchAll

    const str = 'abc/abd/abe';
    const regexp = /ab(a|d|e)/g
    
    let array = [...str.matchAll(regexp)];
    
    array.forEach(console.log)

![](18-3ce22b5c-4ad5-49df-a48b-19a8353deffa.png)

Browser Support

- ES2020
- Chrome / Firefox 지원
- Polyfill을 사용하실 수 있습니다. (core-js)