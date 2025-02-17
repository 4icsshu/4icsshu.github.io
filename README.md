第一堂上課

簡報中 
index.html 原始碼：
```HTML
<!DOCTYPE html>
<html lang="zh-Hant-TW">
  <head>
    <title>這是標題</title>
    <!--這是註解-->
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <p>Hello World!</p>
      <a href="https://ics.wp.shu.edu.tw/">這是超連結
      這是超連結，Hyper Text</a>
  </body>
</html>
```

style.css 原始碼：
```
 /*這是CSS 的註解*/
/* 這是一個多行的註解
這是第二行的註解
這是第三行的註解*/
a {
  color:#ccc;
  text-decoration: none;
  &:hover {
    color:red;
    text-decoration: underline;
  }  
}
```

等等示範用 VS code 撰寫（只是複製貼上）
