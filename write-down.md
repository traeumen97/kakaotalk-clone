# kakaotalk-clone

## const  / let / var

- const: constant(상수)라는 것이고, constant는 값이 바뀔 수 없음

  ```js
  const myName = "seokyung";

  myName = "kimseokyung";
  //처음에 설정한 const 값은 절대 변경할 수 없음
  ```

- let: 값이 바뀔 수 있음

  ```js
  let myName = "seokyung";

  console.log("hello " + myName);

  myName = "kimseokyung"; 
  // 처음에 설정한 let 값을 변경할 수 있음. let은 생성할 때만 작성

  console.log("your new name is " + myName);
  ```