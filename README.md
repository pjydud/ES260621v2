# 스페인어 30일 PWA

GitHub + Vercel 배포용 정적 PWA입니다.

## 파일 구조

저장소 최상단에 아래 파일을 그대로 업로드하세요.

```text
index.html
data.js
manifest.json
sw.js
icon-192.png
icon-512.png
README.md
test.html
```

## 배포 방법

1. GitHub 새 저장소 생성
2. 위 파일들을 폴더 없이 저장소 최상단에 업로드
3. Vercel에서 해당 저장소 연결
4. 배포 완료 후 `/test.html`로 접속해 데이터 확인
5. 정상 확인 후 `/index.html` 또는 기본 주소로 사용

## 앱 구성

- 30일 날짜 선택
- 매일 단어 24개
- 총 단어 720개
- 단어별 예문 포함
- 문법 30일 과정
- 실생활 문장 하루 5개
- 단어 뜻 퀴즈 20문제
- 오프라인 캐시 지원
- 모바일 홈화면 설치 가능
