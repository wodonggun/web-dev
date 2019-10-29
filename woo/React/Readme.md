# 리액트
- 단순 View만을 위한 라이브러리
- 반응 순서 : 데이터 -> 데이터 변경 -> View 변경 (단방향 방식)


- redner함수 : 데이터가 업데이트 되면, 새로운 데이터를 가지고 View를 생성함 -> 기존 Virtual DOM에 리랜더링하고, 이전에 DOM과 비교하여
다른 것만 실제 DOM에 갱신함.



- `초기 랜더링` - 초기에 보일 모습으로, `render(){ ... }`로 구현되어있음. 

- `랜더링` - 재귀방식을 통해 랜더링을 진행함 -> 

- `virtual 랜더링` - 



# 유틸

1. VS Code
2. ESLint - 자바스크립트 문법 및 코드 스타일 검사
3. Reactjs Code Snippets : 함수, 컴포넌트 사용할시에 단축 단어 사용
4. Prettier - Code Formatter : 코드스타일 자동 정리

기본적으로 Node.js에는 npm이 깔려있지만, 속도면에서나 효율적인 캐싱, 유틸 기능 등 `Yarn`을 추천.


# 변수

- `var` : 변수의 범위가 함수단위임 (블록단위 X)
- `let` : 일반 변수(블록 단위)
- `const` : 재선언 불가능


```HTML
import React from 'react';


function App() {
  const name = '리액트';
   
  return (
    <div>
      {name === '리액트' ? (
      <h1>리액트입니다.</h1>
      ) 
    : 
    (
      <h2>리액트 아닙니다.</h2>
    )}

    </div>
  );
}

export default App;
```


