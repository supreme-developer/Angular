# AngularJS vs Javascript

## AngularJS 표현식은 자바스크립트 표현식과 비슷합니다. 아래 목록은 AngularJS 표현식과 자바스크립트 표현식의 차이점입니다.

  - 객체의 접근: 기본적으로 자바스크립트는 모든 객체를 최상위 객체인 window 객체안에서 찾습니다. 이와 반대로 AngularJS는 표현식에 사용된 객체를 scope 안에서 찾습니다. 가령 {{ user }} 라고 작성했다면 user 객체에 접근하는데 window.user가 아닌 scope.user로 scope 객체에 접근합니다. 

  - undefined와 null 무시: 자바스크립트 표현식으로 objectA.propertyA라고 작성했다고 가정합니다. 만약 objectA가  선언되지 않으면 objectA는 undefined일 것입니다. Undefined에서 propertyA에 접근하려 했으니 자바스크립트에서는 오류를 발생합니다. 하지만 AngularJS에서는 오류를 발생하지 않고 무시합니다. 즉 템플릿 {{objectA.propertyA}}라고 작성하여 접근 시에 propertyA가 선언되어 있지 않더라도 아무런 오류를 발생하지 않습니다. 

  - 제어문 작성이 안 됨: if문과 같은 조건절이나 for문과 같은 반복문 그리고 throw문은 작성할 수 없습니다.

# angularJS 단점
 - 1.x 버전인 AngularJS의 지원은 없음
 - TypeScript 기반인 Angualr 마이그레이션 할 시 마이그레이션 문제, typeScript를 배워야하는 문제
 - react, vuejs에 비해서 대용량, 초기로딩 속도 낮음


# angularjs vs vuejs
 - framework의 많은 지원을 바랄경우 angularjs
 - 응용 프로그램의 단일 페이지 레이아웃을 빠르게 구성할 경우 vue.js 

# vuejs 단점
 - vuejs는 코드구현 시 모듈화로 여러 파일로 나눠서 처리는게 어려움

# vuejs 장점
 - html, css, js 를 거의 변경하는 것 없이 custom tag만 추가해서 처리가 가능하다.
 - 

# react 단점
 - JSX라는 문법을 사용함으로써 디자이너와 협업이 어렵다(과연 디자이너가 JSX를 알까??)
 - 양방향 데이터 바인딩을 지원하지 않는다(MVVM패턴을 왜 안가는걸까??)

# 참고문헌
https://brunch.co.kr/@hee072794/112