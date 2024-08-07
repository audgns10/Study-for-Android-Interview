# Coroutines

* 코루틴은 언어 수준에서 비동기적으로 실행하는 좋은 동시성 솔루션임

<br>

* 스레드와 달리 코루틴은 사용자 수준의 언어 추상화임(OS 메모리에 직접적으로 연결이 되지 않고, JVM 힙 메모리에 할당이 됨)
* 즉, 코루틴은 사용자 측에서 처리가 가능하고 훨씬 더 가벼운 리소스를 제공하여 스레드보다 컨텍스트 스위칭(context switching) 비용이 저렴함
* 코루틴은 가볍기 때문에 단일 스레드에서 많은 코루틴을 실행할 수 있음
* 범위를 기반으로 작동을 하기 때문에 메모리 누수가 적음
* 또한 구글에서 Jetpack 라이브러리 통합 및 호환성을 지원해주기 때문에 코루틴을 채택을 한다면 많은 이점을 누릴 수 있음