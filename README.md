<img src="assets/portfolio-header.svg" width="100%" alt="yoonseo — 게임과 일상의 작은 상호작용을 만듭니다" />

게임의 선택, 하루의 기록, 대화의 흐름을 코드로 구현합니다.<br>
직접 만든 화면과 소스에서 확인할 수 있는 구현을 중심으로 프로젝트를 소개합니다.

[대표 게임](#고백은-세이브-로드가-없다) · [웹 프로젝트](#웹-프로젝트) · [Android](#android) · [사용한 기술](#프로젝트에서-사용한-기술)

## 고백은 세이브 로드가 없다

**미니게임의 결과가 능력치가 되고, 만남의 선택이 엔딩으로 이어지는 Win32 비주얼노벨**

<a href="https://github.com/yoon778/26_WinAPI_No_Save_Love_Project">
  <img src="assets/no-save-love.png" width="100%" alt="고백은 세이브 로드가 없다의 노래연습 리듬게임 화면" />
</a>

<sub>프로젝트의 기존 발표·튜토리얼에 쓰인 게임 화면. 새로 촬영한 화면은 아닙니다.</sub>

`C++` `Win32 API` `GDI / GDI+`

- PC방 알바·노래연습·등교길·유혹피하기, 네 가지 미니게임을 이야기 안에 연결
- 미니게임 결과와 인물 선택을 반영하는 7개 엔딩
- 장면 전환, 입력 분배, 화면 버퍼 재사용을 구현한 게임 구조
- 리듬게임에서 실제 창의 위치가 움직이는 연출

[게임과 구현 살펴보기 →](https://github.com/yoon778/26_WinAPI_No_Save_Love_Project) · [팀 역할과 화면 출처](https://github.com/yoon778/26_WinAPI_No_Save_Love_Project/blob/main/docs/CREDITS.md)

## 웹 프로젝트

<table>
  <tr>
    <th width="50%">기특해 · 칭찬일기</th>
    <th width="50%">말사이 · 대화 연습</th>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/yoon778/giteukhae"><img src="assets/giteukhae.png" height="300" alt="기특해의 오늘 기록과 칭찬 도장 화면" /></a></td>
    <td align="center"><a href="https://github.com/yoon778/mal-sai"><img src="assets/mal-sai.png" height="300" alt="말사이의 로컬 체험 모드 화면" /></a></td>
  </tr>
  <tr>
    <td>오늘 잘한 일 한 줄에 동물 친구가 칭찬 도장을 찍어주는 미니앱. 기록·달력·동물 성장·추억 카드로 작은 성취를 다시 돌아봅니다.</td>
    <td>상황을 고르고 AI와 대화한 뒤 힌트와 피드백으로 표현을 돌아보는 연습 앱. API 없이 살펴보는 로컬 체험 모드도 제공합니다.</td>
  </tr>
  <tr>
    <td><code>React</code> <code>TypeScript</code> <code>Apps in Toss</code><br/>기기 저장소 동기화, AI 응답 검증과 실패 대체 처리</td>
    <td><code>JavaScript</code> <code>Node.js</code> <code>SQLite</code><br/>대화 상태 관리, 역할별 AI 호출, 평가 시나리오</td>
  </tr>
  <tr>
    <td><a href="https://github.com/yoon778/giteukhae">화면 · 구현 · 실행 방법 →</a></td>
    <td><a href="https://github.com/yoon778/mal-sai">화면 · 구현 · 실행 방법 →</a></td>
  </tr>
</table>

<sub>기특해는 공개 저장소의 UI 캡처, 말사이는 AI 호출 없이 실행한 로컬 체험 화면입니다.</sub>

## Android

### [AutoMoney](https://github.com/yoon778/AutoMoney)

**금융 알림을 거래 기록으로 정리하는 Android 가계부 MVP**

`Kotlin` `Jetpack Compose` `Room` `Coroutines / Flow`

알림 파싱과 중복 판별, 수정 대기함, 월간 리포트와 예산 관리를 연결한 앱입니다.<br>
[현재 구현과 Android 실행 방법 →](https://github.com/yoon778/AutoMoney)

## 프로젝트에서 사용한 기술

| 영역 | 기술 | 구현을 확인할 프로젝트 |
| --- | --- | --- |
| Windows 게임 | C++, Win32 API, GDI/GDI+ | [고백은 세이브 로드가 없다](https://github.com/yoon778/26_WinAPI_No_Save_Love_Project) |
| 웹 미니앱 | React, TypeScript, Apps in Toss | [기특해](https://github.com/yoon778/giteukhae) |
| 웹 서버·AI 연동 | Node.js, SQLite, OpenAI API | [말사이](https://github.com/yoon778/mal-sai) |
| Android | Kotlin, Jetpack Compose, Room | [AutoMoney](https://github.com/yoon778/AutoMoney) |

---

[공개 저장소 둘러보기](https://github.com/yoon778?tab=repositories) · [화면 출처](assets/SOURCES.md)
