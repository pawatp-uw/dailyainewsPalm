# Perspectives — 2026-06-12

## 1. Oracle — Q4 FY2026 record cloud, RPO $638B (+363%), ~$40B raise

**อาจารย์ (มหาวิทยาลัย):** RPO ที่โต 363% เทียบกับ capex $55.7B และแผนระดมทุน $40B เป็นเคสคลาสสิกของ "backlog-funded growth" — สอน corporate finance ได้ทันทีว่า order book ที่ใหญ่ไม่ได้แปลว่ากระแสเงินสดมาทันที และตลาดลงโทษหุ้นเพราะ financing gap ระหว่างสัญญากับ cash conversion
**ผู้เชี่ยวชาญด้าน AI:** RPO ของ Oracle กลายเป็น proxy ที่ดีที่สุดตัวหนึ่งของ "AI compute demand ที่ commit แล้ว" โดยเฉพาะส่วน ~$75B ที่ลูกค้าจ่ายล่วงหน้า/นำ GPU มาเอง — แต่ต้องระวัง concentration risk เพราะ backlog ส่วนใหญ่มาจากลูกค้า AI รายใหญ่ไม่กี่ราย
**โปรแกรมเมอร์มืออาชีพ:** OCI โต 93% แปลว่า capacity ใหม่กำลังมาแต่ยังตึง — ถ้าวางระบบบน OCI ให้ lock reserved/committed-use capacity ล่วงหน้า และออกแบบ workload ให้ portable เผื่อย้าย region/cloud เมื่อ GPU supply ผันผวน

## 2. Microsoft — Claude Fable 5 ใน Microsoft 365 Copilot

**อาจารย์ (มหาวิทยาลัย):** การที่ Microsoft วาง Copilot เป็น "multi-model platform" (มีทั้ง OpenAI และ Anthropic) เป็นเคสสอน platform strategy — เจ้าของแพลตฟอร์มเปลี่ยนจาก "ผูกกับโมเดลเดียว" เป็น "ตัวกลางที่ให้ลูกค้าเลือกโมเดล" เพื่อลด supplier dependency และเพิ่ม switching cost ฝั่งลูกค้า
**ผู้เชี่ยวชาญด้าน AI:** การมี Fable 5 (Mythos-class) ใน Word/Excel/Outlook ทำให้ frontier reasoning อยู่ใกล้ข้อมูลองค์กรมากขึ้น — แต่ประเด็นสำคัญคือ governance: default-off + IT-admin controls + คำเตือนเรื่อง data retention ของ Anthropic สะท้อนว่า enterprise AI ปี 2026 แข่งกันที่ "ความปลอดภัยของข้อมูล" ไม่ใช่แค่ benchmark
**โปรแกรมเมอร์มืออาชีพ:** ก่อน rollout ให้ตรวจ data residency/retention policy และทดสอบ Fable 5 เทียบ GPT บน workload จริง (สรุปเอกสาร, วิเคราะห์สเปรดชีต, coding) เพราะ default model picker ที่ shift จะกระทบทั้ง cost และ output quality ของ pipeline ที่ผูกกับ Copilot
