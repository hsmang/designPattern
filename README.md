# designPattern

객체지향 설계 5원칙 ( SOLID )
1. SRP ( Single Responsibility Principle) 단일 책임 원칙
 어떠한 클래스를 변경해야 하는 이유는 한가지 뿐 이어야 한다.

2. OCP ( Open Closed Principle ) 개방 폐쇄 원칙
 자신의 확장에는 열려 있고, 주변의 변화에 대해서는 닫혀 있어야 한다.
 상위 클래스 또는 인터페이스를 중간에 둠으로써, 자신은 변화에 대해서는 폐쇄적이지만, 인터페이스는 외부의 변화에 대해서 확장을 개방해 줄 수 있다.

예) Jdbc, Mybatis, hibernate 등

3. LSP ( Liskov Substitution Principle ) 리스코프 치환 원칙
 서브 타입은 언제나 자신의 기반(상위) 타입으로 교체할 수 있어야 한다.

4. ISP ( Interface Segregation Principle ) 인터페이스 분리 원칙
 클라이언트는 자신이 사용하지 않는 메서드에 의존 관계를 맺으면 안된다.
 프로젝트 요구 사항과 설계에 따라서 SRP(단일책임원칙) / ISP (인터페이스 분리원칙) 를 선택 한다.

5. DIP ( Dependency Inversion Principle) 의존 역전 원칙
 자신보다 변하기 쉬운 것에 의존하지 말아야 한다.




-------------------

## 디자인 패턴
 - 자주 사용하는 설계 패턴을 정형화해서 이를 유형별로 가장 최적의 방법으로 개발을 할 수 있도록 정해둔 설계

### Gof 디자인 패턴
 - 모든 사람들이 다양한 경험을 가지고 있을 수 없다. 객체지향 개념에 따른 설계중 재사용할 경우 유용한 설계를 디자인 패턴으로 정리 해둔 것,
 - 총 23개의 패턴이 있음

### 디자인 패턴의 장점
 - 개발자 간의 원활한 소통
 - 소프트웨어 구조 파악 용이
 - 재사용을 통한 개발 시간 단축
 - 설계 변경 요청에 대한 유연한 대처

### 디자인 패턴의 단점
 - 객체지향 설계/구현
 - 초기 투자 비용 부담

### 생성 패턴
- 객체를 생성하는 것과 관련된 패턴으로, 객체의 생성과 변경이 전체 시스템에 미치는 영향을 최소화 하고, 코드의 유연성을 높여준다.
- factory method
- singleton
- prototype
- builder
- abstract factory
- chaining

### 구조 패턴
- 프로그램 내의 자료구조나 인터페이스 구조 등 프로그램 구조를 설계하는데 활용 될 수 있는 패턴
클래스. 객체들의 구성을 통해서 더 큰 구조를 만들 수 있게 해준다.
큰 규모의 시스템에서는 많은 클래스들이 서로 의존성을 가지게 되는데, 이런 복잡한 구조를 개발 하기 쉽게 만들어 주고, 유지보수 하기 쉽게 만들어 준다.
- adapter
- composite
- bridge
- decorator
- facade
- flyweight
- proxy

### 행위 패턴
- 반복적으로 사용되는 객체들의 상호작용을 패턴화한 것으로, 클래스나 객체들이 상호작용하는 방법과 책임을 분산하는 방법을 제공한다. 행위 패턴은 행위 관련 패턴을 사용하여 독립적으로 일을 처리하고자 할때 사용.
- template method
- interpreter
- iterator
- observer
- strategy
- visitor
- chain of responsibiility
- command
- mediator
- state
- memento
