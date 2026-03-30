# 🔤 fonts-CDN

> 웹폰트 CDN 저장소

[![jsdelivr](https://img.shields.io/badge/CDN-jsDelivr-orange?style=flat-square&logo=jsdelivr)](https://www.jsdelivr.com/)
[![GitHub](https://img.shields.io/badge/GitHub-incamel-black?style=flat-square&logo=github)](https://github.com/incamel/fonts-CDN)

---

## 📦 사용법

`<head>` 안에 한 줄만 추가하면 모든 폰트를 사용할 수 있습니다.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/incamel/fonts-CDN@main/fonts.css">
```

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

/* 일본어 */
font-family: 'Noto Sans JP', sans-serif;
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
https://cdn.jsdelivr.net/gh/incamel/fonts-CDN@main/fonts.css
```

---

<p align="center">
  <sub>Maintained by rararayup/sub>
</p>
