# 🍲 Esther House Food Market

> 우거지 해장국 공동구매 페이지

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://if-end.github.io/Esther-House)

---

## 📌 공구 안내

| 항목 | 내용 |
|------|------|
| 상품 | 우거지 해장국 |
| 최소 수량 | 10인분 이상 |
| 결제 방법 | 계좌이체 (마감 후 안내) |
| 배송 | 공동 수령 또는 개별 택배 |

---

## 🛒 신청 방법

1. [공구 페이지](https://if-end.github.io/Esther-House) 접속
2. 이름 / 연락처 / 메뉴 / 수량 입력
3. **신청 등록하기** 버튼 클릭
4. 마감 후 입금 안내 연락 드립니다

---

## 📁 파일 구조

```
Esther-House/
└── index.html   # 공구 신청 페이지 (GitHub Pages)
```

---

## ⚙️ 설정 변경 (운영자용)

`index.html` 하단 `<script>` 상단 값을 수정하세요.

```js
const DEADLINE = new Date('2025-07-05T23:59:59'); // 마감일
const MAX_PARTICIPANTS = 30;                        // 최대 인원
```

메뉴 및 가격은 `<select id="f-menu">` 항목과 `PRICE_MAP` 객체를 함께 수정하세요.

---

## 📞 문의

카카오톡 오픈채팅으로 문의해주세요.
