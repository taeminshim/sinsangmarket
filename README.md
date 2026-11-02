# 신상마켓 화면 제작 가이드

신상마켓 디자인팀이 **디자인 시스템과 UI Builder로 화면을 빠르고 일관되게 치기 위한** 기준 모음이에요.
사람이 보는 가이드이면서, Claude에게 화면 제작을 맡길 때 따르는 규칙이기도 해요.

## Figma 바로가기

**라이브러리 원본**

| | 모바일 | PC |
|---|---|---|
| 디자인 시스템 | [[신상마켓] M_Design system Guide](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6) | [[신상마켓] PC_Design system Guide](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa) |
| UI Builder | [M_UI Builder](https://www.figma.com/design/7eHgyABjNbCL1fVzpbZ1IX) | [PC UI Builder](https://www.figma.com/design/aFam9mIsTVZqNmKdHHYq0f) |

**자주 여는 페이지**

| | 모바일 | PC |
|---|---|---|
| 색 | [Color](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24434-19978) | [Color](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=17610-59050) |
| 글자 | [Type Scale](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24434-19973) | [Type Scale](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=17610-59049) |
| 버튼 | [M. Buttons](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24469-54439) | [M. Buttons](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=18085-50329) · [버튼 컬러](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=1605-29926) |
| 텍스트 링크 | [N. textLink](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24469-54440) | [L. textLink](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=18085-50330) |
| 칩 | [F. Chips](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24459-46483) | [F. Chips](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=17610-59058) |
| 태그 | [G. Tag](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=30291-26552) | [G. Tag](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=22957-27841) |
| UI 요소 | [H. UI Elements](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24469-20909) | [H. UI Element](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=24953-30508) |
| 폼 | [K. Forms](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=27141-56082) | [I. Forms](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=21172-59448) |
| 모달 | [D. Bottom Sheet/Modal](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=32948-62048) | [D. Layer](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=24803-58234) |
| 아이콘 | [A. Icon](https://www.figma.com/design/5WsL9kg8fteVvSDUw4L1s6?node-id=24434-31552) | [A. Icon](https://www.figma.com/design/hzFtDckwBKxfz3QQBrOnHa?node-id=17610-59052) |
| 상품 썸네일·카드 | [빌더 Product_Card](https://www.figma.com/design/7eHgyABjNbCL1fVzpbZ1IX?node-id=948-15) | [빌더 Product_Card](https://www.figma.com/design/aFam9mIsTVZqNmKdHHYq0f?node-id=278-58694) |
| 매장 썸네일 | [빌더 Store_badge](https://www.figma.com/design/7eHgyABjNbCL1fVzpbZ1IX?node-id=2367-19563) | [빌더 Store_badge](https://www.figma.com/design/aFam9mIsTVZqNmKdHHYq0f?node-id=2313-20169) |
| 템플릿 | [Building on templates](https://www.figma.com/design/7eHgyABjNbCL1fVzpbZ1IX?node-id=169-12991) | [Building on templates](https://www.figma.com/design/aFam9mIsTVZqNmKdHHYq0f?node-id=3-84) |
| 간격 가이드 | [Page Spacing](https://www.figma.com/design/7eHgyABjNbCL1fVzpbZ1IX?node-id=480-34034) | [Page Spacing](https://www.figma.com/design/aFam9mIsTVZqNmKdHHYq0f?node-id=198-44524) |

## 팀 기준 (2026-11 합의)

- **모바일은 iOS 375 기준**으로만 그려요. AOS 화면은 따로 치지 않아요.
- **PC는 1440 기준**으로 그려요. 1200·2000은 **꼭 필요한 화면만** 추가로 쳐요.
- **디자인 시스템에서 시작**하고, 빌더에서는 주로 **상품·매장 썸네일**을 가져와요. 빌더 골격 블록(`B-`)은 필요할 때만 써요.
- 색·텍스트·그림자는 값을 직접 넣지 않고 **스타일을 연결**해요.
- 디자인 시스템 컴포넌트는 **해제하지 않아요.** `B-` 빌더 블록은 해제해도 돼요.
- 이름 앞 `★`는 개발 협의 후 시스템 등록 대기, `❤︎`는 디자인팀 내부용 커스텀이에요.

## 문서

| 문서 | 내용 |
|---|---|
| [00-workflow](docs/00-workflow.md) | 작업 절차: A. as-is 수정 / B. 신규 화면, 조립 순서, Figma 작업 팁 |
| [01-screen-standards](docs/01-screen-standards.md) | 라이브러리 4개, 화면 폭·그리드·여백 |
| [02-foundations](docs/02-foundations.md) | 색·글자·라운드·그림자 스타일, 표기 규칙 |
| [03-components-ds](docs/03-components-ds.md) | 디자인 시스템 컴포넌트 이름 규칙, 버튼·칩·태그·폼·모달 규칙 |
| [04-components-mobile](docs/04-components-mobile.md) | 모바일 빌더: 썸네일·카드, 골격 블록(필요할 때만) |
| [05-components-pc](docs/05-components-pc.md) | PC 빌더: 썸네일·카드, 표, 푸터 |
| [06-templates](docs/06-templates.md) | 화면 유형별 배치·여백 참고 |
| [07-states-checklist](docs/07-states-checklist.md) | 상태 화면 체크리스트 |
| [08-audit](docs/08-audit.md) | 그린 뒤 검수 (하드코딩 색·글자, 해제, 다른 라이브러리) |
| [prompts](docs/prompts.md) | Claude에게 요청하는 문장 예시 |

## Claude로 쓰는 법 (채팅)

**처음 한 번: 프로젝트 만들기** (한 사람이 만들어 팀에 공유)
1. Claude에서 프로젝트를 만들어요. 예: "신상마켓 화면 제작"
2. 프로젝트 지식에 이 GitHub 저장소를 연결해요. 저장소를 고치면 프로젝트에도 반영돼요.
3. 프로젝트 지침에 [CLAUDE.md](CLAUDE.md) 내용을 붙여 넣어요.

**작업할 때**
1. 그 프로젝트에서 새 대화를 열어요.
2. [prompts](docs/prompts.md)의 문장에 Figma 링크만 바꿔서 요청해요.
3. Claude가 변경표나 화면 목록을 먼저 보여주면 확인해 주세요. 확인 뒤에 그려요.

**준비물**
- Claude에 **Figma 연결** (그릴 파일 편집 권한 필요)
- 신상마켓 라이브러리 4개 접근 권한
- 이 저장소 접근 권한 (비공개 저장소라 초대 필요)

## 기준을 바꿀 때

1. 해당 `docs/` 파일을 고쳐요.
2. [CHANGELOG.md](CHANGELOG.md) 맨 위에 한 줄 남겨요.
3. Claude 규칙이 바뀌면 [CLAUDE.md](CLAUDE.md)와 프로젝트 지침도 같이 고쳐요.
4. Figma 링크는 이 README 바로가기와 [01-screen-standards](docs/01-screen-standards.md) 두 곳만 고치면 돼요.
