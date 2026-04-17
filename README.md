# FX Manuals Repository

이 저장소는 일렉기타/베이스 멀티이펙터 문서를 **브랜드 > 기종** 단위로 정리하기 위한 개인용 아카이브입니다.

## 목적
- 영문 매뉴얼(`manual.en.md`)과 한글 매뉴얼(`manual.ko.md`)을 함께 관리
- 기종별 핵심 정보(특징, 스펙, 시세, 후기 요약)를 `summary.md` 한 곳에 통합
- 추후 GitHub Pages 등 프론트엔드에서 Markdown 기반으로 쉽게 렌더링

## 폴더 구조
```text
fx-manuals-ko/
├─ README.md
├─ brands/
│  └─ <brand-slug>/
│     └─ <model-slug>/
│        ├─ manual.en.md
│        ├─ manual.ko.md
│        ├─ summary.md
│        └─ assets/
├─ _templates/
│  └─ model/
│     ├─ manual.en.md
│     ├─ manual.ko.md
│     └─ summary.md
└─ indexes/
   ├─ brands.md
   └─ models.md
```

## 네이밍 규칙
- 브랜드/기종 폴더: 소문자 `kebab-case`
- 예시: `line6/hx-stomp`, `boss/gt-1000core`

## 작성 규칙
- 기종당 필수 문서 3개만 유지
  - `manual.en.md`
  - `manual.ko.md`
  - `summary.md`
- 스펙/시세/후기 요약은 별도 파일로 분리하지 않고 `summary.md`에 통합

## 새 기종 추가 방법
1. `_templates/model` 폴더를 복사
2. 대상 위치를 `brands/<brand-slug>/<model-slug>/`로 이동
3. 내용 작성 후 `indexes/brands.md`, `indexes/models.md`에 링크 추가

## 사이트 전개(향후)
- 이 구조는 정적 사이트(Next.js, Astro, Vite + SSG)에서 매우 다루기 좋습니다.
- `brands/**/summary.md`를 콘텐츠 소스로 읽어 목록/상세 페이지를 자동 생성하기 쉽습니다.

## Markdown 데이터 설계(권장)
- `summary.md` 상단에 YAML frontmatter 유지
- 프론트에서 사용할 핵심 키: `brand`, `model`, `category`, `release_year`, `status`, `last_updated`
- 본문은 사람이 읽기 좋은 설명, frontmatter는 사이트 필터/정렬용 메타데이터로 사용
