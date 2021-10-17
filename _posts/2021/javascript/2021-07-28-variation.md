# 변수 (Variation)

#### 안에 담길 수 있는 데이터 타입

다양한 종류의 데이터 타입이 들어갈 수 있다.

일단 크게 두가지 항목으로 카테고리를 나눠보자.

---





#### 기본타입(Primitive type)

1. Number(숫자)
2. String(문자)
3. Boolean(참과 거짓)
4. Undefined
5. Null



---





#### 참조타입(Reference type)

1. Array(배열)
2. Object(객체)
3. Function(함수)



---





먼저 기본타입을 알아보자.



##### Number (숫자) 타입이다.

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

복사 붙여넣기를 해도 좋은데 

반드시 직접 작성하고 넣어보고 값을 본 뒤,  이것이 무슨 의미를 가지고 있는지 생각해보자.







##### string(문자) 타입이다. 

항상 따옴표 안에 들어가있다.

따옴표는 'javaScript'  "javaScript" 아무거나 사용해도 상관없다.

> (이런거 특 : 꼭 나중에 차이점이 생김. )



숫자 타입과 같이 사용해도 무방하고, 여러방법으로 사용해보자.

```js
let number1 = 100;
let number2 = 200;
let comment = '100 plus 200 equals to';

console.log(comment, number1+number2);

console.log('100 plus 200 = ' , number1+number2);
```

한번 직접 적어서 값을 확인해본다.

> 여기서 쉼표가 어디에 있는지 한번 찾아보자.
>
>  ,  를 구분자 라고 하는데 숫자와 문자를 동시에 사용할때는  쉼표로 구분한다. 







##### Boolean(참과 거짓) 

그 자체로 데이터의 값이 된다.

참과 거짓만 이렇게 데이터 타입으로 분리되어있다.

(조건문에서 자세하게 나온다.)

true 

false 

```js
let myAnswer = true;
let yourAnswer = false;
let myPoint = 100;


console.log('your point is',myPoint,' is it true?',myAnswer);
```









참조형 타입.

Array(배열)

[19,44,'good',false]



Object (객체)

{name : 'code Kim', isDeveloper: true}

key라고 해서 이름을 붙인다.

key와 값이 value로 이루어져있다.



Array와  Object는 데이터가 묶여있는 모임.



Function





