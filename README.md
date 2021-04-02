# 안다희 [202030422]
## [03월 30일]
> * **조건문**
>   * if else if 조건문
>   * switch 조건문<br><br>
>
> * **삼항 연산자** : `<불 표현식> ? <참> : <거짓>`<br><br>
>
> * 웹 브라우저에서 작동하는 자바스크립트 : `prompt()` 이름의 함수를 받음
> * Node.js에서 작동하는 자바스크립트 : 단순한 코드로 입력을 받을 수 없음<br><br>
>
> * **배열** : `let 이름 = [자료,자료,자료]`<br><br>
>
> * **반복문**
>   * while 반복문
>   * for 반복문

```
4. if else if 조건문

        if (<불 표현식>) {
        
        } 
        else if (<불 표현식>) {
        
        } 
        else if(<불 표현식>) {
        
        } 
        else {
        
        }


5. switch 조건문

        switch (<비교할 값>) {
        	case <값> :
        	<문장>
        	break;
        	case <값> : 
        	<문장>
        	break;
        	default:
        	<문장>
        	break;
        }
```

```
1. while 반복문

        while (<불 표현식>) {
        	// 불 표현식이 참인 동안 실행할 문장
        }


2. for 반복문

        for (let i = 0; i < <반복 횟수>; i++) {

        }


```
---
## [03월 23일]
> * **기본 자료형** : 불 (true & false)  
> Undefined 자료형 : 변수를 선언했으나 초기화하지 않은 자료형
> * **자료형 변환 방법** : number(), string(), Boolean(), 숫자와 문자열 자료형 자동 변환, 불 자료형 자동 변환<br><br>
>
> * **변수** : 값을 저장할 때 사용하는 식별자, 변수 선언 후 변수에 값을 할당<br><br>
>
> * **상수** : 항상 같은 수, 변수와 반대되는 개념<br><br>
>
> * **연산자**
>   * 논리 연산자 (!, ||, &&)
>   * 복합 대입 연산자 (+=, -=, *=, /=)
>   * 증감 연산자 (변수++, ++변수, 변수--, --변수)
>   * 자료형 확인 연산자 (typeof)
>   * 일치 연산자 (===, !==)
>   * NaN(Not a Number) : 숫자 자료형이지만 숫자가 아닌 것, 자기 자신과 일치하지 않는 유일한 값<br><br>
>
> * **조건문**
>   * if 조건문
>   * if else 조건문
>   * 중첩 조건문

```
1. if 조건문

        if (<불 표현식>) {

        }


2. if else 조건문

        if (<불 표현식>) {
            // 불 표현식이 참일 때 실행할 문장
        } else {
            // 불 표현식이 거짓일 때 실행할 문장
        }


3. 중첩 조건문

        if (불 표현식) {
        	if (불 표현식) {
        		문장;
        	} else {
        		문장;
        	}
        } else {
        if (불 표현식) {
        		문장;
        	} else {
        		문장;
        	}
        }

```
---
## [03월 16일]
> * **자바스크립트로 할 수 있는 것** : 웹 클라이언트 애플리케이션 개발, 웹 서버 개발, 모바일 애플리케이션 개발, 데스크톱 애플리케이션 개발, 게임 개발, 데이터베이스 관리<br><br>
> * **기본 용어** : 표현식, 문장, 프로그램, 키워드, 식별자, 주석<br><br>
> * **기본 출력 방법** : `console.log("문자열")`, REPL<br><br>
> * **기본 자료형** : 숫자, 문자열
