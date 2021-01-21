# Javascript demo

## Cách sử dụng javascript trong HTML

Có 2 cách : 

- Viết code `Javascript` trong thẻ `<script></script>`

```html
<body>
<script>alert("code js")</script>
</body>
```

- Viết code `Javascript` trong file `main.js` rồi trỏ vào `HTML` :

```html
<script src="./main.js"></script>
```

---

## Khai báo biến

Sữ dụng `var` hoặc `let` để khai báo tên biến, nó sẽ tự nhận biết tên biến

> Khuyết khích sử dụng `let`, và sử dụng đặt tên biến bằng quy tắc camelCase

```javascript
let fulllName = "Le Tuan Kiet";
let age = 18;
let isMen = true;
```

---

## Comment

Có 2 cách :

- Ghi chú một dòng bằng `//`
- Ghi chú nhiều dòngb ằng `/**/`

---

## Một số hàm built-in

- `alert` : *hiển thị thông báo chỉ có* **OK**
- `console` : *hiển thị thông báo trong khung console, gồm 3 thuộc tính phổ biến*
  - `console.log` : *hiển thị mọi kiểu dữ liệu*
  - `console.warn` : *hiển thị mọi kiểu dữ liệu dạng* **warning**
  - `console.error` : *hiển thị mọi kiểu dữ liệu dạng* **error**
- `confirm` : *hiển thị thông báo tuỳ chọn* **OK** và **Cancel**
- `prompt` : *hiển thị thông báo yêu cầu nhập*
- `setTimeout` : *chạy code sau 1 khoản thời gian ms*
- `Set interval` : *chạy code liên tục sau 1 khoảng thời gian ms*


