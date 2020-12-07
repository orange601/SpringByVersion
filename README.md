# 4.3.X ~

### 새로운 어노테이션 추가됨  
- @PostMapping
- @GetMapping
- @PutMapping
- @DeleteMapping
- @PatchMapping

* Java 8 기능을 완전히 지원하기 시작하였다.
>> Java 6, Java 7 의 고유 기능들에 대해서도 각각 지원한다.
* Starter Pack의 등장으로 초기 설정이 보다 용이해졌다.
* Groovy 를 통한 Bean 설정이 가능하다.
* Core Container 들의 기능 지원이 확대되었다.
>> 예를 들어, Spring Data Repository 를 사용하고 있다면 간단한 구현으로 주입할 수 있다. (@Autowired Repository<Customer> customerRepository)
>> meta-annotation 지원과 함께 custom-annotation 을 만들 수 있다.
>> Bean 관리가 더 용이해졌다.
>>> @Order 어노테이션을 통해 배열과 리스트 형태의 Bean을 정렬 할 수 있다.
>>> @Lazy 어노테이션을 통해 Lazy Injection이 가능하다.
* @RestController 등 Web 개발 도구의 지원이 강화되었다.
* WebSocket이나 STOMP 등의 프로토콜을 지원하여 양방향 통신이 가능하다.
* 테스트 환경이 개선되어 Framework 레벨에서 테스트 유틸리티를 지원한다.(ex. AopTestUtils, ReflectionTestUtils(개선))
* 2020년 12월 31일부로 개발 및 지원이 종료될 예정이다.
  
# 5.X
* 전체 프레임워크가 Java 8 을 기반 소스코드로 삼으며, 제네릭과 람다 등을 통해 가독성이 향상 되었다.
* JDK 9와도 완벽 호환된다.
* Jackson 2.9, Protobuf 3, Reactor 3.1과의 호환 추가
* Spring WebFlux 추가, 비동기와 넌-블로킹 이벤트 루프 모델 사용 가능
* Kotlin 지원
* Junit 5 지원
* 5.0.x 버전은 2020년 10월까지 지원되며, 5.1.x 버전과 5.2.x 버전은 각각 2020년 10월, 2021년 말까지 활발히 개발될 것이다. 5.3.x 버전은 알파버전으로, 2024년까지 지원이 제공된다.
