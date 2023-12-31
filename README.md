# 객체지향의 사실과 오해

---
#

### [Chapter 1] 협력하는 객체들의 공동체  <br/>

0. 시너지를 생각하라. 전체는 부분의 합보다 크다. 객체지향의 목표는 실세계를 모방하는 것이 아니다. 오히려 새로운 세계를 창조하는 것이다. <br/>

1. **역할, 책임, 협력**은 우리가 삶을 영위하기 위해 다른 사람과 접촉하는 모든 곳에 존재한다. <br/>

2. 요청은 연이어 발생하기 때문에 응답역시 요청의 방향과 반대 방향으로 연쇄적으로 전달된다. <br/>

3.  요청과 응답을 통해 다른 사람과 협력 할 수 있는 능력은 인간으로 하여금 거대하고 복잡한 문제를 해결할 수 있는 공동체를 형성할 수 있게 만든다.   <br/>

4.  협력의 성공은 특정한 역할을 맡은 각 개인이 얼마나 요청을 성실히 이행하는가에 달려 있다. <br/>

5.  할이라는 단어는 의미적으로 책임이라는 개념을 내포한다 <br/>

6. 인간적인 삶이란 때로는 협력하고 때로는 반목하면서 타인과 부대끼며 살아가는 삶이다. <br/>

7. 어떤 객체도 섬이 아니다. <br/>

8. 객체지향 설계라는 예술은 적절한 객체에게 적절한 책임을 할당하는 것에서 시작된다. 얼마나 적절한 책임을 선택하느냐가 애플리케이션의 아름다움을 결정한다 <br/>

9. 결국 협력의 품질을 결정하는 것은 객체의 품질이다. <br/>

10. 객체는 충분히 “협력적”이어야한다. 외부의 도움을 무시한 채 모든 것을 스스로 처리하려고 하는 전지전능한 객체는 내부적인 복잡도에 의해 자멸한다. <br/>

11. 객체는 다른 객체의 명령에 복종하는 것이 아니라 요청에 응답할 뿐이다. 어떤 방식으로 응답할지는 객체 스스로 판단하고 결정한다. 객체는 자율적이어야한다. <br/>

12. 어떤 사물이 자신의 행동을 스스로 결정하고 책임진다면 우리는 그 사물을 자율적인 존재라고 말한다. <br/>

13. 객체는 상태(state)와 행동(behavior)을 함께 지닌 실체라고 정의된다.  <br/>

14. 객체는 다른 객체가 무엇(what)을 수행하는지는 알 수 있지만 어떻게(how) 수행하는지에 대해서는 알 수 없다. <br/>

15. 과거의 전통적인 개발 방법은 데이터와 프로세스를 엄격하게 구분한다. 이에 반해 객체지향에서는 데이터와 프로세스를 객체라는 하나의 틀 안에 함께 묶어 놓음으로써 객체의 자율성을 보장한다. <br/>

16. 객체가 수신된 메세지를 처리하는 방법을 메서드(method)라고 부른다. <br/>

17. 메시지를 수신한 객체가 실행시간에 메서드를 선택할 수 있다는 점은 다른 프로그래밍 언어와 객체지향 프로그래밍 언어를 구분 짓는 핵심적인 특징 중 하나다. <br/>

18.  언어가 인간의 사고를 지배한다. 객체지향 세계에서 클래스(Class)는 에스키모인들의 눈과 유사하다. <br/>

19. 훌륭한 객체지향 설계자가 되기 위해 거쳐야 할 첫 번째 도전은 코드를 담는 클래스의 관점에서 메시지를 주고받는 객체의 관점으로 사고의 중심을 전환하는 것이다. 중요한 것은 어떤 클래스가 필요한가가 아니라 어떤 객체들이 어떤 메시지를 주고받으며 협력하는가다. <br/>

20. 클래스의 구조와 메서드가 아니라 객체의 역할, 책임, 협력에 집중하라. 객체지향은 객체를 지향하는 것이지 클래스를 지향하는 것이 아니다. <br/>

---

#

### [Chapter 2] 이상한 나라의 객체  <br/>

1. 객체지향 패러다임은 지식을 추상화하고 추상화한 지식을 객체 안에 캡슐화함으로써 실세계 문제에 내재된 복잡성을 관리하려고 한다. 객체를 발견하고 창조하는 것은 지식과 행동을 구조화하는 문제다. <br/>

2. 아기들은 물체가 여러 부분으로 구성돼 있더라도 함께 움직일 경우 그 물체를 하나의 유기적인 단위로 인식한다. 아기들 역시 뚜렷한 경계를 가진 객체들의 집합으로 세상을 바라보는 것이다  <br/>

3. 세상을 더 작은 객체로 분해하는 것은 본질적으로 세상이 포함하고 있는 복잡성을 극복하기 위한 인간의 작은 몸부림이다. 즉 객체란 인간이 분명하게 인지하고 구별할 수 있는 물리적인 또는 개념적인 경계를 지닌 어떤 것이다.  <br/>

4. 객체지향 패러다임의 목적은 현실세계를 모방하는 것이 아니라 현실 세계를 기반으로 새로운 세계를 창조하는 것이다.  <br/>

5. 어떤 행동의 성공 여부는 이전에 어떤 행동들이 발생했는지에 영향받는다. 이는 행동 간의 순서가 중요하다는 것을 의미한다.  <br/>

6. 독립적인 하나의 단위로 인식할 수 있는 모든 사물은 객체다. 객체의 다양한 특성을 효과적으로 설명하기 위해서는 객체를 **상태(state), 행동(behavior), 식별자(identity)**를 지닌 실체로 보는 것이 가장 효과적이다.  <br/>
 
7. 객체는 식별가능한 개체 또는 사물이다. 구체적인 사물일 수도, 시간처럼 추상적인 개념일 수도 있다. 소프트웨어 안에서 객체는 **저장된 상태와 실행 가능한 코드를 통해** 구현된다.  <br/>

8. 모든 일들의 공통점은 어떤 행동의 결과는 과거에 어떤 행동들이 일어났었느냐에 의존한다는 것이다.  <br/>

9. 일반적으로 과거에 발생한 행동의 이력을 통해 현재 발생한 행동의 결과를 판단하는 방식은 복잡하고 번거로우며 이해하기 어렵다. 따라서 인간은 행동의 과정과 결과를 단순하게 기술하기 위해 **상태**라는 개념을 고안했다.  <br/>

10. 이렇게 상태를 이용함으로써 과거게 얽메이지 않고 현재를 기반으로 객체의 행동방식을 이해할 수 있다. 따라서 세상의 복잡성을 완화하고 인지과부하를 줄일 수 있는 중요한 개념이다.  <br/>

11. 모든 객체의 상태는 단순한 값과 객체의 조합으로 표현할 수 있다. 이때 객체의 상태를 구성하는 모든 특징을 통틀어 객체의 프로퍼티(property)라고 한다.  <br/>
 
12. 프로퍼티(property)는 고정되어 있기 때문에 정적이다. 반면 프로퍼티(property) 값은 시간의 흐름에 따라 변경되기 때문에 동적이다.  <br/>

13. 객체 간의 선으로 표현되는 링크와 달리 객체를 구성하는 단순한 값은 속성(attribute)이다. 객체의 프로퍼티는 단순한 값인 속성과 다른 객체를 가리키는 링크의 두가지 종류의 조합으로 표현할 수 있다.  <br/>

14. 객체는 스스로의 행동에 의해서만 상태가 변경되는 것을 보장함으로써 객체의 자율성을 유지한다.  <br/>
 
15. 객체의 행동에 의해 객체의 상태가 변경된다는 것은 행동이 부수효과(side effect)를 초래한다는 것을 의미한다.  <br/>

16. 객체의 행동은 객체의 상태를 변경시키지만 행동의 결과는 개체의 상태에 의존적이다.  <br/>

17. 객체의 행동은 상태의 영향을 받는다. 객체의 행동은 상태를 변경시킨다. → 상호작용이 현재의 상태에 어떤 방식으로 의존하는가, 상호작용이 어떻게 현재의 상태를 변경시키는가.  <br/>

18. 객체가 다른 객체와 협력하는 유일한 방법은 다른 객체에게 요청을 보내는 것이다. 따라서 객체의 행동은 객체가 협력에 참여할 수 있는 유일한 방법이다.  <br/>

19. `drinkBeverage()`, `drunken(quantity)`같은 메세지를 전송하는 객체(송신자)는 메시지 수신자의 상태 변경에 대해서는 전혀 알지 못한다.  <br/>
 
20. 객체의 행동을 유발하는 것은 외부로부터 전달된 메세지나 객체의 상태를 변경할지 여부는 객체 스스로 결정한다.  <br/>

21. 상태를 외부에 노출시키지 않고 행동을 경계로 캡슐화하는 것은 결과적으로 객체의 자율성을 높인다. 자율적인 객체는 스스로 판단하고 스스로 결정하기 때문에 객체의 자율성이 높아질수록 객체의 지능도 높아진다.  <br/>

22. 객체가 식별 가능하다는 것은 객체를서로 구별할 수 있는 특정한 프로퍼티가 객체 안에 존재한다는 것을 의미한다.  <br/>

23. 값과 식별자의 가장 큰 차이점은 값은 식별자를 가지지 않지만 객체는 식별자를 가진다는 점이다.  <br/>

24. 값(value)은 숫자, 문자열, 날짜, 시간, 금액 등과 같이 변하지 않는 양을 모델링한다. 흔히 값의 상태는 변하지 않기 때문에 불변상태(immutable state)를 가진다고 말한다.  <br/>

25. 값이 같은지 여부는 상태가 같은지를 이용해 판단한다. 값의 상태가 같으면 두 인스턴스는 동일한 것으로 판단하고 상태가 다르면 두 인스턴스는 다른 것으로 판단한다.  <br/>

26. 객체는 시간에 따라 변경되는 상태를 포함하며, 행동을 통해 상태를 변경한다. 따라서 객체는 가변상태(mutable state)를 가진다고 말한다.  <br/>
 
27. 상태를 기반으로 객체의 동일성을 판단할 수 없는 이유는 시간이 흐름에 따라 객체의 상태가 변하기 때문이다.  <br/>

28. 객체의 상태를 조회하는 작업을 쿼리(query)라고 하고 객체의 상태를 변경하는 작업을 명령(command)라고 한다.객체가 외부에 제공하는 행동의 대부분은 쿼리와 명령으로 구성된다.  <br/>
 
29. 안타깝게도 상태를 먼저 결정하고 행동을 나중에 결정하는 방법은 설계에 나쁜 영향을 끼친다. 협력에 참여하는 훌륭한 객체 시민을 양성하기 위한 가장 중요한 덕목은 상태가 아니라 행동에 초점을 맞추는 것이다. 객체가 적합한지를 결정하는 것은 객체의 상태가 아니라 행동이다. 기억하라. **행동이 상태를 결정한다.**  <br/>

30. 추상화(abstraction)이란 실제의 사물에서 자신이 원하는 특성마 취하고 필요 없는 부분을 추려 핵심만 표현하는 행위를 말한다.  <br/>
 
31. 현실 속의 객체의 의미 일부가 소프트웨어 객체로 전달되기 때문에 프로그램 내의 객체는 현실 속의 객체에 대한 은유다.  <br/>

32. 은유 관계에 있는 실제 객체의 이름을 소프트웨어 객체의 이름으로 사용하면 표현적 차이를 줄여 소프트웨어의 구조를 쉽게 예측할 수 있다.  <br/>

---

#

### [Chapter 3] 타입과 추상화  <br/>

1. 일단 컴퓨터를 조작하는 것이 추상화를 구축하고, 조작하고, 추론하는 것에 관한 모든 것이라는 것을 깨닫고 나면 (훌륭한) 컴퓨터 프로그램을 작성하기 위한 중요한 전제 조건은 추상화를 정확하게 다루는 능력이라는 것이 명확해진다.  <br/>

2. 지하철 노선도 디자인에서 가장 중요한 것은 얼마나 사실적으로 지형을 묘사했느냐가 아니라 역과 역 사이의 연결성을 얼마나 직관적으로 표현했느냐다.  <br/>

3. 해리 벡이 창조한 지하철 노선도의 핵심은 지도가 당연히 가져야 한다고 생각되는 ‘정확성’을 버리고 그 ‘목적’에 집중한 결과다. 역의 위치가 중요한 것이 아니라 역과 역 사이의 연결 관계가 중요했던 것이다.  <br/>

4. 진정한 의미에서 추상화란 현실에서 출발하되 불필요한 부분을 도려내가면서 사물의 놀라운 본질을 드러나게 하는 과정이라고 할 수 있다.  <br/>

5. 어떤 추상화도 의도된 목적이 아닌 다른 목적으로 사용된다면 오도될 수 있다. 추상화의 수준, 이익, 가치는 목적에 의존적이다. 리처드 파인만의 말처럼 “현상은 복잡하다. 법칙은 단순하다. 버릴 게 무엇인지 알아내라.”  <br/>

6. ‘기껏해야 트럼프에 불과해’  엘리스는 인물들의 차이점을 의도적으로 무시하고 공통점만을 강조함으로써 ‘트럼프’라는 그룹에 속할 수 있는 인물들을 취사선택한 것이다.  <br/>

7. 이처럼 공통점을 기반으로 객체들을 묶기 위한 그릇을 개념(Concept)이라고 한다. 개념을 이용하면 여러 그룹으로 분류(Classification)할 수 있다.  <br/>

8. 하트 여왕은 트럼프라는 개념그룹의 일원이고 하얀 토끼는 토끼라는 개념의 일원이다. 이처럼 객체에 어떤 개념을 적용하는 것이 가능해서 개념그룹의 일원이 될 때 객체를 그 개념의 인스턴스(instance)라고 한다.  <br/>

9. 분류란 객체에 특정한 개념을 적용하는 작업이다. 객체에 특정한 개념을 적용하기로 결심했을 때 우리는 그 객체를 특정한 집합의 멤버로 분류하고 있는 것이다.  <br/>
 
10. 추상화를 사용함으로써 우리는 극도로 복잡한 이세상을 그나마 제어가능한 수준으로 단순화할 수  있는 것이다.  <br/>

11. 타입의 정의는 개념의 정의와 완전히 동일하다. 타입은 공통점을 기반으로 객체들을 묶기 위한 틀이다. 어떤 객체에 타입을 적용할 수 있을 때 그 객체를 타입의 인스턴스라고 한다.  <br/>

12. 그렇다면 객체는 데이터인가? 그렇지않다. 다시 한 번 강조하지만 객체에서 중요한 것은 객체의 행동이다.  <br/>

13. 결론적으로 객체의 타입을 결정하는 것은 객체의 행동 뿐이다. 객체가 어떤 데이터를 보유하고 있는지는 타입을 결정하는 데 아무런 영향도 미치지 않는다.  <br/>

14. 같은 타입에 속한 객체는 행동만 동일하다면 서로 다른 데이터를 가질 수 있다. 여기서 동일한 행동이란 동일한 책임을 의미하며, 동일한 책임이란 동일한 메시지 수신을 의미한다. 따라서 동일한 타입에 속한 객체는 내부의 데이터 표현 방식이 다르더라도 동일한 메시지를 수신하고 이를 처리할 수 있다. 이것이 **다형성**에 의미를 부여한다.  <br/>

--- 

#

### [Chapter 04]  역할, 책임, 협력  <br/>

1. 결론적으로 인간이 어떤 본질적인 특성을 지니고 있느냐가 아니라 어떤 상황에 처해있느냐가 인간의 행동을 결정한다. 즉, 각 개인이 처해 있는 정황 또는 문맥이 인간의 행동방식을 결정한다는 것이다.  <br/>

2. 중요한 것은 개별 객체가 아니라 객체들 사이에 이뤄지는 협력이다.   <br/>

3. 훌륭한 객체지향 설계란 겉모습은 아름답지만 협력자들을 무시하는 오만한 객체를 창조하는 것이 아니라 조화를 이루며 적극적으로 상호작용하는 협력적인 객체를 창조하는 것이다. 비록 그 객체를 따로 떼어놓고 봤을 때는 겉모습이 다소 기묘하고 비합리적이라더라도 말이다.  <br/>

4. 데이터의 내부 표현 방식과 무관하게 행동만이 고려 대상이라는 사실은 외부에 데이터를 가무처야 한다는 것을 의미한다. 따라서 훌륭한 객체지향 설계는 외부에 행동만을 제공하고 데이터는 행동  뒤로 감춰야한다. 이 원칙을 흔히 **캡슐화**라고 부른다.  <br/>

5. 객체를 결정하는 것은 행동이다. 데이터는 단지 행동을 따를 뿐이다. 이것이 객체를 객체답게 만드는 가장 핵심적인 원칙이다.  <br/>

6. 트럼프와 트럼프 인간의 예에서 알 수 있는 것처럼 타입과 타입 사이에는 일반화/특수화 관계가 존재할 수 있다. 트럼프는 트럼프 인간보다 더 일반적인 개념이다.  <br/>

7. 주의해야할 점은 타입의 내연을 의미하는 행동의 가짓수와 외연을 의미하는 집합의 크기는 서로 반대라는 사실이다. 일반화/특수화 관계에서 일반적인 타입은 특수한 타입보다 더 적은 수의 행동을 가지지만 더 큰 크기의 외연 집합을 가진다. 특수한 타입은 일반적인 타입보다 더 많은 수의 행동을 가지지만 더 적은 크기의 외연 집합을 가진다.  <br/>

8. 다시 한 번 강조하지만 슈퍼타입과 서브타입에서 중요한 것은 두 타입 간의 관계가 행동에 의해 결정된다는 점이다. 즉, 어떤 타입이 다른 타입의 서브타입이 되기 위해서는 행위적 호환성을 만족시켜야한다.  <br/>

9. 타입을 사용하는 이유는 인간의 인지능력으로는 시간에 따라 동적으로 변하는 개체의 복잡성을 극복하기가 너무 어렵기 때문이다.  <br/>

10. 타입은 시간에 따라 동적으로 변하는 앨리스의 상태를 시간과 무관한 정적인 모습으로 다룰 수 있게 해준다.  <br/>

11. 타입은 추상화다. 타입을 이용하면 객체의 동적인 특성을 추상화할 수 있다. 결국 타입은 시간에 따른 객체의 상태 변경이라는 복잡성을 단순화할 수 있는 효과적인 방법인 것이다.  <br/>

12. 여러분이 객체지향 프로그래밍 언어를 이용해 클래스를 작성하는 시점에는 시스템을 정적인 과점에서 접근하는 것이다. 그러나 실제로 애플리케이션을 실행해 객체의 상태변경을 추적하고 디버깅하는 동안에는 객체의 동적인 모델을 탐험하고 있는 것이다.   <br/>
   
13. 객체를 분류하는 기준은 타입이며, 타입을 나누는 기준은 객체가 수행하는 행동이다.  <br/>

14. 결국 객체지향에서 중요한 것은 동적으로 변하는 객체의 ‘상태’와 상태를 변경하는 ‘행위’이다.  <br/>

15. 객체지향 설계란 애플리케이션의 기능을 구현하기 위한 협력 관계를 고안하고, 협력에 필요한 역할과 책임을 식별한 후 이를 수행할 수 있는 적절한 객체를 식별해나가는 과정이다. <br/>

16. 책임 주도 설계는 객체의 역할, 책임, 협력을 고안하기 위한 방법과 절차를 제시한다. 반면 디자인 패턴은 책임-주도 설계의 결과를 표현한다. 패턴은 모범이 되는 설계다. <br/>

17. 만약 특정한 상황에 적용 가능한 디자인 패턴을 잘 알고 있다면 책임-주도 설계의 절차를 순차적으로 따르지 않고도 손쉽게 포착할 수 있다. 디자인 패턴은 책임-주도 설계의 결과물인 동시에 지름길이다. <br/>

18. 테스트 주도 개발은 테스트를 작성하는 것이 아니라 책임을 수행할 객체 또는 클라이언트가 기대하는 객체의 역할이 메시지를 수신할 때 어떤 결과를 반환하고 그 과정에서 어떤 객체와 협력할 것인지에 대한 기대를 코드의 형태로 작성하는 것이다. <br/>

19. 테스트 주도 개발은 책임-주도 설계를 통해 도달해야하는 목적지를 테스트라는 안전장치를 통해 좀 더 빠르고 견고한 방법으로 도달할 수 있도록 해주는 최상의 설계 프랙티스다. <br/>

---

#

### [Chapter 05] 책임과 메시지 <br/>

1. 의도는 “메시징”이다. 훌륭하고 성장 가능한 시스템을 만들기 위한 핵심은 모듈 내부의 속성과 행동이 어떤가보다는 어떻게 커뮤니케이션 하는 가에 달려있다. <br/>

2. 이 이야기가 들려주는 교훈은 명확한 책임과 역할을 지닌 참가들이 협력에 참여해야 한다는 것이다. 이것은 객체의 세계에서도 마찬가지다. <br/>

3. 적절한 책임이 자율적인 객체를 낳고, 자율적인 객체들이 모여 유연하고 단순한 협력을 낳는다. 따라서 협력에 참여하는 객체가 얼마나 자율적인지 가 전체 애플리케이션의 품질을 결정한다. <br/>

4. 포괄적이고 추상적인 책임을 선택한다고 해서 좋은 건아니다. 어떤 책임이 가장 적절한가는 설계 중인 협력이 무엇인가에 따라 달라진다. 이런 모호함이 객체지향 설계를 난해하면서도 매력적인 예술로 만드는 이유다. <br/>

5. 자율적인 책임의 특징은 객체가 ‘어떻게(how)’해야 하는가가 아니라 ‘무엇(what)’을 해야하는가를 설명한다는 것이다. <br/>
 
6. 메시지는 ‘어떻게’ 수행될 것인지는 명시하지 않는다. 메시지는 단지 오퍼레이션을 통해 무엇이 실행되기를 바라는지만 명시하며, 어떤 메서드를  선택할 것인지는 전적으로 수신자의 결정에 좌우된다. <br/>

7. 외부의 객체는 메시지에 관해서만 볼 수 있고 객체 내부는 볼 수 없기 때문에 자연스럽게 객체의  외부와 내부가 분리된다. <br/>

8. 다형성이란 서로 다른 유형의 객체가 동일한 메시지에 대해 서로 다르게 반응하는 것을 의미한다. <br/>

9. 다형성을 사용하면 송신자가 수신자의 종류를 모르더라도 메시지를 전송할 수 있다. <br/>

10. 객체지향 용어를 이용해 표현하자면 다형성은 송신자와 수신자 간의 객체 타입에 대한 결합도를 메시지에 대한 결합도로 낮춤으로써 달성된다. <br/>

11. 송신자는 오직 메시지만 바라본다. 수신자의 정확한 타입을 모르더라도 상관없다. 단지 수신자가 메시지를 이해하고 처리해 줄 것이라는 사실만 알아도 충분하다. <br/>

12. 진정한 객체지향 패러다임으로의 도약은 개별적인 객체가 아니라 메시지를 주고 받는 객체들 사이의 커뮤니케이션에 초점을 맞출 때 일어난다. <br/>

13. 객체의 내부구조는 감춰져야 한다. 외부의 객체가 객체의 내부를 마음대로 주무를 수 있다면 객체가 자신의 의지에 따라 판단하고 행동할 수 있는 자율성이 저해된다. <br/>
 
14. 메시지를 중심으로 설계된 구조는 유연하고 확장가능하며 재사용 가능하다. 메시지를 믿어라. 그러면 자율적인 책임은 저절로 따라올 것이다. <br/>

15. 객체지향의 힘은 대부분 객체의 외부와 내부를 구분하는 것에서 나온다. <br/>

16. 훌륭한 객체란 구현을 모른채 인터페이스만 알면 쉽게 상호작용할 수 있는 객체를 의미한다. <br/>
 
17. 인터페이스와 구현을 분리한다는 것은 변경될 만한 부분을 객체에 내부에 꽁꽁 숨겨 놓는다는 것을 의미한다. 일반적으로 이 원칙을 수행하기 위한 객체 설계방법을 캡슐화라고 한다. <br/>

18. 객체가 자율적이기 위해서는 자기 자신의 상태를 스스로 관리할 수 있어야 하기 때문에 데이터 캡슐화는 자율적인 객체를 만들기 위한 전제 조건이다. <br/>

19. 외부에 제공해야할 필요가 있는 메시지만을 객체의 공용 인터페이스에 포함시키고 개인적인 비밀은 고용 인터페이스의 뒤에 감춤으로써 외부의 불필요한 공격과 간섭으로부터 내부 상태를 격리할 수 있다.  <br/>

20. 객체가 수행하는 책임들이 자율적일수록 객체의 역할을 이해하기 쉬워진다. <br/>
 
21. 책임이 자율적일수록 적절하게 ‘추상화’되며, ‘응집도’가 높아지고, ‘결합도’가 낮아지며 ‘캡슐화’가 증진되고, ‘인터페이스와 구현이 명확히 분리’되며 설계의 ‘유연성’과 ‘재사용성’이 향상된다. <br/>

---

#

### [Chapter 06 객체 지도] <br/>
 
1. 변경의 여지를 남겨 놓는 가장 좋은 방법은 자주 변경되는 기능이 아닌 안정적인 구조를 중심으로 설계하는 것이다. <br/>

2. 일반적으로 기능을 수집하고 표현하기 위한 기법을 유스케이스 모델링이라 하고 구조를 수집하고 표현하기 위한 기법을 도메인 모델링이라고 한다. 쉽게 예상할 수 있는 것처럼 두 가지 모델링 활동의 결과물을 각각 유스케이스와 도메인 모델이라고 한다. <br/>

3. 모델은 대상을 단순화해서 표현한 것이다. 지식을 선택적으로 단순화하고 의식적으로 구조화한 형태다. <br/>

4. 도메인 모델은 이해관계자들이 바라보는 멘탈 모델이다. <br/>
 
5. 도메인 모델의 핵심은 사용자가 도메인을 바라보는 관점을 반영해 소프트웨어를 설계하고 구현하는 것이다. 도메인에 대한 사용자의 관점을 반영해야 하는 이유는 사용자들이 누구보다도 도메인의 ‘본질적인’ 측면을 가장 잘 이해하고 있기 때문이다. <br/>

6. 사용자와 시스템 간에 이뤄지는 상호작용의 흐름을 텍스트로 정리한 것을 유스케이스라고 한다. <br/>

7. 다이어그램에 노력을 쏟지 말라. 중요한 것은 유스케이스에 담겨있는 이야기다. <br/>

8. 도메인은 안정적인 구조를 개념화하기 위해, 유스케이스는 불안정한 기능을 서술하기 위해 가장 일반적으로 사용되는 도구다. <br/>

---

#
  
### [Chapter 07] 함께 모으기 <br/>

1. 개념관점에서 설계는 도메인 안에 존재하는 개념과 개념들 사이의 관계를 표현한다. 명세 관점은 실제로 소프트웨어 안에서 살아숨쉬는 객체들의 책임에 초점을 맞춘다. 구현관점은 실제 작업을 수행하는 코드와 연관돼있다. <br/>

2. 클래스는 세 가지 관점이라는 안경을 통해 설계와 관련된 다양한 측면을 드러낼 수 있다. 클래스가 은유하느 개념은 도메인 관점을 반영한다. 클래스의 공용 인터페이스는 명세 관점을 반영한다. 클래스의 속성과 메서드는 구현관점을 반영한다. 이러한 세가지 관점이 쉽게 식별되도록 깔끔하게 분리해야한다. <br/>

3. 클래스는 객체가 공유하는 본질적인 속성을 정의한다. 동일한 범주에 속하는 객체는 모두 동일한 속성을 가져야만 한다. <br/>

4. 한 타입이 다른 타입의 서브타입이 되기 위해서는 슈퍼타입에 순응해야한다는 것이다. 순응에는 구조적인 순응(프로퍼티 타입 동일)과 행위적인 순응(메서드 타입 동일)의 두 가지 종류가 있다.  <br/>

5. 상속의 또 다른 용도는 코드 중복을 방지하고 공통 코드를 재사용하기 위한 언어적 메커니즘을 제공하는 것이다. <br/>

6. 여러 클래스로 구성된 상속계층에서 수신된 메시지를 이해하는 기본적인 방법은 클래스간의 위임(Delegation)을 사용하는 것이다. <br/>

7. 합성관계는 부분을 전체 안에 캡슐화함으로써 인지 과부하를 방지한다. 주문 항목은 주문의 일부이므로 이 모델을 다루는 사람은 주문 항목과 관련된 세부사항은 무시하고 주문과 상품만이 존재하는 것처럼 모델을 다룰 수 있다. <br/>
