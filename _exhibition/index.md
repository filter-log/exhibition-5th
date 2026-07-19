---
title: 언젠가 가겠지 푸르른 이 청춘
slug: exhibition-5th
dates: 2026.08.11 - 2026.08.13
venue: 미정
tagline: 필링이들의 다섯 번째 이야기
poster_image: /assets/exhibition/poster-template.svg
hero_alt: Filter Spring Exhibition poster
cms_url: https://app.pagescms.org/filter-log/exhibition-5th/main
public_url: https://filter-log.github.io/exhibition-5th
---
`exhibition-template`는 새로운 전시회 저장소를 빠르게 시작하기 위한 기본 아카이브다. 상단의 포스터와 설명, 하단의 썸네일 타일, 작가 목록, 업로드 UI, Pages CMS, GitHub Actions 후처리 파이프라인이 하나의 저장소 안에서 함께 동작하도록 설계했다.

새 전시회를 만들 때는 이 파일 하나만 수정하면 `_config.yml`, `assets/js/config.js`, `_exhibition/index.md`가 자동으로 맞춰진다. 작품과 작가 데이터는 각각 컬렉션 파일로 분리되어 있어서 Pages CMS와 Worker 업로드가 같은 마크다운 구조를 공유한다.
