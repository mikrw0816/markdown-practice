# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

안녕하세요. 문장 테스트

# 줄바꿈(Line Breaks)

안녕하세요.<br>
문장 테스트  
!!!

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a href="https://naver.com" title="네이버로 이동">NAVER</a>  
[NAVER](https://naver.com "네이버로 이동")

<a href="https://naver.com" target="_blank">NAVER</a>  
target="_blank"는 지원 안함

# 이미지(Images)

![스타벅스](https://www.starbucks.co.kr/common/img/common/logo.png)

[![스타벅스](https://www.starbucks.co.kr/common/img/common/logo.png)](https://www.starbucks.co.kr/)  
이미지 + 링크

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 인용문을 작성하세요!
>>> 인용문을 작성하세요!  
>>> 인용문을 작성하세요!  
>>> 인용문을 작성하세요!

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://google.com">GOOGLE</a>  
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

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
안녕하세요
```

# 표(Table)

position 속성

값 | 의미 | 기본값
-- | :--: | --:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

<span style="text-decoration: underline;">가나다라</span>마바사아자차카타파하<br/>
ABCDEFGHIJKLMNOPQRSTUVWXYZ

<a href="https://naver.com" title="네이버" target="_blank">NAVER</a> 

---

<img src="https://www.starbucks.co.kr/common/img/common/logo.png" alt="스타벅스">

# 수평선(Horizontal Rule)

---

***
___