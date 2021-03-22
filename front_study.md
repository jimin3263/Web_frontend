# html/css


### html 기본 구조  
```html   
<!DOCTYPE html>
<!--스크린 리더가 언어 자동 인식-->
<html lang="ko">
    <!--head: 웹페이지 정보-->
    <head
        <meta charset="UTF-8" />
        <title>탭 이름</title>
    </head>
    <!--브라우저에 실제 작성되는 내용-->
    <body>
      
    </body>
</html>
```  

### 태그  
- [html 다양한 태그](https://www.w3schools.com/html/)  
- [css 다양한 태그](https://www.w3schools.com/css/)
 
```html
<h1>헤딩 1</h1>
<h2>헤딩 2</h2>
<h3>헤딩 3</h3>
<ul>
   <li>순서 없는 리스트</li>
   <li>순서 없는 리스트</li>
</ul>
<ol>
  <li>순서 있는 리스트</li>
  <li>순서 있는 리스트</li>
</ol>
<br> <!--줄바꿈-->
<a  href="link"> link 명</a>
<img src = "image 경로", alt = "텍스트" width= "크기" height ="지정">
```

### 폰트 적용  
- [구글 폰트](https://fonts.google.com/)
- [눈누 무료 폰트](https://noonnu.cc/)
> html의 head에 추가  
```html
<link rel= "stylesheet" href= "./style.css"/>
``` 
> style.css 생성  
```css
/*구글 폰트*/
@import url('https://fonts.googleapis.com/css2?family=Yeon+Sung&display=swap');
.text_font{
    font-family: 'Yeon Sung', cursive;
}
/*눈누 무료 폰트*/
@font-face {
    font-family: 'SDKukdetopokki-Lt';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/SDKukdetopokki-aLt00.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
.title_font{
    font-family: 'SDKukdetopokki-Lt';
    color: rgb(5, 5, 78);
}
```

### padding, margin 

- padding: 박스 테두리와 안쪽 콘텐츠 사이의 여백
- margin: 박스 테두리 바깥의 여백  
- em: 상위 요소의 글자 크기를 1em으로 둠
- rem: 최상위 요소의 글자 크기를 1rem으로 둠

```html
<div>
   <!-- 줄 바꿈 없이 div 박스 순서대로 표시 -->
  <div style="display: inline-block; padding: 20px">홈</div>
</div>
```
**references: [코딩 커뮤니티(코뮤)](https://cafe.naver.com/codeuniv/9806)**  
