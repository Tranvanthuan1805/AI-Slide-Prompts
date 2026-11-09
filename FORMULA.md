# 🧩 Công Thức Xây Dựng Prompt Hiệu Quả

> Hiểu công thức này, bạn có thể tự tạo prompt cho BẤT KỲ chủ đề nào.

---

## 🎯 Công thức CRSCE

```
[Context] + [Role] + [Structure] + [Constraints] + [Examples]
```

| Thành phần | Ý nghĩa | Ví dụ |
|---|---|---|
| **Context** | Bối cảnh & mục tiêu | "Tôi cần thuyết trình 10 phút cho giám khảo cuộc thi khởi nghiệp..." |
| **Role** | AI đóng vai gì | "Bạn là chuyên gia thiết kế slide với 10 năm kinh nghiệm..." |
| **Structure** | Cấu trúc mong muốn | "Tạo outline 8 slide theo cấu trúc Problem → Solution → Market..." |
| **Constraints** | Giới hạn & yêu cầu | "Mỗi slide tối đa 30 chữ, tối thiểu 1 visual metaphor..." |
| **Examples** | Ví dụ tham khảo | "Phong cách tương tự TED Talk, không dùng bullet point dày đặc..." |

---

## 📐 Template công thức cơ bản

```
Vai trò: Bạn là [role] với chuyên môn về [domain].

Nhiệm vụ: Tạo [loại slide] về chủ đề "[topic]" cho [đối tượng khán giả].

Mục tiêu: Người xem cần [cảm nhận/hiểu/làm được gì] sau khi xem slide.

Cấu trúc: Tạo outline [n] slide theo thứ tự:
1. [Slide 1 — tên + mục tiêu]
2. [Slide 2 — tên + mục tiêu]
...

Yêu cầu visual: [màu sắc, phong cách, cảm xúc muốn truyền tải]

Giới hạn: [số chữ/slide, không dùng X, phải có Y]

Output: [Outline / Full content / Speaker notes / cả 3]
```

---

## 🔥 3 Lỗi Phổ Biến Khi Viết Prompt Slide

### ❌ Lỗi 1: Prompt quá ngắn và mơ hồ
```
BAD:  "Tạo slide về AI cho tôi"
GOOD: "Tạo slide thuyết trình 15 phút về ứng dụng AI trong giáo dục,
       dành cho sinh viên năm 2 chưa có nền tảng kỹ thuật, mục tiêu
       là khơi gợi hứng thú và cung cấp 3 tool AI họ có thể dùng ngay"
```

### ❌ Lỗi 2: Không xác định khán giả
```
BAD:  "Slide về biến đổi khí hậu"
GOOD: "Slide về biến đổi khí hậu cho học sinh THPT dự thi Olympic
       Môi trường toàn quốc, nhấn mạnh giải pháp thực tế mà giới trẻ
       có thể thực hiện ngay tại Việt Nam"
```

### ❌ Lỗi 3: Quên yêu cầu về cảm xúc
```
BAD:  "Tạo slide pitch startup"
GOOD: "Tạo slide pitch startup, giọng điệu tự tin nhưng không ngạo mạn,
       dùng storytelling bắt đầu bằng một pain point cụ thể mà người
       xem có thể đồng cảm ngay từ slide đầu tiên"
```

---

## 🎨 Các phong cách slide phổ biến

| Phong cách | Đặc điểm | Dùng khi |
|---|---|---|
| **Minimalist** | Nhiều white space, 1 ý/slide | Thuyết trình chuyên nghiệp, TED-style |
| **Data-driven** | Chart, số liệu là nhân vật chính | Báo cáo, phân tích, investor |
| **Story-first** | Mở đầu bằng narrative | Pitch, cuộc thi, truyền cảm hứng |
| **Visual metaphor** | Hình ảnh ẩn dụ làm trung tâm | Creative, marketing |
| **Academic** | Cấu trúc rõ, trích dẫn nhiều | Luận văn, seminar khoa học |
| **Conversational** | Câu hỏi, dialogue với khán giả | Workshop, đào tạo |

---

> 💡 Xem thêm mẹo nâng cao khi kết hợp nhiều tool tại [TIPS.md](TIPS.md)
