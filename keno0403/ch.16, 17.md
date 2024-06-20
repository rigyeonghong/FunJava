## Reactive manifesto
- 리액티브 애플리케이션과 시스템 개발의 핵심 원칙을 공식적으로 정의하며 반응성, 회복성, 탄력성, 메시지 주도의 특성을 가진다.

## Reactive programming
- application level 에서는 비동기로 작업을 수행함을 뜻한다.
- system level 에서는 컴포넌트에서 발생한 장애를 고립시켜 문제가 전파되어 시스템 장애로 이어지는 것을 방지한다.

## Reactive stream
- reactive programming 은 reactive stream 을 사용하는 프로그래밍이다.
- reactive stream prorject 에서 4개의 인터페이스를 최소 구현 기능 집합으로 정의했다.
- publisher, subscriber, subscription, processor

## application
- Java 와 spring 기준으로 RxJava -> project reactor -> webflux 으로 발전했다.
