# harness-engineering-handbook

คู่มือ: **Harness Engineering — ฉบับเข้าใจถึงแก่น** — ศาสตร์ของการออกแบบระบบรอบ AI agent สำหรับคนที่ใช้ agent เป็นแล้ว อยากเข้าใจว่าข้างในทำงานยังไง และคิดแบบคนออกแบบระบบได้

📖 อ่านออนไลน์: **https://tayakorn221.github.io/harness-engineering-handbook/** (HTML ไฟล์เดียวจบ ไม่มี dependency)

## เกี่ยวกับเล่มนี้

ขั้นปิดของบันไดสาย AI ต่อจาก [Prompt 0 → Hero](https://tayakorn221.github.io/prompt-engineering-handbook/) — จาก "สั่ง AI เป็น" สู่ "ออกแบบระบบรอบ AI เป็น" ผ่าน **14 บท 5 ระดับ**:

- **L0 ปูพื้น** — Agent = Model + Harness (ทำไมโมเดลเดียวกันเก่งไม่เท่ากัน), กายวิภาคของ agent loop
- **L1 เสาหลัก** — context management, tool design (API สำหรับผู้ใช้ที่เป็น AI), feedback loops
- **L2 คุมให้อยู่** — guardrails & permissions (blast radius × reversibility, prompt injection), observability, stop conditions & failure modes
- **L3 ขยายระบบ** — memory & skills (progressive disclosure), subagents & orchestration, evals
- **L4 แงะของจริง** — ผ่า Claude Code เป็น case study, ออกแบบ harness ของตัวเอง, อนาคตของศาสตร์นี้

เน้นเข้าใจกลไกว่า "ทำไม" ไม่ใช่ท่องสูตร · ใช้ Claude Code เป็นตัวอย่างประจำเล่มแต่หลักการเป็นกลางใช้ได้ทุก harness · ภาษาไทย พร้อมไดอะแกรม 20 รูป · ส่วนหนึ่งของ [Handbooks](https://tayakorn221.github.io/handbooks/) — เขียนเพื่อเข้าใจ ไม่ใช่เพื่อท่องจำ

## ไฟล์

| ไฟล์ | คำอธิบาย |
|------|----------|
| `index.html` | ตัวคู่มือ — single-file HTML, ธีม paper + teal/red, sidebar TOC + reading progress |

---

Last updated: 2026-07-02
