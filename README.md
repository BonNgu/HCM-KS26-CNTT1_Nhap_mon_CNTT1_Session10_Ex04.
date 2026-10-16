# 🌱 Mô hình IPO trong trang trại thông minh

> **IPO** giống như việc nấu cơm: bạn cho **gạo và nước vào**, nồi **nấu**, rồi cho ra **cơm chín**.

## 1. Ba thành phần của IPO

- **Input (đầu vào):** thông tin hệ thống nhận được, ví dụ độ ẩm đất đo bằng cảm biến.
- **Process (xử lý):** bước "suy nghĩ" của hệ thống, so sánh thông tin với mức mong muốn rồi ra quyết định.
- **Output (đầu ra):** hành động hệ thống thực hiện, ví dụ bật hoặc tắt máy bơm.

## 2. Ví dụ: hệ thống tưới cây tự động

| 📥 Input | ⚙️ Process | 📤 Output |
|---|---|---|
| Cảm biến báo độ ẩm đất là 30% | Bộ điều khiển so sánh: 30% thấp hơn mức cần là 60% | Máy bơm bật, tưới nước cho cây |
| Cảm biến báo độ ẩm đất là 65% | Bộ điều khiển so sánh: 65% đã đủ | Máy bơm tắt |

**Luồng hoạt động:**

`Độ ẩm đất → So sánh với mức cần → Bật/tắt máy bơm`

## 3. Tự kiểm tra

- [ ] **Câu 1:** Trong ví dụ trên, "cảm biến độ ẩm" thuộc thành phần nào?
  *Gợi ý: nó cung cấp thông tin cho hệ thống.*
- [ ] **Câu 2:** Nếu trời mưa và độ ẩm đất lên 80%, **Output** sẽ là gì?
  *Gợi ý: hệ thống thấy đất đã đủ nước.*

---

<details>
<summary>Đáp án gợi ý</summary>

1. Thuộc **Input** (đầu vào).
2. Máy bơm **tắt** (hoặc giữ nguyên trạng thái tắt).

</details>
