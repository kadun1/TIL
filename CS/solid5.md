# Solid 5원칙

• SRP: 단일 책임 원칙(single responsibility principle)<br/>
&emsp;- 한 클래스는 하나의 책임만 가져야 한다.<br/>
• OCP: 개방-폐쇄 원칙 (Open/closed principle)<br/>
&emsp;- 소프트웨어 요소는 확장에는 열려 있으나 변경에는 닫혀 있어야 한다.<br/>
• LSP: 리스코프 치환 원칙 (Liskov substitution principle)<br/>
&emsp;- 프로그램의 객체는 정확성을 깨트리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야 한다.<br/>
• ISP: 인터페이스 분리 원칙 (Interface segregation principle)<br/>
&emsp;- 특정 클라이언트를 위한 인터페이스 여러개가 범용 인터페이스 하나보다 낫다.<br/>
• DIP: 의존관계 역전 원칙 (Dependency inversion principle)<br/>
&emsp;- 프로그래머는 “추상화에 의존해야지, 구체화에 의존하면 안된다.” 의존성 주입은 이 원칙
을 따르는 방법 중 하나다. 즉 구현 클래스에 의존하지 않고, 인터페이스에 의존해야 한다.<br/>