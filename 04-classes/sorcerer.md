# จอมเวทสายเลือด (Sorcerer)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**ซอร์เซอเรอร์ / จอมเวทสายเลือด (Sorcerer)** คือผู้ที่มีเวทมนตร์ไหลอยู่ในสายเลือดตั้งแต่เกิด พวกเขาไม่ต้องเรียนจากตำราเหมือน Wizard — แต่ **ดัดแปลงเวทได้ตามใจด้วย Metamagic** ซึ่งไม่มีคลาสไหนทำได้

> **จุดต่างกับ Wizard:** Wizard มีสเปล **หลากหลายกว่ามาก** แต่ Sorcerer **ใช้สเปลที่มีได้ทรงพลังกว่า** ด้วย Metamagic

---

## ข้อมูลพื้นฐาน (Class Table)

| หัวข้อ | ค่า |
|---|---|
| **Primary Ability** | **Charisma (CHA)** |
| **Hit Die** | **d6** (น้อยที่สุดในเกม) |
| **HP เลเวล 1** | **6 + CON modifier** |
| **HP เลเวลถัดไป** | **1d6 + CON** (หรือค่าคงที่ **4 + CON**) |
| **Saving Throw Proficiency** | **Constitution, Charisma** |
| **Armor Proficiency** | **ไม่มี** |
| **Weapon Proficiency** | Simple Weapons |
| **Skill Proficiency** | เลือก **2** จาก: **Arcana, Deception, Insight, Intimidation, Persuasion, Religion** |
| **Spellcasting Ability** | **Charisma (CHA)** |
| **Spellcasting Focus** | **Arcane Focus** |
| **Subclass (Sorcerous Origin)** | เลือกที่ **เลเวล 3** |

### อุปกรณ์เริ่มต้น

**เลือก A:** Spear, ×2 Dagger, Arcane Focus (คริสตัล), Dungeoneer's Pack, **28 GP**
**เลือก B:** **50 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

| เลเวล | Prof | Features | Sorcery<br>Points | Cantrips | เตรียม<br>สเปล | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **1** | +2 | **Spellcasting**, **Innate Sorcery** [แนะนำ] | — | **4** | 2 | **2** | — | — | — | — | — | — | — | — |
| **2** | +2 | **Font of Magic** [แนะนำมาก], **2 อย่าง (Metamagic)** | **2** | 4 | 4 | 3 | — | — | — | — | — | — | — | — |
| **3** | +2 | **Sorcerous Origin (Subclass)** [แนะนำ] | 3 | 4 | 6 | 4 | **2** | — | — | — | — | — | — | — |
| **4** | +2 | **ASI** | 4 | **5** | 7 | 4 | 3 | — | — | — | — | — | — | — |
| **5** | **+3** | **Sorcerous Restoration** | 5 | 5 | 9 | 4 | 3 | **2** | — | — | — | — | — | — |
| **6** | +3 | **Subclass Feature** | 6 | 5 | 10 | 4 | 3 | 3 | — | — | — | — | — | — |
| **7** | +3 | **Sorcery Incarnate** [แนะนำ] | 7 | 5 | 11 | 4 | 3 | 3 | **1** | — | — | — | — | — |
| **8** | +3 | **ASI** | 8 | 5 | 12 | 4 | 3 | 3 | 2 | — | — | — | — | — |
| **9** | **+4** | — | 9 | 5 | 14 | 4 | 3 | 3 | 3 | **1** | — | — | — | — |
| **10** | +4 | **+2 อย่าง (Metamagic)** | 10 | **6** | 15 | 4 | 3 | 3 | 3 | 2 | — | — | — | — |
| **11** | +4 | — | 11 | 6 | 16 | 4 | 3 | 3 | 3 | 2 | **1** | — | — | — |
| **12** | +4 | **ASI** | 12 | 6 | 16 | 4 | 3 | 3 | 3 | 2 | 1 | — | — | — |
| **13** | **+5** | — | 13 | 6 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | **1** | — | — |
| **14** | +5 | **Subclass Feature** | 14 | 6 | 17 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | — | — |
| **15** | +5 | — | 15 | 6 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | **1** | — |
| **16** | +5 | **ASI** | 16 | 6 | 18 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | — |
| **17** | **+6** | **+2 อย่าง (Metamagic)** | 17 | 6 | 19 | 4 | 3 | 3 | 3 | 2 | 1 | 1 | 1 | **1** |
| **18** | +6 | **Subclass Feature** | 18 | 6 | 20 | 4 | 3 | 3 | 3 | 3 | 1 | 1 | 1 | 1 |
| **19** | +6 | **Epic Boon Feat** | 19 | 6 | 21 | 4 | 3 | 3 | 3 | 3 | 2 | 1 | 1 | 1 |
| **20** | +6 | **Arcane Apotheosis** | 20 | 6 | 22 | 4 | 3 | 3 | 3 | 3 | 2 | 2 | 1 | 1 |

> **Sorcerer ได้ Cantrip มากที่สุดในเกม (4 อันตั้งแต่เลเวล 1)** แต่มี **สเปลที่เตรียมได้น้อยที่สุดในบรรดา Full Caster**

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 — Spellcasting

> - ใช้ **Charisma** เป็นค่าร่ายเวท
> - **Spell Save DC = 8 + CHA modifier + Proficiency Bonus**
> - **Spell Attack = CHA modifier + Proficiency Bonus**
> - **เปลี่ยนสเปลที่เตรียมไว้ได้ 1 อัน ทุกครั้งที่เลื่อนเลเวล**

> **Sorcerer มีสเปลน้อย** — ต้องเลือกสเปลที่ **ใช้ได้หลายสถานการณ์** ไม่ใช่สเปลเฉพาะทาง

---

### เลเวล 1 — เวทมนตร์โดยกำเนิด (Innate Sorcery) กฎใหม่ 2024

> **Bonus Action:** ปลดปล่อยพลังในสายเลือด **1 นาที**
>
> ระหว่างนั้น:
> - **Spell Save DC ของคุณ +1** [แนะนำ]
> - **คุณมี Advantage ในการทอย Spell Attack ทั้งหมด** [แนะนำ]
>
> **ใช้ได้ 2 ครั้งต่อ Long Rest**

**ทำไมนี่คือการบัฟที่สำคัญที่สุดของกฎ 2024:** Sorcerer เดิมไม่มีอะไรพิเศษที่เลเวล 1 เลย ตอนนี้มีปุ่ม "โหมดพลังเต็ม" ที่ทำให้เวทแรงขึ้นทั้งชุด

> **ใช้เมื่อเจอบอสหรือศึกใหญ่** — 1 นาที = 10 เทิร์น ครอบคลุมทั้งการต่อสู้

---

### เลเวล 2 — บ่อเกิดเวทมนตร์ (Font of Magic)

> คุณมี **Sorcery Points (SP / แต้มเวท) เท่ากับเลเวล Sorcerer** — **ฟื้นทั้งหมดเมื่อ Long Rest**

### แปลง Sorcery Points Spell Slot

**Bonus Action:** แลกเปลี่ยนได้ทั้งสองทาง

| แปลง SP Spell Slot | ใช้ SP |
|---|---|
| **Slot ระดับ 1** | **2 SP** |
| **Slot ระดับ 2** | **3 SP** |
| **Slot ระดับ 3** | **5 SP** |
| **Slot ระดับ 4** | **6 SP** |
| **Slot ระดับ 5** | **7 SP** |

| แปลง Spell Slot SP | ได้ SP |
|---|---|
| ใช้ Slot ระดับใดก็ตาม | **SP เท่ากับระดับของ Slot** |

> **การแปลงไม่คุ้มในเชิงตัวเลข** (2 SP ได้ Slot ระดับ 1 แต่ Slot ระดับ 1 ให้แค่ 1 SP) — **ควรใช้ SP ไปกับ Metamagic เป็นหลัก** แล้วแปลงเป็น Slot เฉพาะตอนฉุกเฉิน

---

### เลเวล 2 — เวทดัดแปลง (Metamagic) ความสามารถหลักของคลาส

> เลือก **Metamagic 2 อย่าง** (ได้เพิ่มอีก 2 ที่เลเวล 10 และอีก 2 ที่เลเวล 17 — รวม **6 อย่าง**)
> **เปลี่ยนตัวเลือกได้ทุกครั้งที่เลื่อนเลเวล**
>
> **ใช้ Metamagic ได้ทีละ 1 อย่างต่อการร่าย 1 ครั้ง** (ยกเว้นเลเวล 7+ ด้วย Sorcery Incarnate)

### Metamagic ทั้ง 10 อย่าง

| Metamagic | ต้นทุน | ผล |
|---|---|---|
| **เวทฉับพลัน (Quickened Spell)** [แนะนำอย่างยิ่ง] | **2 SP** | **เปลี่ยนสเปลที่ใช้ Action ใช้ Bonus Action แทน** |
| **เวทคู่แฝด (Twinned Spell)** [แนะนำมาก] | **1 SP** | สเปลที่เล็งเป้าหมาย **1 ตัว** **เล็งเป้าหมายที่ 2 ได้** (สเปลนั้นต้องเล็งได้แค่ 1 ตัวและไม่มีระยะ Self) |
| **เวทเงียบงัน (Subtle Spell)** [แนะนำมาก] | **1 SP** | ร่ายโดย**ไม่ต้องใช้องค์ประกอบ Verbal, Somatic, และ Material** — ร่ายได้ตอนถูกมัด ตอนอยู่ใน `Silence` หรือร่ายโดยไม่มีใครรู้ |
| **เวทระมัดระวัง (Careful Spell)** [แนะนำมาก] | **1 SP** | เลือกเพื่อนได้ถึง **CHA modifier คน** **พวกเขา Save สำเร็จอัตโนมัติและรับดาเมจ 0** (ปล่อย `Fireball` ใส่กลางวงได้!) |
| **เวทเข้มข้น (Heightened Spell)** [แนะนำมาก] | **2 SP** | เป้าหมาย 1 ตัว **เสียเปรียบในการทอย Saving Throw ครั้งแรก** ต่อสเปลนั้น |
| **เวทเสริมพลัง (Empowered Spell)** [แนะนำ] | **1 SP** | **ทอยเต๋าดาเมจใหม่ได้ถึง CHA modifier ลูก** (ต้องใช้ผลใหม่) — **ใช้ร่วมกับ Metamagic อื่นได้!** [แนะนำ] |
| **เวทระยะไกล (Distant Spell)** [แนะนำ] | **1 SP** | **ระยะเพิ่มเป็น 2 เท่า** • หรือสเปลระยะ **Touch 30 ฟุต** |
| **เวทยืดเวลา (Extended Spell)** | **1 SP** | **ระยะเวลาเพิ่มเป็น 2 เท่า** (สูงสุด 24 ชม.) + **Advantage ในการทอย Concentration Save** ของสเปลนั้น |
| **เวทติดตาม (Seeking Spell)** | **1 SP** | เมื่อ **Spell Attack พลาด ทอยใหม่ได้** |
| **เวทแปรธาตุ (Transmuted Spell)** | **1 SP** | **เปลี่ยนธาตุของสเปล** เป็น Acid, Cold, Fire, Lightning, Poison, หรือ Thunder |

### Metamagic ที่แนะนำตามลำดับ

| อันดับ | Metamagic | เหตุผล |
|---|---|---|
| 1 | **Quickened Spell** | [แนะนำอย่างยิ่ง] ร่าย 2 สเปลในเทิร์นเดียว (`Quickened Fireball` + Cantrip) — เปลี่ยนเกม |
| 2 | **Twinned Spell** | [แนะนำมาก] `Haste` 2 คน, `Hold Person` 2 ตัว, `Polymorph` 2 ตัว — คุ้มมาก |
| 3 | **Subtle Spell** | [แนะนำมาก] ร่ายเวทได้โดยไม่มีใครรู้ — ทรงพลังทั้งในและนอกการต่อสู้ |
| 4 | **Careful Spell** | [แนะนำมาก] ปล่อยสเปลพื้นที่ได้โดยไม่โดนเพื่อน |
| 5 | **Heightened Spell** | [แนะนำมาก] ทำให้บอสล้มเหลวในการ Save ที่สำคัญ |
| 6 | **Empowered Spell** | [แนะนำ] ราคาถูก + ใช้ร่วมกับอันอื่นได้ |

> **แนะนำ 2 อันแรกที่เลเวล 2:** `Quickened Spell` + `Twinned Spell` (หรือ `Careful Spell` ถ้าเน้นสเปลพื้นที่)

---

### เลเวล 5 — การฟื้นฟูเวทมนตร์ (Sorcerous Restoration)

> **เมื่อจบ Short Rest ฟื้น Sorcery Points เท่ากับ `ครึ่งหนึ่งของเลเวล Sorcerer` (ปัดลง)**
> **ใช้ได้ 1 ครั้งต่อ Long Rest**

---

### เลเวล 7 — ร่างอวตารแห่งเวท (Sorcery Incarnate)

> - **ขณะที่ Innate Sorcery ทำงานอยู่ ใช้ Metamagic ได้ 2 อย่างพร้อมกันในการร่าย 1 ครั้ง** [แนะนำ]
> - **ถ้า Innate Sorcery ใช้หมดแล้ว ใช้ 2 Sorcery Points เพื่อเปิดใช้อีกครั้งได้** [แนะนำ]

> **คอมโบเลเวล 7:** `Innate Sorcery` (Advantage + DC +1) `Quickened + Heightened Fireball` = บอสแทบไม่มีทางรอด

---

### เลเวล 20 — การก้าวสู่เทพแห่งเวท (Arcane Apotheosis) — Capstone

> **ขณะที่ Innate Sorcery ทำงานอยู่**
> **คุณสามารถใช้ Metamagic 1 อย่าง โดยไม่เสีย Sorcery Points ในแต่ละเทิร์นของคุณ**

---

## Subclasses (Sorcerous Origin) — เลือกที่เลเวล 3

Sorcerer มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 6, 14, 18**
**ทุก Subclass ให้ชุดสเปลที่เตรียมไว้เสมอ (ไม่นับโควตา)**

---

### 1. Draconic Sorcery — สายเลือดมังกร

> **ธีม:** บรรพบุรุษเป็นมังกร — **สายที่ทนที่สุดและง่ายที่สุด**

**Draconic Spells (เตรียมไว้เสมอ):**

| เลเวล Sorcerer | สเปล |
|---|---|
| 3 | `Alter Self`, `Chromatic Orb`, `Command`, `Dragon's Breath` |
| 5 | `Fear`, `Fly` |
| 7 | `Arcane Eye`, `Charm Monster` |
| 9 | `Legend Lore`, `Summon Dragon` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Draconic Resilience** | [แนะนำมาก] • **HP สูงสุด +1 ต่อเลเวล Sorcerer** (แก้ปัญหา d6!)<br>• **ตอนไม่ใส่เกราะ: AC = `10 + DEX + CHA`** [แนะนำ] — เกล็ดมังกรขึ้นบนผิว |
| **6** | **Elemental Affinity** | [แนะนำ] เลือกธาตุ 1 อย่างจาก Draconic Ancestry (Acid/Cold/Fire/Lightning/Poison):<br>• **บวก CHA modifier ในดาเมจของสเปลที่ทำธาตุนั้น** (1 ครั้ง/เทิร์น)<br>• **ได้ Resistance ต่อธาตุนั้น** |
| **14** | **Dragon Wings** | **Bonus Action:** [แนะนำมาก] งอกปีกมังกร — **Fly Speed เท่ากับ Speed** เป็นเวลา **1 ชั่วโมง** (ฟรี 1 ครั้ง/Long Rest หรือใช้ 3 SP) |
| **18** | **Dragon Companion** | [แนะนำ] ร่ายสเปล **`Summon Dragon` ฟรี 1 ครั้ง/Long Rest** โดยไม่เสีย Slot • มังกรที่เรียกมา **ไม่ต้อง Concentration** |

> **แนะนำมือใหม่ที่สุด** — AC 10+DEX+CHA (ประมาณ 16-18) + HP เพิ่ม ทำให้ไม่ตายง่ายเหมือน Sorcerer สายอื่น

---

### 2. Wild Magic — เวทมนตร์ป่วน

> **ธีม:** เวทมนตร์ควบคุมไม่ได้ — **สายที่สนุกและคาดเดาไม่ได้ที่สุด**

**Wild Magic Spells (เตรียมไว้เสมอ):**

| เลเวล Sorcerer | สเปล |
|---|---|
| 3 | `Detect Magic`, `Fog Cloud`, `Blur`, `Silence` |
| 5 | `Haste`, `Slow` |
| 7 | `Polymorph`, `Confusion` |
| 9 | `Contact Other Plane`, `Bigby's Hand` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Wild Magic Surge** | **ทันทีหลังร่ายสเปลระดับ 1 ขึ้นไป** [แนะนำ] **ทอย d20** — **ออก 20 = เกิด Wild Magic Surge** (ทอย d100 บนตาราง 50 ผลลัพธ์)<br>(หรือ DM อาจสั่งให้ทอยเมื่อไหร่ก็ได้) |
| **3** | **Tides of Chaos** | **ได้ Advantage ในการทอย d20 Test 1 ครั้ง** [แนะนำ] — จากนั้นต้อง**ทอย Wild Magic Surge ทันทีหลังร่ายสเปลครั้งถัดไป** (ใช้ Prof Bonus ครั้ง/Long Rest) |
| **6** | **Bend Luck** | **Reaction + 1 SP:** [แนะนำมาก] เมื่อสิ่งมีชีวิตที่มองเห็นทอย d20 Test **บวกหรือลบ `1d4`** จากผลนั้น |
| **14** | **Controlled Chaos** | **เมื่อทอย Wild Magic Surge ทอย d100 สองครั้ง แล้วเลือกผลที่ชอบ** [แนะนำ] |
| **18** | **Tamed Surge** | **ทันทีหลังร่ายสเปล เลือกผลจากตาราง Wild Magic Surge ได้เองเลย** [แนะนำมาก] (ไม่ต้องทอย) — ใช้ได้ 1 ครั้ง/Long Rest |

**ตัวอย่างผล Wild Magic Surge (จากตาราง d100):**
- ร่าย `Fireball` ทันทีที่จุดที่เลือก • กลายเป็นกระถางต้นไม้ 1 นาที • ฟื้น HP เต็ม
- Speed เพิ่ม 10 ฟุต 1 นาที • ผมเปลี่ยนสี • ทุกคนในระยะ 30 ฟุตกลายเป็น Invisible 1 นาที
- ตัวคุณลอยขึ้น 10 ฟุต • เรียก Unicorn มา 1 นาที • Sorcery Points ฟื้น 5 แต้ม

> **สายที่สนุกที่สุดในการเล่นบทบาท** แต่ **ต้องมี DM ที่เปิดใจ** เพราะผลลัพธ์อาจทำให้แผนพัง

---

### 3. Aberrant Sorcery — สายเลือดอสูรกาย

> **ธีม:** พลังจิตจากสิ่งมีชีวิตนอกโลก (Aberration) — **สายควบคุมจิตใจ**

**Psionic Spells (เตรียมไว้เสมอ):**

| เลเวล Sorcerer | สเปล |
|---|---|
| 3 | `Arms of Hadar`, `Calm Emotions`, `Detect Thoughts`, `Dissonant Whispers`, `Mind Sliver` |
| 5 | `Hunger of Hadar`, `Sending` |
| 7 | `Evard's Black Tentacles`, `Summon Aberration` |
| 9 | `Rary's Telepathic Bond`, `Telekinesis` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Telepathic Speech** | **Bonus Action:** สร้างสายสื่อสารทางจิตกับสิ่งมีชีวิต 1 ตัวในระยะ 30 ฟุต เป็นเวลา `CHA modifier` นาที (ระยะไกลถึง 1 ไมล์) |
| **6** | **Psionic Sorcery** | **เมื่อร่าย Psionic Spell** [แนะนำมาก] ร่ายด้วย **Sorcery Points แทน Spell Slot** ได้ (SP = ระดับสเปล) • และร่ายแบบนั้น **ไม่ต้องใช้องค์ประกอบ Verbal, Somatic, Material** เลย |
| **6** | **Psychic Defenses** | **Resistance ต่อ Psychic damage** [แนะนำ] และ **Advantage ในการทอย Save ต้าน Charmed และ Frightened** |
| **14** | **Revelation in Flesh** | **Bonus Action + 1 SP ขึ้นไป:** [แนะนำมาก] เลือก 1 อย่างต่อ SP ที่จ่าย (10 นาที):<br>• **See Invisibility 60 ft + Darkvision 60 ft**<br>• **Swim Speed = 2× Speed + หายใจใต้น้ำได้**<br>• **Fly Speed = Speed (บินอยู่กับที่ได้)**<br>• **ร่างยืดหยุ่น: ลอดช่องแคบ 1 นิ้วได้ + Advantage ในการหลุด Grapple** |
| **18** | **Warping Implosion** | **Action + 5 SP:** [แนะนำ] **วาร์ป 120 ฟุต** สิ่งมีชีวิตในระยะ 30 ฟุตจากจุดเดิม ทอย **STR Save** — ล้มเหลว = **`3d10 Force` + ถูกดึงเข้าหาจุดเดิม** |

---

### 4. Clockwork Sorcery — สายเลือดกลไกจักรวาล

> **ธีม:** พลังจากมิติแห่งระเบียบ (Mechanus) — **สายซัพพอร์ตและควบคุมโชคชะตา**

**Clockwork Spells (เตรียมไว้เสมอ):**

| เลเวล Sorcerer | สเปล |
|---|---|
| 3 | `Aid`, `Alarm`, `Lesser Restoration`, `Protection from Evil and Good` |
| 5 | `Dispel Magic`, `Protection from Energy` |
| 7 | `Freedom of Movement`, `Summon Construct` |
| 9 | `Greater Restoration`, `Wall of Force` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Restore Balance** | **Reaction:** [แนะนำมาก] เมื่อสิ่งมีชีวิตในระยะ 60 ฟุตกำลังจะทอยด้วย **Advantage หรือ Disadvantage** **ยกเลิกมัน** (ทอยปกติ) — ใช้ได้ **Prof Bonus ครั้ง/Long Rest** |
| **6** | **Bastion of Law** | **Action + 1-5 SP:** [แนะนำมาก] ให้ตัวเองหรือสิ่งมีชีวิตในระยะ 30 ฟุต ได้ **โล่พลังงาน = `d8 จำนวนเท่ากับ SP ที่จ่าย`**<br>**เมื่อเป้าหมายรับดาเมจ ทอยเต๋าจากโล่เพื่อลดดาเมจ** (เต๋าหมดแล้วโล่หาย) |
| **14** | **Trance of Order** | **Bonus Action:** [แนะนำมาก] เข้าสู่สภาวะจิตแห่งระเบียบ **1 นาที**:<br>• **การทอย Attack Roll และ Ability Check ที่ออกต่ำกว่า 10 นับเป็น 10** [แนะนำ]<br>• **ศัตรูโจมตีคุณด้วย Advantage ไม่ได้**<br>ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ 5 SP) |
| **18** | **Clockwork Cavalcade** | **Action:** [แนะนำมาก] ลูกบาศก์ 30 ฟุต:<br>• **ฟื้น HP รวม 100** ให้สิ่งมีชีวิตที่เลือก<br>• **ยกเลิกสเปลระดับ 6 หรือต่ำกว่าทั้งหมด** ในพื้นที่<br>• **ซ่อมของที่พังทั้งหมด** ในพื้นที่<br>ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ 7 SP) |

> **สายซัพพอร์ตที่ดีที่สุด** — `Restore Balance` ยกเลิก Advantage ของบอสได้ในจังหวะชี้เป็นชี้ตาย

---

## เปรียบเทียบ 4 Subclass

| | **Draconic** | **Wild Magic** | **Aberrant** | **Clockwork** |
|---|---|---|---|---|
| **จุดเด่น** | **ทนที่สุด (AC+HP)** | สนุก คาดเดาไม่ได้ | ควบคุมจิต + ร่ายเงียบ | **ซัพพอร์ต+ควบคุมโชค** |
| **ความยาก** | ง่ายสุด | กลาง (ต้องเปิดตาราง) | กลาง | ง่าย |
| **ช่วยทีม** | ต่ำ | กลาง (Bend Luck) | กลาง | **สูงสุด** |
| **แนะนำมือใหม่** | **ใช่** | ใช่ (ถ้าชอบลุ้น) | ใช่ | **ใช่** |

---
---

# รายการเวทของ Sorcerer (Sorcerer Spell List)

> **[C] = Concentration** | **[R] = Ritual** | [แนะนำ] = แนะนำ
> รายการเวทของ Sorcerer เป็น **ส่วนย่อยของรายการ Wizard** เน้นสเปลโจมตีและควบคุม (ไม่มีสเปลตรวจสอบ/พิธีกรรมมากนัก)

---

## ได้ 4 อันตั้งแต่เลเวล 1 (Cantrips)

| Cantrip | ทำอะไร |
|---|---|
| **ระเบิดพลังเวท (Sorcerous Burst)** [แนะนำอย่างยิ่ง] | Spell Attack — **1d8** ธาตุที่เลือก (Acid/Cold/Fire/Lightning/Poison/Psychic/Thunder) • **ถ้าเต๋าออกค่าสูงสุด ทอยเพิ่มได้อีกลูก** [แนะนำ] (สูงสุดตาม CHA modifier) — Cantrip เอกลักษณ์ของ Sorcerer |
| **ลูกไฟ (Fire Bolt)** [แนะนำมาก] | Spell Attack ระยะ 120 ฟุต — **1d10 Fire** |
| **ลำแสงเยือกแข็ง (Ray of Frost)** [แนะนำ] | Spell Attack — **1d8 Cold** + **ลด Speed 10 ฟุต** |
| **สัมผัสช็อต (Shocking Grasp)** | Spell Attack ระยะ 5 ฟุต — **1d8 Lightning** + **เป้าหมายใช้ Reaction ไม่ได้** |
| **สัมผัสเยือกเย็น (Chill Touch)** | Spell Attack — **1d10 Necrotic** + เป้าหมายฟื้น HP ไม่ได้ |
| **สาดกรด (Acid Splash)** | DEX Save — **1d6 Acid** ใส่ศัตรู 2 ตัว |
| **พ่นพิษ (Poison Spray)** | CON Save — **1d12 Poison** |
| **เสียงกัมปนาท (Thunderclap)** | CON Save — **1d6 Thunder** รอบตัว 5 ฟุต |
| **มือเวท (Mage Hand)** [แนะนำ] | มือลอยระยะ 30 ฟุต |
| **ภาพลวงตาเล็ก (Minor Illusion)** [แนะนำ] | สร้างภาพหรือเสียงลวง |
| **มายากลจิ๊บจ๊อย (Prestidigitation)** [แนะนำ] | เอฟเฟกต์เวทเล็ก ๆ |
| **แสง (Light)** | วัตถุเปล่งแสง 20 ฟุต |
| **สาร (Message)** | กระซิบระยะ 120 ฟุต |
| **ซ่อมแซม (Mending)** | ซ่อมของที่เสียหาย |
| **แสงเริงระบำ (Dancing Lights)** | แสงลอย 4 ดวง |
| **มิตรภาพ (Friends)** | Advantage ใน CHA Check ต่อ 1 ตัว |
| **ปัดใบมีด (Blade Ward)** | Resistance กายภาพจนจบเทิร์นหน้า |
| **โจมตีแม่นยำ (True Strike)** | โจมตีด้วยอาวุธโดยใช้ CHA แทน |
| **ธาตุจิ๋ว (Elementalism)** | เอฟเฟกต์ธาตุเล็ก ๆ |

> **แนะนำ 4 อันแรก:** `Sorcerous Burst` [แนะนำอย่างยิ่ง] + `Fire Bolt` [แนะนำมาก] + `Mage Hand` [แนะนำ] + `Minor Illusion` หรือ `Prestidigitation`

---

## สเปลระดับ 1

| สเปล | ทำอะไร |
|---|---|
| **โล่ (Shield)** [แนะนำอย่างยิ่ง] | **Reaction: +5 AC ทันที** จนจบเทิร์นหน้า |
| **เกราะเวท (Mage Armor)** [แนะนำมาก] | **AC = 13 + DEX** เป็นเวลา 8 ชั่วโมง — **ต้องมี!** |
| **ขีปนาวุธเวท (Magic Missile)** [แนะนำมาก] | **3 ลูก × 1d4+1 Force** — **ไม่มีวันพลาด** |
| **ทรงกลมหลากสี (Chromatic Orb)** [แนะนำ] | Spell Attack — **3d8** ธาตุที่เลือก (เพชร 50 GP) |
| **มือเพลิง (Burning Hands)** | กรวย 15 ฟุต — **3d6 Fire** |
| **คลื่นกัมปนาท (Thunderwave)** [แนะนำ] | ลูกบาศก์ 15 ฟุต — **2d8 Thunder** + ผลัก 10 ฟุต |
| **น้ำมันลื่น (Grease)** [แนะนำ] | พื้นที่ 10 ฟุต — DEX Save ล้มเหลว = **Prone** |
| **หลับใหล (Sleep)** | CON Save — ล้มเหลว = **Incapacitated** |
| **หมอกคลุม (Fog Cloud)** [C] | ทรงกลม 20 ฟุต — Heavily Obscured |
| **สาดสีสัน (Color Spray)** | กรวย 15 ฟุต — CON Save ล้มเหลว = Blinded |
| **มีดน้ำแข็ง (Ice Knife)** | Spell Attack 1d10 + ระเบิด 2d6 Cold |
| **ลำแสงป่วยไข้ (Ray of Sickness)** | Spell Attack — 2d8 Poison + Poisoned |
| **สายฟ้าแม่มด (Witch Bolt)** [C] | 1d12 Lightning + Action ทุกเทิร์นทำ 1d12 ซ้ำ |
| **เสน่ห์ (Charm Person)** | Humanoid — Charmed 1 ชั่วโมง |
| **ปลอมตัว (Disguise Self)** | เปลี่ยนรูปลักษณ์ 1 ชั่วโมง |
| **ภาพเงียบ (Silent Image)** [C] | ภาพลวงตา 15 ฟุต |
| **ถอยรวดเร็ว (Expeditious Retreat)** [C] | Bonus Action Dash ทุกเทิร์น |
| **ชีวิตลวง (False Life)** | Temp HP 2d4+4 |
| **ขนนกร่วง (Feather Fall)** [แนะนำ] | Reaction: 5 คนตกช้าลง |
| **ตรวจจับเวท (Detect Magic)** [C][R] | รับรู้เวทมนตร์ในระยะ 30 ฟุต |
| **เข้าใจภาษา (Comprehend Languages)** [R] | อ่านและเข้าใจทุกภาษา |
| **กระโดด (Jump)** | ระยะกระโดด ×3 |

> **แนะนำ 2 อันแรก (เลเวล 1 เตรียมได้แค่ 2!):** `Shield` [แนะนำอย่างยิ่ง] + `Magic Missile` [แนะนำมาก] (ร่าย `Mage Armor` ทีหลังตอนเลเวล 2)

---

## สเปลระดับ 2 — ได้ที่เลเวล 3

| สเปล | ทำอะไร |
|---|---|
| **ก้าวหมอก (Misty Step)** [แนะนำอย่างยิ่ง] | **Bonus Action: วาร์ป 30 ฟุต** |
| **ใยแมงมุม (Web)** [แนะนำมาก] [C] | ลูกบาศก์ 20 ฟุต — DEX Save ล้มเหลว = **Restrained** |
| **ภาพสะท้อน (Mirror Image)** [แนะนำมาก] | สร้างภาพลวงตา 3 ตัว |
| **ลำแสงเผาไหม้ (Scorching Ray)** [แนะนำ] | **3 ลำ × 2d6 Fire** |
| **ตรึงมนุษย์ (Hold Person)** [แนะนำมาก] [C] | WIS Save — ล้มเหลว = ****Twinned Spell ได้!** (Paralyzed)** |
| **ล่องหน (Invisibility)** [แนะนำ] [C] | เป้าหมาย Invisible 1 ชั่วโมง |
| **ชักจูง (Suggestion)** [แนะนำ] [C] | WIS Save — ล้มเหลว = ทำตามคำแนะนำ 8 ชั่วโมง |
| **แตกสลาย (Shatter)** [แนะนำ] | ทรงกลม 10 ฟุต — 3d8 Thunder |
| **เบลอ (Blur)** [C] | ศัตรูโจมตีคุณแบบเสียเปรียบ |
| **ลมหายใจมังกร (Dragon's Breath)** [C] | เพื่อนพ่นลมหายใจ **3d6** เป็น Bonus Action ทุกเทิร์น |
| **ขยาย/ย่อ (Enlarge/Reduce)** [C] | เปลี่ยนขนาดเป้าหมาย 1 ระดับ |
| **ลอยตัว (Levitate)** [C] | ยกเป้าหมายลอยขึ้น 20 ฟุต |
| **แปลงร่าง (Alter Self)** [C] | เปลี่ยนรูปลักษณ์ / หายใจใต้น้ำ / สร้างอาวุธธรรมชาติ |
| **ความมืด (Darkness)** [C] | ทรงกลม 15 ฟุตมืดสนิท |
| **มงกุฎบ้าคลั่ง (Crown of Madness)** [C] | ควบคุมให้เป้าหมายโจมตีพวกเดียวกัน |
| **ทรงกลมเพลิง (Flaming Sphere)** [C] | ลูกไฟลอย — Bonus Action ย้าย + 2d6 Fire |
| **เมฆมีดสั้น (Cloud of Daggers)** [C] | ลูกบาศก์ 5 ฟุต — 4d4 Slashing |
| **หนามจิต (Mind Spike)** [C] | 3d8 Psychic + รู้ตำแหน่งเป้าหมาย 1 ชั่วโมง |
| **มายาบังคับ (Phantasmal Force)** [C] | ภาพลวงตาในใจเป้าหมาย |
| **ปีนแบบแมงมุม (Spider Climb)** [C] | เดินบนกำแพงและเพดาน |
| **ตาบอด/หูหนวก (Blindness/Deafness)** | CON Save — Blinded หรือ Deafened |
| **อ่านใจ (Detect Thoughts)** [C] | อ่านความคิดผิวเผิน |
| **เสริมความสามารถ (Enhance Ability)** [C] | Advantage ใน Ability Check |
| **ลมกระโชก (Gust of Wind)** [C] | เส้น 60 ฟุต — ผลัก 15 ฟุต |
| **เปิดกุญแจ (Knock)** | เปิดกุญแจหรือประตูที่ล็อก |
| **เห็นสิ่งล่องหน (See Invisibility)** | เห็นสิ่งที่ Invisible |
| **มองในมืด (Darkvision)** | ให้ Darkvision 60 ฟุต |

> **แนะนำ:** `Misty Step` [แนะนำอย่างยิ่ง] + `Web` [แนะนำมาก] + `Hold Person` [แนะนำมาก] (คู่กับ Twinned Spell)

---

## สเปลระดับ 3 — ได้ที่เลเวล 5

| สเปล | ทำอะไร |
|---|---|
| **ลูกไฟ (Fireball)** [แนะนำอย่างยิ่ง] | ทรงกลม 20 ฟุต — **8d6 Fire** (คู่กับ `Careful Spell` = ไม่โดนเพื่อน) |
| **ขัดขวางเวท (Counterspell)** [แนะนำอย่างยิ่ง] | **Reaction:** ยกเลิกสเปลที่ศัตรูกำลังร่าย |
| **ลวดลายสะกดจิต (Hypnotic Pattern)** [แนะนำอย่างยิ่ง] [C] | ลูกบาศก์ 30 ฟุต — **Charmed + Incapacitated** |
| **เร่งความเร็ว (Haste)** [แนะนำอย่างยิ่ง] [C] | Speed ×2, +2 AC, Action เพิ่ม (**Twinned Spell = บัฟ 2 คน!**) |
| **บิน (Fly)** [แนะนำมาก] | **Fly Speed 60 ฟุต** (Twinned Spell ได้) |
| **หน่วง (Slow)** [แนะนำ] | 6 ตัว — Speed ครึ่ง, −2 AC, Action ได้อย่างเดียว |
| **สายฟ้าฟาด (Lightning Bolt)** [แนะนำ] | เส้น 100 ฟุต — **8d6 Lightning** |
| **สลายเวท (Dispel Magic)** [แนะนำมาก] | ยกเลิกสเปลระดับ 3 หรือต่ำกว่า |
| **ความกลัว (Fear)** [แนะนำ] [C] | กรวย 30 ฟุต — Frightened + ทิ้งของ + วิ่งหนี |
| **ป้องกันธาตุ (Protection from Energy)** [C] | Resistance ต่อธาตุที่เลือก |
| **กะพริบ (Blink)** | 50% หายไปในมิติ Ethereal ทุกเทิร์น |
| **ร่างหมอก (Gaseous Form)** [C] | กลายเป็นหมอก — Resistance กายภาพ |
| **ภาพใหญ่ (Major Image)** [C] | ภาพลวงตา 20 ฟุต พร้อมเสียงและกลิ่น |
| **พายุลูกเห็บ (Sleet Storm)** [C] | Difficult Terrain + ทำลาย Concentration |
| **เมฆเหม็น (Stinking Cloud)** [C] | ทรงกลม 20 ฟุต — เสีย Action ทั้งเทิร์น |
| **สัมผัสดูดเลือด (Vampiric Touch)** [C] | 3d6 Necrotic + ฟื้น HP ครึ่งหนึ่ง |
| **ตาทิพย์ (Clairvoyance)** [C] | มองหรือฟังจากจุดไกล |
| **แสงตะวัน (Daylight)** | แสงสว่างรัศมี 60 ฟุต |
| **ภาษา (Tongues)** | เข้าใจและพูดทุกภาษา |
| **หายใจใต้น้ำ (Water Breathing)** [R] | 10 คนหายใจใต้น้ำ |
| **เดินบนน้ำ (Water Walk)** [R] | 10 คนเดินบนของเหลว |

> **แนะนำ:** `Fireball` [แนะนำอย่างยิ่ง] + `Counterspell` [แนะนำอย่างยิ่ง] + `Haste` [แนะนำอย่างยิ่ง] (Twinned)

---

## สเปลระดับ 4 — ได้ที่เลเวล 7

| สเปล | ทำอะไร |
|---|---|
| **แปลงร่าง (Polymorph)** [แนะนำอย่างยิ่ง] [C] | แปลงศัตรูให้ไร้พิษภัย หรือแปลงเพื่อนเป็น T-Rex (**Twinned Spell ได้!**) |
| **ล่องหนขั้นสูง (Greater Invisibility)** [แนะนำมาก] [C] | Invisible แม้จะโจมตีหรือร่ายเวท |
| **ประตูมิติ (Dimension Door)** [แนะนำมาก] | วาร์ป 500 ฟุต พร้อมเพื่อน 1 คน |
| **เนรเทศ (Banishment)** [แนะนำมาก] [C] | CHA Save — ล้มเหลว = หายไป 1 นาที |
| **กำแพงเพลิง (Wall of Fire)** [แนะนำมาก] [C] | กำแพง 60 ฟุต — **5d8 Fire** |
| **สับสน (Confusion)** [แนะนำ] [C] | ศัตรูทำอะไรสุ่ม ๆ |
| **โล่ไฟ (Fire Shield)** [แนะนำ] | Resistance Fire/Cold + สวนกลับ 2d8 |
| **พายุน้ำแข็ง (Ice Storm)** | 2d8 Bludgeoning + 4d6 Cold |
| **เหี่ยวเฉา (Blight)** | **8d8 Necrotic** |
| **ทรงกลมกรด (Vitriolic Sphere)** | **10d4 Acid** + 5d4 ในเทิร์นถัดไป |
| **เสน่ห์อสูร (Charm Monster)** | สิ่งมีชีวิตใดก็ได้ — Charmed |
| **ครอบงำสัตว์ (Dominate Beast)** [C] | ควบคุมสัตว์ |
| **ผิวหิน (Stoneskin)** [C] | Resistance กายภาพที่ไม่ใช่เวท |

---

## สเปลระดับ 5 — ได้ที่เลเวล 9

| สเปล | ทำอะไร |
|---|---|
| **ไฟฟ้าลัดวงจรสมอง (Synaptic Static)** [แนะนำมาก] | ทรงกลม 20 ฟุต — **8d6 Psychic** + **−1d6 ในการทอยโจมตีและ Check** |
| **มือยักษ์ (Bigby's Hand)** [แนะนำมาก] [C] | มือพลังยักษ์ — โจมตี **4d8 Force** / ผลัก / บีบ / ป้องกัน |
| **ปลุกวัตถุ (Animate Objects)** [แนะนำมาก] [C] | ปลุกวัตถุ 10 ชิ้นให้โจมตี |
| **ตรึงอสูร (Hold Monster)** [แนะนำมาก] [C] | สิ่งมีชีวิตใดก็ได้ — **Twinned Spell ได้ (Paralyzed)** |
| **ครอบงำมนุษย์ (Dominate Person)** [แนะนำมาก] [C] | ควบคุม Humanoid ทั้งหมด |
| **กรวยเยือกแข็ง (Cone of Cold)** [แนะนำ] | กรวย 60 ฟุต — **8d8 Cold** |
| **จิตเคลื่อนย้าย (Telekinesis)** [แนะนำ] [C] | ควบคุมวัตถุ/สิ่งมีชีวิต 1,000 ปอนด์ |
| **กำแพงหิน (Wall of Stone)** [แนะนำ] [C] | สร้างกำแพงหินขนาดใหญ่ |
| **เมฆสังหาร (Cloudkill)** [C] | ทรงกลม 20 ฟุต — 5d8 Poison + เคลื่อนที่เอง |
| **ฝูงแมลง (Insect Plague)** [C] | ทรงกลม 20 ฟุต — 4d10 Piercing |
| **ลมเหล็ก (Steel Wind Strike)** | วาร์ปโจมตีศัตรู 5 ตัว — **6d10 Force** |
| **เรียกมังกร (Summon Dragon)** [C] | เรียกวิญญาณมังกรมาร่วมรบ |
| **รูปลักษณ์ (Seeming)** | เปลี่ยนรูปลักษณ์ทั้งทีม |
| **สร้างสรรค์ (Creation)** | สร้างวัตถุจากอากาศ |
| **วงวาร์ป (Teleportation Circle)** | สร้างประตูวาร์ป |

---

## สเปลระดับ 6-9

### ระดับ 6 (เลเวล 11)
| สเปล | ทำอะไร |
|---|---|
| **Disintegrate** [แนะนำมาก] | **10d6+40 Force** — HP เหลือ 0 = **กลายเป็นผงทันที** |
| **Chain Lightning** [แนะนำมาก] | **10d8 Lightning** กระโดดใส่ศัตรู 4 ตัว |
| **Globe of Invulnerability** [แนะนำ] | สเปลระดับ 5 หรือต่ำกว่าจากภายนอกผ่านเข้ามาไม่ได้ |
| **Arcane Gate** [แนะนำ] | สร้างประตูวาร์ป 2 บานที่เชื่อมกัน |
| **Mass Suggestion** | ชักจูงคน 12 คนพร้อมกัน |
| **Sunbeam** [C] | ลำแสงตะวัน — 6d8 Radiant + Blinded |
| **Circle of Death** | ทรงกลม 60 ฟุต — 8d6 Necrotic |
| **Eyebite** [C] | ทำให้เป้าหมาย Asleep / Panicked / Sickened |
| **Flesh to Stone** [C] | เป้าหมายกลายเป็นหิน |
| **True Seeing** | เห็นทะลุภาพลวงตา เห็นสิ่งล่องหน |
| **Otiluke's Freezing Sphere** | ทรงกลม 60 ฟุต — 10d6 Cold |
| **Move Earth** [C] | เปลี่ยนภูมิประเทศดินและทราย |
| **Scatter** | วาร์ปสิ่งมีชีวิต 5 ตัวไปที่อื่น |

### ระดับ 7 (เลเวล 13)
| สเปล | ทำอะไร |
|---|---|
| **Delayed Blast Fireball** [แนะนำมาก] [C] | ลูกไฟสะสมพลัง — สูงสุด **24d6** |
| **Teleport** [แนะนำมาก] | วาร์ปทีมทั้งกลุ่มไปที่ไหนก็ได้ |
| **Finger of Death** [แนะนำ] | **7d8+30 Necrotic** — ถ้าตายกลายเป็น Zombie รับใช้ |
| **Reverse Gravity** [แนะนำ] [C] | กลับแรงโน้มถ่วงในทรงกระบอก 100 ฟุต |
| **Prismatic Spray** | กรวย 60 ฟุต — 8 ธาตุสุ่ม |
| **Fire Storm** | เลือกลูกบาศก์ 10 ลูก — 7d10 Fire |
| **Etherealness** | เข้าสู่มิติ Ethereal |
| **Plane Shift** | วาร์ปไปมิติอื่น |

### ระดับ 8 (เลเวล 15)
| สเปล | ทำอะไร |
|---|---|
| **Power Word Stun** [แนะนำมาก] | เป้าหมายที่ HP ≤ 150 **Stunned ทันที** |
| **Dominate Monster** [แนะนำมาก] [C] | ควบคุมสิ่งมีชีวิตใดก็ได้ |
| **Sunburst** [แนะนำ] | ทรงกลม 60 ฟุต — **12d6 Radiant + Blinded** |
| **Incendiary Cloud** [C] | เมฆไฟ 10d8 Fire ที่เคลื่อนที่ได้ |
| **Earthquake** [C] | แผ่นดินไหวรัศมี 100 ฟุต |
| **Demiplane** | สร้างประตูไปยังมิติส่วนตัว |

### ระดับ 9 (เลเวล 17)
| สเปล | ทำอะไร |
|---|---|
| **Wish** [แนะนำอย่างยิ่ง] | **สเปลที่ทรงพลังที่สุดในเกม** — ร่ายสเปลระดับ 8 หรือต่ำกว่าฟรี หรือขอพรอะไรก็ได้ |
| **Time Stop** [แนะนำอย่างยิ่ง] | **หยุดเวลา 1d4+1 เทิร์น** |
| **Meteor Swarm** [แนะนำมาก] | 4 จุด รัศมี 40 ฟุต — **20d6 Fire + 20d6 Bludgeoning** |
| **Power Word Kill** [แนะนำมาก] | เป้าหมายที่ **HP ≤ 100 ตายทันที** |
| **Gate** [C] | เปิดประตูมิติ / เรียกสิ่งมีชีวิตที่รู้จักชื่อ |

---

## คำแนะนำการสร้าง Sorcerer

### ค่าพลังที่ควรจัด

```
CHA สูงสุดเสมอ (17 ตั้งแต่เลเวล 1 20)
CON สูงรอง (14-16) HP น้อยที่สุด + ต้องรักษา Concentration
DEX ปานกลาง (14) AC (Mage Armor) และ Initiative
WIS ถ้าเหลือ
INT / STR ต่ำได้
```

### Species ที่แนะนำ
| Species | เหตุผล |
|---|---|
| **Dragonborn** [แนะนำ] | เข้าธีมสายเลือดมังกรสมบูรณ์แบบ + Breath Weapon |
| **Tiefling** [แนะนำมาก] | สเปลฟรี + Resistance ธาตุ + เข้าธีม |
| **Dwarf** [แนะนำมาก] | +1 HP ทุกเลเวล (แก้ปัญหา d6) |
| **Gnome** [แนะนำ] | Advantage ใน INT/WIS/CHA Save |
| **Human** | Feat ฟรี (`Tough`) |
| **Aasimar** | Healing Hands + Necrotic Shroud (ใช้ CHA) |

### Background ที่แนะนำ
**Charlatan** (DEX/CON/CHA) [แนะนำมาก] — ตรงเป๊ะทั้ง 3 ค่า • **CON/INT/CHA — ได้ `Lucky` (Merchant)** • **Acolyte** (INT/WIS/CHA)

### Feat ที่แนะนำ (เลเวล 4+)
| Feat | ทำไม |
|---|---|
| **Ability Score Improvement (CHA)** [แนะนำมาก] | ดัน CHA ถึง 20 ก่อนอย่างอื่น |
| **War Caster** [แนะนำมาก] | Advantage ในการรักษา Concentration |
| **Resilient (Constitution)** [แนะนำมาก] | Proficiency ใน CON Save |
| **Tough** [แนะนำ] | +2 HP ต่อเลเวล (จำเป็นมากสำหรับ d6) |
| **Fey Touched** / **Shadow Touched** | +1 CHA + ได้สเปลเพิ่มนอกรายการ Sorcerer |
| **Metamagic Adept** | ได้ Metamagic เพิ่ม 2 อย่าง + 2 SP |
| **Elemental Adept** | ทำให้ศัตรูที่มี Resistance ต่อธาตุนั้นเสียประโยชน์ |

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

| ผิด | ถูก |
|---|---|
| เลือกสเปลเฉพาะทาง | **Sorcerer มีสเปลน้อยที่สุด** — เลือกสเปลที่ใช้ได้หลายสถานการณ์ |
| แปลง Spell Slot เป็น SP ตลอด | **ไม่คุ้ม** — ใช้ SP กับ Metamagic เป็นหลัก |
| ลืมใช้ Innate Sorcery | ใช้ทุกศึกใหญ่ — **Advantage ทุก Spell Attack + DC +1** |
| ลืมร่าย `Mage Armor` ตอนเช้า | AC 13+DEX แทน 10+DEX — ร่ายทุกวัน (8 ชั่วโมง) |
| ยืนใกล้ศัตรู | **HP d6 น้อยที่สุดในเกม** — ยืนหลังแนวเสมอ |
| ไม่เอา `Shield` | **สเปลที่ดีที่สุดของสายเวท** — +5 AC ด้วย Reaction |
| ใช้ Metamagic 2 อย่างพร้อมกันก่อนเลเวล 7 | **ทำไม่ได้** จนกว่าจะได้ Sorcery Incarnate |

---

## สรุป Sorcerer ในหนึ่งบรรทัด

> **Metamagic ดัดแปลงเวทได้ตามใจ (ร่าย 2 สเปลในเทิร์นเดียว / บัฟ 2 คน / ไม่โดนเพื่อน) + Cantrip เยอะที่สุด = คลาสที่ใช้สเปลได้ทรงพลังที่สุด แต่มีสเปลให้เลือกน้อยที่สุด**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
