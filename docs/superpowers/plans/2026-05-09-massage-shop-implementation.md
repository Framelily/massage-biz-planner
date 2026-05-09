# Khum Lanna Spa — Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to track this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.
>
> **For human owner:** This plan converts the design spec at `docs/superpowers/specs/2026-05-09-massage-shop-business-plan-design.md` into concrete actions. Each Task = a milestone (days–weeks). Substeps = real-world actions to do.

**Goal:** เปิดร้าน Lanna luxury spa + membership ในนิมมานซอยใน เชียงใหม่ ภายใน 6-12 เดือน

**Architecture:** 3-bed boutique spa, 70-85 ตร.ม., owner equity 200-300K + bank loan 700-800K = 1M total. ดำเนินการแบบ 6 phases (pre-launch 6 เดือน → opening → 12 เดือนแรก)

**Key Tech / Tools / Vendors:**

- **Booking + POS**: Loyverse (free) + Fresha (booking SaaS) + iPad
- **Listings**: Google Business Profile, Klook, Viator, Treatwell, TripAdvisor
- **Marketing**: Instagram, Facebook, TikTok, LINE OA, Google Ads, Meta Ads
- **Banks**: ออมสิน (GSB-IGNITE), กรุงไทย SME, บสย. credit guarantee
- **Permits**: สบส., กรมพัฒนาธุรกิจการค้า, ประกันสังคม, เทศบาลนครเชียงใหม่
- **Education**: ITM Chiang Mai หรือ กรมพัฒนาฝีมือแรงงาน เชียงใหม่ (course 100 ชม.)

---

## How to Use This Plan

- ทำตามลำดับ **Tasks** ในแต่ละ phase (ภายใน phase เดียวกันหลาย tracks ทำ parallel ได้)
- Mark `[x]` เมื่อ task complete
- ทุก task มี: **Goal**, **Where**, **Documents**, **Cost**, **Timeline**, **Sub-steps**, **Done when**
- มี dependency ระบุชัด → อย่าข้าม
- Update spec doc + memory file ถ้า decision เปลี่ยน

---

# Phase 0: Pre-launch (เดือน -6 ถึง -1)

## Track A — Owner Education & Company Setup

### Task A1: ลงทะเบียนหลักสูตร "ผู้ดำเนินการสปา 100 ชั่วโมง"

**Goal**: ได้ใบประกาศที่ใช้ขอใบ สบส. (ห้ามข้าม — ใบนี้คือ key)
**Target month**: เดือน -6 (ลงทะเบียน) → เดือน -4 (จบ + ใบประกาศ)
**Cost**: 15,000 - 25,000 บาท
**Dependencies**: ไม่มี (เริ่มได้เลย)

**Sub-steps:**

- [ ] Compare 3 institutions ใน เชียงใหม่:
  - ITM (International Training Massage School) — โทร 053-218-632
  - กรมพัฒนาฝีมือแรงงาน เชียงใหม่ — โทร 053-121-002 (ถูกกว่า)
  - โรงเรียนเชียงใหม่อาชีพแพทย์แผนไทย
- [ ] โทรสอบถาม: ค่าเรียน, รอบเปิดถัดไป, ตารางเรียน, ใบประกาศใช้ขอ สบส. ได้แน่นอน?
- [ ] เลือกสถาบัน + ชำระค่าเรียน
- [ ] เริ่มเรียน — 4 weeks intensive (ส่วนใหญ่จันทร์-ศุกร์ 9:00-16:00)
- [ ] ผ่านสอบ → รับใบประกาศ
- [ ] เก็บสำเนาใบประกาศ + ตัวจริง (จะใช้ตอนยื่นใบ สบส. และตอน pitch แบงก์)

**Done when**: มีใบประกาศ "ผู้ดำเนินการสปา 100 ชั่วโมง" ในมือ

---

### Task A2: หาผู้ก่อการบริษัท (≥3 คน)

**Goal**: เตรียมคนสำหรับจดบริษัทจำกัด (ต้องมีผู้ก่อการ ≥3 คน)
**Target month**: เดือน -6
**Cost**: 0 (เป็นแค่การเตรียม)
**Dependencies**: ไม่มี

**Sub-steps:**

- [ ] เลือก 2-3 คนจาก ครอบครัว/เพื่อนสนิท เป็นผู้ถือหุ้นเล็ก (1-5%)
- [ ] อธิบายให้เข้าใจ: เป็นแค่ผู้ก่อการ ไม่ต้องลงเงินจริง (ใช้แค่ชื่อ + บัตร)
- [ ] เก็บสำเนาบัตร ปชช. + ทะเบียนบ้านของทุกคน
- [ ] ตกลง % ถือหุ้น (เจ้าของ ≥51%, ที่เหลือกระจาย)

**Done when**: มี 3 คน + เอกสารพร้อม

---

### Task A3: จดทะเบียนบริษัทจำกัด

**Goal**: ได้นิติบุคคลพร้อมเลข TAX ID เปิดบัญชีธนาคารบริษัท
**Target month**: เดือน -5
**Cost**: 10,000 - 15,000 บาท (รวมทนาย/บัญชี + ค่าธรรมเนียมรัฐ)
**Where**: กรมพัฒนาธุรกิจการค้า เชียงใหม่ (DBD) หรือผ่าน [DBD e-Registration](https://www.dbd.go.th/)
**Dependencies**: A2 (มีผู้ก่อการ)

**Sub-steps:**

- [ ] ตั้งชื่อบริษัท 3 ตัวเลือก (เผื่อชื่อซ้ำ) เช่น "บริษัท ขุมล้านนาสปา จำกัด"
- [ ] จองชื่อบริษัทผ่าน DBD e-Service (รออนุมัติ 1-2 วัน)
- [ ] ทำหนังสือบริคณห์สนธิ + ข้อบังคับบริษัท (ใช้ template ของ DBD หรือจ้างทนาย ~5K)
- [ ] กำหนดทุนจดทะเบียน 1,000,000 บาท (ชำระจริง 25% = 250,000 บาท)
  - 🔑 ระบุ 1M ทำให้ดูจริงจังต่อแบงก์
- [ ] ประชุมจัดตั้งบริษัท (ผู้ก่อการมาเซ็น)
- [ ] ยื่นจดทะเบียน DBD เชียงใหม่ → รอ 3-7 วัน
- [ ] รับหนังสือรับรองบริษัท + ตราประทับบริษัท
- [ ] ขอเลขประจำตัวผู้เสียภาษี (TAX ID) — กรมสรรพากร เชียงใหม่
- [ ] เปิดบัญชีบริษัท (ชั่วคราวที่แบงก์ใดก็ได้ — จะเปลี่ยนตามแบงก์ที่กู้)

**Done when**: มีหนังสือรับรองบริษัท + TAX ID + บัญชีบริษัท

---

### Task A4: Hire Accountant + Lawyer Retainer

**Goal**: มีที่ปรึกษามืออาชีพช่วยตั้งแต่วันแรก
**Target month**: เดือน -5
**Cost**: ~6-8K/เดือน รวม (accountant 3-5K + lawyer 3K)
**Dependencies**: A3

**Sub-steps:**

- [ ] หา accountant SME freelance ใน เชียงใหม่ (ขอ referral จาก SCB SME center หรือ Facebook กลุ่ม "ผู้ประกอบการเชียงใหม่")
- [ ] สัมภาษณ์ 2-3 เจ้า — ตรวจสอบประสบการณ์ธุรกิจสปา/บริการ
- [ ] เซ็นสัญญา accountant — รายเดือน
- [ ] หา lawyer (สำหรับ employment contract, lease review, license)
- [ ] เซ็น retainer lawyer — 3K/เดือน

**Done when**: มี accountant + lawyer พร้อมงาน

---

## Track B — Funding (Bank Loan)

### Task B1: เตรียมเอกสาร Bank Pitch

**Goal**: ชุดเอกสารสมบูรณ์ก่อนยื่นแบงก์
**Target month**: เดือน -6 ถึง -5
**Cost**: 0 (DIY) ถ้าจ้าง consultant ~10-20K
**Dependencies**: ไม่มี (เริ่มทันที)

**Sub-steps:**

- [ ] Print spec doc (`docs/superpowers/specs/2026-05-09-massage-shop-business-plan-design.md`) เป็น PDF
- [ ] ทำ Excel financial model 3 ปี:
  - Sheet 1: P&L month-by-month
  - Sheet 2: Cash flow
  - Sheet 3: Balance sheet
  - Sheet 4: Sensitivity analysis (base/conservative/optimistic)
  - Sheet 5: Loan repayment schedule
- [ ] รวบรวมเอกสารส่วนตัว:
  - บัตร ปชช. + ทะเบียนบ้าน
  - Statement bank 6 เดือน
  - ใบรับรองรายได้ปัจจุบัน (ถ้ามี)
  - หลักฐานเงินที่จะลง equity 200-300K (ในบัญชีตัวเอง)
- [ ] รวบรวมเอกสารบริษัท (จาก A3):
  - หนังสือรับรองบริษัท
  - หนังสือบริคณห์สนธิ
  - บัญชีรายชื่อผู้ถือหุ้น (บอจ.5)
  - ตราประทับ
- [ ] ขอใบเสนอราคา 3 เจ้า/รายการ สำหรับ:
  - Renovation contractor
  - เตียงนวด + furniture
  - อุปกรณ์สปา
  - เอามาแนบเป็นหลักฐาน "Use of funds"
- [ ] หา LOI/MOU จาก partner ก่อนได้ 2-3 เจ้า:
  - Coworking (Punspace/Yellow): "intent to cross-promo"
  - Hotel (boutique 4-5*): "intent to refer guests"
  - ทำเป็นจดหมายสั้นๆ ลายเซ็น

**Done when**: PDF business plan + Excel model + เอกสารส่วนตัว/บริษัท + 3 quotes/รายการ + LOI 2-3 เจ้า

---

### Task B2: สมัคร บสย. ค้ำประกัน

**Goal**: ได้ บสย. ค้ำให้แบงก์ (เพราะ equity ratio ต่ำ — ไม่มีหลักประกันเอง)
**Target month**: เดือน -5
**Cost**: ค่าธรรมเนียม บสย. ~1.75% ของวงเงิน/ปี (~12-14K/ปี สำหรับ 750K)
**Where**: บสย. (Thai Credit Guarantee Corp) — สาขาเชียงใหม่ หรือ [tcg.or.th](https://www.tcg.or.th/)
**Dependencies**: A3, B1

**Sub-steps:**

- [ ] โทรสอบถาม บสย. เชียงใหม่ — โครงการที่เหมาะกับ SME มือใหม่
- [ ] เลือกโครงการ: PGS (Portfolio Guarantee Scheme) หรือ DGS — สอบถามเจ้าหน้าที่
- [ ] กรอกใบสมัคร + แนบเอกสารจาก B1
- [ ] รอผลพิจารณา — 2-3 สัปดาห์
- [ ] รับหนังสือยืนยันการค้ำประกัน

**Done when**: มีหนังสือยืนยัน บสย.

---

### Task B3: ยื่นกู้แบงก์ (parallel 2 เจ้า)

**Goal**: ได้วงเงินกู้ 700-800K ที่ดอกเบี้ยดีสุด
**Target month**: เดือน -5 (ยื่น) → เดือน -4 (อนุมัติ + เซ็น)
**Cost**: ค่าทำสัญญา ~5K
**Where**:

- ออมสิน (GSB-IGNITE / SMEs Start-up) — สาขาใหญ่เชียงใหม่
- กรุงไทย SME D-MoneyConnect — สาขาใหญ่เชียงใหม่

**Dependencies**: A3, B1, B2 (ยื่น บสย. คู่กัน)

**Sub-steps:**

- [ ] นัดเจ้าหน้าที่ SME — ทั้ง 2 แบงก์ในวันเดียวกัน (เปรียบเทียบ rate)
- [ ] ยื่นเอกสารชุดเดียวกัน + บสย. ผ่านอนุมัติ (จาก B2)
- [ ] แบงก์เชิญดู site (ทำเลที่กำลังเล็ง — Task D)
- [ ] รอผล — 3-4 สัปดาห์
- [ ] เปรียบเทียบ offer:
  - Interest rate
  - ระยะผ่อน
  - **Grace period** (ขั้นต่ำ 3-6 เดือน — สำคัญ)
  - Collateral requirements
- [ ] เลือก offer ที่ดีกว่า → เซ็นสัญญา
- [ ] เปิดบัญชีนิติบุคคลที่แบงก์ที่กู้ (ปิด/โอนจากชั่วคราว A3)
- [ ] เงินเข้าบัญชี

⚠️ **ห้ามเซ็น** ก่อน: ทำเลพร้อมเซ็นสัญญา (Task D6) — เพราะแบงก์มักให้เงินตรง vendor ไม่ใช่เข้ามือ

**Done when**: เงินกู้เข้าบัญชี (หรือ approved พร้อมเบิกตอน sign lease)

---

## Track C — Manager Hire (CRITICAL)

### Task C1: เขียน Job Description + ลงประกาศ

**Goal**: ดึง candidates ที่ใช่
**Target month**: เดือน -6
**Cost**: 1-2K (LinkedIn premium 1 เดือน)
**Dependencies**: ไม่มี

**Sub-steps:**

- [ ] เขียน JD ภาษา ไทย + อังกฤษ — ระบุชัด:
  - 5+ ปี spa/wellness premium
  - English working level
  - ฐาน 30-40K + 5-10% net profit bonus
  - 2-year contract + non-compete 1 ปี
  - Free 1 massage/wk
- [ ] ลงประกาศใน:
  - LinkedIn (search "Spa Manager Chiang Mai" target sector hospitality/wellness)
  - JobsDB / JobThai
  - Facebook กลุ่ม "Chiang Mai Hospitality Jobs"
  - Thai Spa Association job board
- [ ] ติดต่อ headhunter agency (optional, 1-2 เดือนเงินเดือน fee — คุ้มถ้าได้คนดี)

**Done when**: มี ≥10 applicants

---

### Task C2: Screen + Interview ≥5 Candidates

**Goal**: เลือก 1 manager ที่ใช่
**Target month**: เดือน -5
**Cost**: 0
**Dependencies**: C1

**Sub-steps:**

- [ ] Screen resume → shortlist 5-7 คน
- [ ] รอบ 1 (phone/Zoom 30 นาที): personality + English level + expectations
- [ ] รอบ 2 (in-person 1 ชม.): scenarios — "ลูกค้าร้องเรียน X จะทำยังไง?", "Therapist ลาออก 2 คนพร้อมกัน?"
- [ ] รอบ 3 (work session 2 ชม.): ให้ candidate review business plan + แสดงความเห็น (เช็คว่าคิดเป็นจริง)
- [ ] Background check: references จากนายจ้างเก่า (อย่างน้อย 2 เจ้า), ตรวจประวัติ
- [ ] ✅ Pick the one

**Done when**: เลือก manager ได้ + ตกลงเงินเดือน

---

### Task C3: เซ็นสัญญา Manager

**Goal**: Lock in manager ก่อนคนอื่น poach ไป
**Target month**: เดือน -4
**Cost**: 0 (lawyer ทำสัญญารวมใน retainer)
**Dependencies**: C2, A4

**Sub-steps:**

- [ ] Lawyer ร่างสัญญา 2 ปี (ก่อนเปิดร้าน 3 เดือน + หลังเปิด 21 เดือน)
- [ ] ใส่ clauses:
  - Probation 3 เดือนหลังร้านเปิด
  - Non-compete 1 ปีหลังออก ในรัศมี 2km
  - Confidentiality (customer data ห้ามเอาออก)
  - Bonus 5-10% ของ net profit
  - Termination notice 30 วัน
- [ ] ทั้งสองฝ่ายเซ็น
- [ ] เริ่มจ่ายเงินเดือนตั้งแต่เดือน -3 (part-time) → เดือน -2 full-time

**Done when**: สัญญาเซ็น manager พร้อมเริ่ม

---

## Track D — Property

### Task D1: Field Survey Nimman ซอยใน + Competitor Analysis

**Goal**: เข้าใจตลาดจริง + ระบุทำเลเป้า 5-10 จุด
**Target month**: เดือน -6
**Cost**: 0 (เดินเอง) + ค่ากาแฟ
**Dependencies**: ไม่มี

**Sub-steps:**

- [ ] เลือก 4 zones target ตาม priority:
  1. สิริมังคลาจารย์ ซอย 1-7
  2. Nimman Soi 13, 17
  3. ห้วยแก้ว ซอยใน 7, 9
  4. สันติธรรม ซอยใน 4-6
- [ ] เดิน 2 ครั้ง/zone — ครั้งหนึ่งวันธรรมดาบ่าย, อีกครั้งเสาร์-อาทิตย์ตอนค่ำ
- [ ] นับร้านนวด/สปา ทุกร้านในรัศมี 200m จากจุดเป้า:
  - ชื่อร้าน
  - Theme / decor
  - ราคาหน้าร้าน
  - ดูคนเข้าออก ~30 นาที (ปริมาณ)
- [ ] เข้าไปนวดที่ 5-7 ร้าน (เป็นลูกค้าจริง) — เช็ค service level + price + ambiance
- [ ] บันทึกใน Google Sheet: 20 ร้าน, ราคา avg, จุดอ่อน, จุดแข็ง
- [ ] ระบุพื้นที่ว่างสำหรับ "Lanna luxury" (ไม่มีคู่แข่ง direct)

**Done when**: Spreadsheet 20 ร้าน + selected 4-5 zones priority

---

### Task D2: Property Hunting List

**Goal**: หา 5-10 ตึกแถวที่ตรง spec (70-85 ตร.ม., 24-28K/เดือน, 2 ชั้น)
**Target month**: เดือน -4
**Cost**: 0 (DIY) หรือ broker fee 1 เดือนเงินเดือน
**Dependencies**: D1

**Sub-steps:**

- [ ] หาในแหล่งต่างๆ:
  - DDproperty, Hipflat, Baania (filter เชียงใหม่ commercial)
  - Facebook กลุ่ม "ปล่อยเช่าตึกแถวเชียงใหม่"
  - LINE OA broker เชียงใหม่ (search "นายหน้าเชียงใหม่")
  - เดินดูป้าย "ให้เช่า" ใน 4 zones (D1)
- [ ] กรองตาม spec ใน Section 3 ของ business plan:
  - 70-85 ตร.ม.
  - 2 ชั้น (ดีสุด)
  - ที่จอด 2-3 คัน หรือใกล้ public parking
  - 30A ขึ้นไป
- [ ] List 5-10 ตึก พร้อมข้อมูล: address, ค่าเช่า, ขนาด, รูป, contact

**Done when**: Spreadsheet 5-10 candidates

---

### Task D3: Property Visits + Evaluation

**Goal**: เลือก 1 ตึกที่ใช่
**Target month**: เดือน -4 ถึง -3
**Cost**: 0
**Dependencies**: D2

**Sub-steps:**

- [ ] นัดดู ทุกตึก list ใน D2
- [ ] ดูที่ checklist (พิมพ์เอาไป):
  - [ ] ขนาด/layout เหมาะกับ 3 ห้องนวด + 1 couple + reception?
  - [ ] นิติบุคคลให้เปิดสปาได้? (ขอดู blueprint, สอบถามนิติ)
  - [ ] ระบบไฟ 30A+? น้ำพอ?
  - [ ] Soundproof OK? (เพื่อนบ้านได้ยินไหม)
  - [ ] ที่จอดรถ?
  - [ ] ใกล้ coworking/hotel?
  - [ ] ป้าย/หน้าตึกเห็นได้จากถนน?
- [ ] ถ่ายรูป + วิดีโอทุกตึก
- [ ] เทียบ pros/cons ในตาราง
- [ ] สอบถามค่าเช่าจริง + เงื่อนไข
- [ ] เลือก top 2

**Done when**: Top 2 ตัวเลือก

---

### Task D4: เจรจา + เซ็นสัญญาเช่า

**Goal**: ได้สัญญา 3 ปี + option ต่อ + free rent 1-2 เดือน
**Target month**: เดือน -3
**Cost**: ~78K (3 เดือนล่วงหน้า + มัดจำ — สำหรับ 26K/เดือน)
**Dependencies**: D3, B3 (loan approved/standby), A4 (lawyer review)

**Sub-steps:**

- [ ] เริ่มเจรจาตึก top 1
- [ ] ขอ:
  - สัญญา 3 ปี + option ต่อ 3 ปี
  - มัดจำ 2 เดือน + ล่วงหน้า 1 เดือน (default ปกติ 3+1)
  - **Free rent 1-2 เดือน** สำหรับ renovation
  - ระบุชัด: เจ้าของ vs ผู้เช่า ใครจ่ายอะไร (ค่าน้ำ ค่าไฟ ค่าซ่อม กรณี structural)
- [ ] Lawyer review draft สัญญา (ใช้ retainer A4)
- [ ] เซ็นสัญญา + จ่ายเงิน
- [ ] รับกุญแจ + blueprint
- [ ] ถ้า top 1 เจรจาล้มเหลว → ไป top 2

**Done when**: เซ็นสัญญา + รับกุญแจ + ที่อยู่ทางการพร้อมไปขอใบ สบส.

---

## Track E — Brand & Marketing Setup

### Task E1: Logo + Brand Guideline

**Goal**: Logo + brand asset พร้อมใช้
**Target month**: เดือน -5
**Cost**: 8-15K (designer freelance)
**Dependencies**: ตกลงชื่อร้าน

**Sub-steps:**

- [ ] ตัดสินใจชื่อร้านขั้นสุดท้าย
  - เกณฑ์: ออกเสียงได้ใน 1 ครั้ง / Google ค้นเจอ / .com ว่าง
  - ตรวจ trademark — [ipthailand.go.th](https://www.ipthailand.go.th/)
- [ ] เช็ค .com / .co.th ว่าง
- [ ] หา designer freelance (Fastwork, Fiverr Thai, หรือ designer ใน เชียงใหม่)
- [ ] Brief: Lanna luxury, modern wellness, 3 mockups
- [ ] Logo + 3-5 สีหลัก + typography + brand voice doc
- [ ] รับ source files (AI, PNG, SVG) + brand guideline PDF

**Done when**: Logo + brand kit ครบ

---

### Task E2: Setup Social Media Accounts + Content Seeding

**Goal**: IG/FB account ดู established (ไม่ใช่เพิ่งสร้าง)
**Target month**: เดือน -4
**Cost**: 0 (DIY) หรือ ~5K/เดือน social manager freelance
**Dependencies**: E1

**Sub-steps:**

- [ ] สร้าง Instagram + Facebook + TikTok + LINE OA
- [ ] Bio: brand promise + จุด CTA
- [ ] Profile pic = logo
- [ ] Cover = brand image
- [ ] Lock username เดียวกันทุก platform
- [ ] เริ่มลง content 2-3 posts/wk:
  - Lanna culture (สมุนไพร, ลูกประคบ explained)
  - Decor/architecture inspiration
  - Behind-the-scenes (ดู renovation progress พอตอนถึงเดือน -3)
- [ ] Hashtag strategy: #ChiangMaiSpa #LannaMassage #NimmanSpa #ChiangMaiWellness

**Done when**: 4 platforms live + 8-12 posts published

---

### Task E3: Landing Page

**Goal**: เว็บไซต์ booking + info
**Target month**: เดือน -3
**Cost**: ~2K/เดือน (Squarespace) หรือ 5-10K one-time (designer build Wix)
**Dependencies**: E1

**Sub-steps:**

- [ ] ซื้อ domain (.com หรือ .co.th)
- [ ] เลือก platform: Squarespace (ง่าย) / Wix / WordPress
- [ ] หน้าเว็บ:
  - Home: hero image + brand promise + CTA "Book Now"
  - Services: menu จาก spec Section 2
  - About: Lanna story + team
  - Contact: address, hours, map, LINE QR
  - Membership: tier breakdown + signup
- [ ] Embed Fresha booking widget (Task I1)
- [ ] SEO: meta title, description, schema markup (LocalBusiness)
- [ ] Test mobile responsive

**Done when**: Domain live + booking ทำงาน + mobile OK

---

### Task E4: Google Business Profile

**Goal**: Visible บน Google Maps + Search
**Target month**: เดือน -3
**Cost**: 0
**Dependencies**: D6 (มี address ทางการ)

**Sub-steps:**

- [ ] [google.com/business](https://www.google.com/business)
- [ ] สร้าง profile:
  - ชื่อร้าน + category (Spa, Massage)
  - Address (จาก D6)
  - Phone
  - Hours: 10:00-22:00 ทุกวัน
  - Services + ราคา
- [ ] Verify (ส่งโปสการ์ด ~1-2 สัปดาห์ — เริ่มยิ่งเร็วยิ่งดี)
- [ ] ใส่รูป (placeholder ก่อน → upgrade หลัง photoshoot)
- [ ] ใส่ Q&A pre-filled (5-10 คำถาม)

**Done when**: Profile verified + visible บน Maps

---

### Task E5: Photoshoot

**Goal**: 50-80 hero shots ใช้ทั้งปี
**Target month**: เดือน -1 (หลัง renovation เสร็จ)
**Cost**: 15-25K (photographer freelance Chiang Mai 1 day)
**Dependencies**: F5 (renovation done), F7 (furniture installed)

**Sub-steps:**

- [ ] หา photographer freelance (Fastwork "lifestyle photographer Chiang Mai")
- [ ] ดู portfolio — ต้องมี spa/hospitality experience
- [ ] เซ็นสัญญา + agree shot list:
  - Exterior + signage
  - Reception + waiting area
  - Treatment rooms (3 rooms different angles)
  - Couple room
  - Foot lounge
  - Decor close-ups (Lanna textiles, brass details)
  - Treatment in action (real models — 2 models รับ + 2 therapists ทำจริง)
  - Product flat lays (oils, herbal compresses, tea)
- [ ] Shoot day — 8-10 ชั่วโมง
- [ ] Receive edited files (50-80 hero + 100+ stories format)
- [ ] Backup ในหลายที่

**Done when**: Photo library ครบ + categorized

---

### Task E6: List บน Klook / Viator / Treatwell / TripAdvisor

**Goal**: Tourist-channel listings active
**Target month**: เดือน -1
**Cost**: 0 (commission-based 20-25%)
**Dependencies**: E4 (GBP), E5 (photos)

**Sub-steps:**

- [ ] Apply [Klook Partner](https://partners.klook.com/) (อนุมัติ 2-3 weeks)
- [ ] Apply Viator
- [ ] Apply Treatwell (ยุโรป-focus)
- [ ] Claim TripAdvisor listing
- [ ] Each platform: 3-5 packages live (เช่น 90min Lanna Thai 700, 60min Office Syndrome 500, Half-day Retreat 2,500)
- [ ] Initial promo: -15% first 30 days

**Done when**: ทุก platform live

---

### Task E7: Press + Influencer Outreach

**Goal**: 5-8 micro-influencers + 2-3 press features
**Target month**: เดือน -1 ถึง 0
**Cost**: 0 (barter) + 5-10K hospitality budget
**Dependencies**: E5

**Sub-steps:**

- [ ] List 15-20 micro-influencers (1K-10K followers) ใน เชียงใหม่ — Wellness/lifestyle/expat focus
- [ ] DM intro + offer free spa session for content (3 stories + 1 reel + 1 post)
- [ ] เลือก 5-8 ที่ตอบ + match brand
- [ ] นัดมาเดือน -1 (preview) หรือเดือน 0 (post-opening)
- [ ] List press: Chiang Mai Citylife, Citylocating, MarryMag, TAT Chiang Mai office
- [ ] Send press kit (PDF + photos) — เน้น "Lanna luxury wellness" angle

**Done when**: 5-8 influencers booked + 2-3 press confirmed

---

## Track F — Renovation & Physical Setup

### Task F1: Hire Contractor (3-quote bidding)

**Goal**: Fixed-price contract กับช่างที่เชื่อถือได้
**Target month**: เดือน -3
**Cost**: ~210K (renovation budget)
**Dependencies**: D6 (sign lease)

**Sub-steps:**

- [ ] หาช่าง 3 เจ้าใน เชียงใหม่:
  - ขอ referral จาก Facebook กลุ่ม "ผู้รับเหมาเชียงใหม่"
  - ดูผลงาน portfolio (ขอดูรูปงานเก่า + ไปดูที่จริง 1-2 site)
- [ ] Brief ทั้ง 3:
  - Layout จาก Section 3 ของ business plan
  - Quality level: Lanna luxury (premium)
  - Timeline: 5-6 weeks
  - Materials list (ไม้สัก, ทองเหลือง, ผ้าทอ — ระบุ supplier ถ้ามี)
- [ ] Receive 3 quotes (รายการ + ราคา + timeline + warranty)
- [ ] เปรียบเทียบ + เจรจา
- [ ] Lawyer review contract — ใส่:
  - Fixed price (no overrun without written approval)
  - 10% retention paid 30 days after completion
  - Penalty clause for delay (1% of contract/day delay)
  - Warranty 6 months
  - Insurance (ช่างต้องมีประกันงาน)
- [ ] เซ็น + จ่าย deposit 30%

**Done when**: เซ็นสัญญา + เริ่มงาน

---

### Task F2: Renovation Execution

**Goal**: ร้านพร้อมเปิด
**Target month**: เดือน -3 ถึง -1 (5-6 weeks)
**Cost**: รวมใน F1
**Dependencies**: F1

**Sub-steps:**

- [ ] Owner ไปไซต์ทุก 3-4 วัน — ตรวจ progress
- [ ] Manager (จาก C3) ไปไซต์รายวัน เริ่มเดือน -2
- [ ] Milestones:
  - Week 1-2: รื้อ + กั้นห้อง + ระบบไฟ/น้ำ/แอร์
  - Week 3-4: ฝ้า + พื้น + ผนัง + sanitary
  - Week 5: Decor + finishing + ติดตั้ง fixture
  - Week 6: Touch-up + cleaning + final inspection
- [ ] ถ่ายรูปทุก milestone — ใช้ใน social content (Task E2)
- [ ] Final inspection + sign off + จ่าย 60% (เหลือ 10% retention)

**Done when**: ร้านสร้างเสร็จ + final inspection passed

---

### Task F3: Order Furniture + Equipment + Linens

**Goal**: ของพร้อมส่งภายในเดือน -1
**Target month**: เดือน -3 (สั่งล่วงหน้า lead time)
**Cost**: 95K (furniture) + 35K (equipment) + 40K (linens) = 170K
**Dependencies**: D6, F1 (สั่งหลัง confirm layout)

**Sub-steps:**

- [ ] เตียงนวด (3 ตัว premium):
  - Suppliers: Massage Bed Thailand, IndoArt, หรือ custom local Chiang Mai
  - Spec: width 80cm, height adjustable, leather/eco-leather, 15-20K/ตัว
- [ ] Reception furniture: เคาน์เตอร์ไม้สัก + 4 chair
- [ ] Foot lounge furniture: 2 reclining chairs + ottoman
- [ ] อุปกรณ์สปา:
  - เครื่องอบลูกประคบ
  - หม้ออุ่นน้ำมัน
  - หินร้อน set
  - อ่างเท้าทองเหลือง 2 ใบ
- [ ] Linens (2 sets):
  - ผ้าปูเตียง 30 ผืน
  - ผ้าเช็ดตัว 60 ผืน
  - ชุดลูกค้า 30 ชุด
  - เสื้อพนักงาน 12 ชุด (3 per staff × 4)
- [ ] Track delivery — ทุกอย่างต้องถึงก่อนเดือน -1 week 2

**Done when**: ของถึงร้าน + inventory checked

---

## Track G — Permits

### Task G1: ยื่นใบ สบส.

**Goal**: ใบอนุญาตประกอบกิจการสปา
**Target month**: เดือน -3 ถึง -1
**Cost**: 5-10K + ค่าตรวจสถานที่
**Where**: สบส. เชียงใหม่ (สำนักงานสนับสนุนบริการสุขภาพ เขต 1) — โทร 053-217-115
**Dependencies**: A1 (ใบ 100 ชม.), A3 (นิติบุคคล), D6 (lease), F2 ระยะ 50%+

**Sub-steps:**

- [ ] โทรนัด สบส. — ขอ checklist เอกสารล่าสุด
- [ ] เตรียมเอกสาร:
  - คำขอใบอนุญาต (แบบฟอร์ม สบส.)
  - ใบประกาศผู้ดำเนินการสปา (จาก A1)
  - หนังสือรับรองบริษัท (จาก A3)
  - สัญญาเช่า (จาก D6)
  - แบบแปลนร้าน (จาก F1)
  - รายชื่อพนักงาน + ใบ cert (จาก H — ส่งเพิ่มทีหลัง)
- [ ] ยื่นเอกสาร
- [ ] นัดเจ้าหน้าที่มา inspect site — ทำตอนเดือน -1 (ร้านเสร็จแล้ว)
- [ ] Inspection day:
  - ห้องนวด ≥5 ตร.ม. ทุกห้อง ✓
  - มีผ้าม่าน/พาร์ทิชัน ✓
  - แสง + ระบายอากาศ ✓
  - ห้องน้ำสะอาด ✓
  - ป้ายราคาแสดงชัด ✓
- [ ] ผ่าน inspection → รอใบ 1-2 weeks → รับใบ

**Done when**: มีใบ สบส. ในมือ → เปิดร้านได้ตามกฎหมาย

---

### Task G2: ลงทะเบียนประกันสังคม + ประกันภัย

**Goal**: Compliance + ป้องกันความเสี่ยง
**Target month**: เดือน -1
**Cost**: ประกันสังคม % รายเดือน + ประกันภัย ~25-50K/ปี
**Dependencies**: H3 (sign therapist contracts)

**Sub-steps:**

- [ ] ลงทะเบียนนายจ้างประกันสังคมภายใน 30 วันหลังจ้างคนแรก — สำนักงานประกันสังคม เชียงใหม่
- [ ] กรอกแบบ สปส. 1-01 (ขึ้นทะเบียนนายจ้าง) + สปส. 1-03 (ขึ้นทะเบียนลูกจ้าง) ทุกคน
- [ ] หลังลงทะเบียน → ส่งเงินสมทบรายเดือน (5% นายจ้าง + 5% ลูกจ้าง, cap 750/ฝั่ง)
- [ ] ทำประกันภัย 3 ตัวขั้นต่ำ:
  - ประกันทรัพย์สิน (ติดต่อ ทิพยประกันภัย, อาคเนย์, MSIG) — ~12K/ปี
  - **ประกัน Public Liability** (ความรับผิดต่อบุคคลที่สาม) — สำคัญสุด ~15K/ปี วงเงิน 5M
  - Professional Indemnity therapists — ~7K/ปี
- [ ] เก็บกรมธรรม์ + ติดสำเนาในร้าน

**Done when**: ลงทะเบียน social security + กรมธรรม์ 3 ตัวในมือ

---

## Track H — Staff Recruitment & Training

### Task H1: MOU โรงเรียนนวด + Recruitment Pipeline

**Goal**: Pipeline therapist สำหรับเปิดและขยาย
**Target month**: เดือน -3
**Cost**: 0 (MOU แค่ลายลักษณ์อักษร)
**Dependencies**: A3 (นิติบุคคล)

**Sub-steps:**

- [ ] ติดต่อ:
  - ITM Chiang Mai
  - Lanna Massage School (ใกล้ Wat Phra Singh)
  - กรมพัฒนาฝีมือแรงงาน เชียงใหม่
- [ ] เสนอ MOU:
  - จองสิทธิ์ recruit fresh grads อันดับแรก
  - ทุนเรียนแลก 1-2 ปี service (optional)
- [ ] เซ็น MOU 2-3 เจ้า

**Done when**: MOU ≥2 เจ้า

---

### Task H2: Recruit + Hire 4 Therapists

**Goal**: 1 senior + 3 regular therapists
**Target month**: เดือน -3 ถึง -2
**Cost**: 0 (recruitment) + เริ่มจ่ายเงินเดือนเดือน -1
**Dependencies**: H1, C3 (manager onboard)

**Sub-steps:**

- [ ] ลงประกาศ:
  - MOU schools (จาก H1)
  - Facebook กลุ่ม "หานวดเชียงใหม่"
  - JobsDB
- [ ] Manager (C3) handle screen + interview
- [ ] Hiring process per spec Section 5:
  1. Resume screen (ใบ cert + experience)
  2. Trial massage 1hr (manager เป็น customer)
  3. Personality interview 40min
  4. Background check
  5. Probation 3 เดือน
- [ ] Hire 4 (เริ่ม start date เดือน -1)
- [ ] Lawyer ร่างสัญญาทุกคน + non-compete
- [ ] เซ็นสัญญา + ตรวจใบ cert ทุกคน (ขั้นต่ำ "นวดเพื่อสุขภาพ 372 ชม.")

**Done when**: 4 therapists เซ็นสัญญา start เดือน -1

---

### Task H3: Recruit Receptionist

**Goal**: 1 receptionist (English-speaking)
**Target month**: เดือน -2
**Cost**: 0 (recruitment) + เริ่มเงินเดือนเดือน -1
**Dependencies**: C3

**Sub-steps:**

- [ ] ลงประกาศ — เน้น: English working level, customer service experience, willing to learn massage industry
- [ ] Manager interview (English test สั้นๆ)
- [ ] Hire 1 (เผื่อ part-time 2 คน rotation cover 12hr)
- [ ] เซ็นสัญญา + commission 10% on memberships sold

**Done when**: Receptionist hired

---

### Task H4: Staff Training Program (14 วัน)

**Goal**: ทีมพร้อมเปิดร้าน
**Target month**: เดือน -1
**Cost**: ~10-15K (guest trainer + materials)
**Dependencies**: H2, H3, F2 (ร้านเสร็จ)

**Sub-steps:**

ใช้ schedule จาก spec Section 5 — 14-day program:

- [ ] Day 1: Brand & Concept (Owner + Manager)
- [ ] Day 2-7: Lanna Techniques (Senior Therapist + guest trainer)
- [ ] Day 8-9: SOP Walkthrough (Manager)
- [ ] Day 10-11: Hospitality (English vocab, etiquette)
- [ ] Day 12: Soft skills (objection handling, upsell)
- [ ] Day 13: Mock service full dry-run
- [ ] Day 14: Refresher + final QA

**Done when**: ทีมผ่าน final QA + พร้อมเปิด

---

## Track I — Operations Setup

### Task I1: Booking System + POS

**Goal**: Booking + payment ใช้งานได้
**Target month**: เดือน -2
**Cost**: ~20K (iPad refurb) + 1-2K/เดือน (Fresha SaaS)
**Dependencies**: E1 (brand)

**Sub-steps:**

- [ ] ซื้อ iPad refurbished
- [ ] Setup Fresha account — import services จาก spec Section 2
- [ ] Setup Loyverse POS (free) — link กับ booking
- [ ] Setup เครื่อง EDC (ขอจากแบงก์ที่เปิดบัญชีนิติบุคคล) — รับบัตรเครดิต/PromptPay
- [ ] Test workflow: customer book online → ปรากฏใน iPad → checkout pay → receipt
- [ ] Setup membership tier ใน Fresha
- [ ] Setup gift voucher / loyalty stamp

**Done when**: End-to-end booking + payment ทำงาน

---

### Task I2: SOP Documents

**Goal**: คู่มือทุกขั้นตอน — manager เปลี่ยนยังไง ส่งต่อได้
**Target month**: เดือน -2
**Cost**: 0 (DIY)
**Dependencies**: C3

**Sub-steps:**

- [ ] Owner + Manager เขียน SOP ตาม spec Section 5:
  - 9-step Customer Journey (with English/Thai script)
  - Hygiene SOP (ผ้า/ห้องน้ำ/เตียง/น้ำมัน/ลูกประคบ)
  - Safety SOP + contraindication checklist
  - Complaint handling (4-step process)
  - Refund Policy ("100% Satisfaction Guarantee")
  - Membership sales script
- [ ] Print + เก็บที่ reception 1 ชุด + manager 1 ชุด + cloud backup
- [ ] Train ทุกคน (รวมใน H4)

**Done when**: SOP doc ครบ + ทุกคนอ่านแล้ว

---

### Task I3: Financial Tracking Setup

**Goal**: ทราบ P&L + cashflow รายวัน/รายเดือน
**Target month**: เดือน -2
**Cost**: ~3-5K/เดือน (accountant retainer — A4)
**Dependencies**: A4

**Sub-steps:**

- [ ] Accountant setup:
  - Chart of accounts
  - Excel/software bookkeeping (PEAK Account, FlowAccount)
  - Daily cash log template
  - Monthly P&L report format
- [ ] Setup ภาษีหัก ณ ที่จ่ายระบบ — ภงด.1, 3, 53
- [ ] Setup VAT — register ก่อนรายได้ถึง 1.8M (อาจช้าก็ลงเดือน 4-5)
- [ ] Owner + Manager ทำ daily cash reconciliation routine

**Done when**: System live + first transaction ทดสอบผ่าน

---

## Track J — Soft Launch & Grand Opening

### Task J1: Soft Launch Preview

**Goal**: 20-30 Google reviews + content ก่อน opening day
**Target month**: เดือน -1 week 3-4
**Cost**: ~5-8K (free service × 30-50 คน × cost ~150 บาท/คน)
**Dependencies**: G1 (ใบ สบส.), H4 (training done), F2 (ร้านเสร็จ), E5 (photos)

**Sub-steps:**

- [ ] List 30-50 invitees จาก Facebook groups:
  - "Chiang Mai Digital Nomads"
  - "Chiang Mai Expats Club"
  - Coworking communities (Punspace, Yellow members)
  - Partner contacts (hotel concierges, gym staff)
- [ ] Send invitation: "Free preview + chance to be among first to review"
- [ ] Schedule 5-7 days, ~5-7 คน/วัน
- [ ] Each visit: free 60min service + ขอ Google review + tag IG
- [ ] Track: reviews collected, IG mentions, follow-up bookings

**Done when**: ≥20 Google reviews 4.5+ star + content for IG

---

### Task J2: Grand Opening Event

**Goal**: Press + influencer + community impact
**Target month**: เดือน 0 week 2 (Friday evening)
**Cost**: 25-30K
**Dependencies**: J1, E7

**Sub-steps:**

- [ ] Date: Friday evening 18:00-22:00
- [ ] Invite 50-80 คน:
  - Soft launch attendees ที่กลับมา (J1)
  - Influencers (จาก E7)
  - Hotel concierges + partners
  - Press (Citylife, Citylocating)
- [ ] Setup:
  - Welcome drink (สมุนไพร signature)
  - Bites (Lanna-themed, catered)
  - Free 15min mini massage stations (3 therapists rotate)
  - Photo booth
  - Live ดนตรี Lanna (1-2 hours)
- [ ] During event:
  - Owner + Manager work the room
  - Photographer + videographer capture content
  - Membership signup booth (intro promo)
- [ ] Follow-up day after: thank you message + Google review ask

**Done when**: Event done + ≥30 social posts shared + ≥5 members signed

---

### Task J3: Launch Month Operations

**Goal**: Hit Month 1 KPI (revenue 85K, 10 members)
**Target month**: เดือน 0 week 1 → end of month
**Cost**: covered ใน OpEx
**Dependencies**: All previous

**Sub-steps:**

- [ ] Soft opening week 1 (limited hours 12-20:00, friends/family discount 30%)
- [ ] Week 2: Grand opening (J2) → switch to full hours 10-22
- [ ] Daily routines:
  - Morning brief (manager 9:30am — review yesterday + today's bookings)
  - Cash reconciliation end of day
  - Google review ask every customer
  - Update IG stories minimum 3/day
- [ ] Weekly:
  - Team meeting (Sunday) — review numbers + issues + improvement
  - P&L snapshot
- [ ] Track every booking source (walk-in, Klook, IG, partner referral, Google search)

**Done when**: End of Month 1 — review KPIs, decide adjustments

---

# Phase 1+: Post-Launch (เดือน 1-12)

## Reference Tasks (revisit after Phase 0 complete)

ตามที่ระบุใน spec Section 9, Phase 1+ tasks depend heavily on data from Phase 0/1. ให้เปิดมาทำใหม่หลังเดือน 1 ผ่าน:

### Phase 2 (เดือน 1-3) — Survival
- Daily review velocity (Google reviews target 50+ by month 3)
- Weekly team meetings + monthly P&L
- Iterate menu/pricing weekly
- 🚨 Red flag check end of month 3: still not break-even → emergency pivot

### Phase 3 (เดือน 4-6) — Stabilization
- Optimize utilization (peak/off-peak pricing analysis)
- Add 1-2 services if data supports
- Hire 5th therapist
- Marketing budget upward 10K → 15-20K
- VAT registration (รายได้ใกล้ 1.8M)

### Phase 4 (เดือน 7-9) — Growth
- Annual Lanna Card launch
- Retreat partnerships
- Cash reserve building (target 2-month OpEx)

### Phase 5 (เดือน 10-12) — Scale Prep
- 4th bed installation if utilization >60%
- Branch 2 location scouting
- SOP fully documented for replication

### Year 1 Exit Decision
อ้างอิง spec Section 9 — ✅ Strong / ⚠️ OK / 🚨 Weak criteria

---

# Self-Review Checklist (ทำหลังจบ plan)

หลังทำ Phase 0 ครบ ก่อนเปิดร้าน owner + manager review:

- [ ] ใบอนุญาตทุกใบในมือ (สบส. + นิติบุคคล + TAX ID + ประกันสังคม + กรมธรรม์)
- [ ] เงินกู้เข้าบัญชี + working capital reserve 220K ยังครบ
- [ ] ทำเลพร้อม + decor 100%
- [ ] ทีม 5 คน + training ครบ
- [ ] Booking system + POS ทดสอบผ่าน
- [ ] SOP documented + ทุกคนอ่านแล้ว
- [ ] Marketing channels live (GBP, IG, FB, Klook, Viator, partners ≥3)
- [ ] Google reviews ≥20 (จาก soft launch)
- [ ] Plan B fund 100K ระบุว่าหาได้จากไหน (ครอบครัว/วงเงินเสริม)

ทุกข้อ check → 🚀 พร้อมเปิด

---

## Key Contacts & Resources

**Government:**
- กรมพัฒนาธุรกิจการค้า เชียงใหม่ — บริการจดบริษัท
- กรมสรรพากร เชียงใหม่ — ขอ TAX ID
- สบส. เชียงใหม่ (053-217-115) — ใบอนุญาตสปา
- กรมพัฒนาฝีมือแรงงาน เชียงใหม่ (053-121-002) — หลักสูตร 100 ชม.
- ประกันสังคม เชียงใหม่
- เทศบาลนครเชียงใหม่ — ใบอนุญาตป้าย

**Banks:**
- ออมสิน สาขาใหญ่เชียงใหม่ — GSB-IGNITE / SMEs Start-up
- กรุงไทย สาขาใหญ่เชียงใหม่ — SME D-MoneyConnect
- บสย. (Thai Credit Guarantee) — เครดิตค้ำประกัน

**Industry:**
- ITM Chiang Mai (053-218-632) — หลักสูตรนวด + manager network
- Lanna Massage School (Wat Phra Singh area)
- Thai Spa Association

**Online:**
- DBD e-Service: <https://www.dbd.go.th/>
- บสย.: <https://www.tcg.or.th/>
- Klook Partner: <https://partners.klook.com/>
- Google Business: <https://www.google.com/business>

---

## Open Questions / Decisions Pending

ตาม spec ยังต้องตัดสิน:

- [ ] ชื่อร้านขั้นสุดท้าย (working: Khum Lanna Spa)
- [ ] วงเงินกู้แน่นอน (700K vs 800K) — ขึ้นกับ equity
- [ ] เลือกธนาคารหลัก (เปรียบเทียบหลังยื่น 2 เจ้า)
- [ ] เจ้าของเรียน 100 ชม. ที่สถาบันไหน
- [ ] Manager candidate ตัวจริง

อัพเดท `docs/superpowers/specs/2026-05-09-massage-shop-business-plan-design.md` เมื่อตัดสินใจ
