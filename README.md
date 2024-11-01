# Schedule Management

## API 명세서

### Schedule
| 기능       | Method | URL             | Request | Response | 상태코드                                  |
|----------|-------|-----------------|---|---|---------------------------------------|
| 일정 생성    | POST | /schedules      | - | - | 200:정상 등록 400:잘못된 값                   |
| 전체 일정 조회 | GET   | /schedules      | - | - | 200:정상 조회, 400:잘못된 값                  |
| 선택 일정 조회 | GET   | /schedules/{id} | - | - | 200:정상 조회, 400:잘못된 값, 404: 일정 찾을 수 없음 |
| 선택 일정 수정 | PUT   | /schedules/{id} | - | - | 200:정상 수정, 400:잘못된 값, 404: 일정 찾을 수 없음 |
| 일정 삭제    | DELETE | /schedules/{id} | - | - | 200:정상 삭제, 400:잘못된 값, 404: 일정 찾을 수 없음 |
<br>
<details>
<summary> 일정 생성</summary>

|메서드|
|----|
|POST|
#### Request
```
{
}
```
</details>

<details>
<summary> 전체 일정 조회</summary>

| 메서드 |
|-----|
| GET |
#### Response
```
{
}
```
</details>


***
### ERD
![Alt text](/src/ERD.png)
***
### SQL
