## 자주 사용하는 annotation

```java
@BeforeAll
// 전체 테스트 시작 전 처음으로 한번만 실행
// 테스트 환경 초기화때 사용 (static 으로 선언)
@BeforeEach 
// 테스트 케이스 시작 전에 매번 실행
// 각 인스턴스에 대해 메스드를 호출해야 하므로 static 아님
@AfterAll
// 전체 테스트를 마치고 종료하기 전에 한 번만 실행
// 데이터베이스 연결 종료 및 공통적으로 사용하는 자원을 해제할 때 사용 static 선언
@AfterEach
// 각 케이스를 종료하기 전 매번 실행 static 아님
```
