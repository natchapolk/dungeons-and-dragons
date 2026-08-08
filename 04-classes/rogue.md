# โจร / นักลอบสังหาร (Rogue)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**โร้ก / โจร (Rogue)** คือผู้เชี่ยวชาญการลอบเร้น การหลบหลีก และการโจมตีจุดอ่อน พวกเขา **ดาเมจต่อครั้งสูงมาก** ด้วย **Sneak Attack** และเป็นคลาสที่ **เก่งสกิลที่สุดในเกม**

> **แนะนำสำหรับผู้เล่นใหม่ (อันดับ 3)** — ไม่มีเวทให้จำ แต่มีสิ่งที่ทำได้หลากหลายมาก และตีแรงตั้งแต่เลเวล 1

---

## ข้อมูลพื้นฐาน (Class Table)

| หัวข้อ | ค่า |
|---|---|
| **Primary Ability** | **Dexterity (DEX)** |
| **Hit Die** | **d8** |
| **HP เลเวล 1** | **8 + CON modifier** |
| **HP เลเวลถัดไป** | **1d8 + CON** (หรือค่าคงที่ **5 + CON**) |
| **Saving Throw Proficiency** | **Dexterity, Intelligence** |
| **Armor Proficiency** | Light Armor |
| **Weapon Proficiency** | Simple Weapons + **Martial Weapon ที่มีคุณสมบัติ Finesse หรือ Light** |
| **Tool Proficiency** | **Thieves' Tools** |
| **Skill Proficiency** | เลือก **4** จาก: **มากที่สุดในเกม (Acrobatics, Athletics, Deception, Insight, Intimidation, Investigation, Perception, Performance, Persuasion, Sleight of Hand, Stealth)** |
| **Weapon Mastery** | **2 ชนิด** |
| **Subclass** | เลือกที่ **เลเวล 3** |

### อุปกรณ์เริ่มต้น

**เลือก A:** Leather Armor, ×2 Dagger, Shortsword, Shortbow + 20 Arrows, Thieves' Tools, Burglar's Pack, **8 GP**
**เลือก B:** **100 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

| เลเวล | Prof<br>Bonus | Features (ความสามารถ) | Sneak<br>Attack |
|---|---|---|---|
| **1** | +2 | **Expertise**, **Sneak Attack**, **Thieves' Cant**, **Weapon Mastery** | **1d6** |
| **2** | +2 | **Cunning Action** [แนะนำ] | 1d6 |
| **3** | +2 | **Rogue Subclass** [แนะนำ], **Steady Aim** | **2d6** |
| **4** | +2 | **Ability Score Improvement (ASI)** | 2d6 |
| **5** | **+3** | **Cunning Strike** [แนะนำ], **Uncanny Dodge** | **3d6** |
| **6** | +3 | **เพิ่ม 2 สกิล (Expertise)** | 3d6 |
| **7** | +3 | **Evasion** [แนะนำ], **Reliable Talent** | **4d6** |
| **8** | +3 | **ASI** | 4d6 |
| **9** | **+4** | **Subclass Feature** | **5d6** |
| **10** | +4 | **ASI** | 5d6 |
| **11** | +4 | **Improved Cunning Strike** | **6d6** |
| **12** | +4 | **ASI** | 6d6 |
| **13** | **+5** | **Subclass Feature** | **7d6** |
| **14** | +5 | **Devious Strikes** | 7d6 |
| **15** | +5 | **Slippery Mind** | **8d6** |
| **16** | +5 | **ASI** | 8d6 |
| **17** | **+6** | **Subclass Feature** | **9d6** |
| **18** | +6 | **Elusive** | 9d6 |
| **19** | +6 | **Epic Boon Feat** | **10d6** |
| **20** | +6 | **Stroke of Luck** | 10d6 |

> **Rogue ได้ ASI/Feat 6 ครั้ง** (เลเวล 4, 8, 10, 12, 16 + Epic Boon 19) — มากเป็นอันดับ 2 รองจาก Fighter

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 — การโจมตีลับ (Sneak Attack) ความสามารถหลักของคลาส

> **1 ครั้งต่อเทิร์น** คุณสามารถเพิ่มดาเมจ **1d6** เมื่อโจมตีโดน โดยต้องเข้าเงื่อนไขทั้ง 2 ข้อ:
>
> **เงื่อนไขที่ 1 — อาวุธ:** ต้องใช้อาวุธที่มีคุณสมบัติ **Finesse** หรือ **Ranged**
>
> **เงื่อนไขที่ 2 — สถานการณ์ (อย่างใดอย่างหนึ่ง):**
> - คุณมี **Advantage** ในการโจมตีครั้งนั้น
> - **มีเพื่อนร่วมทีมอยู่ในระยะ 5 ฟุตจากเป้าหมาย** และคุณ**ไม่มี Disadvantage**

**ดาเมจตามเลเวล:**

| เลเวล | Sneak Attack | ดาเมจเฉลี่ย |
|---|---|---|
| 1 | 1d6 | 3.5 |
| 5 | 3d6 | 10.5 |
| 11 | 6d6 | 21 |
| 17 | 9d6 | 31.5 |
| 20 | 10d6 | **35** |

> **จุดที่มือใหม่พลาดบ่อย:**
> - **1 ครั้งต่อเทิร์น เท่านั้น** (ไม่ใช่ต่อ Action) — แต่**ใช้ในเทิร์นของศัตรูได้ด้วย** ถ้าคุณมี Reaction Attack!
> - **ไม่จำเป็นต้องซ่อนตัว** — แค่มีเพื่อนยืนติดศัตรูก็พอ
> - **ใช้กับ Opportunity Attack ได้**
> - **Critical Hit เต๋า Sneak Attack ก็คูณสองด้วย**

### อาวุธที่ใช้ Sneak Attack ได้

| ประเภท | อาวุธ |
|---|---|
| **ประชิด (Finesse)** | **Rapier** [แนะนำ] (1d8, Vex), **Shortsword** [แนะนำ] (1d6, Vex), Dagger (1d4, Nick), Scimitar (1d6, Nick), Whip (1d4, Slow), Dart |
| **Ranged** | **Shortbow** [แนะนำ] (1d6, Vex), **Hand Crossbow** [แนะนำ] (1d6, Vex), Light Crossbow, Sling, Blowgun |

> **แนะนำที่สุด: Rapier (ประชิด) + Shortbow หรือ Hand Crossbow (ระยะไกล)**

---

### เลเวล 1 — ความเชี่ยวชาญ (Expertise)

> เลือก **Skill 2 อย่าง** ที่คุณมี Proficiency **บวก Proficiency Bonus สองเท่า**
> (ได้เพิ่มอีก 2 สกิลที่เลเวล 6)

** สกิลที่แนะนำสำหรับ Expertise:**

| ลำดับ | สกิล | เหตุผล |
|---|---|---|
| 1 | **Stealth** [แนะนำมาก] | หัวใจของ Rogue — ซ่อนตัวเพื่อได้ Advantage = ได้ Sneak Attack |
| 2 | **Perception** [แนะนำ] | ใช้บ่อยที่สุดในเกม + เพิ่ม Passive Perception |
| 3 | **Thieves' Tools** [แนะนำ] | (นับเป็น Tool แต่ Expertise ใช้ได้) — เปิดกุญแจ ปลดกับดัก |
| 4 | **Investigation** | หาความลับ กับดัก |
| 5 | **Sleight of Hand** | ล้วงกระเป๋า ซ่อนของ |
| 6 | **Deception / Persuasion** | ถ้าเป็น "หน้ากลุ่ม" ในการเจรจา |

> **ตัวอย่าง:** เลเวล 5 (Prof +3) มี DEX 18 (+4) + Expertise ใน Stealth
> **Stealth = 1d20 + 4 + 6 = 1d20 + 10** (ทอยขั้นต่ำ 11!)

---

### เลเวล 1 — ภาษาลับโจร (Thieves' Cant)

> - คุณรู้ **Thieves' Cant** — ภาษาลับที่ใช้สื่อสารกันในโลกใต้ดิน (คำแสลง สัญลักษณ์ ท่าทาง)
> - ใช้เวลาสื่อสาร**นานกว่าปกติ 4 เท่า** แต่คนนอกไม่มีทางเข้าใจ
> - **ได้ภาษาอื่นเพิ่มอีก 1 ภาษา** ตามที่เลือก

---

### เลเวล 1 — Weapon Mastery

> เลือกอาวุธ **2 ชนิด** ปลดล็อก Mastery Property (เปลี่ยนได้ตอน Long Rest)

** แนะนำ:** **Rapier (Vex)** + **Shortbow (Vex)**

**ทำไม Vex ดีที่สุดสำหรับ Rogue:**
```
เทิร์นที่ 1: ตีโดน ได้ Vex
เทิร์นที่ 2: การโจมตีต่อเป้าหมายนั้นได้ Advantage การันตี Sneak Attack!
```

---

### เลเวล 2 — การกระทำเจ้าเล่ห์ (Cunning Action)

> **ในเทิร์นของคุณ ใช้ Bonus Action เพื่อทำอย่างใดอย่างหนึ่ง:**
>
> | Action | ผล |
> |---|---|
> | **Dash** | เพิ่มระยะเคลื่อนที่อีกเท่าตัว |
> | **Disengage** | เคลื่อนที่ออกโดยไม่โดน Opportunity Attack |
> | **Hide** | ซ่อนตัว (DC 15 Stealth) ได้สภาวะ **Invisible** |

**ทำไมนี่คือ Feature ที่เปลี่ยนเกม:**
- **โจมตี + ซ่อนตัว ในเทิร์นเดียว** เทิร์นหน้าโจมตีจากที่ซ่อน = Advantage = Sneak Attack แน่นอน
- **โจมตี + ถอนตัว** ตีแล้วหนีโดยไม่โดนสวน
- Rogue กลายเป็นคลาสที่ **เคลื่อนที่คล่องที่สุดในเกม**

---

### เลเวล 3 — เล็งนิ่ง (Steady Aim)

> **Bonus Action:** ได้ **Advantage ในการทอยโจมตีครั้งถัดไป** ในเทิร์นนี้
> **แลกกับ: Speed = 0 จนจบเทิร์นนี้** (ต้องไม่ได้เคลื่อนที่มาก่อนในเทิร์นนี้)

**ทำไมดี:** **การันตี Sneak Attack ทุกเทิร์น** แม้จะไม่มีเพื่อนยืนติดศัตรูและไม่มีที่ซ่อน — เหมาะกับ **Rogue สายธนู** มากที่สุด

---

### เลเวล 5 — การโจมตีเจ้าเล่ห์ (Cunning Strike) กฎใหม่ 2024

> **เมื่อคุณทำ Sneak Attack** คุณสามารถ **สละเต๋า Sneak Attack บางลูก** เพื่อสร้างผลพิเศษ

| ผลพิเศษ | ต้นทุน (เต๋า) | ผล |
|---|---|---|
| **Poison** | **1d6** | เป้าหมายทอย **CON Save** — ล้มเหลว = **Poisoned 1 นาที** (ทอยใหม่ได้ทุกจบเทิร์นของมัน) • ต้องมี **Poisoner's Kit** |
| **Trip** | **1d6** | ถ้าเป้าหมาย **Large หรือเล็กกว่า** ทอย **DEX Save** ล้มเหลว = **Prone** |
| **Withdraw** | **1d6** | คุณ**เคลื่อนที่ได้ครึ่ง Speed ทันที โดยไม่โดน Opportunity Attack** |

> **DC ของ Save = 8 + DEX modifier + Proficiency Bonus**

**ทำไมดี:** เปลี่ยน "ดาเมจส่วนเกิน" เป็น "การควบคุมสนามรบ" ได้ตามสถานการณ์

> **Trip ทรงพลังที่สุด** — ทำให้ศัตรู Prone เพื่อนที่ตีระยะประชิดได้ Advantage หมด

---

### เลเวล 5 — การหลบเหนือธรรมชาติ (Uncanny Dodge)

> **Reaction:** เมื่อศัตรูที่คุณ**มองเห็น**โจมตีคุณโดน
> **ลดดาเมจจากการโจมตีนั้นลงครึ่งหนึ่ง**

**ทำไมดี:** ช่วยชีวิตได้จริง โดยเฉพาะกับ Critical Hit ที่ดาเมจสูง

---

### เลเวล 7 — การหลบหลีก (Evasion)

> **เมื่อคุณต้องทอย DEX Saving Throw** เพื่อลดดาเมจครึ่งหนึ่ง (เช่น Fireball, ลมหายใจมังกร)
>
> - **สำเร็จ รับดาเมจ 0**
> - **ล้มเหลว รับดาเมจแค่ครึ่งเดียว**

**ทำไมดี:** ทำให้ Rogue แทบไม่กลัวสเปลระเบิดพื้นที่เลย

---

### เลเวล 7 — ความสามารถที่เชื่อถือได้ (Reliable Talent)

> **เมื่อคุณทอย Ability Check โดยใช้สกิล/เครื่องมือที่มี Proficiency**
> **ถ้าทอย d20 ได้ 9 หรือน้อยกว่า นับเป็น 10**

**ทำไมนี่คือ Feature ที่ทรงพลังมาก:**

| ตัวอย่าง | ผล |
|---|---|
| Stealth +10 (Expertise) ทอยได้ 3 | **นับเป็น 10 ผลรวม 20** |
| ค่าต่ำสุดที่เป็นไปได้ | **20** (ไม่มีทางน้อยกว่านี้) |

> Rogue เลเวล 7+ ที่มี Expertise **แทบไม่มีวันล้มเหลวในสกิลที่ถนัด**

---

### เลเวล 11 — Improved Cunning Strike

> **ใช้ Cunning Strike ได้ 2 ผลพร้อมกัน** (ต้องสละเต๋าตามต้นทุนของทั้งคู่)

---

### เลเวล 14 — การโจมตีชั่วร้าย (Devious Strikes)

> Cunning Strike ได้ตัวเลือกใหม่ที่แรงขึ้น:

| ผลพิเศษ | ต้นทุน | ผล |
|---|---|---|
| **Daze** | **2d6** | เป้าหมายทอย **CON Save** — ล้มเหลว = จนถึงจบเทิร์นหน้าของมัน **ทำได้แค่ Action หรือ Bonus Action อย่างใดอย่างหนึ่ง** (ไม่ได้ทั้งคู่) และ **ใช้ Reaction ไม่ได้** |
| **Knock Out** | **6d6** | เป้าหมายทอย **CON Save** — ล้มเหลว = **Unconscious 1 นาที** (จบเมื่อโดนดาเมจหรือมีคนปลุก) |
| **Obscure** | **3d6** | เป้าหมายทอย **DEX Save** — ล้มเหลว = **Blinded จนจบเทิร์นหน้าของมัน** |

---

### เลเวล 15 — จิตลื่นไหล (Slippery Mind)

> ได้ **Proficiency ใน Wisdom Saving Throw และ Charisma Saving Throw**

**ทำไมดี:** แก้จุดอ่อนที่ใหญ่ที่สุดของ Rogue — WIS Save ที่โดน `Hold Person`, `Dominate` บ่อย

---

### เลเวล 18 — จับไม่ติด (Elusive)

> **ตราบที่คุณไม่ถูก Incapacitated**
> **ไม่มีการโจมตีใดที่ทอยใส่คุณได้ด้วย Advantage**

**ทำไมดี:** ศัตรูไม่มีทางได้ Advantage ใส่คุณเลย — ป้องกันได้ทั้งการซุ่มโจมตี, Prone, Restrained ฯลฯ

---

### เลเวล 20 — จังหวะโชคดี (Stroke of Luck) — Capstone

> **หลังจากที่คุณทอย d20 Test ล้มเหลว**
> คุณสามารถ**เปลี่ยนผลการทอยนั้นเป็น 20 (Natural 20)** ได้ทันที
>
> **ใช้ได้ 1 ครั้ง — ฟื้นเมื่อ Short Rest หรือ Long Rest**

**ทำไมดี:** **Critical Hit ตามใจสั่ง** — Rogue เลเวล 20 คริติคอลด้วย 20d6 Sneak Attack

---

## Subclasses (Roguish Archetype) — เลือกที่เลเวล 3

Rogue มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 9, 13, 17**

---

### 1. Thief — จอมโจร

> **ธีม:** โจรตัวจริง — ปีนป่าย ล้วงกระเป๋า ใช้ของวิเศษได้ทุกชนิด

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Fast Hands** | **Bonus Action:** ใช้ **Sleight of Hand** เพื่อล้วงกระเป๋า/ใช้ Thieves' Tools ปลดกับดักหรือเปิดกุญแจ • **หรือ**ใช้ **เช่นดื่มยา ใช้ของ (Utilize action)** |
| **3** | **Second-Story Work** | [แนะนำ] ได้ **Climb Speed = Speed** • และเมื่อกระโดดไกล **บวกระยะเพิ่ม = DEX modifier (ฟุต)** |
| **9** | **Supreme Sneak** | เมื่อใช้ **Cunning Strike: Withdraw** ให้ใช้ **Hide action ฟรี** ด้วย • ต้นทุน Withdraw ลดเหลือ 0 เต๋า |
| **13** | **Use Magic Device** | [แนะนำมาก] • ใช้ **Magic Item ทุกชนิดได้** แม้จะไม่ตรงเงื่อนไข (คลาส/Attunement)<br>• **Scroll:** ร่ายสเปลจาก Spell Scroll ได้ถึงระดับ 1-2 (ทอย DC 10 + ระดับสเปลถ้าสูงกว่า)<br>• **Charges:** ใช้ของที่มี Charge ทอย d6, ออก 6 = ไม่เสีย Charge<br>• **Attunement:** Attune ของวิเศษได้ **4 ชิ้น** (แทน 3) |
| **17** | **Thief's Reflexes** | **ในรอบแรกของการต่อสู้ คุณได้ 2 เทิร์น** [แนะนำมาก] (เทิร์นแรกตาม Initiative ปกติ, เทิร์นที่สองที่ Initiative − 10) |

> **แนะนำมือใหม่** — เข้าใจง่าย มีประโยชน์ทั้งในและนอกการต่อสู้

---

### 2. Assassin — นักลอบสังหาร

> **ธีม:** ฆาตกรมืออาชีพ — โจมตีเทิร์นแรกแรงมหาศาล

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Assassinate** | [แนะนำ] • **Advantage ในการทอย Initiative**<br>• **ในเทิร์นแรกของการต่อสู้:** คุณมี **Advantage** ในการโจมตีศัตรูที่ยังไม่ได้เล่นเทิร์น<br>• **ถ้าตีโดนในเทิร์นแรกนั้น เพิ่มดาเมจเท่ากับเลเวล Rogue** |
| **3** | **Assassin's Tools** | ได้ **Poisoner's Kit** และ **Disguise Kit** พร้อม Proficiency |
| **9** | **Infiltration Expertise** | ใช้เวลา 7 วัน + 25 GP **สร้างตัวตนปลอมที่สมบูรณ์แบบ** • ปลอมตัวเป็นตัวตนนั้นได้ในเวลา 1 นาที |
| **13** | **Envenom Weapons** | เมื่อใช้ **Cunning Strike: Poison** เพิ่มดาเมจ **2d6 Poison** เข้าไปด้วย |
| **17** | **Death Strike** | [แนะนำมาก] ในเทิร์นแรกของการต่อสู้ เมื่อคุณตีโดนศัตรูที่ **Surprised** มันทอย **CON Save (DC 8+DEX+Prof)** — **ล้มเหลว = ดาเมจ ×2** |

> **แรงที่สุดตอนเปิดฉาก** — แต่ถ้าการต่อสู้ยืดเยื้อจะเหลือแค่ Rogue ปกติ

---

### 3. Arcane Trickster — จอมเวทเจ้าเล่ห์

> **ธีม:** โจรที่ใช้เวทมนตร์หลอกล่อ (Third Caster — ใช้ **INT**)

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Spellcasting** | เรียนสเปลจากรายการ **เน้น **Illusion** และ **Enchantment** (Wizard)** — ใช้ **INT** |
| **3** | **Mage Hand Legerdemain** | [แนะนำ] ได้ Cantrip `Mage Hand` • มือลอย **มองไม่เห็น** • ใช้มือ **ล้วงกระเป๋า / เปิดกุญแจ / ใช้ Thieves' Tools** ระยะไกลได้ • ควบคุมด้วย **Bonus Action** |
| **9** | **Magical Ambush** | [แนะนำ] ถ้าคุณ **Invisible** ต่อเป้าหมายตอนร่ายเวทใส่มัน **มันเสียเปรียบในการทอย Saving Throw ของเวทนั้น** |
| **13** | **Versatile Trickster** | **Bonus Action:** ใช้ `Mage Hand` กวนใจศัตรูในระยะ 5 ฟุตจากมือ **คุณได้ Advantage ในการโจมตีศัตรูนั้นจนจบเทิร์น** |
| **17** | **Spell Thief** | **Reaction:** [แนะนำมาก] เมื่อศัตรูร่ายเวทใส่คุณ มันทอย **Save ตามค่าร่ายเวทของคุณ** — ล้มเหลว = **สเปลนั้นไม่มีผล และคุณขโมยสเปลนั้นมาใช้ได้ 8 ชั่วโมง** (ศัตรูใช้สเปลนั้นไม่ได้ระหว่างนั้น) — ใช้ได้ 1 ครั้ง/Long Rest |

**ตาราง Spell Slot (Third Caster):** เหมือน Eldritch Knight — [ดูตารางในไฟล์ Fighter](fighter.md#3--eldritch-knight--อัศวินเวทมนตร์)

** สเปลที่แนะนำ:**
- **Cantrip:** `Mage Hand` (ได้ฟรี), `Minor Illusion` [แนะนำ], `Booming Blade` [แนะนำ], `Prestidigitation`
- **ระดับ 1:** **`Find Familiar`** [แนะนำมาก] (Familiar ยืนติดศัตรู = ได้ Sneak Attack ตลอด!), `Shield` [แนะนำ], `Disguise Self`, `Silvery Barbs`
- **ระดับ 2:** `Invisibility` [แนะนำ], `Mirror Image`, `Misty Step`
- **ระดับ 3:** `Fly`, `Hypnotic Pattern` (ถ้ามีเข้าถึง)
- **ระดับ 4:** `Greater Invisibility` [แนะนำมาก] (Advantage ตลอด = Sneak Attack ทุกเทิร์น)

> **`Find Familiar` คือคอมโบเด็ดของ Arcane Trickster** — ส่ง Familiar ไปยืนติดศัตรู แล้วคุณได้เงื่อนไข Sneak Attack ทุกเทิร์นโดยไม่ต้องพึ่งเพื่อน

---

### 4. Soulknife — ดาบวิญญาณ

> **ธีม:** Rogue พลังจิต — สร้างมีดพลังจิตและอ่านใจคน

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Psionic Power** | ได้ **จำนวน = 2× Prof Bonus (Psionic Energy Dice)**:<br>• **Psi-Bolstered Knack** — เมื่อทอย Ability Check ที่มี Proficiency **ล้มเหลว** บวก 1 เต๋าเข้าไป (ถ้ายังล้มเหลว ไม่เสียเต๋า)<br>• **Psychic Whispers** — สื่อสารทางจิตกับสิ่งมีชีวิตได้ (ฟรี 1 ครั้ง/Long Rest) |
| **3** | **Psychic Blades** | [แนะนำ] สร้าง **มีดพลังจิต** ด้วย Magic action:<br>• เป็นอาวุธ **Simple Melee, Finesse, Thrown (60/120)** ทำ **1d6 Psychic**<br>• **หลังโจมตีด้วย Psychic Blade ใช้ Bonus Action สร้างอีกเล่มโจมตีซ้ำ** (ดาเมจ 1d4 + Ability modifier)<br>• **ไม่ต้องพกอาวุธ ไม่มีวันถูกปลดอาวุธ** |
| **9** | **Soul Blades** | • **Homing Strikes** — เมื่อโจมตีด้วย Psychic Blade **พลาด** ใช้ 1 เต๋าบวกเข้าไปในการทอย (ถ้ายังพลาด ไม่เสียเต๋า)<br>• **Psychic Teleportation** — **Bonus Action:** ขว้างมีดแล้ว **วาร์ปไปที่นั่น** (ระยะ = 1 เต๋า × 10 ฟุต) |
| **13** | **Psychic Veil** | **Magic action:** กลายเป็น **Invisible 1 ชั่วโมง** (จบเมื่อโจมตีหรือทำให้ศัตรูทอย Save) — ฟรี 1 ครั้ง/Long Rest หรือใช้ 1 เต๋า |
| **17** | **Rend Mind** | [แนะนำมาก] เมื่อทำ Sneak Attack ด้วย Psychic Blade ใช้ **3 เต๋า** ให้เป้าหมายทอย **WIS Save** — ล้มเหลว = **Stunned 1 นาที** (ทอยใหม่ได้ทุกจบเทิร์นของมัน) |

**Psionic Energy Dice ตามเลเวล:** เลเวล 3 = d6, เลเวล 5 = d8, เลเวล 11 = d10, เลเวล 17 = d12
**ฟื้น:** 1 เต๋าเมื่อ **1 ครั้ง/Long Rest (Bonus Action)** หรือทั้งหมดเมื่อ **Long Rest**

> **สายที่ทนที่สุดในระยะยาว** — ไม่ต้องพึ่งอาวุธ ไม่ต้องพึ่งสภาพแวดล้อม

---

## เปรียบเทียบ 4 Subclass

| | **Thief** | **Assassin** | **Arcane Trickster** | **Soulknife** |
|---|---|---|---|---|
| **จุดเด่น** | ยืดหยุ่น ใช้ของวิเศษ | เปิดฉากแรงมาก | มีเวทหลอกล่อ | ไม่พึ่งอุปกรณ์ |
| **ความยาก** | ง่าย | ง่าย | ยาก (จำเวท) | กลาง |
| **ค่าพลังที่ต้องมี** | DEX, CON | DEX, CON | + **INT 14+** | DEX, CON |
| **นอกการต่อสู้** | **สูงมาก** | สูง (ปลอมตัว) | **สูงมาก** | กลาง |
| **แนะนำมือใหม่** | **ใช่** | ใช่ | ไม่ | ใช่ |

---

## คำแนะนำการสร้าง Rogue

### ค่าพลังที่ควรจัด

```
DEX สูงสุดเสมอ (17 ตั้งแต่เลเวล 1 ดันถึง 20)
CON สูงรอง (14) — HP น้อยและอยู่ใกล้ศัตรู
WIS ปานกลาง (12-14) — WIS Save เป็นจุดอ่อน
INT สูงถ้าเล่น Arcane Trickster (14+)
CHA ถ้าเป็นหน้ากลุ่ม
STR ต่ำได้
```

### Species ที่แนะนำ
| Species | เหตุผล |
|---|---|
| **Halfling** [แนะนำมาก] | **ซ่อนหลังเพื่อน = Sneak Attack ทุกเทิร์น (Naturally Stealthy)** + **Luck** |
| **Elf (Wood)** [แนะนำ] | Speed 35 + `Pass Without Trace` + Perception |
| **Elf (Drow)** [แนะนำ] | Darkvision 120 ft + `Faerie Fire` (ให้ Advantage ทั้งทีม) |
| **Gnome** | Advantage ใน INT/WIS/CHA Save + Small ซ่อนง่าย |
| **Human** | Feat ฟรี (`Alert` = ไปก่อนศัตรู) |
| **Orc / Dwarf** | Darkvision 120 ft |

### Background ที่แนะนำ
**DEX/CON/INT — ได้ `Alert` (Criminal)** [แนะนำมาก] • **DEX/WIS/CHA — ได้ `Lucky` (Wayfarer)** • **Charlatan** (DEX/CON/CHA)

### Feat ที่แนะนำ (เลเวล 4+)
| Feat | ทำไม |
|---|---|
| **Ability Score Improvement (DEX)** [แนะนำ] | ดัน DEX ถึง 20 ก่อนอย่างอื่น |
| **Alert** [แนะนำ] | ไปก่อนศัตรู = Sneak Attack ก่อน |
| **Skulker** [แนะนำ] | ซ่อนตัวเก่งขึ้น + ไม่เปิดเผยตำแหน่งเมื่อยิงพลาด |
| **Piercer** | ทอยเต๋าดาเมจ Piercing ใหม่ได้ 1 ลูก |
| **Resilient (Wisdom)** | แก้จุดอ่อน WIS Save |
| **Crossbow Expert** | ใช้ Hand Crossbow ในระยะประชิดได้ไม่เสียเปรียบ |
| **Mobile** | Speed +10 + ไม่โดน Opportunity Attack จากคนที่เราตี |

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

| ผิด | ถูก |
|---|---|
| ใช้ Greatsword/Longsword | **ต้องเป็นอาวุธ Finesse หรือ Ranged** ไม่งั้นไม่ได้ Sneak Attack |
| คิดว่าต้องซ่อนตัวถึงจะ Sneak Attack ได้ | **มีเพื่อนยืนติดศัตรูก็พอ** |
| พยายาม Sneak Attack หลายครั้งต่อเทิร์น | **1 ครั้ง/เทิร์นเท่านั้น** (แต่ใช้ในเทิร์นศัตรูได้ด้วย Reaction) |
| ลืมใช้ Cunning Action ทุกเทิร์น | **Bonus Action ต้องใช้เสมอ** — Hide, Disengage, หรือ Dash |
| ยืนแนวหน้ารับดาเมจ | Rogue **HP d8 และเกราะ Light** — ตี แล้วถอย |
| ไม่เอา Expertise ใน Stealth | **Stealth คือหัวใจ** ต้องมี Expertise |

---

## สรุป Rogue ในหนึ่งบรรทัด

> **ดาเมจต่อครั้งสูงมาก (Sneak Attack) + เก่งสกิลที่สุดในเกม (Expertise + Reliable Talent) + คล่องตัวที่สุด (Cunning Action) = คลาสที่ทำได้ทุกอย่างโดยไม่ต้องจำเวท**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
