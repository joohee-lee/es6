# es6

- Variables and scoping
- Template literals
- Destructuring
- Arrow functions
- Classes
- Modules
- Promises for asynchronous programming

## Variables and scoping
1. let

1.1 블록 레벨 스코프 (Block-level scope) & 자바스크립트는 함수 레벨 스코프(Function-level scope)
- 함수 레벨 스코프(Function-level scope)
함수 내에서 선언된 변수는 함수 내에서만 유효하며 함수 외부에서는 참조할 수 없다. 
즉, 함수 내부에서 선언한 변수는 지역 변수이며 함수 외부에서 선언한 변수는 모두 전역 변수이다.

- 블록 레벨 스코프(Block-level scope)
모든 코드 블록(함수, if 문, for 문, while 문, try/catch 문 등) 내에서 선언된 변수는 코드 블록 내에서만 유효하며 코드 블록 외부에서는 참조할 수 없다. 즉, 코드 블록 내부에서 선언한 변수는 지역 변수이다.

1.2  변수 중복 선언 금지 
```
let bar = 123;
let bar = 456;  // Uncaught SyntaxError: Identifier 'bar' has already been declared

```

2. const 
