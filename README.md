# kafka-sample
* 실행 방법
  ``` 
  $ ./gradlew docker
  $ docker compose up
  ```
* kafka 확인(kafka-ui)
    - url : `http://localhost:8989/`
* 테스트
  ```
  curl --location 'http://localhost:8081/todo/new' \
      --header 'Content-Type: application/json' \
      --data '{"message":"helloworld"}'
  ```