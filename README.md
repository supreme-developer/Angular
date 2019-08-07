# Angular vs Javascript

## AngularJS 표현식은 자바스크립트 표현식과 비슷합니다. 아래 목록은 AngularJS 표현식과 자바스크립트 표현식의 차이점입니다.

  - 객체의 접근: 기본적으로 자바스크립트는 모든 객체를 최상위 객체인 window 객체안에서 찾습니다. 이와 반대로 AngularJS는 표현식에 사용된 객체를 scope 안에서 찾습니다. 가령 {{ user }} 라고 작성했다면 user 객체에 접근하는데 window.user가 아닌 scope.user로 scope 객체에 접근합니다. 

  - undefined와 null 무시: 자바스크립트 표현식으로 objectA.propertyA라고 작성했다고 가정합니다. 만약 objectA가  선언되지 않으면 objectA는 undefined일 것입니다. Undefined에서 propertyA에 접근하려 했으니 자바스크립트에서는 오류를 발생합니다. 하지만 AngularJS에서는 오류를 발생하지 않고 무시합니다. 즉 템플릿 {{objectA.propertyA}}라고 작성하여 접근 시에 propertyA가 선언되어 있지 않더라도 아무런 오류를 발생하지 않습니다. 

  - 제어문 작성이 안 됨: if문과 같은 조건절이나 for문과 같은 반복문 그리고 throw문은 작성할 수 없습니다.


