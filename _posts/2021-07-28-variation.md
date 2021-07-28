# 변수 (Variation)

#### 담길 수 있는 데이터 타입

다양한 종류의 데이터 타입이 들어갈 수 있다.

일단 크게 두가지 항목으로 카테고리를 나눠보자.



##### 기본타입(Primitive type)

1.Number(숫자)

2.String(문자)

3.Boolean(참과 거짓)

4.Undefined

5.Null







##### 참조타입(Reference type)

Array(배열)

Object(객체)

Function(함수)





먼저 기본타입을 알아보자.



Number (숫자) 타입이다.

```js
let myNumber1 = 0;
let myNumber2 = 100;
let myNumber3 = -50;


console.log(myNumber2);
console.log(myNumber1+myNumber2);
console.log(myNumber2-myNumber3);
console.log(myNumber2*myNumber3);
console.log(myNumber2/myNumber3);
console.log(myNumber2%myNumber3);

```





string(문자) 타입이다. 

항상 따옴표 안에 들어가있다.(나중에 차이점이 생긴다. '' "")

```js
let number1 = 100;
let number2 = 200;

console.log('100 plus 200 equals to ', number1+number2);
```

구분자 , 를 사용하여

문자와 숫자를 동시에 사용 가능하다.





Boolean(참과 거짓) 그 자체로 데이터의 값이 된다.

컴퓨터는 0과1의 값으로 이루어져있는데, 요 자체로 값이 된다.

참과 거짓만 이렇게 데이터 타입으로 분리되어있다.

(조건문에서 자세하게 나온다.)

true == 1

false == 0



Undefined

Null

==================





참조형 타입.

Array(배열)

[19,44,'good',false]



Object (객체)

{name : 'code Kim', isDeveloper: true}

key라고 해서 이름을 붙인다.

key와 값이 value로 이루어져있다.



Array와  Object는 데이터가 묶여있는 모임.



Function





