# 💎 Google Gemini Prompts — Data & Google Workspace

> **Tool:** [Gemini](https://gemini.google.com) + Google Slides | **Điểm mạnh:** Tích hợp Google Docs/Sheets, phân tích data, tạo nội dung đa phương tiện

---

## Cách dùng Gemini cho slide

**Option 1:** Gemini → "Help me create a presentation" → paste prompt  
**Option 2:** Google Slides → Extensions → Gemini → prompt trong sidebar  
**Option 3:** Gemini Advanced → tạo nội dung → paste vào Slides + dùng Gemini Image Gen

---

## Prompt 1: Từ data/research → Slide (Gemini's superpower)

```
I have the following data/research findings that need to be turned into a compelling presentation:

[PASTE YOUR DATA, RESEARCH NOTES, OR BULLET POINTS HERE]

Please:
1. Identify the 3-5 most important insights from this data
2. Suggest a narrative structure that tells a coherent story with this data
3. For each key insight, recommend the best visualization type
4. Write slide content (headline + supporting text) for each key insight
5. Identify any data gaps or questions that the audience might ask

The presentation is for [AUDIENCE] who need to [MAKE A DECISION / UNDERSTAND A SITUATION / TAKE ACTION].

Format output as ready-to-use slide content.
```

---

## Prompt 2: Annual/Quarterly Report

```
Create a [ANNUAL/QUARTERLY] report presentation for [ORGANIZATION/TEAM/PROJECT].

Report period: [TIME PERIOD]
Key achievements: [LIST]
Key challenges: [LIST]  
Key metrics: [LIST WITH NUMBERS]
Goals for next period: [LIST]

Structure the report as a "Story of Progress":
1. Executive summary — 3 numbers that define this period
2. Highlights reel — best moments/achievements with visual proof
3. What we set out to do (goals) vs. what we achieved
4. Deep dive: What drove results (winners)
5. Deep dive: What didn't work and what we learned
6. Market/environment context — external factors that impacted us
7. Financial summary (if applicable) — clear, honest, visual
8. Team & culture highlights
9. Roadmap for next period
10. Recognition & thanks

Tone: Transparent and honest, celebrate wins without over-claiming,
acknowledge challenges without making excuses.
```

---

## Prompt 3: Research Summary Presentation

```
Summarize the following research topic into a presentation:

Topic: [CHỦ ĐỀ NGHIÊN CỨU]
Key papers/sources I've read: [TÊN TÀI LIỆU]
My target audience: [KHÁN GIẢ]

Using Google Search to supplement my notes, create:
1. Current state of knowledge on this topic (what's established)
2. Recent developments (what's new in the last 2-3 years)
3. Key debates or open questions in the field
4. Practical applications (how does this affect real life?)
5. What's coming next (research directions, predictions)

For each section:
- Write a compelling headline (not just a topic label)
- Provide 2-3 key points with supporting evidence
- Suggest relevant visualization (chart, diagram, timeline, map)
- Include 1 "surprising fact" that will make the audience lean forward

Add: A "Further Reading" slide with top 5 resources for deeper exploration.
```

---

## Prompt 4: Science & Technology Explainer

```
Create an explainer presentation on "[TECHNOLOGY/SCIENTIFIC CONCEPT]" using
the "Explain Like I'm 5 → PhD" progression:

Slide 1-2: ELI5 version
- Use a familiar everyday analogy
- No jargon whatsoever
- 1 simple visual metaphor

Slide 3-4: Intermediate explanation
- Introduce proper terminology, but explain each term
- Connect back to the simple analogy
- Add 1 real-world example

Slide 5-7: Technical depth
- How it actually works (mechanisms, processes)
- Key components and their roles
- Current limitations and challenges

Slide 8-9: Applications & implications
- Current real-world applications (with specific examples)
- Near-future applications (3-5 years)
- Potential risks or ethical considerations

Slide 10: The frontier
- "Here's what even the experts don't know yet"
- Open questions in the field
- Why this matters for [AUDIENCE'S FIELD/INTEREST]

Include: Suggested images/diagrams for each slide using descriptive prompts
for Gemini's image generation.
```

---

## 💡 Gemini + Google Slides Workflow

```
Bước 1: Gemini → Tạo outline + nội dung slide
Bước 2: Copy sang Google Slides
Bước 3: Gemini sidebar trong Slides → "Help me improve this slide"
Bước 4: Gemini Image Gen → tạo custom visuals
Bước 5: Nếu có data trong Sheets → link chart trực tiếp vào Slides
```
