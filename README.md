# Aetos Catalog

Aetos 제품군의 공개 버전 Catalog입니다.

제품 Metadata와 Release BOM은 Private Repository인 `KLIC-Aetos`에서 관리하고, 이 Repository에는 외부에 공개할 Catalog 결과만 게시합니다.

## 게시 흐름

```text
KLIC-Aetos
  -> Catalog 생성
  -> Aetos-Catalog에 공개 산출물 전달
  -> main 브랜치 Push
  -> GitHub Pages 자동 게시
```

## 공개 정보

- 제품명과 역할
- Aetos 제품 버전
- Release 상태
- 지원 호환성
- 공개 가능한 Commit Revision

인증정보, 고객 정보, 내부 Patch 내용은 이 Repository에 게시하지 않습니다.

## GitHub Pages 설정

Repository Settings의 Pages에서 다음을 선택합니다.

```text
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

`index.html`이 Repository 최상위에 있으므로 별도 빌드 과정이 필요하지 않습니다.
