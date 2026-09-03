# DungeonCopilot 요청 폼 테스트

`microsoft/DungeonCopilot`에 적용하기 전에 GitHub Issue Forms 화면을 직접 눌러보기 위한 테스트 저장소입니다.

## 눌러볼 곳

https://github.com/ltnalsxl/DungeonCopilot-issue-form-test/issues/new/choose

## 담긴 것

| 파일 | 폼 | 라벨 |
|---|---|---|
| `.github/ISSUE_TEMPLATE/01-typo.yml` | 오타 수정 | `typo` |
| `.github/ISSUE_TEMPLATE/02-feature.yml` | 기능 요청 / 개선 제안 | `enhancement` |
| `.github/ISSUE_TEMPLATE/03-region.yml` | 지역 데이터 추가 | `region` |
| `.github/ISSUE_TEMPLATE/config.yml` | 빈 이슈 차단, 고객 후기 폼 링크 | - |

`config.yml`의 고객 후기 링크는 Microsoft Forms 주소가 정해지면 바꿔 넣으면 됩니다.

## 확인할 것

- 유형 선택 화면에 카드 세 장이 뜨는지
- 필수 항목을 비우면 제출이 막히는지
- 캡처 이미지를 칸에 붙여넣으면 올라가는지
- 제출한 이슈에 라벨이 자동으로 붙는지
