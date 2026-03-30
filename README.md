# 🔤 fonts-CDN

> 웹폰트 CDN 저장소

[![jsdelivr](https://img.shields.io/badge/CDN-jsDelivr-orange?style=flat-square&logo=jsdelivr)](https://www.jsdelivr.com/)
[![GitHub](https://img.shields.io/badge/GitHub-rararayup-black?style=flat-square&logo=github)](https://github.com/rararayup/fonts-CDN)

---

## 📦 사용법

### ✅ 방법 1. `<head>` 에 직접 추가

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rararayup/fonts-CDN@main/fonts.css">
```

---

### ✅ 방법 2. `reset.scss` 상단에 추가 (권장)

```scss
// reset.scss 최상단
@import url('https://cdn.jsdelivr.net/gh/rararayup/fonts-CDN@main/fonts.css');

// 이후 reset 스타일
*, *::before, *::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
// ...
```

> ⚠️ `@import url()` 은 반드시 파일 **최상단**에 위치해야 합니다.

---

### ✅ 방법 3. 그누보드 `head.php` / `_head_sub.php` 에 추가

**메인페이지 (`head.php`)**
```php
add_stylesheet('<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rararayup/fonts-CDN@main/fonts.css">', 0);
```

**서브페이지 (`_head_sub.php`)**
```php
add_stylesheet('<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rararayup/fonts-CDN@main/fonts.css">', 0);
```

> 💡 `add_stylesheet()` 의 두 번째 인자 `0` 은 출력 순서로, 숫자가 작을수록 먼저 로드됩니다.

---

## 🗂 포함된 폰트 목록

### 🇰🇷 한국어

| 폰트 | 종류 | font-family |
|------|------|-------------|
| Pretendard | Sans-serif | `'Pretendard'` |
| Noto Sans KR | Sans-serif | `'Noto Sans KR'` |
| Noto Serif KR | Serif | `'Noto Serif KR'` |

### 🇯🇵 일본어

| 폰트 | 종류 | font-family |
|------|------|-------------|
| Noto Sans JP | Sans-serif | `'Noto Sans JP'` |
| Noto Serif JP | Serif | `'Noto Serif JP'` |

### 🇨🇳 중국어

| 폰트 | 종류 | font-family |
|------|------|-------------|
| Noto Sans SC | Sans-serif (간체) | `'Noto Sans SC'` |
| Noto Sans TC | Sans-serif (번체) | `'Noto Sans TC'` |

### 🔤 영문

| 폰트 | 종류 | font-family |
|------|------|-------------|
| The Seasons | Serif (자체 서버) | `'The Seasons'` |
| Playfair Display | Serif | `'Playfair Display'` |
| Cormorant Garamond | Serif | `'Cormorant Garamond'` |
| Montserrat | Sans-serif | `'Montserrat'` |
| Lato | Sans-serif | `'Lato'` |

---

## 💻 CSS 사용 예시

```css
/* 한국어 기본 */
font-family: 'Pretendard', sans-serif;

/* 한국어 세리프 */
font-family: 'Noto Serif KR', serif;

/* 영문 고급 세리프 */
font-family: 'The Seasons', serif;
font-family: 'Playfair Display', serif;
font-family: 'Cormorant Garamond', serif;

/* 일본어 */
font-family: 'Noto Sans JP', sans-serif;

/* 중국어 간체 */
font-family: 'Noto Sans SC', sans-serif;

/* 중국어 번체 */
font-family: 'Noto Sans TC', sans-serif;
```

---

## 📁 저장소 구조

```
fonts-CDN/
├── the-seasons/
│   ├── the-seasons-regular.woff2
│   ├── the-seasons-bold.woff2
│   └── the-seasons-italic.woff2
├── fonts.css
└── README.md
```

---

## 🔗 CDN 주소

```
https://cdn.jsdelivr.net/gh/rararayup/fonts-CDN@main/fonts.css
```

---

<p align="center">
  <sub>Maintained by rararayup</sub>
</p>
