# JournalReview

심혈관 임상시험 논문(LODESTAR, RACING) 저널리뷰 발표자료를 관리하는 저장소입니다.
Quarto(`.qmd`)로 작성하고 Reveal.js HTML 슬라이드로 렌더링합니다.

## Contents

- `docs/LODESTAR/`: LODESTAR 발표자료
  - `index.qmd`: 슬라이드 원본
  - `index.html`: 렌더 결과
- `docs/RACING/`: RACING 발표자료
  - `index.qmd`: 슬라이드 원본
  - `index.html`: 렌더 결과

## What This Repo Is For

- 논문 핵심 내용을 발표용 슬라이드로 구조화
- 배경, 방법, 결과, 한계, 임상적 의미를 한 번에 리뷰
- Figure/Table 이미지를 포함한 최종 발표 산출물 보관

## How to Use

1. 각 폴더의 `index.html`을 열어 발표자료를 확인합니다.
2. 수정이 필요하면 `index.qmd`를 편집합니다.
3. Quarto로 다시 렌더링해 `index.html`을 갱신합니다.

## Notes

- 이 저장소는 원자료 분석 코드 중심이 아니라 발표자료 중심입니다.
- trial별 슬라이드 스타일과 구성은 독립적으로 관리합니다.
