# angular componet
CBD 프레임워크이다.
- Component Based Development
- Angular 애플리케이션은 컴포넌트를 중심으로 구성된다.
- 클라이언트 사이드 렌더링 방식으로 뷰를 생성한다. 

## MVC와 CBD의 차이점

## Component ?
- 동작 가능한 하나의 부품이다.
- CBD(Component Based Development)
 

component role
- 애플리케이션의 화면을 구성하는 뷰(view)를 생성하고 관리하는 것이다.

* 캡슐화 (Encapsultation)
(타인이 외부에서 조작)을 대비해 외부에서 특정 속성이나 메소드를 사용할 수 없도록 숨겨놓은 것이다.

캡슐화의 예
- 자바는 클래스의 속성과 메소드에 접근 제한을 걸어(private) 직접 속성과 메소드에 접근할 수 없게 만들어준다.
캡슐화를 통한 정보 은폐 장점
- 데이터가 바뀌어도 다른 객체에 영향을 주지 않아 독립성이 유지된다. 


## Web Component
- 웹 애플리케이션의 뷰는 html, css, javascript가 필요하다.
- HTML Template, Shadow DOM, HTML import, Custom Element가 웹 컴포넌트의 4대 기술 스펙이다.

- HTML Template
컴포넌트의 뷰를 생성
- Shadow DOM
DOM을 캡슐화 할 수 있어야 한다. (외부로부터의 간섭을 제어하기 위해서 스코프를 분리)
- HTML import
외부에서 컴포넌트를 호출 할 수 있어야 한다.
- Custom Element
컴포넌트를 명시적으로 호출하기 위한 명칭 선언. </br>
HTML 요소와 같이 사용할 수 있어야한다. (?)

Refernce
http://webclub.tistory.com/156
https://medium.com/vincent-ogloblinsky/export-angular-components-as-custom-elements-with-angular-elements-a2a0bfcd7f8a