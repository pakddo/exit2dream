# Native Lazy Loading

Created: Oct 15, 2019 10:27 PM

![](ejbol2wks361ioxoir2g-687bfd41-db0a-42c4-869c-f0f36578f648.gif)

# What is lazy loading?

- 페이지 내 현재 중요하지 않은 리소스의 로드를 늦추는 기술
- 일반적으로 이미지나 비디오 등의 큰 데이터들을 “필요할 때” 로드하는 것을 말함
- 지금까지는 JavaScript의 IntersectionObserver, 혹은 scroll 위치를 보고 구현했음
- lazy loading 을 이용시 보이는 이미지들만 출력하고 안보이는 이미지들을 206 상태로 대기시킴

# Image Common Loading

![](Untitled-500369b5-a19a-4014-89b4-dcbe6d40a2c1.png)

# Image Lazy Loading

![](Untitled-6dd08069-1c91-4442-8c94-9f4a1536ec3d.png)

# <img loading=“lazy”/>

    -<img src="celebration.jpg" loading="lazy" alt="..." />
    <iframe src="video-player.html" loading="lazy"></iframe>

# Browser Support

![](test-f2329827-bb7c-499a-851c-31a1dfede90d.png)

# Example

[https://addyosmani.com/blog/lazy-loading/?q=io](https://addyosmani.com/blog/lazy-loading/?q=io)

[https://mathiasbynens.be/demo/img-loading-lazy](https://mathiasbynens.be/demo/img-loading-lazy)