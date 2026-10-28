# 롱이 화면 둘러보기

홈에서 학습을 시작하고, 단어,문장 배열을 연습한 뒤 복습으로 이어지는 화면을 모았습니다. 대표 이미지는 라이트 모드이며, 주요 화면의 다크 모드도 함께 볼 수 있습니다.

[홈과 목표](#home) | [단어 학습](#words) | [패턴 학습](#patterns) | [설정](#settings) | [다크 모드](#themes)

<a id="home"></a>

## 홈과 일일 학습 목표

| 홈 | 일일 목표 변경 |
| --- | --- |
| <img src="screenshots/light/01-home.png" alt="오늘 학습량과 목표 달성률을 확인하는 라이트 모드 홈" width="320"> | <img src="screenshots/light/02-daily-goal.png" alt="하루 목표 챕터 수를 선택하는 바텀 시트" width="320"> |

오늘의 학습량과 연속 학습 일수, 목표 달성률을 확인하고 단어,패턴 학습을 시작합니다. 목표 변경은 바텀 시트에서 처리합니다. 홈의 숫자는 촬영용 에뮬레이터의 로컬 학습 기록입니다.

<a id="words"></a>

## HSK 단어 학습

| 레벨,챕터 선택 | 단어 카드와 예문 |
| --- | --- |
| <img src="screenshots/light/04-hsk-levels.png" alt="레벨과 챕터를 펼쳐 선택하는 화면" width="320"> | <img src="screenshots/light/05-word-study.png" alt="뜻과 번역을 펼친 단어 카드와 노란색 단어 강조" width="320"> |

HSK 레벨과 챕터를 골라 단어를 학습합니다. 카드를 누르면 뜻과 예문 번역이 나타나며, 예문 속 학습 단어는 파스텔 노란색으로 강조합니다.

| 학습 완료 | 선택한 단어 복습 |
| --- | --- |
| <img src="screenshots/light/06-study-complete.png" alt="학습한 단어 수와 다시 볼 단어 목록을 표시하는 완료 화면" width="320"> | <img src="screenshots/light/07-word-review.png" alt="완료 화면에서 다시 볼 단어만 선택해 복습하는 화면" width="320"> |

`다시 볼래요`로 표시한 단어를 완료 화면에 모아 보여주고, 복습하기를 누르면 해당 단어만 다시 학습합니다. 단어 학습은 별도 객관식 채점 대신 사용자의 다시 보기 선택을 기준으로 기록합니다.

<a id="patterns"></a>

## 문장 패턴 학습

| 패턴 선택 | 문제 시작 |
| --- | --- |
| <img src="screenshots/light/08-pattern-list.png" alt="패턴 제목과 뜻, 레벨, 문제 수를 확인하는 목록" width="320"> | <img src="screenshots/light/09-pattern-study.png" alt="왼쪽 강조선의 패턴 제목과 큰 한국어 뜻을 보여주는 화면" width="320"> |

학습할 패턴과 뜻을 확인한 뒤 한국어 문제 문장에 맞게 중국어 조각을 드래그합니다. 패턴 이름과 한국어 문제는 역할에 따라 강조 방식을 구분했습니다.

| 문장 배열 | 오답 제출 |
| --- | --- |
| <img src="screenshots/light/10-pattern-arranged.png" alt="기준 순서대로 조각을 모두 배치한 상태" width="320"> | <img src="screenshots/light/15-pattern-incorrect.png" alt="다른 순서로 조각을 배치해 오답을 제출한 상태" width="320"> |

서버 채점을 우선 사용하며 네트워크 연결 실패에서는 문제의 기준 순서로 로컬 채점합니다. 일반 API 오류를 로컬 채점으로 덮어쓰지는 않습니다. 오답이면 조각을 다시 배열하거나 `오답노트로`를 선택할 수 있습니다.

| 오답이 있는 완료 | 모두 정답인 완료 |
| --- | --- |
| <img src="screenshots/light/11-pattern-complete.png" alt="완료 화면에서 실제 제출한 내 배열과 정답을 펼쳐 비교" width="320"> | <img src="screenshots/light/16-pattern-all-correct.png" alt="정답 후 복습 버튼 없이 학습을 마치는 완료 화면" width="320"> |

오답노트는 사용자가 선택한 문제를 복습 대상으로 모읍니다. 완료 화면에서는 내 답과 기준 답을 펼쳐 비교하며, 복습 버튼으로 해당 문제를 다시 풉니다. 모두 정답이면 복습 버튼 없이 마칩니다.

라이트 모드 오답 완료 화면은 실제 오답을 제출한 사례이며, 모두 정답 화면은 같은 문제를 복습에서 맞힌 후 촬영했습니다. 다크 모드 오답 화면은 답 제출 없이 오답노트로 보낸 사례이므로 내 답에 `-`가 표시됩니다.

<a id="settings"></a>

## 설정과 저장 공간

| 설정 | 삭제 범위 선택 |
| --- | --- |
| <img src="screenshots/light/03-settings.png" alt="System Light Dark 화면 모드와 앱 버전 및 캐시 용량을 표시하는 설정" width="320"> | <img src="screenshots/light/12-cache-delete-dialog.png" alt="단어 패턴 학습 데이터를 구분해 삭제 범위를 선택하는 시트" width="320"> |

System,Light,Dark 모드를 선택할 수 있습니다. 캐시는 단어,예문과 패턴 콘텐츠를 구분하고, 학습 기록은 별도의 선택 항목으로 표시합니다. 삭제 시트는 선택 화면만 촬영했으며 데이터를 삭제하지 않았습니다.

<a id="themes"></a>

## 라이트,다크 모드 비교

<details>
<summary>주요 6개 화면의 라이트,다크 비교 펼치기</summary>

### 홈

| 라이트 | 다크 |
| --- | --- |
| <img src="screenshots/light/01-home.png" alt="홈 라이트 모드" width="320"> | <img src="screenshots/dark/01-home.png" alt="홈 다크 모드" width="320"> |

### 단어 카드

| 라이트 | 다크 |
| --- | --- |
| <img src="screenshots/light/05-word-study.png" alt="단어 카드 라이트 모드" width="320"> | <img src="screenshots/dark/05-word-study.png" alt="단어 카드 다크 모드" width="320"> |

### 패턴 목록

| 라이트 | 다크 |
| --- | --- |
| <img src="screenshots/light/08-pattern-list.png" alt="패턴 목록 라이트 모드" width="320"> | <img src="screenshots/dark/08-pattern-list.png" alt="패턴 목록 다크 모드" width="320"> |

### 패턴 문제

| 라이트 | 다크 |
| --- | --- |
| <img src="screenshots/light/09-pattern-study.png" alt="패턴 문제 라이트 모드" width="320"> | <img src="screenshots/dark/09-pattern-study.png" alt="패턴 문제 다크 모드" width="320"> |

### 오답 상세

| 라이트 | 다크 |
| --- | --- |
| <img src="screenshots/light/11-pattern-complete.png" alt="오답 상세 라이트 모드" width="320"> | <img src="screenshots/dark/11-pattern-complete.png" alt="오답 상세 다크 모드" width="320"> |

### 설정

| 라이트 | 다크 |
| --- | --- |
| <img src="screenshots/light/03-settings.png" alt="설정 라이트 모드" width="320"> | <img src="screenshots/dark/03-settings.png" alt="설정 다크 모드" width="320"> |

</details>

## 촬영 기준

2026-10-28에 `0.0.8(104)`를 Android 에뮬레이터에서 실행해 촬영했습니다. 최신 화면은 라이트 14장,다크 6장이며, 캡처 조건과 확인한 학습 흐름은 [검증 기록](../docs/04-verification.md)에 정리했습니다.

<a id="legacy"></a>

</details>

[서비스 소개](../README.md) | [현재 구현](../docs/03-implementation.md) | [검증 기록](../docs/04-verification.md)
