# MovieQL

Movie API with GraphQL

# GraphQL

- 요청한 정보들을 원하는 방식으로 받을 수 있음
- overfetching, underfetching 문제 해결
  - overfetching : 요청한 영역의 정보보다 더 많은 정보를 서버에서 받는 것
  - underfetching : 하나를 완성하기 위해서 많은 소스를 요청하는 것
- 설치 : `yarn add graphql-yoga`

- 그 외 dependency :  `babel`, `nodemon`

- `index.js`  : 어떤 Schema와 어떤 resolver를 사용해서 graphQL 서버를 생성할 것인지 설정



# Query and Resolver

- `schema` : 무엇을 받고 무엇을 줄지에 대한 정보
- `mutation` : `state`를 업데이트하는 경우 (ex. 서버, 데이터베이스, 메모리에서 데이터를 바꿈)

- `query` : 문제
- `resolvers` : Query를 해결한다.





# Extending the Schema

- Playground : POSTMAN의 DB 버전



# Creating Queries with Arguments

- Resolvers : GraphQL 서버에서 요청을 받는다. 
- GraphQL 서버가 Query나 Mutation 정의를 발견하면
- resolver를 찾아서 해당 함수를 실행
- 이때, 함수에 argument 전달 가능







# GraphQL로 Rest API를 Wrapping

- `YTS API` : 토렌트에서 사용하는 API로 Open API

  - [ 공식문서](<https://yts.lt/api>)

  