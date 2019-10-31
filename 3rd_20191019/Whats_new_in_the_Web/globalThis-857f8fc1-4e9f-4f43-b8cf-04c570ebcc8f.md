# globalThis

Created: Oct 19, 2019 8:13 AM

![](1_aeFzjKB-7Y804GicKxk5Rg-cdf46770-3bad-410f-b9de-0ddab8e1b93a.jpeg)

# Cross-platform problem

- JavaScript가 사용되는 곳은 브라우저 뿐만이 아님
- 문제는 각 플랫폼 별로 Global 객체가 가지고 있는 이름이 서로 다름
- e.g.) Browser에서는 `window`, Node.js에서는 `global`

![](-a0368473-66aa-4b77-bffb-10a8b6dd0355.png)

# Chrome Console

![](-bfd70eb2-b24f-480f-838f-836a0bc6c5ec.png)

# Node.js REPL

![](-caa6d1c1-1cff-44b5-bd05-5b5f716acab2.png)

# Browser Support

- Edge를 제외한 대부분의 모던 브라우저에서 구현되어 있음
- 대충 열 줄 정도의 코드로도 Polyfill 가능.
- npm install @ungap/global-this