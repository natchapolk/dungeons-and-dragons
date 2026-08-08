# พรานป่า (Ranger)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**เรนเจอร์ / พรานป่า (Ranger)** คือนักล่าผู้เชี่ยวชาญถิ่นทุรกันดาร ผสมผสาน **การต่อสู้ + การติดตาม + เวทธรรมชาติ** พวกเขาเป็น **นักสอดแนม (Scout)** ที่ดีที่สุดในเกม

> **กฎ 2024 บัฟ Ranger อย่างมาก** — เปลี่ยน Favored Enemy เดิม (ที่แทบไม่มีประโยชน์) เป็นการร่าย **`Hunter's Mark` ฟรี** และเพิ่ม **Weapon Mastery**

---

## ข้อมูลพื้นฐาน (Class Table)

| หัวข้อ | ค่า |
|---|---|
| **Primary Ability** | **Dexterity (DEX)** และ **Wisdom (WIS)** |
| **Hit Die** | **d10** |
| **HP เลเวล 1** | **10 + CON modifier** |
| **HP เลเวลถัดไป** | **1d10 + CON** (หรือค่าคงที่ **6 + CON**) |
| **Saving Throw Proficiency** | **Strength, Dexterity** |
| **Armor Proficiency** | Light, Medium Armor, **Shield** |
| **Weapon Proficiency** | Simple Weapons, **Martial Weapons** |
| **Skill Proficiency** | เลือก **3** จาก: **Animal Handling, Athletics, Insight, Investigation, Nature, Perception, Stealth, Survival** |
| **Weapon Mastery** | **2 ชนิด** |
| **Spellcasting Ability** | **Wisdom (WIS)** |
| **Subclass** | เลือกที่ **เลเวล 3** |

### อุปกรณ์เริ่มต้น

**เลือก A:** Studded Leather Armor, Scimitar, Shortsword, Longbow + 20 Arrows, Quiver, Druidic Focus (ไม้เท้า), Explorer's Pack, **7 GP**
**เลือก B:** **150 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

| เลเวล | Prof<br>Bonus | Features | Favored<br>Enemy | เตรียม<br>สเปล | Slot<br>1 | Slot<br>2 | Slot<br>3 | Slot<br>4 | Slot<br>5 |
|---|---|---|---|---|---|---|---|---|---|
| **1** | +2 | **Spellcasting**, **Favored Enemy** [แนะนำ], **Weapon Mastery** | **2** | 2 | **2** | — | — | — | — |
| **2** | +2 | **Deft Explorer** [แนะนำ], **Fighting Style** | 2 | 3 | 2 | — | — | — | — |
| **3** | +2 | **Ranger Subclass** [แนะนำ] | 2 | 4 | **3** | — | — | — | — |
| **4** | +2 | **ASI** | 2 | 5 | 3 | — | — | — | — |
| **5** | **+3** | **Extra Attack** [แนะนำ] | **3** | 6 | **4** | **2** | — | — | — |
| **6** | +3 | **Roving** | 3 | 6 | 4 | 2 | — | — | — |
| **7** | +3 | **Subclass Feature** | 3 | 7 | 4 | **3** | — | — | — |
| **8** | +3 | **ASI** | 3 | 7 | 4 | 3 | — | — | — |
| **9** | **+4** | **Expertise** [แนะนำ] | **4** | 9 | 4 | 3 | **2** | — | — |
| **10** | +4 | **Tireless** | 4 | 9 | 4 | 3 | 2 | — | — |
| **11** | +4 | **Subclass Feature** | 4 | 10 | 4 | 3 | **3** | — | — |
| **12** | +4 | **ASI** | 4 | 10 | 4 | 3 | 3 | — | — |
| **13** | **+5** | **Relentless Hunter** [แนะนำ] | **5** | 11 | 4 | 3 | 3 | **1** | — |
| **14** | +5 | **Nature's Veil** | 5 | 11 | 4 | 3 | 3 | 1 | — |
| **15** | +5 | **Subclass Feature** | 5 | 12 | 4 | 3 | 3 | **2** | — |
| **16** | +5 | **ASI** | 5 | 12 | 4 | 3 | 3 | 2 | — |
| **17** | **+6** | **Precise Hunter** [แนะนำ] | **6** | 14 | 4 | 3 | 3 | 3 | **1** |
| **18** | +6 | **Feral Senses** | 6 | 14 | 4 | 3 | 3 | 3 | 1 |
| **19** | +6 | **Epic Boon Feat** | 6 | 15 | 4 | 3 | 3 | 3 | **2** |
| **20** | +6 | **Foe Slayer** | 6 | 15 | 4 | 3 | 3 | 3 | 2 |

> **Ranger ไม่มี Cantrip**

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 — ศัตรูที่ถูกเลือก (Favored Enemy) กฎใหม่ 2024

> - **สเปล `Hunter's Mark` เป็นสเปลที่เตรียมไว้เสมอ** (ไม่นับโควตา)
> - **ร่ายฟรีได้ตามจำนวนในตาราง (2-6 ครั้ง) ต่อ Long Rest โดยไม่เสีย Spell Slot**

### สเปล ระดับ 1, Divination (`Hunter's Mark`) [C]

| หัวข้อ | รายละเอียด |
|---|---|
| **Casting Time** | **Bonus Action** |
| **Range** | 90 ฟุต |
| **Duration** | **Concentration, 1 ชั่วโมง** |
| **ผล** | ทำเครื่องหมายศัตรู 1 ตัว <br>• **การโจมตีด้วยอาวุธของคุณต่อมัน เพิ่มดาเมจ `1d6 Force`**<br>• **ถ้ามันตาย ย้ายเครื่องหมายไปตัวใหม่ได้ด้วย Bonus Action ฟรี** |
| **ใช้ Slot สูงกว่า** | ระดับ 3-4: **Concentration 8 ชั่วโมง** • ระดับ 5+: **24 ชั่วโมง** |

**ทำไมนี่คือการบัฟที่สำคัญที่สุดของ Ranger ในกฎ 2024:**

```
เลเวล 5 (Extra Attack) + Hunter's Mark:
โจมตี 2 ครั้ง × (1d8 ธนู + 4 DEX + 1d6 Hunter's Mark)
= ~25 ดาเมจต่อเทิร์น ฟรี ๆ ทุกการต่อสู้
```

> **ข้อควรระวัง:** `Hunter's Mark` ใช้ **Concentration** — ร่ายสเปล Concentration อื่นไม่ได้พร้อมกัน

---

### เลเวล 1 — Spellcasting

> - ใช้ **Wisdom** เป็นค่าร่ายเวท
> - **Spell Save DC = 8 + WIS modifier + Proficiency Bonus**
> - **Spell Attack = WIS modifier + Proficiency Bonus**
> - **เปลี่ยนสเปลที่เตรียมไว้ได้ 1 อัน ทุกครั้งที่เลื่อนเลเวล** (ไม่ใช่ทุก Long Rest เหมือน Cleric/Paladin)
> - **Spellcasting Focus:** **กิ่งไม้ ไม้เท้า (Druidic Focus)**

---

### เลเวล 1 — Weapon Mastery

> เลือกอาวุธ **2 ชนิด** ปลดล็อก Mastery Property

** แนะนำ:**

| แนวทาง | อาวุธ + Mastery |
|---|---|
| **สายธนู** [แนะนำ] | **Longbow (Slow)** + **Shortsword (Vex)** |
| **สายสองอาวุธ** | **Scimitar (Nick)** + **Shortsword (Vex)** |
| **สายดาบ+โล่** | **Rapier (Vex)** + **Javelin (Slow)** |

---

### เลเวล 2 — นักสำรวจชำนาญ (Deft Explorer)

> - **ได้ Expertise ใน Skill 1 อย่าง** [แนะนำ] ที่คุณมี Proficiency
> - **เรียนภาษาเพิ่ม 2 ภาษา**

> **แนะนำ Expertise ใน `Perception` หรือ `Stealth`**

---

### เลเวล 2 — Fighting Style

> ได้ **Fighting Style Feat 1 อัน**

** แนะนำสำหรับ Ranger:**

| Fighting Style | เหมาะกับ |
|---|---|
| **+2 โจมตีระยะไกล (Archery)** [แนะนำมาก] | **สายธนู — ตัวเลือกที่ดีที่สุด** |
| **Two-Weapon Fighting** | สายสองอาวุธ |
| **Defense** (+1 AC) | สายดาบ+โล่ |
| **Druidic Warrior** [แนะนำ] | **ได้ Cantrip จากรายการ Druid 2 อัน** — แก้ปัญหาที่ Ranger ไม่มี Cantrip (แนะนำ `Guidance` + `Shillelagh`/`Starry Wisp`) |

---

### เลเวล 5 — Extra Attack

> **โจมตีได้ 2 ครั้ง** เมื่อใช้ Attack action

> **นี่คือจุดที่ Ranger กลายเป็นคลาสดาเมจที่ดี** — 2 ครั้ง × Hunter's Mark

---

### เลเวล 6 — เร่ร่อน (Roving)

> - **Speed +10 ฟุต** (ตอนไม่ใส่ Heavy Armor)
> - **ได้ Climb Speed และ Swim Speed เท่ากับ Speed** [แนะนำ]

**ทำไมดี:** ปีนกำแพงและว่ายน้ำได้เร็วเท่าเดิน — เป็นหน่วยสอดแนมที่ไปได้ทุกที่

---

### เลเวล 9 — ครั้งที่ 2 (Expertise)

> ได้ **Expertise ใน Skill อีก 2 อย่าง**

---

### เลเวล 10 — ไม่รู้เหนื่อย (Tireless)

> - **Magic action:** ให้ **Temp HP = `1d8 + WIS modifier`** แก่ตัวเอง — ใช้ได้ **Prof Bonus ครั้ง/Long Rest**
> - **ทุกครั้งที่จบ Short Rest ลด Exhaustion 1 ระดับ** [แนะนำ]

---

### เลเวล 13 — นักล่าไม่ลดละ (Relentless Hunter)

> **การได้รับดาเมจไม่ทำให้ Concentration ของ `Hunter's Mark` ขาด**

**ทำไมดี:** แก้จุดอ่อนที่ใหญ่ที่สุดของ Ranger — ไม่ต้องกลัวเสีย Hunter's Mark ตอนโดนตีอีกต่อไป

---

### เลเวล 14 — ม่านธรรมชาติ (Nature's Veil)

> **Bonus Action:** กลายเป็น **Invisible** จนถึงจบเทิร์นหน้าของคุณ
> **ใช้ได้ Prof Bonus ครั้ง/Long Rest**

**ทำไมดี:** ได้ **Advantage ในการโจมตี** + ศัตรูตีเราเสียเปรียบ + หนีได้

---

### เลเวล 17 — นักล่าแม่นยำ (Precise Hunter)

> **คุณมี Advantage ในการทอยโจมตีศัตรูที่ติด `Hunter's Mark` ของคุณ**

---

### เลเวล 18 — ประสาทสัมผัสสัตว์ป่า (Feral Senses)

> - ได้ **Blindsight 30 ฟุต** — รับรู้สิ่งรอบตัวโดยไม่ต้องใช้ตา (เห็นสิ่งที่ Invisible ในระยะนี้)

---

### เลเวล 20 — นักสังหารศัตรู (Foe Slayer) — Capstone

> **เต๋าของ `Hunter's Mark` เปลี่ยนจาก d6 เป็น `d10`**
> **และคุณสามารถเปลี่ยนเป้าหมาย `Hunter's Mark` ได้ฟรี (ไม่ใช้ Bonus Action) 1 ครั้งต่อเทิร์น**

---

## Subclasses (Ranger Subclass) — เลือกที่เลเวล 3

Ranger มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 7, 11, 15**
**ทุก Subclass ให้ "Subclass Spells" ที่เตรียมไว้เสมอ**

---

### 1. Hunter — นักล่า

> **ธีม:** นักล่ามอนสเตอร์ผู้เชี่ยวชาญ — **ดาเมจสูงและง่ายที่สุด**

**Subclass Spells:**

| เลเวล | สเปล |
|---|---|
| 3 | `Hunter's Mark` (ได้จาก Favored Enemy อยู่แล้ว) |
| 5 | `Pass Without Trace` |
| 9 | `Conjure Barrage` |
| 13 | `Grasping Vine` |
| 17 | `Volley` / `Conjure Volley` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Hunter's Lore** | **รู้ Immunity, Resistance, และ Vulnerability** ของศัตรูที่ติด `Hunter's Mark` ของคุณ |
| **3** | **Hunter's Prey** | [แนะนำ] เลือก 1 อย่าง (เปลี่ยนได้ตอน Long Rest):<br>• **Colossus Slayer** — **1 ครั้ง/เทิร์น:** เพิ่ม **1d8** ถ้าเป้าหมาย **HP ไม่เต็ม**<br>• **Horde Breaker** — **1 ครั้ง/เทิร์น:** โจมตีศัตรูตัวที่ 2 ที่อยู่ในระยะ 5 ฟุตจากเป้าหมายแรก |
| **7** | **Defensive Tactics** | เลือก 1 อย่าง (เปลี่ยนได้ตอน Long Rest):<br>• **Escape the Horde** — **ศัตรูตี Opportunity Attack ใส่คุณแบบเสียเปรียบ**<br>• **Multiattack Defense** — เมื่อศัตรูตีคุณโดน **การโจมตีที่เหลือของมันในเทิร์นนั้นเสียเปรียบ** |
| **11** | **Superior Hunter's Prey** | **1 ครั้ง/เทิร์น:** [แนะนำมาก] เมื่อทำดาเมจศัตรูที่ติด `Hunter's Mark` **ศัตรูอีก 1 ตัวในระยะ 30 ฟุตจากเป้าหมาย ก็รับดาเมจ Hunter's Mark ด้วย** |
| **15** | **Superior Hunter's Defense** | **Reaction:** เมื่อรับดาเมจ **ได้ Resistance ต่อดาเมจนั้นและดาเมจประเภทเดียวกัน** จนกว่าจะเริ่มเทิร์นหน้าของคุณ |

> **แนะนำมือใหม่ที่สุด** — ดาเมจตรง ๆ ไม่มีอะไรให้จัดการเพิ่ม

---

### 2. Gloom Stalker — นักสะกดรอยเงามืด

> **ธีม:** ผู้ล่าในความมืด — **แรงที่สุดในเทิร์นแรก**

**Subclass Spells:**

| เลเวล | สเปล |
|---|---|
| 3 | `Disguise Self` |
| 5 | `Rope Trick` |
| 9 | `Fear` |
| 13 | `Greater Invisibility` |
| 17 | `Seeming` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Dread Ambusher** | [แนะนำมาก] • **Bonus Action:** ทำ **Dread Ambusher Attack** — โจมตี 1 ครั้ง เพิ่มดาเมจ **`Prof Bonus` เป็น Psychic** (ใช้ได้ Prof Bonus ครั้ง/Long Rest)<br>• **เมื่อทอย Initiative: ได้ Speed +10 ฟุต ในเทิร์นแรก** และ **Bonus Action ใช้ Dread Ambusher ฟรี** |
| **3** | **Umbral Sight** | [แนะนำ] • **หรือ +60 ถ้ามีอยู่แล้ว (Darkvision 60 ft)**<br>• **คุณ Invisible ต่อสิ่งมีชีวิตที่ใช้ Darkvision มองหาคุณในความมืด** [แนะนำมาก] |
| **7** | **Iron Mind** | ได้ **Proficiency ใน Wisdom Saving Throw** (หรือ INT/CHA ถ้ามี WIS อยู่แล้ว) |
| **11** | **Stalker's Flurry** | **1 ครั้ง/เทิร์น** [แนะนำ] เมื่อ Dread Ambusher Attack **พลาด** **โจมตีซ้ำอีก 1 ครั้ง** • หรือถ้าโดน เลือกผล **โจมตีศัตรูอีกตัว (Sudden Strike)** หรือ **เพิ่มดาเมจ Psychic ให้ศัตรูรอบข้าง (Mote of Potential)** |
| **15** | **Shadowy Dodge** | **Reaction:** เมื่อศัตรูโจมตีคุณ **ทำให้การโจมตีนั้นเสียเปรียบ** และถ้าพลาด **โจมตีกลับ 1 ครั้ง** |

> **สายที่โด่งดังว่าแรงที่สุด** — เทิร์นแรกโจมตี 3 ครั้ง (2 จาก Extra Attack + 1 จาก Dread Ambusher)

---

### 3. Fey Wanderer — นักเดินทางแดนภูต

> **ธีม:** Ranger ผู้ได้รับพลังจาก Feywild — **เก่งเข้าสังคมที่สุด**

**Subclass Spells:**

| เลเวล | สเปล |
|---|---|
| 3 | `Charm Person` |
| 5 | `Misty Step` |
| 9 | `Dispel Magic` |
| 13 | `Dimension Door` |
| 17 | `Mislead` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Dreadful Strikes** | **1 ครั้ง/เทิร์น:** [แนะนำ] เมื่อตีโดนด้วยอาวุธ เพิ่มดาเมจ **`1d4 Psychic`** (เพิ่มเป็น 1d6 ที่เลเวล 11) |
| **3** | **Otherworldly Glamour** | **บวก WIS modifier ในการทอย Charisma Check ทั้งหมด** [แนะนำ] (ขั้นต่ำ +1) • และได้ Proficiency ใน **Deception, Performance, หรือ Persuasion** 1 อย่าง |
| **7** | **Beguiling Twist** | • **Advantage ในการทอย Save ต้าน Charmed และ Frightened**<br>• **Reaction:** เมื่อใครก็ตามในระยะ 120 ฟุต Save สำเร็จต่อสภาวะ Charmed/Frightened **บังคับให้สิ่งมีชีวิตที่คุณเลือกทอย WIS Save — ล้มเหลว = Charmed หรือ Frightened โดยคุณ 1 นาที** |
| **11** | **Fey Reinforcements** | [แนะนำ] ได้สเปล **`Summon Fey`** เตรียมไว้เสมอ และ **ร่ายฟรี 1 ครั้ง/Long Rest** • ร่ายได้โดยไม่ต้อง Concentration |
| **15** | **Misty Wanderer** | **ร่าย `Misty Step` โดยไม่เสีย Spell Slot ได้ Prof Bonus ครั้ง/Long Rest** [แนะนำ] • และ**พาเพื่อน 1 คนในระยะ 5 ฟุตไปด้วยได้** |

> **สายที่ทำให้ Ranger เป็น "หน้ากลุ่ม" ได้** — WIS สูงอยู่แล้ว บวกเข้าไปใน CHA Check ทั้งหมด

---

### 4. Beast Master — เจ้าแห่งสัตว์

> **ธีม:** Ranger ที่มีสัตว์คู่ใจร่วมรบ (Primal Companion)

**Subclass Spells:**

| เลเวล | สเปล |
|---|---|
| 3 | `Animal Friendship` |
| 5 | `Beast Sense` |
| 9 | `Conjure Animals` |
| 13 | `Stoneskin` |
| 17 | `Commune with Nature` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Primal Companion** | [แนะนำมาก] เรียกสัตว์วิญญาณคู่ใจด้วย **ใช้เวลา 1 ชั่วโมง (Magic action)** — เลือก 1 แบบ:<br> **Beast of the Sky** — บินได้ 60 ฟุต ว่องไว<br> **Beast of the Land** — แข็งแรง ทำให้ศัตรู Prone ได้<br> **Beast of the Sea** — ว่ายน้ำ + Grapple เก่ง<br><br>• สัตว์เล่นในเทิร์นของคุณ — คุณใช้ **Bonus Action สั่งให้มันโจมตี**<br>• มัน **เคลื่อนที่และทำ Action อื่นได้เองฟรี**<br>• **HP = 5 × เลเวล Ranger** • **โบนัสของมันใช้ Proficiency Bonus ของคุณ**<br>• ถ้าตาย เรียกใหม่ได้ (ฟรี 1 ครั้ง/Long Rest หรือใช้ Spell Slot) |
| **7** | **Exceptional Training** | [แนะนำ] เมื่อใช้ **Bonus Action** สั่งสัตว์ มันสามารถใช้ **Dash, Disengage, Dodge, หรือ Help** ได้ด้วย • และ **การโจมตีของมันนับเป็น Magical** |
| **11** | **Bestial Fury** | **สัตว์ของคุณโจมตี 2 ครั้ง** [แนะนำมาก] เมื่อคุณสั่งให้มันโจมตี • และ **1 ครั้ง/เทิร์น** เมื่อมันตีโดนศัตรูที่ติด `Hunter's Mark` **เพิ่มดาเมจ Hunter's Mark** |
| **15** | **Share Spells** | [แนะนำ] เมื่อคุณร่ายสเปลใส่ตัวเอง **สัตว์ของคุณในระยะ 30 ฟุตได้รับผลด้วย** |

> **ต้องจัดการ 2 ตัวละครในเทิร์นเดียว** — ทำให้เกมช้าลง แต่ดาเมจรวมสูงมาก

---

## เปรียบเทียบ 4 Subclass

| | **Hunter** | **Gloom Stalker** | **Fey Wanderer** | **Beast Master** |
|---|---|---|---|---|
| **จุดเด่น** | ดาเมจสม่ำเสมอ | **แรงที่สุดเทิร์นแรก** | เข้าสังคม + ควบคุม | มีสัตว์คู่ใจ |
| **ความยาก** | ง่ายสุด | ง่าย | กลาง | ยาก (คุม 2 ตัว) |
| **นอกการต่อสู้** | ต่ำ | สูง (ลอบเร้น) | **สูงสุด** | สูง (สัตว์สอดแนม) |
| **แนะนำมือใหม่** | **ใช่** | **ใช่** | ใช่ | ไม่ |

---
---

# รายการเวทของ Ranger (Ranger Spell List)

> **Ranger ไม่มี Cantrip** (ยกเว้นเอา Fighting Style `Druidic Warrior`)
> **เปลี่ยนสเปลที่เตรียมไว้ได้ 1 อัน ทุกครั้งที่เลื่อนเลเวล**
> **[C] = Concentration** | **[R] = Ritual**

---

## สเปลระดับ 1 (Level 1 Spells)

| สเปล | ทำอะไร |
|---|---|
| **สัญญาณเตือน (Alarm)** [R] | ตั้งสัญญาณเตือนในพื้นที่ 20 ฟุต เป็นเวลา 8 ชั่วโมง |
| **ผูกมิตรสัตว์ (Animal Friendship)** | สัตว์ทอย WIS Save — ล้มเหลว = **Charmed 24 ชั่วโมง** |
| **รักษาบาดแผล (Cure Wounds)** [แนะนำ] | สัมผัส ฟื้น **2d8 + WIS** HP |
| **ตรวจจับเวท (Detect Magic)** [C][R] | รับรู้เวทมนตร์ในระยะ 30 ฟุต |
| **ตรวจจับพิษและโรค (Detect Poison and Disease)** [C][R] | รับรู้พิษและโรคในระยะ 30 ฟุต |
| **โจมตีดักจับ (Ensnaring Strike)** [แนะนำ] [C] | **Bonus Action หลังตีโดน:** เป้าหมายทอย STR Save — ล้มเหลว = **Restrained + 1d6 Piercing ทุกเทิร์น** |
| **เถาวัลย์พันธนาการ (Entangle)** [C] | พื้นที่ 20 ฟุต — ศัตรูทอย STR Save ล้มเหลว = **Restrained** |
| **หมอกคลุม (Fog Cloud)** [C] | ทรงกลม 20 ฟุต — **บังสายตาทั้งหมด (Heavily Obscured)** |
| **เบอร์รี่วิเศษ (Goodberry)** [แนะนำ] | สร้างเบอร์รี่ 10 ลูก — แต่ละลูกฟื้น **1 HP** และให้อาหารครบ 1 วัน (**ใช้ Bonus Action กินได้**) |
| **ห่าหนาม (Hail of Thorns)** [C] | **Bonus Action หลังยิงโดน:** ศัตรูรอบเป้าหมาย 5 ฟุต ทอย DEX Save — **1d10 Piercing** |
| **เครื่องหมายนักล่า (Hunter's Mark)** [แนะนำมาก] [C] | **+1d6 ดาเมจทุกครั้งที่ตีเป้าหมายนั้น** (เตรียมไว้เสมอ) |
| **กระโดด (Jump)** | ระยะกระโดดของเป้าหมาย **เพิ่มเป็น 3 เท่า** |
| **ก้าวยาว (Longstrider)** | **Speed +10 ฟุต** เป็นเวลา 1 ชั่วโมง |
| **พูดกับสัตว์ (Speak with Animals)** [R] | สื่อสารกับสัตว์ได้ 10 นาที |

> **แนะนำที่เลเวล 1-4:** `Cure Wounds` + `Goodberry` (หรือ `Ensnaring Strike` ถ้าเน้นควบคุม)

---

## สเปลระดับ 2 (Level 2 Spells) — ได้ที่เลเวล 5

| สเปล | ทำอะไร |
|---|---|
| **ช่วยเหลือ (Aid)** [แนะนำ] | เพื่อน 3 คน **HP สูงสุด +5 และฟื้น 5 HP** 8 ชั่วโมง |
| **ส่งสารด้วยสัตว์ (Animal Messenger)** [R] | ส่งข้อความผ่านสัตว์เล็ก |
| **ผิวเปลือกไม้ (Barkskin)** | **AC ขั้นต่ำเป็น 17** (ถ้า AC ต่ำกว่านั้น) |
| **สัมผัสสัตว์ (Beast Sense)** [C][R] | มองผ่านตาสัตว์ที่ยินยอม |
| **แนวธนู (Cordon of Arrows)** | ปักลูกธนู 4 ดอก — ยิงอัตโนมัติเมื่อศัตรูเข้าใกล้ 30 ฟุต |
| **มองในมืด (Darkvision)** | ให้ Darkvision 60 ฟุต 8 ชั่วโมง |
| **เสริมความสามารถ (Enhance Ability)** [C] | เป้าหมายได้ **Advantage ใน Ability Check ของค่าที่เลือก** |
| **หากับดัก (Find Traps)** | รู้ว่ามีกับดักในระยะ 120 ฟุตหรือไม่ |
| **ลมกระโชก (Gust of Wind)** [C] | เส้น 60 ฟุต — ศัตรูทอย STR Save ล้มเหลว = **ผลัก 15 ฟุต** |
| **ฟื้นฟูขั้นต้น (Lesser Restoration)** [แนะนำ] | ลบสภาวะ Blinded, Deafened, Paralyzed, หรือ Poisoned |
| **ค้นหาสัตว์หรือพืช (Locate Animals or Plants)** [R] | รู้ตำแหน่งสัตว์/พืชชนิดที่ระบุในระยะ 5 ไมล์ |
| **ค้นหาวัตถุ (Locate Object)** [C] | รู้ตำแหน่งวัตถุที่คุ้นเคยในระยะ 1,000 ฟุต |
| **อาวุธเวท (Magic Weapon)** | อาวุธได้ **+1 โจมตีและดาเมจ** และนับเป็น Magical |
| **ไร้ร่องรอย (Pass Without Trace)** [แนะนำมาก] [C] | **+10 Stealth ให้ทั้งทีม** และไม่ทิ้งร่องรอย — สเปลลอบเร้นที่ดีที่สุดในเกม |
| **ป้องกันพิษ (Protection from Poison)** | ลบพิษ + Advantage ต้านพิษ + Resistance Poison 1 ชั่วโมง |
| **ความเงียบ (Silence)** [C][R] | ทรงกลม 20 ฟุต — **ไม่มีเสียงใด ๆ** (ศัตรูร่ายเวทที่มี Verbal ไม่ได้!) |
| **หนามแหลม (Spike Growth)** [แนะนำ] [C] | พื้นที่ 20 ฟุตกลายเป็น Difficult Terrain + **2d4 ดาเมจต่อการเคลื่อนที่ 5 ฟุต** |
| **เรียกสัตว์ (Summon Beast)** | เรียกสัตว์วิญญาณมาช่วยรบ 1 ชั่วโมง |

> **แนะนำ:** `Pass Without Trace` [แนะนำมาก] + `Spike Growth` [แนะนำ] (คอมโบกับ Ranger สายควบคุม)

---

## สเปลระดับ 3 (Level 3 Spells) — ได้ที่เลเวล 9

| สเปล | ทำอะไร |
|---|---|
| **เรียกฝูงสัตว์ (Conjure Animals)** [แนะนำ] [C] | เรียกวิญญาณสัตว์ป่ามาช่วยรบ — สร้างพื้นที่ Difficult Terrain + ดาเมจ |
| **ห่ากระสุน (Conjure Barrage)** | กรวย 60 ฟุต — ศัตรูทอย DEX Save — **5d8** ดาเมจตามอาวุธที่ใช้ |
| **แสงตะวัน (Daylight)** | แสงสว่างรัศมี 60 ฟุต |
| **สลายเวท (Dispel Magic)** [แนะนำ] | ยกเลิกสเปลระดับ 3 หรือต่ำกว่า |
| **อาวุธธาตุ (Elemental Weapon)** [C] | อาวุธได้ +1 โจมตี และ +1d4 ดาเมจธาตุ |
| **ลูกศรสายฟ้า (Lightning Arrow)** [C] | **Bonus Action หลังยิง:** เป้าหมายรับ **4d8 Lightning** + ศัตรูรอบ 10 ฟุตรับ 2d8 |
| **หลอมกับหิน (Meld into Stone)** [R] | ซ่อนตัวในหิน 8 ชั่วโมง |
| **ป้องกันการตรวจจับ (Nondetection)** | ป้องกันการถูกตรวจจับด้วยเวท 8 ชั่วโมง |
| **เร่งการเติบโตพืช (Plant Growth)** | พื้นที่ 100 ฟุตกลายเป็น Difficult Terrain (หรือเพิ่มผลผลิตพืช) |
| **ป้องกันธาตุ (Protection from Energy)** [แนะนำ] [C] | **Resistance ต่อธาตุที่เลือก** 1 ชั่วโมง |
| **ชุบชีวิต (Revivify)** [แนะนำมาก] | ชุบชีวิตผู้ที่ตายไม่เกิน 1 นาที (ต้องใช้เพชร 300 GP) |
| **พูดกับพืช (Speak with Plants)** | สื่อสารกับพืชในระยะ 30 ฟุต |
| **เรียกภูต (Summon Fey)** | เรียกสิ่งมีชีวิต Fey มาช่วยรบ |
| **หายใจใต้น้ำ (Water Breathing)** [R] | 10 คนหายใจใต้น้ำได้ 24 ชั่วโมง |
| **เดินบนน้ำ (Water Walk)** [R] | 10 คนเดินบนของเหลวได้ 1 ชั่วโมง |
| **กำแพงลม (Wind Wall)** [C] | กำแพงลม 50 ฟุต — บล็อกลูกธนูและแก๊ส |

---

## สเปลระดับ 4 (Level 4 Spells) — ได้ที่เลเวล 13

| สเปล | ทำอะไร |
|---|---|
| **เรียกภูตพนา (Conjure Woodland Beings)** [C] | เรียกวิญญาณป่ามาช่วย — โจมตีศัตรูรอบตัวคุณ |
| **ครอบงำสัตว์ (Dominate Beast)** [C] | ควบคุมสัตว์ 1 ตัว |
| **อิสระในการเคลื่อนที่ (Freedom of Movement)** [แนะนำ] | **ไม่ติด Difficult Terrain, Grappled, Restrained, Paralyzed** และไม่ถูกลด Speed 1 ชั่วโมง |
| **เถาวัลย์คว้า (Grasping Vine)** [C] | เถาวัลย์ดึงศัตรูมา 20 ฟุต (Bonus Action ทุกเทิร์น) |
| **ค้นหาสิ่งมีชีวิต (Locate Creature)** [C] | รู้ตำแหน่งสิ่งมีชีวิตที่คุ้นเคย |
| **ผิวหิน (Stoneskin)** [C] | **Resistance ต่อ Bludgeoning, Piercing, Slashing** ที่ไม่ใช่เวท |
| **เรียกธาตุ (Summon Elemental)** [C] | เรียกวิญญาณธาตุมาช่วยรบ |

---

## สเปลระดับ 5 (Level 5 Spells) — ได้ที่เลเวล 17

| สเปล | ทำอะไร |
|---|---|
| **สื่อสารกับธรรมชาติ (Commune with Nature)** [R] | รู้ข้อมูลเกี่ยวกับพื้นที่รอบตัวในรัศมี 3 ไมล์ |
| **ห่าลูกศร (Conjure Volley)** | ทรงกระบอกรัศมี 40 ฟุต — **8d8** ดาเมจตามอาวุธ |
| **ฟื้นฟูขั้นสูง (Greater Restoration)** [แนะนำ] | ลบ Exhaustion 1 ระดับ / คำสาป / Charmed / Petrified ฯลฯ |
| **ลมเหล็ก (Steel Wind Strike)** [แนะนำมาก] | **วาร์ปโจมตีศัตรูได้ถึง 5 ตัว** ในระยะ 30 ฟุต — **6d10 Force** แต่ละตัว |
| **แล่งธนูรวดเร็ว (Swift Quiver)** [แนะนำ] [C] | **Bonus Action ทุกเทิร์น: ยิงธนู 2 ครั้งเพิ่ม** 1 นาที |
| **ก้าวผ่านต้นไม้ (Tree Stride)** [C] | วาร์ปจากต้นไม้หนึ่งไปอีกต้น (ระยะ 500 ฟุต) |

---

## คำแนะนำการสร้าง Ranger

### แนวทางที่ 1: DEX Ranger สายธนู (แนะนำที่สุด)

```
DEX 17 WIS 14 CON 14 STR 10 INT 10 CHA 8
Armor: Studded Leather Half Plate
Weapon: Longbow (+ Shortsword สำรอง)
Fighting Style: Archery [แนะนำ]
Weapon Mastery: Longbow (Slow) + Shortsword (Vex)
Feat แนะนำ: Sharpshooter [แนะนำ], ASI (DEX)
Subclass: Hunter หรือ Gloom Stalker
```

### แนวทางที่ 2: DEX Ranger สองอาวุธ

```
DEX 17 WIS 14 CON 15 STR 10 INT 10 CHA 8
Armor: Studded Leather
Weapon: Scimitar + Shortsword
Fighting Style: Two-Weapon Fighting
Weapon Mastery: Scimitar (Nick) [แนะนำ] + Shortsword (Vex)
```
> **Nick ทำให้โจมตีมือสองได้โดยไม่เสีย Bonus Action** เอา Bonus Action ไปร่าย `Hunter's Mark` ได้

### Species ที่แนะนำ
| Species | เหตุผล |
|---|---|
| **Elf (Wood)** [แนะนำมาก] | Speed 35 + `Pass Without Trace` ฟรี + Perception เข้าธีมเต็ม |
| **Human** [แนะนำ] | Feat ฟรี |
| **Halfling** | Luck + ซ่อนตัวเก่ง |
| **Goliath** | Speed 35 |
| **Orc / Dwarf** | Darkvision 120 ft (ดีต่อ Gloom Stalker) |

### Background ที่แนะนำ
**Guide** (DEX/CON/WIS) [แนะนำมาก] (ตรงเป๊ะ + ได้ Magic Initiate Druid) • **Sailor** (STR/DEX/WIS) • **Wayfarer** (DEX/WIS/CHA)

### Feat ที่แนะนำ (เลเวล 4+)
| Feat | ทำไม |
|---|---|
| **Ability Score Improvement (DEX)** [แนะนำ] | ดัน DEX ถึง 20 |
| **Sharpshooter** [แนะนำมาก] | ไม่เสียเปรียบระยะไกล + ไม่สนที่กำบัง (สายธนู) |
| **Crossbow Expert** | ถ้าใช้ Hand Crossbow |
| **ถ้าเป็น Elf (Elven Accuracy)** | ทอย 3 ลูกเมื่อมี Advantage |
| **Alert** | ไปก่อนศัตรู (โดยเฉพาะ Gloom Stalker) |
| **Resilient (Constitution)** | รักษา Concentration ของ `Hunter's Mark` |

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

| ผิด | ถูก |
|---|---|
| ลืมร่าย `Hunter's Mark` ทุกการต่อสู้ | **ร่ายเป็น Bonus Action เทิร์นแรกเสมอ** — ร่ายฟรีได้ 2-6 ครั้ง/วัน |
| ร่ายสเปล Concentration อื่นทับ | **จะเสีย `Hunter's Mark`** — วางแผนให้ดี |
| ปล่อย WIS ต่ำ | WIS กระทบ **Spell Save DC** และสกิลสำคัญ (Perception, Survival) |
| ดันทั้ง STR และ DEX | **เลือกอย่างเดียว** — สาย DEX ยืดหยุ่นกว่า |
| ลืม Expertise ตอนเลเวล 2 | เลือก **Perception หรือ Stealth** |

---

## สรุป Ranger ในหนึ่งบรรทัด

> **`Hunter's Mark` ฟรีหลายครั้งต่อวัน + เดินทางได้ทุกภูมิประเทศ + สกิล 3 อย่าง + Expertise = นักสอดแนมที่ดีที่สุดในเกม พร้อมดาเมจสม่ำเสมอ**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
