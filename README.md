# DUOBLADE 웹 제안서

수의병원 현장을 위한 저온 안전 전기수술 솔루션 **DUOBLADE** 웹 제안서입니다.
오름㈜ × ㈜크레센.

모바일 우선(mobile-first) 반응형 단일 페이지로 제작되었습니다.

## 구성

```
├── index.html            # 웹 제안서 (HTML/CSS/JS 단일 파일)
└── assets/
    └── images/
        ├── hero.png      # 메인 히어로 배너
        ├── device-or.png # 수술실 사용 이미지
        └── lineup.png    # 제품 4종 라인업
```

## 로컬에서 보기

`index.html` 파일을 브라우저로 바로 열면 됩니다.
또는 간단한 정적 서버로:

```bash
npx serve .
```

## GitHub Pages 배포

1. 이 저장소에 푸시합니다.
2. GitHub → **Settings → Pages**
3. **Source: Deploy from a branch** → Branch: `main` / 폴더: `/(root)` 선택 후 저장
4. 잠시 후 `https://value-oreum.github.io/Duoblade/` 에서 공개됩니다.

## Vercel 배포

- Framework Preset: `Other`
- Build Command: 비움
- Output Directory: 비움

## 문의

공급문의 · 오름㈜ — 채형원 이사
📞 010-2675-0418 · ✉️ narrsis01@gmail.com
