# REVIEW-JAVA-DAY3
자바복습하기 3일차 


*Student studentAhn = new Student(); 
 
 Student 클래스의 멤버변수를 저장할 공간이 필요 **힙(heap) 메모리 사용**
 
 생성된 클래스를 변수에 대입하면 인스턴스가 저장된 메모리를 studentAhn변수가 가리킴 (참조). studentAhn은 지역변수이므로 **스택(stack)메모리** 생성 
 
 인스턴스는 **힙(heap)**에 생성

힙이란? 프로그램에서 사용하는 동적 메모리 공간. 객체가 생성될 떄 사용하는 공간. c나 c++은 프로그래머가 직접 메모리를 해제해야 하지만, 자바에서는 **가비지 컬렉터**가 자동으로 메모리를 해제해줌.

클래스메서드 (static 사용) 내부에서는 인스턴스 변수를 사용할 수가 없다.

클래스 메서드와 클래스 변수는 인스턴스가 생성되지 않아도 사용할 수 있습니다.

1. 지역변수 : 스택이라는 메모리에 저장

2. 멤버 변수 : 인스턴스 변수라고도 하며, 클래스가 생성될 때 힙이라는 메모리에 저장

3. 정적 변수 : static 예약어를 사용한 변수로 클래스 생성과 상관없이 처음부터 데이터 영억 메모리에 생성되며, **인스턴스 변수와 static 변수는 사용하는 메모리가 다르다**
