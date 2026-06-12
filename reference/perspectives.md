# Perspectives — 2026-06-12

## 1. Oracle — Q4 FY2026: Record Revenue แต่หุ้นร่วงบน AI Capex Concerns

**อาจารย์ (มหาวิทยาลัย):** RPO โต 363% สวนทาง capex $55.7B และ cash flow deficit $23.7B เป็นเคสคลาสสิกของ "backlog-funded growth stage" ที่ margin ถูก sacrifice เพื่อ capture AI infrastructure market ก่อนคู่แข่ง — ใช้สอน investment cycle + leverage financing ใน corporate finance ได้ทันที
**ผู้เชี่ยวชาญด้าน AI:** RPO ~$75B prepaid/customer-GPU เป็น proxy ที่ดีที่สุดของ "committed AI compute demand" ที่จะเห็นใน revenue จริงใน 12-24 เดือน แต่ต้องระวัง concentration risk เพราะ backlog มาจากลูกค้า AI รายใหญ่ไม่กี่ราย — หาก 2-3 รายยกเลิก RPO จะ collapse ทันที
**โปรแกรมเมอร์มืออาชีพ:** OCI IaaS +93% หมายความว่า Oracle อัดเม็ดเงิน build capacity อย่างรวดเร็ว แต่ demand ยังนำ supply — ถ้าวางงานบน OCI ให้ reserve committed-use contract ล่วงหน้าและทำ workload ให้ portable เผื่อ GPU shortage ผันผวนในระยะ 2-4 ไตรมาสข้างหน้า

## 2. Microsoft — Claude Fable 5 ใน M365 Copilot: Multi-Model Platform Strategy

**อาจารย์ (มหาวิทยาลัย):** Microsoft กำลัง pivot จาก "single-model OS" มาเป็น "model-broker" — เป็นเคส platform economics ที่น่าสนใจ: เจ้าของแพลตฟอร์มลด supplier dependency (ไม่ lock-in กับ OpenAI เพียงรายเดียว) โดยเพิ่ม model choice ให้ลูกค้า พร้อมสร้าง switching cost ผ่าน M365 governance layer
**ผู้เชี่ยวชาญด้าน AI:** Fable 5 (Mythos-class) ใน Word/Excel/Outlook ทำให้ frontier reasoning เข้าถึงข้อมูลองค์กรได้จริง — สิ่งที่ต้องทดสอบคือ latency, cost per task และ output quality เทียบ GPT-5.x บน workload จริงก่อนตัดสินใจ shift default model
**โปรแกรมเมอร์มืออาชีพ:** default-off + IT admin governance + คำเตือน Anthropic data retention สะท้อน enterprise security model ปี 2026 — ก่อน rollout ให้ map data flow ว่า input ใดจะ pass ไป Anthropic เพราะ compliance + audit trail ใน M365 environment ต้องชัดเจน

## 3. Xiaomi — MiMo Code V0.1.0: Open-Source Terminal AI Coding Agent

**อาจารย์ (มหาวิทยาลัย):** Xiaomi (consumer electronics) เข้าแข่งใน developer tools เป็นเคส boundary-crossing competition — คล้าย Nvidia เข้า PC CPU หรือ Apple เข้า chip design; ใช้สอนเรื่อง competitive moat ของ AI coding tools ที่กำลัง commoditize เร็ว
**ผู้เชี่ยวชาญด้าน AI:** Background context subagent เป็น genuine approach สำหรับ agentic coding ที่ต้องการ long-horizon context — แต่ benchmark เป็น self-reported และ V0.1.0 ยังเป็น early release; ต้องรอ third-party verification (SWE-Bench Pro 62% vs Claude Code 57% — Xiaomi เป็นผู้ทดสอบเอง)
**โปรแกรมเมอร์มืออาชีพ:** MIT license + single-command install + MiMo-V2.5 ฟรีถึง 23 มิ.ย. = zero-friction experiment เหมาะกับงาน refactoring ขนาดใหญ่หรือ multi-file agentic pipeline — ทดลองบน macOS/Linux ก่อน commit ใน production workflow
