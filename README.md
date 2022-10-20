# memories_on_the_map-SERVER

* ## stack📖
  * express (nodejs)
  * mysql
  * passport-local

#
* ## update comments
  * 2022-10-15
    <br>```😎 LOGIN, JOIN, LOGOUT [REST API]  구현 완료```

    * 추가 해야 되는 사항🌞
        1. DB 최적화, 유저가 DB에 접근을 많이하지않으므로, 최적화를 해서 좀 더 속도적 측면해서 이점을 확보해야한다.
        2. 현재 일반적인 세션으로 만들었지만, 보안성이 크게 문제가 될거같으면, JWT TOKEN 방식으로 변경해서 사용
        3. USER을 제외하면 나머지는 no-sql 로 사용
        4. 일단 클라이언트 구성
  * 2022-10-21
    <br>```😎 USER CRUD REST API 구현 완료```

    * 추가해야되는 사항
        1. 가입시 프론트에서 맵에대한 좌표정보및, 게시판 정보를 불러올 사용자개인 DB 형성
        2. Vue 에서 기본 플랫폼이 잡혀서 나머지는 진행가능할거같음 