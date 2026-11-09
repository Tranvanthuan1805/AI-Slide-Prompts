# 🧠 Claude Prompts — Phân Tích Sâu & Nghiên Cứu

---

## Prompt 1: Phân tích Case Study

```
<task>
Phân tích case study "[TÊN CASE STUDY]" và tạo slide thuyết trình.
</task>

<analysis_framework>
Phân tích theo 4 lớp:
1. WHAT happened (sự kiện thực tế, không phán xét)
2. WHY it happened (root causes — 5 Whys approach)
3. WHAT WORKED / WHAT DIDN'T (evidence-based, không bias)
4. WHAT CAN WE LEARN (generalizable lessons, không chỉ cho case này)
</analysis_framework>

<slide_structure>
Tạo 10 slide:
- Slide 1: "The Paradox" — 1 câu mô tả điều gây ngạc nhiên nhất về case này
- Slide 2: Context & Stakes — tại sao case này QUAN TRỌNG
- Slide 3-4: Timeline visual — key events với turning points được highlight
- Slide 5-6: Deep dive vào 2 quyết định/yếu tố QUAN TRỌNG NHẤT
- Slide 7: What worked — evidence-backed analysis
- Slide 8: What failed — honest post-mortem, không blame cá nhân
- Slide 9: Transferable lessons — framework có thể apply vào tình huống khác
- Slide 10: "If I were in their shoes..." — synthesis với critical thinking
</slide_structure>

<quality_check>
Trước khi output, tự check:
- Có claim nào cần dẫn chứng nhưng chưa có không?
- Có bias nào trong analysis không?
- Lessons có thực sự transferable không?
</quality_check>
```

---

## Prompt 2: So sánh đa chiều (Comparative Analysis)

```
<task>
Tạo slide so sánh [ĐỐI TƯỢNG A] và [ĐỐI TƯỢNG B] (có thể là 2 lý thuyết,
2 công nghệ, 2 chính sách, 2 mô hình kinh doanh...).
</task>

<comparison_principles>
Comparison phải:
1. FAIR — dùng cùng tiêu chí cho cả hai
2. NUANCED — không phải "A tốt hơn B" mà là "A tốt hơn B ở X trong context Y"
3. USEFUL — giúp khán giả đưa ra quyết định, không chỉ academic exercise
4. HONEST ABOUT UNCERTAINTY — khi không rõ, nói rõ là không rõ
</comparison_principles>

<slide_structure>
- Slide 1: Framing — "Đây không phải câu hỏi X vs Y, mà là: Khi nào nên dùng X, khi nào nên dùng Y?"
- Slide 2: Shared foundations — những gì A và B ĐỀU ĐỒNG Ý (quan trọng để establish common ground)
- Slide 3-4: Core differences — dùng side-by-side comparison với specific examples
- Slide 5: Where A wins — specific use cases, không phải generic
- Slide 6: Where B wins — specific use cases, không phải generic
- Slide 7: The nuanced middle — khi nào hybrid approach tốt hơn
- Slide 8: Decision framework — "Nếu bạn đang đứng trước X, hỏi mình 3 câu này..."
- Slide 9: Future trajectory — A và B đang converge hay diverge?
- Slide 10: My synthesis — quan điểm cá nhân có lập luận rõ ràng
</slide_structure>
```

---

## Prompt 3: Nghiên cứu khoa học / Technology Deep Dive

```
<task>
Tạo slide giải thích [CÔNG NGHỆ / KHÁI NIỆM KHOA HỌC] cho khán giả [MÔ TẢ].
</task>

<explanation_strategy>
Dùng "Feynman Technique" cho slide:
Level 1: Giải thích như cho đứa trẻ 12 tuổi (Slide 1-2)
Level 2: Giải thích với analogy từ đời thường (Slide 3-4)
Level 3: Giải thích technical details cho audience (Slide 5-7)
Level 4: Implications và "frontier questions" (Slide 8-10)
</explanation_strategy>

<requirements>
- Mỗi technical concept phải có 1 analogy dễ hiểu
- Mỗi claim technical phải có "why should audience care" ngay sau đó
- Slide 5-7: Technical depth — không đơn giản hóa quá mức, nhưng accessible
- Luôn distinguish "what we know" vs "what we think we know" vs "what we're guessing"
- Kết thúc bằng: "Câu hỏi mà ngay cả các chuyên gia hàng đầu cũng chưa trả lời được"

Output bao gồm: Outline + Key analogies + Potential confusions to address
</requirements>
```

---

## Prompt 4: Phản biện & Cải thiện slide hiện có

```
<task>
Đây là outline slide hiện tại của tôi:

[PASTE OUTLINE/NỘI DUNG SLIDE VÀO ĐÂY]

Hãy đóng vai một người phản biện khắt khe nhất và review toàn bộ.
</task>

<review_framework>
Đánh giá theo 5 tiêu chí với điểm 1-10 kèm giải thích:

1. CLARITY (Rõ ràng): Mỗi slide có 1 message rõ ràng không? Có slide nào "muddy" không?
2. EVIDENCE (Bằng chứng): Claims có được support bởi evidence không? Chỗ nào yếu?
3. FLOW (Mạch lạc): Logic transition giữa slides có smooth không? Có "jump" nào không?
4. IMPACT (Ấn tượng): Slide nào đang "boring"? Slide nào có potential mạnh hơn?
5. AUDIENCE FIT (Phù hợp khán giả): Nội dung có phù hợp với audience đã nêu không?
</review_framework>

<output>
1. Điểm tổng thể + nhận xét 1 đoạn
2. Top 3 vấn đề lớn nhất cần fix ngay
3. Phiên bản cải thiện cho 2-3 slide yếu nhất
4. 1 "hidden strength" trong bài mà tôi có thể khai thác tốt hơn
</output>
```
