# 🧠 Claude Prompts — Phân Tích Sâu & Cấu Trúc Logic

> **Model khuyên dùng:** Claude Sonnet / Opus | **Điểm mạnh:** Critical thinking, cấu trúc chặt chẽ, nội dung học thuật

---

## Tại sao dùng Claude cho slide?

Claude đặc biệt mạnh ở:
- **Logical structure**: Xây dựng argument có chiều sâu, MECE
- **Academic depth**: Phân tích học thuật, cite reasoning rõ ràng
- **Critical thinking**: Phản biện, tìm weak points trong argument của bạn
- **Long-form synthesis**: Tổng hợp nhiều nguồn thành narrative mạch lạc

---

## Prompt đa năng cho Claude

```
<task>
Tôi cần tạo slide thuyết trình về [CHỦ ĐỀ].
</task>

<context>
- Khán giả: [MÔ TẢ KHÁN GIẢ]
- Mục tiêu: [KHÁN GIẢ SẼ NGHĨ/LÀM/CẢM GÌ SAU KHI XEM]
- Thời gian: [X phút]
- Trình độ kiến thức của khán giả về chủ đề: [THẤP / TRUNG BÌNH / CAO]
</context>

<requirements>
1. Xây dựng outline slide với logical flow chặt chẽ
2. Mỗi slide phải có: (a) Headline claim, (b) Supporting evidence/reasoning, (c) Transition to next
3. Identify potential weak points trong argument và cách address chúng
4. Slide cuối: Synthesis — không chỉ summary, mà là "so what" cho khán giả
</requirements>

<format>
Output theo format:
## Slide [n]: [HEADLINE]
**Claim:** [1 câu]
**Evidence:** [2-3 điểm]
**Visual suggestion:** [mô tả hình ảnh/chart]
**Transition:** [câu dẫn sang slide tiếp theo]
</format>
```

---

## 📂 Xem thêm prompts theo chủ đề

| File | Nội dung |
|---|---|
| [deep-analysis.md](deep-analysis.md) | Prompts phân tích sâu, research |
| [critical-review.md](critical-review.md) | Prompts review và cải thiện slide hiện có |
