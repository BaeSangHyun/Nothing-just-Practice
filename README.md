# Nothing-just-Practice

##Markdown 연습용 페이지

h1
==
h2
--
# h1
## h2
### h3
#### h4

> 1.테스트
> 2.테스트2
> 3.테스트3

[Naver][link]
[link]: http://naver.com "네이버"

Google: [Google](http://google.com)

<http://google.com>

[네이버]보다는 [구글]이 더 좋다.

[네이버]: http://naver.com
[구글]: http://google.com

*기울이기*
**강조하기**

```html
<a href="http://www.google.com/" target="blank">Google</a>
```

```css
.list > li {
    position: absolute;
    top: 40px;
}
```

```javascript
function func(){
    var a = 'AAA';
    return a;
}
```
---
값 | 의미 | 기본값
---|:---:|---:
'static' | 유형(기준) 없음 / 배치 불가능 | 'static'
'relative | 요소 **자신**을 기준으로 배치 |
'absolute | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
'fixed' | **브라우저 창**을 기준으로 배치 |

<hr>
구글 로고


[![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](http://google.com)


# D3: Data-Driven Documents

<a href="https://d3js.org"><img src="https://d3js.org/logo.svg" align="left" hspace="10" vspace="6"></a>

**D3** (or **D3.js**) is a JavaScript library for visualizing data to life using SVG, Canvas and HTML. D3 combines powerful visualization and techniques with a data-driven approach to dOM manipulation, giving you the full capabilities of modern browsers and the freedom to design the righ visual interface for you data

## Resources
- [API Reference](https://github.com/d3/d3/blob/master/API.md)
- [Release Notes](https://github.com/d3/d3/releases)
- [Gallery](https://github.com/d3/d3/wiki/Gallery)
- [Examples](https://bl.ocks.org/mbostock)
- [Wiki](https://github.com/d3/d3/wiki)

## Installing
If you use `npm istall d3`. Otherwise, download the [latest release](https://github.com/d3/d3/releases/latest).

```javascript
<script src="https://d3js.org/d3.v5.js"></script>
```
