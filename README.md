# 제목(Header)

# 제목 1
## 제목 2
### 제목 3



# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산</br>
대한 사람 대한으로 길이 보전하세



# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게__**  
~~취소선~~  
<u>밑줄</u>



# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
      1. 순서가 필요한 목록
      1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록



# 링크(Links)

<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>  
[NAVER](https://naver.com "NAVER로이동!")

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>  



# 이미지(Image)

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)



# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

> 인용문을 작성하세요!  
>>중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3



# 인라인(Inline) 코드 강조

CSS에서 `background` 혹은  
`background-image` 속성으로 요소에  
배경 이미지를 삽입할 수 있습니다.



# 블록(Block) 코드 강조

```html
<a href="https://naver.com" target="_blank">NAVER</a>  
```

```css
.list > li {
  position: absoulte;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'aaa';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
 동해물과 백두산이 
 마르고 달도록  
```



# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|--  
statoc | 기준 없음 | o
relatve | 요소 자신 | o
statoc | 위치상 부모 요소 | x
relatve | 뷰포트 | x 




# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" target="_blank">NAVER</a>  

<img width="78" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">



# 수평선(Horizontal Rule)

---

***
___



# Git 
1. git init
1. git status
1. git add .
1. git status
1. git commit -m 'text'
1. git remote add origin (github  주소)
1. git push origin master
