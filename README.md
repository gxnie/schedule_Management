# Schedule Management

## API 명세서

### Schedule
| 기능       | Method | URL             | Request | Response | 상태코드                |
|----------|-------|-----------------|---|---|---------------------|
| 일정 생성    | POST | /schedules      | - | - | 200:정상 등록 400:잘못된 값 |
| 전체 일정 조회 | GET   | /schedules      | - | - | 200:정상 조회 400:잘못된 값 |
| 선택 일정 조회 | GET   | /schedules/{id} | - | - | 200:정상 조회 400:잘못된 값 |
| 선택 일정 수정 | PUT   | /schedules/{id} | - | - | 200:정상 수정 400:잘못된 값 |
| 일정 삭제    | DELETE | /schedules/{id} | - | - | 200:정상 삭제 400:잘못된 값 |

***
### ERD
