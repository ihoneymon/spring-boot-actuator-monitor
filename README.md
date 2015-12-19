Monitor Sample Application for SpringBoot Actuator
==================================================

스프링부트에서 제공하는 유지보수를 위한 액츄에이터 기능을 활용하는 간단한 대시보드 애플리케이션 만들기

# [SpringBoot Actuator: Production-ready features](http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#production-ready)

액츄에이터 엔드포인트는 애플리케이션에 대한 감시 및 상호작용을 허용한다. 스프링부트는 이미 작성되어 있는 엔드포인트들을 상당히 많은 엔드포인트를 포함하고 있으며 필요하다면 추가할 수 있다.

그 중에서도 현재 애플리케이션의 상태를 확인할 수 있는 측정`metrics` 관련한 항목을 이용하면 애플리케이션의 상태를 살필 수 있을 것으로 보인다. 이 측정값들을 이용한 모니터링 대시보드를 함 만들어자.

프론트쪽은 잼병이라 어찌될지 모르겠네. ㅎㅎ