# Figma
## 🍑 embed로 삽입하기
1. 작성한 내용을 오픈합니다.
2. 왼쪽 패널에 있는 'Prototype' 탭을 선택합니다
3. 'Share' 메뉴를 선택합니다.
4. 나타나는 팝업창에서 아래쪽에 ``` <>Get embed code ``` 선택한 후 나타나는 코드를 복사합니다.
5. 배포된 html 태그안에 '붙여넣기'합니다 

### 샘플코드 
```html
<html>
  <head>
    <style>
      h1,h2 { text-align: center;}
      #content {
        width: 800px;
        margin: auto;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
      }
    </style>
  </head>
  <body>
    <h1>Figma </h1>
    <h2>embed로 삽입하기</h2>
    <div id="content">
  <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="414" height="896" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F6OiIub6gEbuZJVw9oMbYxK%2Ftaxi-booking%3Ftype%3Ddesign%26scaling%3Dmin-zoom%26page-id%3D0%253A1%26node-id%3D0-2" allowfullscreen></iframe>
     
    </div>
  </body>
</html>
```

결과화면은,

<img width="250" alt="스크린샷 2023-05-12 오후 3 29 09" src="https://github.com/PhoebeYoon/Figma/assets/48478079/00fec597-ac29-4c9b-8c61-2191e350a3f0">



