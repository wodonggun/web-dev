# CSS 특징

  클래스는 가장 최근에 선언된 스타일이 적용됨.
  id -> class -> 태그선택자 순서  
 

- `class` :  `.`으로 표시
- `id`   :  `#`으로 표시

# 우선순위
1. id 선택자(#)
2. 클래스 선택자(.)
3. 태그 선택자

# CSS 삽입 방법

```HTML
<!DOCTYPE html>
<html>
  <head>
    <style>
      h2{color:blue}
    </style>
  </head>
  <body>
    <h1 style="color:red">Hello World</h1>
    <h2>Hello world</h2>
  </body>
</html>
```
  
  

- tag 선택자
```HTML
li{
    color:red;
    font-size: 12px;
    text-decoration:underline;
    }
```
  
  

- id 선택자
```HTML
#select{
    font-size:50px;
  }
```
  
  
- class 선택자
```HTML
.hello{
    font-size:100px;
  }
```

