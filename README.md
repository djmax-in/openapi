# V-ARCHIVE API
게임 DJMAX RESPECT V의 웹기반 성과 관리 도구인 V-ARCHIVE의 API를 정리한 문서
## 등록되어있는 곡&패턴 목록
https://v-archive.net/db/songs.json
## 성과표 목록
https://v-archive.net/db/boards.json
## 기록 등록 API
[POST /client/open/{userNo}/score](https://github.com/djmax-in/openapi/wiki/%EA%B8%B0%EB%A1%9D-%EB%93%B1%EB%A1%9D-API)
## 성과표 조회 API
[GET  /api/archive/{nickname}/board/{button}/{board}](https://github.com/djmax-in/openapi/wiki/%EC%9C%A0%EC%A0%80-%EC%84%B1%EA%B3%BC%ED%91%9C-%EC%A1%B0%ED%9A%8C-API)
## 티어 조회 API
[GET /api/archive/{nickname}/tier/{button}](https://github.com/djmax-in/openapi/wiki/%EC%9C%A0%EC%A0%80-%ED%8B%B0%EC%96%B4-%EC%A1%B0%ED%9A%8C-API)
## 유저 곡별 기록 조회 API
[GET /api/archive/{nickname}/title/{titleNum}](https://github.com/djmax-in/openapi/wiki/%EC%9C%A0%EC%A0%80-%EA%B3%A1%EB%B3%84-%EA%B8%B0%EB%A1%9D-%EC%A1%B0%ED%9A%8C-API)
