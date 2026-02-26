---
title: "Markdown 작성 가이드"
date: 2026-02-26
categories:
  - blog
tags:
  - markdown
  - guide
toc: true
toc_sticky: true
---

Jekyll 블로그에서 자주 사용하는 Markdown 문법을 정리합니다.

## 텍스트 서식

**굵게**, *기울임*, ~~취소선~~, `인라인 코드`

## 목록

- 첫 번째 항목
- 두 번째 항목
  - 하위 항목

1. 순서 있는 목록
2. 두 번째 항목

## 코드 블록

```python
def hello():
    print("Hello, World!")
```

## 인용문

> 좋은 코드는 그 자체로 최고의 문서다.
> — Steve McConnell

## 표

| 항목 | 설명 |
|------|------|
| Jekyll | 정적 사이트 생성기 |
| Markdown | 경량 마크업 언어 |
| GitHub Pages | 무료 호스팅 서비스 |

## 이미지

이미지는 `assets/images/` 폴더에 넣고 아래처럼 사용합니다:

```markdown
![alt text](/assets/images/filename.png)
```

## 링크

[Minimal Mistakes 공식 문서](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)