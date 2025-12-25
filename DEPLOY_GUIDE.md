# 🎄 2025 Christmas Tree 배포 가이드

## Created by Tsun Kim (김경한)

---

## 🌐 GitHub Pages로 무료 호스팅하기

### 1단계: GitHub 저장소 생성

1. https://github.com 접속 및 로그인
2. 우측 상단 `+` → `New repository` 클릭
3. Repository name: `christmas-tree-2025`
4. **Public** 선택
5. `Create repository` 클릭

### 2단계: 파일 업로드

#### 방법 A: 웹에서 직접 업로드
1. 생성된 저장소 페이지에서 `uploading an existing file` 클릭
2. 이 폴더의 모든 파일을 드래그 앤 드롭:
   - `index.html`
   - `c14773516089/` 폴더 (커서 파일들)
3. `Commit changes` 클릭

#### 방법 B: Git 명령어 사용
```bash
git remote add origin https://github.com/[사용자명]/christmas-tree-2025.git
git branch -M main
git push -u origin main
```

### 3단계: GitHub Pages 활성화

1. Repository 페이지 → `Settings` 탭
2. 좌측 메뉴에서 `Pages` 클릭
3. **Source**: `Deploy from a branch`
4. **Branch**: `main` 선택 → `/ (root)` 선택
5. `Save` 클릭

### 4단계: 사이트 접속

약 1-2분 후 아래 주소로 접속 가능:
```
https://[사용자명].github.io/christmas-tree-2025/
```

---

## 🚀 다른 무료 호스팅 옵션

### Netlify (추천)
1. https://netlify.com 접속
2. 회원가입 후 `Add new site` → `Deploy manually`
3. 폴더를 드래그 앤 드롭
4. 즉시 배포 완료! (랜덤 URL 제공)

### Vercel
1. https://vercel.com 접속
2. GitHub 연동 또는 직접 업로드
3. 자동 배포

### Surge (CLI)
```bash
npm install -g surge
surge
```

---

## 📱 공유하기

배포 후 받은 URL을 친구들에게 공유하세요!

예시:
- `https://tsunkim.github.io/christmas-tree-2025/`
- `https://christmas-2025.netlify.app/`

---

🎄 Merry Christmas 2025! 🎄
Created by **Tsun Kim (김경한 / KIM GYEONG HAN)**

