# The Way Company — 사진 전용 공개 저장소

이메일·카드뉴스에 들어가는 **사진(이미지)만** 올리는 곳입니다.
여기 올린 사진은 인터넷 주소(URL)가 생겨서, 이메일(Brevo)에서도 잘 보입니다.

> ⚠️ **이 저장소는 공개(Public)입니다.**
> 사진 외의 것(문서, 회사 내부 자료, 비밀번호 등)은 절대 올리지 마세요.

---

## 폴더 구조

```
email/                  → 이메일용 사진
  common/               → 로고 등 공통 사진 (항상 재사용)
  {YYYY-MM}-{캠페인명}/  → 그 달 캠페인 사진 (예: 2026-07-brazil-mobility)
card/                   → 카드뉴스용 사진
  {폴더명}/
```

## 사진 올리는 방법 (컴퓨터에서)

1. 이 저장소 페이지에서 원하는 폴더(예: `email/common`)를 클릭해 들어갑니다.
2. 오른쪽 위 **Add file → Upload files** 버튼을 누릅니다.
3. 사진 파일을 끌어다 놓고, 아래 초록색 **Commit changes** 버튼을 누릅니다.

## 파일 이름 규칙

- **영문 소문자, 숫자, 하이픈(-)만** 사용합니다. 한글·공백 금지.
- 예: `logo-black.png`, `poster-2026-08.png`, `header-2026-07.png`

## 사진 주소(URL) 형식

올린 사진은 1~2분 뒤 아래 주소로 볼 수 있습니다:

```
https://marketing-thewaycompany.github.io/-thewaycompany-assets/email/{폴더명}/{파일명}
https://marketing-thewaycompany.github.io/-thewaycompany-assets/card/{폴더명}/{파일명}
```
