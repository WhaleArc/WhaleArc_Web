# 레포 두 개로 나누기 (WhaleArc_Web / WhaleArc_App)

웹과 앱을 **별도 레포**로 쓰려면 아래 순서대로 하세요.

---

## 1. GitHub에서 레포 두 개 만들기

1. **https://github.com/WhaleArc** (팀 페이지) 접속
2. **Repositories** → **New repository**
3. **WhaleArc_Web** 이름으로 생성 (README 추가 안 함) → Create
4. 다시 **New repository** → **WhaleArc_App** 이름으로 생성 → Create

---

## 2. WhaleArc_Web 푸시 (지금 만든 웹 코드)

```bash
cd /Users/hanyang/Desktop/whaleArc/WhaleArc_Web
git remote add origin git@github.com:WhaleArc/WhaleArc_Web.git
git push -u origin main
```

---

## 3. WhaleArc_App 푸시

```bash
cd /Users/hanyang/Desktop/whaleArc/WhaleArc_App
git remote add origin git@github.com:WhaleArc/WhaleArc_App.git
git push -u origin main
```

---

## 폴더 위치

| 위치 | 내용 |
|------|------|
| `whaleArc/WhaleArc_Web/` | 웹 레포용 (frontend + backend + images) — **WhaleArc_Web** 에 푸시 |
| `whaleArc/WhaleArc_App/` | 앱 레포용 (placeholder) — **WhaleArc_App** 에 푸시 |

이후 웹 작업은 **WhaleArc_Web** 레포에서, 앱 작업은 **WhaleArc_App** 레포에서 하면 됩니다.
