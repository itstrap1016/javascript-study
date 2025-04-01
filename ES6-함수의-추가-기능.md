## 함수의 구분

- 일반 함수: constructor(o), prototype(o), super(x), arguments(o)
- 메서드: constructor(x), prototype(x), super(o), arguments(o)
- 화살표 함수: constructor(x), prototype(x), super(x), arguments(x)

## 화살표 함수

- 화살표 함수는 상위 스코프의 this를 참조한다
- arguements도 상위 스코프의 arguments를 참조한다
- arguments 대신 Rest 파라미터 사용
