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
- `is`
  - `Number.isInteger` : *kiểm tra số nguyên*
  - `isNaN` : *kiểm tra có phải số không*

---

## Chuỗi

Một số thuộc tính thường dùng : 

- `length` : *độ dài chuỗi*
- `Find Index` :
  - `indexOf` : *vị trí của từ đầu tiên tìm được*
  - `lastindexOf` : *vị trí từ cuối cùng tìm được*
- `slice` : *cắt chữ tại vị trí nào đó*
- `replace` : *thay thế chữ này thành chữ kia trong chuỗi*
- `Convert`
  - `toUpperCase` : *biến chuỗi thành in hoa*
  - `toLowerCase` : *biến chuỗi thành in thường*
- `trim` : *loại bỏ khoảng trắng dư thừa trong chuỗi*
- `split` : *biến chuỗi thành mảng thông qua ký tự lặp lại*
- `charAt` : *trả về ký tự tại vị trí trong chuỗi*

---

## Số

Một số thuộc tính thường dùng 

- `toString` : *biến số thành chuỗi*
- `toFixed` : *làm tròn số theo quy tắc làm tròn*
- `parseInt` : *biến thành số nguyên*

---

## Mảng

Một số thuộc tính thường dùng : 

- `toString` : *biến mảng thành chuỗi*
- `join` : *biến mảng thành chuỗi có thêm dấu ngăn cách*
- `pop` :  *xoá và trả về 1 phần tử cuối mảng*
- `push` : *thêm 1 hoặc nhiều phần tử lên cuối mảng*
- `shift` :  *xoá và trả về 1 phần tử đầu mảng*
- `unshift` : *thêm 1 hoặc nhiều phần tử lên đầu mảng*
- `splice` :  *xoá và chèn thêm phần tử vào mảng*
- `concat` : *nối 2 mảng lại với nhau*
- `slice` : *cắt phần tử trong mảng*