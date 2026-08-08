# อัศวินศักดิ์สิทธิ์ (Paladin)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**พาลาดิน / อัศวินศักดิ์สิทธิ์ (Paladin)** คือนักรบผู้สาบานตนต่ออุดมการณ์ พลังของพวกเขามาจาก **คำสาบาน (Oath)** ไม่ใช่จากเทพเจ้าโดยตรง พวกเขาตีแรง ทนมาก รักษาเพื่อนได้ และมี **ออร่า (Aura)** ที่บัฟทั้งทีม

> **Paladin คือคลาสที่ "ทำได้ทุกอย่าง"** — แนวหน้า + ดาเมจ + รักษา + บัฟทีม แต่ต้องดัน 3 ค่าพลัง (STR, CHA, CON)

---

## ข้อมูลพื้นฐาน (Class Table)

| หัวข้อ | ค่า |
|---|---|
| **Primary Ability** | **Strength (STR)** และ **Charisma (CHA)** |
| **Hit Die** | **d10** |
| **HP เลเวล 1** | **10 + CON modifier** |
| **HP เลเวลถัดไป** | **1d10 + CON** (หรือค่าคงที่ **6 + CON**) |
| **Saving Throw Proficiency** | **Wisdom, Charisma** |
| **Armor Proficiency** | **ครบทุกอย่าง (Light, Medium, Heavy Armor + Shield)** |
| **Weapon Proficiency** | Simple Weapons, **Martial Weapons** |
| **Skill Proficiency** | เลือก **2** จาก: **Athletics, Insight, Intimidation, Medicine, Persuasion, Religion** |
| **Weapon Mastery** | **2 ชนิด** |
| **Spellcasting Ability** | **Charisma (CHA)** |
| **Subclass (Sacred Oath)** | เลือกที่ **เลเวล 3** |

### อุปกรณ์เริ่มต้น

**เลือก A:** Chain Mail, Shield, Longsword, ×6 Javelin, Holy Symbol, Priest's Pack, **9 GP**
**เลือก B:** **150 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

| เลเวล | Prof<br>Bonus | Features | Channel<br>Divinity | เตรียม<br>สเปล | Slot<br>1 | Slot<br>2 | Slot<br>3 | Slot<br>4 | Slot<br>5 |
|---|---|---|---|---|---|---|---|---|---|
| **1** | +2 | **Lay On Hands**, **Spellcasting**, **Weapon Mastery** | — | 2 | **2** | — | — | — | — |
| **2** | +2 | **Fighting Style**, **Paladin's Smite** [แนะนำ] | — | 3 | 2 | — | — | — | — |
| **3** | +2 | **Channel Divinity** [แนะนำ], **Sacred Oath (Subclass)** | **2** | 4 | **3** | — | — | — | — |
| **4** | +2 | **ASI** | 2 | 5 | 3 | — | — | — | — |
| **5** | **+3** | **Extra Attack** [แนะนำ], **Faithful Steed** | 2 | 6 | **4** | **2** | — | — | — |
| **6** | +3 | **Aura of Protection** [แนะนำมาก] | 2 | 6 | 4 | 2 | — | — | — |
| **7** | +3 | **Subclass Feature** | 2 | 7 | 4 | **3** | — | — | — |
| **8** | +3 | **ASI** | 2 | 7 | 4 | 3 | — | — | — |
| **9** | **+4** | **Abjure Foes** | **3** | 9 | 4 | 3 | **2** | — | — |
| **10** | +4 | **Aura of Courage** [แนะนำ] | 3 | 9 | 4 | 3 | 2 | — | — |
| **11** | +4 | **Radiant Strikes** [แนะนำ] | 3 | 10 | 4 | 3 | **3** | — | — |
| **12** | +4 | **ASI** | 3 | 10 | 4 | 3 | 3 | — | — |
| **13** | **+5** | — | 3 | 11 | 4 | 3 | 3 | **1** | — |
| **14** | +5 | **Restoring Touch** | 3 | 11 | 4 | 3 | 3 | 1 | — |
| **15** | +5 | **Subclass Feature** | 3 | 12 | 4 | 3 | 3 | **2** | — |
| **16** | +5 | **ASI** | 3 | 12 | 4 | 3 | 3 | 2 | — |
| **17** | **+6** | — | 3 | 14 | 4 | 3 | 3 | 3 | **1** |
| **18** | +6 | **30 ฟุต (Aura Expansion)** [แนะนำ] | 3 | 14 | 4 | 3 | 3 | 3 | 1 |
| **19** | +6 | **Epic Boon Feat** | 3 | 15 | 4 | 3 | 3 | 3 | **2** |
| **20** | +6 | **Subclass Capstone** | 3 | 15 | 4 | 3 | 3 | 3 | 2 |

> **Paladin ไม่มี Cantrip** — ใช้เฉพาะสเปลที่ต้องใช้ Slot

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 — มือแห่งการเยียวยา (Lay On Hands)

> คุณมี **คลังพลังรักษา (Healing Pool) = 5 × เลเวล Paladin** HP
>
> **Bonus Action:** สัมผัสสิ่งมีชีวิต ดึง HP จากคลังมาฟื้นให้เท่าไหร่ก็ได้
>
> **หรือ:** ใช้ **5 HP จากคลัง** เพื่อ **ลบสภาวะ Poisoned** ออกจากเป้าหมาย
>
> **ฟื้นคลัง:** Long Rest

| เลเวล | คลัง HP |
|---|---|
| 1 | 5 |
| 5 | 25 |
| 10 | 50 |
| 20 | **100** |

> **Lay On Hands ไม่ฟื้นสภาวะอื่นนอกจาก Poisoned** และไม่ให้ Temp HP

---

### เลเวล 1 — Spellcasting

> - ใช้ **Charisma** เป็นค่าร่ายเวท
> - **Spell Save DC = 8 + CHA modifier + Proficiency Bonus**
> - **Spell Attack = CHA modifier + Proficiency Bonus**
> - **เตรียมสเปลใหม่ได้ทุกครั้งที่จบ Long Rest** (เลือกจากรายการ Paladin ทั้งหมด)
> - **Spellcasting Focus:** **ติดบนโล่ได้! (Holy Symbol)**

---

### เลเวล 1 — Weapon Mastery

> เลือกอาวุธ **2 ชนิด** ปลดล็อก Mastery Property

** แนะนำ:** **Longsword (Sap)** + **Javelin (Slow)** สำหรับสายดาบ+โล่
หรือ **Greatsword (Graze)** + **Maul (Topple)** สำหรับสาย 2 มือ

---

### เลเวล 2 — Fighting Style

> ได้ **Fighting Style Feat 1 อัน**

** แนะนำสำหรับ Paladin:**

| Fighting Style | เหมาะกับ |
|---|---|
| **Defense** (+1 AC) [แนะนำ] | ทุกสาย — Paladin ใส่เกราะเสมอ |
| **+2 ดาเมจ (Dueling)** [แนะนำ] | สายดาบ+โล่ |
| **Great Weapon Fighting** | สายอาวุธ 2 มือ |
| **Protection** | สายปกป้องเพื่อน (Reaction ทำให้ศัตรูที่ตีเพื่อนเสียเปรียบ) |
| **Blessed Warrior** [แนะนำ] | **ได้ Cantrip จากรายการ Cleric 2 อัน** — แก้ปัญหาที่ Paladin ไม่มี Cantrip |

---

### เลเวล 2 — การฟาดฟันศักดิ์สิทธิ์ (Paladin's Smite) ความสามารถที่โด่งดังที่สุด

> **กฎ 2024 เปลี่ยน Divine Smite เป็น "สเปลระดับ 1"** แทนที่จะเป็นความสามารถอิสระ
>
> **Paladin's Smite ให้:**
> - **สเปล `Divine Smite` เป็นสเปลที่เตรียมไว้เสมอ** (ไม่นับโควตา)
> - **ร่ายได้ฟรี 1 ครั้งต่อ Long Rest โดยไม่เสีย Spell Slot**

### สเปล ระดับ 1, Evocation (`Divine Smite`)

| หัวข้อ | รายละเอียด |
|---|---|
| **Casting Time** | **Bonus Action** — ใช้ทันทีหลังจากที่คุณ**ตีโดนด้วยอาวุธ Melee หรือ Unarmed Strike** |
| **Range** | Self |
| **ผล** | เพิ่มดาเมจ **2d8 Radiant** ให้การโจมตีนั้น |
| **เพิ่มดาเมจ** | **+1d8 ต่อระดับ Slot ที่สูงขึ้น** |
| **โบนัสพิเศษ** | **+1d8 เพิ่มอีก** ถ้าเป้าหมายเป็น **Fiend (ปีศาจ) หรือ Undead (อันเดด)** |

**ตารางดาเมจ Divine Smite:**

| Slot ที่ใช้ | ดาเมจ | ใส่ Fiend/Undead |
|---|---|---|
| ระดับ 1 | **2d8** (~9) | **3d8** (~13.5) |
| ระดับ 2 | **3d8** (~13.5) | **4d8** (~18) |
| ระดับ 3 | **4d8** (~18) | **5d8** (~22.5) |
| ระดับ 4 | **5d8** (~22.5) | **6d8** (~27) |
| ระดับ 5 | **6d8** (~27) | **7d8** (~31.5) |

> **จุดที่เปลี่ยนจากกฎเก่า (สำคัญมาก):**
> - **ใช้ Bonus Action** ไม่สามารถใช้ Smite หลายครั้งในเทิร์นเดียวได้อีกแล้ว (เมื่อก่อนทำได้)
> - **นับเป็นสเปล** **ร่ายสเปลอื่นด้วย Action ในเทิร์นเดียวกันไม่ได้** (ยกเว้น Cantrip)
> - **1 ครั้งต่อเทิร์นเท่านั้น**

> **กลยุทธ์:** เก็บ Slot ไว้ Smite ตอน **Critical Hit** — ดาเมจคูณสอง!

---

### เลเวล 3 — พลังแห่งเทพ (Channel Divinity)

> ใช้พลังศักดิ์สิทธิ์เพื่อสร้างผลพิเศษ — **ใช้ได้ 2 ครั้ง** (3 ครั้งที่เลเวล 9)
> **ฟื้น: 1 ครั้งเมื่อ Short Rest, ทั้งหมดเมื่อ Long Rest**

**ทุก Paladin ได้ 1 อย่างพื้นฐาน:**

| Channel Divinity | ผล |
|---|---|
| **Divine Sense** | **Bonus Action:** จนถึงจบเทิร์นหน้า คุณ**รู้ตำแหน่งของ Celestial, Fiend, และ Undead ทุกตัวในระยะ 60 ฟุต** ที่ไม่มี Total Cover — และรู้ชนิดของมัน |

**+ Channel Divinity เพิ่มจาก Subclass** (ดูส่วน Subclass)

---

### เลเวล 5 — Extra Attack

> **โจมตีได้ 2 ครั้ง** เมื่อใช้ Attack action

---

### เลเวล 5 — พาหนะผู้ภักดี (Faithful Steed)

> - **สเปล `Find Steed` เป็นสเปลที่เตรียมไว้เสมอ** (ไม่นับโควตา)
> - **ร่ายฟรี 1 ครั้งต่อ Long Rest** โดยไม่เสีย Spell Slot

---

### เลเวล 6 — ออร่าแห่งการปกป้อง (Aura of Protection) Feature ที่ทรงพลังที่สุดของ Paladin

> **คุณและเพื่อนร่วมทีมทุกคนในระยะ 10 ฟุตจากคุณ (30 ฟุตที่เลเวล 18)**
> **ได้โบนัสในการทอย Saving Throw ทั้งหมด เท่ากับ CHA modifier ของคุณ** (ขั้นต่ำ +1)
>
> ต้องไม่ถูก Incapacitated

**ทำไมนี่คือ Feature ที่ทีมทุกทีมอยากได้:**

| CHA | โบนัส Save ให้ทุกคน |
|---|---|
| 16 (+3) | **+3** |
| 18 (+4) | **+4** |
| 20 (+5) | **+5** |

> **+5 ในทุก Saving Throw ของทุกคนในทีม** = ทีมแทบไม่โดนสเปลควบคุมของศัตรูเลย
> นี่คือเหตุผลที่ผู้เล่นหลายคน Multiclass **2 เลเวล Paladin** เพื่อเอา Smite หรือ **6-7 เลเวล** เพื่อเอา Aura นี้

---

### เลเวล 9 — ขับไล่ศัตรู (Abjure Foes)

> **Channel Divinity + Magic action:** เลือกสิ่งมีชีวิตได้ถึง **Prof Bonus ตัว** ในระยะ 60 ฟุต
> ทอย **WIS Save** — **ล้มเหลว = Frightened 1 นาที**
>
> ระหว่าง Frightened: **ทำได้แค่ Action หรือ Bonus Action อย่างใดอย่างหนึ่ง** และ **เคลื่อนที่ไม่ได้**
> (จบทันทีเมื่อได้รับดาเมจ)

---

### เลเวล 10 — ออร่าแห่งความกล้าหาญ (Aura of Courage)

> **คุณและเพื่อนร่วมทีมในระยะ Aura ของคุณ ภูมิคุ้มกันสภาวะ Frightened**
> (ถ้ามีสภาวะอยู่แล้วจะถูกระงับชั่วคราวขณะอยู่ในออร่า)

---

### เลเวล 11 — การโจมตีเปล่งรัศมี (Radiant Strikes)

> **การโจมตีด้วยอาวุธ Melee และ Unarmed Strike ของคุณทุกครั้ง**
> **เพิ่มดาเมจ `1d8 Radiant` โดยอัตโนมัติ**

**ทำไมดี:** ดาเมจฟรีทุกครั้ง ไม่เสียทรัพยากรอะไรเลย

```
เลเวล 11 โจมตี 2 ครั้ง = +2d8 Radiant ฟรีทุกเทิร์น (~9 ดาเมจ)
```

---

### เลเวล 14 — สัมผัสฟื้นฟู (Restoring Touch)

> **เมื่อใช้ Lay On Hands** คุณสามารถ**ใช้ 5 HP จากคลัง** เพื่อลบสภาวะ 1 อย่าง:
> **Blinded, Charmed, Deafened, Frightened, Paralyzed, หรือ Stunned**
> (ลบได้หลายอย่างในครั้งเดียว โดยจ่าย 5 HP ต่อสภาวะ)

---

### เลเวล 18 — ขยายออร่า (Aura Expansion)

> **ระยะ Aura ทั้งหมดของคุณเพิ่มจาก 10 ฟุต เป็น 30 ฟุต**

---

## Subclasses (Sacred Oath) — เลือกที่เลเวล 3

Paladin มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 7, 15, 20**
**ทุก Subclass ให้ "Oath Spells" ที่เตรียมไว้เสมอ (ไม่นับโควตา)**

---

### 1. Oath of Devotion — คำสาบานแห่งความภักดี

> **ธีม:** อัศวินผู้ยึดมั่นในเกียรติ ความยุติธรรม และความจริง (Paladin แบบคลาสสิก)

**Oath Spells:**

| เลเวล Paladin | สเปล |
|---|---|
| 3 | `Protection from Evil and Good`, `Shield of Faith` |
| 5 | `Aid`, `Zone of Truth` |
| 9 | `Beacon of Hope`, `Dispel Magic` |
| 13 | `Freedom of Movement`, `Guardian of Faith` |
| 17 | `Commune`, `Flame Strike` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Sacred Weapon** (Channel Divinity) | **Bonus Action:** อาวุธของคุณเปล่งแสง **10 นาที**:<br>• **บวก CHA modifier ในการทอยโจมตี** (ขั้นต่ำ +1)<br>• อาวุธนับเป็น **Magical**<br>• เปล่งแสง **Bright Light 20 ฟุต + Dim Light 20 ฟุต** |
| **7** | **Aura of Devotion** | [แนะนำ] คุณและเพื่อนในระยะ Aura **ภูมิคุ้มกันสภาวะ Charmed** |
| **15** | **Smite of Protection** | [แนะนำ] เมื่อคุณร่าย `Divine Smite` **คุณและเพื่อนในระยะ Aura ได้ Half Cover** จนกว่าจะเริ่มเทิร์นหน้าของคุณ |
| **20** | **Holy Nimbus** | **Bonus Action:** เข้าสู่สภาวะศักดิ์สิทธิ์ **10 นาที**:<br>• เปล่ง **Bright Light 30 ฟุต**<br>• **1 ครั้ง/เทิร์น เมื่อศัตรูเริ่มเทิร์นในแสง หรือเข้ามาในแสง รับ `10 Radiant damage`**<br>• **Advantage ในการทอย Saving Throw ต่อสเปลที่ร่ายโดย Fiend และ Undead**<br>ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5) |

> **แนะนำมือใหม่** — Sacred Weapon แก้ปัญหาการตีพลาด เข้าใจง่าย

---

### 2. Oath of Glory — คำสาบานแห่งเกียรติยศ

> **ธีม:** วีรบุรุษผู้แสวงหาความยิ่งใหญ่ (แบบเทพนิยายกรีก) — เน้นความเร็วและการช่วยทีม

**Oath Spells:**

| เลเวล Paladin | สเปล |
|---|---|
| 3 | `Guiding Bolt`, `Heroism` |
| 5 | `Enhance Ability`, `Magic Weapon` |
| 9 | `Haste`, `Protection from Energy` |
| 13 | `Compulsion`, `Freedom of Movement` |
| 17 | `Commune`, `Flame Strike` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Peerless Athlete** (Channel Divinity) | **Bonus Action:** **1 ชั่วโมง** — **Advantage ใน Athletics และ Acrobatics Check** • **ยกของได้เป็น 2 เท่า** • **ระยะกระโดด +10 ฟุต** |
| **3** | **Inspiring Smite** (Channel Divinity) | **Bonus Action** [แนะนำ] ทันทีหลังร่าย `Divine Smite` **แจก Temp HP รวม `2d8 + เลเวล Paladin`** ให้ตัวเองและเพื่อนในระยะ 30 ฟุต (แบ่งได้ตามใจ) |
| **7** | **Aura of Alacrity** | **Speed ของคุณ +10 ฟุต** [แนะนำ] • เพื่อนที่เริ่มเทิร์นในระยะ 10 ฟุตจากคุณ **ได้ Speed +10 ฟุต** จนจบเทิร์น |
| **15** | **Glorious Defense** | **Reaction:** [แนะนำ] เมื่อคุณหรือเพื่อนในระยะ 10 ฟุตถูกโจมตี **บวก CHA modifier ใน AC ของการโจมตีนั้น** — ถ้าทำให้พลาด **โจมตีกลับ 1 ครั้งทันที** — ใช้ได้ Prof Bonus ครั้ง/Long Rest |
| **20** | **Living Legend** | **Bonus Action: 10 นาที**:<br>• **Advantage ในการทอย Charisma Check ทั้งหมด**<br>• **1 ครั้ง/เทิร์น: การโจมตีที่พลาด นับเป็นโดนแทน**<br>• **เมื่อทอย Saving Throw ล้มเหลว ทอยใหม่ได้ (1 ครั้ง/เทิร์น)**<br>ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5) |

> **สายที่ช่วยทีมด้านความเร็วและ Temp HP ได้ดีที่สุด**

---

### 3. Oath of the Ancients — คำสาบานแห่งบรรพกาล

> **ธีม:** อัศวินผู้พิทักษ์แสงสว่าง ชีวิต และความงามในโลก (ธีมธรรมชาติ/Fey)

**Oath Spells:**

| เลเวล Paladin | สเปล |
|---|---|
| 3 | `Ensnaring Strike`, `Speak with Animals` |
| 5 | `Misty Step`, `Moonbeam` |
| 9 | `Plant Growth`, `Protection from Energy` |
| 13 | `Ice Storm`, `Stoneskin` |
| 17 | `Commune with Nature`, `Tree Stride` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Nature's Wrath** (Channel Divinity) | **Magic action:** สิ่งมีชีวิตที่เลือกในระยะ 15 ฟุต ทอย **STR Save** — **ล้มเหลว = Restrained (ถูกตรึงด้วยเถาวัลย์) 1 นาที** (ทอยใหม่ได้ทุกจบเทิร์น) |
| **7** | **Aura of Warding** | [แนะนำมาก] คุณและเพื่อนในระยะ Aura ได้ **Resistance ต่อ Necrotic, Psychic, และ Radiant damage** |
| **15** | **Undying Sentinel** | **เมื่อ HP ลดเหลือ 0 แต่ไม่ตายทันที HP เหลือ 1 แทน** [แนะนำ] (ใช้ได้ 1 ครั้ง/Long Rest) • และคุณ **ไม่แก่ตัวลงอีกต่อไป** |
| **20** | **Elder Champion** | **Bonus Action:** แปลงร่างเป็นสิ่งมีชีวิตแห่งธรรมชาติ **10 นาที**:<br>• **ฟื้น 10 HP เมื่อเริ่มเทิร์นของคุณ**<br>• **ร่ายสเปล Paladin ที่มี Casting Time เป็น Action ใช้ Bonus Action แทนได้**<br>• **ศัตรูในระยะ 10 ฟุต เสียเปรียบในการทอย Saving Throw ต่อสเปลและ Channel Divinity ของคุณ**<br>ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5) |

> **Aura of Warding เป็นหนึ่งใน Aura ที่ทรงพลังที่สุดในเกม** — Resistance 3 ธาตุให้ทั้งทีม

---

### 4. Oath of Vengeance — คำสาบานแห่งการล้างแค้น

> **ธีม:** ผู้ตามล่าความชั่วร้ายโดยไม่สนวิธีการ — **ดาเมจสูงที่สุด**

**Oath Spells:**

| เลเวล Paladin | สเปล |
|---|---|
| 3 | `Bane`, `Hunter's Mark` |
| 5 | `Hold Person`, `Misty Step` |
| 9 | `Haste`, `Protection from Energy` |
| 13 | `Banishment`, `Dimension Door` |
| 17 | `Hold Monster`, `Scrying` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Vow of Enmity** (Channel Divinity) | **Bonus Action:** [แนะนำมาก] เลือกศัตรู 1 ตัวในระยะ 30 ฟุต **คุณมี Advantage ในการโจมตีมันทุกครั้ง เป็นเวลา 1 นาที** (ถ้ามันตายก่อน ย้ายไปตัวใหม่ได้ด้วย Bonus Action) |
| **7** | **Relentless Avenger** | เมื่อคุณตีโดนด้วย **Opportunity Attack** **เคลื่อนที่ได้ครึ่ง Speed ทันที** โดยไม่โดน Opportunity Attack |
| **15** | **Soul of Vengeance** | **Reaction:** [แนะนำ] เมื่อศัตรูที่ติด **Vow of Enmity** โจมตีหรือร่ายเวท **โจมตีมัน 1 ครั้งทันที** |
| **20** | **Avenging Angel** | **Bonus Action:** งอกปีก **10 นาที**:<br>• **Fly Speed 60 ฟุต**<br>• **ศัตรูที่เริ่มเทิร์นในระยะ 30 ฟุต ทอย WIS Save — ล้มเหลว = Frightened 1 นาที** และ **การโจมตีของคุณต่อมันมี Advantage**<br>ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5) |

> **สายดาเมจสูงสุด** — Vow of Enmity ให้ Advantage ตลอด = คริติคอลบ่อย = Smite แรง

---

## เปรียบเทียบ 4 Subclass

| | **Devotion** | **Glory** | **Ancients** | **Vengeance** |
|---|---|---|---|---|
| **จุดเด่น** | ไม่พลาด + ต้าน Charm | ความเร็ว + Temp HP | Resistance 3 ธาตุ | **ดาเมจสูงสุด** |
| **ความยาก** | ง่าย | กลาง | ง่าย | ง่าย |
| **ช่วยทีม** | สูง | **สูงสุด** | **สูงสุด** | ต่ำ |
| **แนะนำมือใหม่** | **ใช่** | ใช่ | ใช่ | **ใช่ (สายตี)** |

---
---

# รายการเวทของ Paladin (Paladin Spell List)

> **Paladin ไม่มี Cantrip** (ยกเว้นเอา Fighting Style `Blessed Warrior`)
> **เตรียมสเปลใหม่ได้ทุกครั้งที่จบ Long Rest** — เลือกจากรายการทั้งหมดด้านล่าง
> **[C] = ต้องรักษา Concentration** | **[R] = ร่ายแบบ Ritual ได้**

---

## สเปลระดับ 1 (Level 1 Spells)

| สเปล | ทำอะไร |
|---|---|
| **ประทานพร (Bless)** [แนะนำมาก] [C] | เพื่อน 3 คน **+1d4 ในการทอยโจมตีและ Saving Throw** 1 นาที — **สเปลที่ดีที่สุดของ Paladin** |
| **บัญชา (Command)** | เป้าหมายทอย WIS Save — ล้มเหลว = ทำตามคำสั่ง 1 คำ (Approach, Drop, Flee, Grovel, Halt) |
| **บังคับประลอง (Compelled Duel)** [C] | เป้าหมายทอย WIS Save — ล้มเหลว = **เสียเปรียบเมื่อโจมตีคนอื่นที่ไม่ใช่คุณ และเดินห่างจากคุณไม่ได้** |
| **รักษาบาดแผล (Cure Wounds)** | สัมผัส ฟื้น **2d8 + CHA** HP |
| **ตรวจจับดีชั่ว (Detect Evil and Good)** [C] | รับรู้ Aberration, Celestial, Elemental, Fey, Fiend, Undead ในระยะ 30 ฟุต |
| **ตรวจจับเวท (Detect Magic)** [C][R] | รับรู้เวทมนตร์ในระยะ 30 ฟุต |
| **ตรวจจับพิษและโรค (Detect Poison and Disease)** [C][R] | รับรู้พิษและโรคในระยะ 30 ฟุต |
| **พรแห่งเทพ (Divine Favor)** [แนะนำ] | **1 นาที: การโจมตีด้วยอาวุธเพิ่ม 1d4 Radiant** (ไม่ต้อง Concentration ในกฎ 2024) |
| **ฟาดฟันศักดิ์สิทธิ์ (Divine Smite)** [แนะนำมาก] | **Bonus Action หลังตีโดน: +2d8 Radiant** (เตรียมไว้เสมอ) |
| **วีรกรรม (Heroism)** [C] | เป้าหมาย **ภูมิคุ้มกัน Frightened** + ได้ **Temp HP = CHA modifier ทุกเทิร์น** |
| **ป้องกันจากดีชั่ว (Protection from Evil and Good)** [C] | เป้าหมายที่ระบุ **โจมตีเป้าหมายเราแบบเสียเปรียบ** และเป้าหมายเรา **ภูมิคุ้มกัน Charmed/Frightened/Possessed** จากพวกมัน |
| **ชำระอาหารและน้ำ (Purify Food and Drink)** [R] | ล้างพิษออกจากอาหารและน้ำในรัศมี 5 ฟุต |
| **ฟาดฟันแผดเผา (Searing Smite)** [แนะนำ] | **Bonus Action หลังตีโดน: +1d6 Fire** และเป้าหมาย**ไหม้ 1d6 ทุกเทิร์น** จนกว่าจะดับ |
| **โล่แห่งศรัทธา (Shield of Faith)** [แนะนำ] [C] | **Bonus Action: +2 AC** ให้เป้าหมาย 10 นาที |
| **ฟาดฟันกัมปนาท (Thunderous Smite)** [แนะนำ] | **Bonus Action หลังตีโดน: +2d6 Thunder** + เป้าหมายทอย STR Save ล้มเหลว = **ผลัก 10 ฟุต + Prone** |
| **ฟาดฟันแค้นเคือง (Wrathful Smite)** | **Bonus Action หลังตีโดน: +1d6 Psychic** + เป้าหมายทอย WIS Save ล้มเหลว = **Frightened** |

> **แนะนำที่เลเวล 1-2:** `Bless` [แนะนำมาก] + `Divine Favor` หรือ `Shield of Faith`

---

## สเปลระดับ 2 (Level 2 Spells) — ได้ที่เลเวล 5

| สเปล | ทำอะไร |
|---|---|
| **ช่วยเหลือ (Aid)** [แนะนำมาก] | เพื่อน 3 คน **HP สูงสุด +5 และฟื้น 5 HP** เป็นเวลา **8 ชั่วโมง** (สเปลบัฟที่คุ้มที่สุด) |
| **เรียกพาหนะ (Find Steed)** | เรียกม้า/สัตว์พาหนะวิญญาณ (เตรียมไว้เสมอที่เลเวล 5) |
| **หลับสงบ (Gentle Repose)** [R] | ป้องกันศพเน่าเปื่อยและกลายเป็น Undead 10 วัน |
| **ฟื้นฟูขั้นต้น (Lesser Restoration)** [แนะนำ] | ลบสภาวะ **Blinded, Deafened, Paralyzed, หรือ Poisoned** |
| **ค้นหาวัตถุ (Locate Object)** [C] | รู้ตำแหน่งวัตถุที่คุ้นเคยในระยะ 1,000 ฟุต |
| **อาวุธเวท (Magic Weapon)** | อาวุธได้ **+1 ในการทอยโจมตีและดาเมจ** และนับเป็น Magical (ไม่ต้อง Concentration ในกฎ 2024) |
| **คำอธิษฐานรักษา (Prayer of Healing)** | ใช้เวลา 10 นาที เพื่อน 5 คนฟื้น **2d8 + CHA** HP |
| **ป้องกันพิษ (Protection from Poison)** | ลบพิษ 1 อย่าง + **Advantage ต้านพิษ + Resistance Poison** 1 ชั่วโมง |
| **ฟาดฟันเรืองแสง (Shining Smite)** [แนะนำ] [C] | **Bonus Action หลังตีโดน: +2d6 Radiant** + เป้าหมาย**เปล่งแสง** (ศัตรูโจมตีมันได้ Advantage) |
| **พันธะปกป้อง (Warding Bond)** | เพื่อนได้ **+1 AC, +1 Save, Resistance ทุกดาเมจ** แต่**คุณรับดาเมจเท่ากันด้วย** |
| **เขตความจริง (Zone of Truth)** | ในรัศมี 15 ฟุต ทุกคนที่ทอย CHA Save ล้มเหลว **โกหกไม่ได้** 10 นาที |

> **แนะนำ:** `Aid` [แนะนำมาก] (บัฟที่ดีที่สุดในเกม) + `Lesser Restoration`

---

## สเปลระดับ 3 (Level 3 Spells) — ได้ที่เลเวล 9

| สเปล | ทำอะไร |
|---|---|
| **ออร่าแห่งชีวิต (Aura of Vitality)** [แนะนำ] [C] | 1 นาที: **Bonus Action ทุกเทิร์น** ฟื้น **2d6 HP** ให้ใครก็ได้ในระยะ 30 ฟุต (รวม 20d6 ถ้าครบ 10 เทิร์น!) |
| **ฟาดฟันตาบอด (Blinding Smite)** [C] | **Bonus Action หลังตีโดน: +3d8 Radiant** + เป้าหมายทอย CON Save ล้มเหลว = **Blinded** |
| **สร้างอาหารและน้ำ (Create Food and Water)** | สร้างอาหาร 45 ปอนด์ + น้ำ 30 แกลลอน |
| **ผ้าคลุมนักรบศักดิ์สิทธิ์ (Crusader's Mantle)** [แนะนำ] [C] | เพื่อนทุกคนในระยะ 30 ฟุต **เพิ่มดาเมจ +1d4 Radiant** ในการโจมตีด้วยอาวุธทุกครั้ง |
| **แสงตะวัน (Daylight)** | สร้างแสงสว่างรัศมี 60 ฟุต — ยกเลิก Magical Darkness ระดับ 3 หรือต่ำกว่า |
| **สลายเวท (Dispel Magic)** [แนะนำ] | ยกเลิกสเปลระดับ 3 หรือต่ำกว่า (สูงกว่าต้องทอย) |
| **อาวุธธาตุ (Elemental Weapon)** [C] | อาวุธได้ **+1 โจมตี และ +1d4 ดาเมจธาตุ** |
| **วงเวท (Magic Circle)** | สร้างวงกันสิ่งมีชีวิตประเภทที่เลือก (Celestial, Elemental, Fey, Fiend, Undead) |
| **ลบคำสาป (Remove Curse)** | ลบคำสาปออกจากคนหรือของ |
| **ชุบชีวิต (Revivify)** [แนะนำมาก] | **ชุบชีวิตผู้ที่ตายไม่เกิน 1 นาที** ด้วย HP 1 (ต้องใช้เพชร 300 GP) |

> **แนะนำ:** `Revivify` [แนะนำมาก] (ต้องมีติดตัวเสมอ) + `Aura of Vitality` (รักษาได้เยอะที่สุด)

---

## สเปลระดับ 4 (Level 4 Spells) — ได้ที่เลเวล 13

| สเปล | ทำอะไร |
|---|---|
| **ออร่าแห่งชีวิต (Aura of Life)** [แนะนำ] [C] | รัศมี 30 ฟุต: เพื่อน **Resistance ต่อ Necrotic** • **HP สูงสุดลดไม่ได้** • เพื่อนที่ HP 0 **ฟื้นเป็น 1 HP อัตโนมัติเมื่อเริ่มเทิร์น** |
| **ออร่าแห่งความบริสุทธิ์ (Aura of Purity)** [แนะนำ] [C] | รัศมี 30 ฟุต: เพื่อน **Resistance ต่อ Poison** • **ภูมิคุ้มกันโรค** • **Advantage ในการทอย Save ต้านสภาวะทั้งหมด** |
| **เนรเทศ (Banishment)** [แนะนำ] [C] | เป้าหมายทอย CHA Save — ล้มเหลว = **หายไปจากสนามรบ 1 นาที** |
| **ป้องกันความตาย (Death Ward)** [แนะนำ] | 8 ชั่วโมง: **ครั้งแรกที่ HP ลดเหลือ 0 เหลือ 1 แทน** |
| **ค้นหาสิ่งมีชีวิต (Locate Creature)** [C] | รู้ตำแหน่งสิ่งมีชีวิตที่คุ้นเคยในระยะ 1,000 ฟุต |
| **ฟาดฟันเซซวน (Staggering Smite)** | **Bonus Action หลังตีโดน: +4d6 Psychic** + เป้าหมายทอย WIS Save ล้มเหลว = **เสียเปรียบทุกอย่าง + ใช้ Reaction ไม่ได้** |

---

## สเปลระดับ 5 (Level 5 Spells) — ได้ที่เลเวล 17

| สเปล | ทำอะไร |
|---|---|
| **ฟาดฟันเนรเทศ (Banishing Smite)** [C] | **Bonus Action หลังตีโดน: +5d10 Force** — ถ้าเป้าหมาย HP เหลือ **ต่ำกว่า 50 เนรเทศทันที** |
| **วงแห่งพลัง (Circle of Power)** [แนะนำ] [C] | รัศมี 30 ฟุต: เพื่อน **Advantage ในการทอย Save ต้านสเปล** • และถ้า Save สำเร็จ **รับดาเมจ 0** (แทนครึ่ง) |
| **คลื่นทำลายล้าง (Destructive Wave)** [แนะนำ] | รัศมี 30 ฟุต: ศัตรูทอย CON Save — ล้มเหลว = **5d6 Thunder + 5d6 Radiant/Necrotic + Prone** |
| **สลายดีชั่ว (Dispel Evil and Good)** [C] | Celestial/Elemental/Fey/Fiend/Undead โจมตีคุณเสียเปรียบ + ขับไล่มันได้ |
| **คำสั่งผูกมัด (Geas)** | บังคับให้เป้าหมายทำตามคำสั่ง **30 วัน** (ฝ่าฝืน = 5d10 Psychic ต่อวัน) |
| **ฟื้นฟูขั้นสูง (Greater Restoration)** [แนะนำ] | ลบ **Exhaustion 1 ระดับ / คำสาป / Charmed / Petrified / การลด HP สูงสุด / การลดค่า Ability** |
| **อาวุธศักดิ์สิทธิ์ (Holy Weapon)** [แนะนำ] [C] | อาวุธเปล่งแสง **+2d8 Radiant ทุกครั้ง** • ระเบิดได้ (4d8 + Blinded) |
| **ปลุกคนตาย (Raise Dead)** [แนะนำ] | ชุบชีวิตผู้ที่ตายไม่เกิน **10 วัน** (ต้องใช้เพชร 500 GP) |
| **เรียกทูตสวรรค์ (Summon Celestial)** | เรียกสิ่งมีชีวิตสวรรค์มาช่วยรบ 1 ชั่วโมง |

---

## คำแนะนำการสร้าง Paladin

### ค่าพลังที่ควรจัด

```
STR สูงสุด (16-17) สำหรับโจมตี
CHA สูงรอง (14-16) สำคัญมาก! กระทบ Aura of Protection และ Spell DC
CON ปานกลาง (14)
WIS ถ้าเหลือ
DEX / INT ต่ำได้ (ใส่ Heavy Armor ไม่ต้องใช้ DEX)
```

> **Paladin เป็นคลาส MAD** (ต้องดัน 3 ค่า) — เลเวลต่ำอาจรู้สึกอ่อน แต่เลเวล 6+ (Aura of Protection) จะแรงมาก
> **แนวทางทางเลือก: DEX Paladin** — ใช้ DEX + CHA แทน แล้วใส่ Half Plate + Rapier

### Species ที่แนะนำ
| Species | เหตุผล |
|---|---|
| **Aasimar** [แนะนำมาก] | เข้าธีมสมบูรณ์แบบ + Celestial Revelation (บินได้/ทำ Frightened) + CHA สูง |
| **Human** [แนะนำ] | Feat ฟรี |
| **Dragonborn** [แนะนำ] | Breath Weapon แทนการโจมตีได้ + บินได้เลเวล 5 |
| **Goliath** | Speed 35 + Giant Ancestry |
| **Dwarf** | +1 HP ทุกเลเวล |

### Background ที่แนะนำ
**Noble** (STR/INT/CHA) [แนะนำมาก] (Background เดียวที่ให้ทั้ง STR และ CHA) • **Entertainer** (STR/DEX/CHA) • **INT/WIS/CHA — เข้าธีม (Acolyte)**

### Feat ที่แนะนำ (เลเวล 4+)
| Feat | ทำไม |
|---|---|
| **Ability Score Improvement (CHA)** [แนะนำมาก] | CHA กระทบ Aura ที่บัฟทั้งทีม |
| **Great Weapon Master** [แนะนำ] | สายอาวุธ 2 มือ |
| **Polearm Master** [แนะนำ] | Bonus Attack ด้วยด้ามอาวุธ (แต่ชนกับ Smite ที่ใช้ Bonus Action) |
| **Sentinel** [แนะนำ] | หยุดศัตรูที่พยายามผ่านเราไปหาเพื่อน |
| **Inspiring Leader** | ให้ Temp HP ทั้งทีม (ใช้ CHA) |
| **War Caster** | Advantage ในการรักษา Concentration |

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

| ผิด | ถูก |
|---|---|
| ปล่อย CHA ต่ำ | **CHA คือหัวใจของ Paladin** — Aura of Protection บัฟทั้งทีม |
| ใช้ Smite ทุกครั้งที่ตีโดน | **เก็บ Slot ไว้ใช้ตอน Critical Hit** หรือกับบอส |
| ลืมว่า Smite ใช้ Bonus Action (กฎ 2024) | **ร่ายสเปลอื่นด้วย Action ในเทิร์นเดียวกันไม่ได้** |
| ยืนห่างจากทีม | **ยืนใกล้ทีมเสมอ** เพื่อให้ Aura of Protection ครอบคลุม |
| ลืมใช้ Lay On Hands | เป็นการรักษาที่ **ไม่เสีย Spell Slot** — ใช้ให้หมดทุกวัน |

---

## สรุป Paladin ในหนึ่งบรรทัด

> **ตีแรงจัดด้วย Divine Smite + ทนเหมือน Fighter + รักษาเพื่อนได้ + Aura of Protection บัฟ Save ทั้งทีม = คลาสที่ทำได้ทุกอย่าง แต่ต้องดัน STR, CHA, CON**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
