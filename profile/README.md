## 📖 프로젝트 소개

>‘마음편’은 귀가길의 불안함을 덜고, 누구나 편안하게 마음 놓고 귀가할 수 있도록 만들어진 서비스입니다.

혼자 걷는 밤길이 불안한 사람들, 사랑하는 가족의 귀가가 걱정되는 보호자, 안전한 동네를 만들고 싶은 시민 모두를 위한 앱입니다.

지역별 CCTV·안심지킴이집·경찰서 등 안심 시설의 위치를 안내해주어 사용자 스스로도 안전한 경로를 선택할 수 있도록 도와줍니다.

‘마음편’은 기술이 줄 수 있는 가장 따뜻한 안전, 바로 그 마음을 지향합니다.

당신의 밤길에 마음 놓을 수 있는 동행이 되어드릴게요.

---
## :link: 배포 링크

> ### [⛪ 배포 링크 - 플레이스토어](https://play.google.com/store/apps/details?id=com.maumpeace.safeapp)

---

## 🖥️ 서비스 소개

![media1](https://github.com/user-attachments/assets/cc053183-1ea3-4b6f-9e90-5be5cf99db2c)

---

## 🧰 사용 스택


### :wrench: System Architecture

<img width="952" alt="스크린샷 2025-05-21 오전 10 56 50" src="https://github.com/user-attachments/assets/d2d1a029-0c30-44c1-a811-6ab580063bf2" />

--- 

## :busts_in_silhouette: 팀 동료


### BE

| <a href=https://github.com/uuuj0821><img src="https://avatars.githubusercontent.com/u/85716720?v=4" width=100px/><br/><sub><b>@GithubID</b></sub></a><br/> | <a href=https://github.com/GwonDohyeon><img src="https://avatars.githubusercontent.com/u/90237119?v=4" width=100px/><br/><sub><b>@GithubID</b></sub></a><br/> | <a href=https://github.com/socical-dev><img src="https://avatars.githubusercontent.com/u/77969043?v=4" width=100px/><br/><sub><b>@GithubID</b></sub></a><br/> |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
|                                                                            박유진                                                                             |                                                                            권도현                                                                             |                                          정근영                                           |

## 📑 프로젝트 규칙

### Branch Strategy
> - main / dev 브랜치 기본 생성 
> - main과 dev로 직접 push 제한
> - PR 전 최소 1인 이상 승인 필수

### Git Convention
> 1. 적절한 커밋 접두사 작성
> 2. 커밋 메시지 내용 작성
> 3. 내용 뒤에 이슈 (#이슈 번호)와 같이 작성하여 이슈 연결

> | 접두사        | 설명                           |
> | ------------- | ------------------------------ |
> | Feat :     | 새로운 기능 구현               |
> | Fix :      | 버그 수정                      |
> | Docs :     | 문서 추가 및 수정              |
> | Refactor : | 코드 리팩토링 (동작 변경 없음) |
> | Release :   | 배포                           |
> | Chore :    | 기타 작업                      |

> ### Description
- **소셜 로그인**: 카카오 로그인으로 간편한 시작
- **실시간 지도 기반 위치 정보**: CCTV, 경찰서, 지킴이집 등 안전 시설 표시
- **긴급 버튼**: 위험 상황 발생 시 가장 가까운 안전지점으로 자동 안내
- **안전 경로 탐색**: 도착지 및 최대 3개의 경유지를 포함한 최적 경로 제공
- **자녀 위치 실시간 SSE 수신**: 보호자는 앱 내에서 자녀의 움직임을 실시간으로 확인 가능
- **보호자/자녀 관계 연동**: 관계 등록, 승인, 삭제 기능 제공
- **푸시 알림**: Firebase Messaging을 활용한 알림 수신
- **설정**: 공지사항, 도움말, 개인정보처리방침 확인 및 로그아웃 가능

---

> ### Discussion
> * 추후 논의할 점에 대해 작성해주세요.

### Code Convention
>FE/BE
> - 패키지명 FLAT_CASE
> - 응답에 사용되지 않는 필드명 SNAKE_CASE
> - 클래스명 PASCAL_CASE
> - 공통 응답 포맷은 {"success": bool, "message": str} 형식이며, 필드명은 CAMEL_CASE
> - FCM 메시지 형식은{"notification": {"title": title,"body": body},"data": data or {}}
> - 모든 뷰는 APIView 사용(user 앱 제외)

### Communication Rules
> - Discord 활용 
> - 정기 회의


## :clipboard: Documents
> [📜 API 명세서](https://documenter.getpostman.com/view/41188267/2sB2qZENNs)
> 
> [📜 요구사항 정의서](https://docs.google.com/document/d/1he4XTaUivLDLF_A0sgQsAVxApbGX_fGhwZKjlpJpjwg/edit?tab=t.1y371wrul365)
> 
> [📜 ERD](https://www.erdcloud.com/d/Pb2PpEMnk3HuK9o8P)
>
> [📜 Flow Chart](https://drive.google.com/file/d/1t5MrrreN4SDx9DKSnZVz1X-JWH4Evwv_/view)
