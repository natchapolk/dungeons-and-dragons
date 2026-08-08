# นักพรตหมัด (Monk)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**มองก์ / นักพรตหมัด (Monk)** คือนักสู้ที่ฝึกฝนร่างกายและจิตใจจนควบคุม **พลังภายใน (Ki)** ได้ พวกเขาต่อสู้ด้วยมือเปล่า **เร็วที่สุดในเกม** และโจมตีถี่ที่สุด โดยไม่ต้องพึ่งเกราะหรืออาวุธ

> **กฎ 2024 บัฟ Monk อย่างหนัก** — เปลี่ยนชื่อ "Ki Points" เป็น **Focus Points**, เพิ่ม **Uncanny Metabolism** ที่ฟื้น Focus ตอนเริ่มต่อสู้, และทำให้ **Stunning Strike** ไม่เสียเปล่า

---

## ข้อมูลพื้นฐาน (Class Table)

| หัวข้อ | ค่า |
|---|---|
| **Primary Ability** | **Dexterity (DEX)** และ **Wisdom (WIS)** — ต้องสูงทั้งคู่ |
| **Hit Die** | **d8** |
| **HP เลเวล 1** | **8 + CON modifier** |
| **HP เลเวลถัดไป** | **1d8 + CON** (หรือค่าคงที่ **5 + CON**) |
| **Saving Throw Proficiency** | **Strength, Dexterity** |
| **Armor Proficiency** | **ไม่มี** (ใส่เกราะแล้วเสีย Feature เกือบทั้งหมด) |
| **Weapon Proficiency** | Simple Weapons + **Martial Weapon ที่มีคุณสมบัติ Light** |
| **Tool Proficiency** | **Artisan's Tools 1 ชนิด** หรือ **เครื่องดนตรี 1 ชนิด** |
| **Skill Proficiency** | เลือก **2** จาก: **Acrobatics, Athletics, History, Insight, Religion, Stealth** |
| **Subclass** | เลือกที่ **เลเวล 3** |

### อุปกรณ์เริ่มต้น

**เลือก A:** Spear, ×5 Dart, Artisan's Tools หรือ Musical Instrument, Explorer's Pack, **11 GP**
**เลือก B:** **50 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

| เลเวล | Prof<br>Bonus | Features (ความสามารถ) | Martial<br>Arts Die | Focus<br>Points | Unarmored<br>Movement |
|---|---|---|---|---|---|
| **1** | +2 | **Martial Arts**, **Unarmored Defense** | **d6** | — | — |
| **2** | +2 | **Monk's Focus** [แนะนำ], **Unarmored Movement**, **Uncanny Metabolism** | d6 | **2** | **+10 ft** |
| **3** | +2 | **Monk Subclass** [แนะนำ], **Deflect Attacks** | d6 | 3 | +10 ft |
| **4** | +2 | **ASI**, **Slow Fall** | d6 | 4 | +10 ft |
| **5** | **+3** | **Extra Attack** [แนะนำมาก], **Stunning Strike** | **d8** | 5 | +10 ft |
| **6** | +3 | **Empowered Strikes**, **Subclass Feature** | d8 | 6 | **+15 ft** |
| **7** | +3 | **Evasion** | d8 | 7 | +15 ft |
| **8** | +3 | **ASI** | d8 | 8 | +15 ft |
| **9** | **+4** | **Acrobatic Movement** | d8 | 9 | +15 ft |
| **10** | +4 | **Heightened Focus**, **Self-Restoration** | d8 | 10 | **+20 ft** |
| **11** | +4 | **Subclass Feature** | **d10** | 11 | +20 ft |
| **12** | +4 | **ASI** | d10 | 12 | +20 ft |
| **13** | **+5** | **Deflect Energy** | d10 | 13 | +20 ft |
| **14** | +5 | **Disciplined Survivor** | d10 | 14 | **+25 ft** |
| **15** | +5 | **Perfect Focus** | d10 | 15 | +25 ft |
| **16** | +5 | **ASI** | d10 | 16 | +25 ft |
| **17** | **+6** | **Subclass Feature** | **d12** | 17 | +25 ft |
| **18** | +6 | **Superior Defense** | d12 | 18 | **+30 ft** |
| **19** | +6 | **Epic Boon Feat** | d12 | 19 | +30 ft |
| **20** | +6 | **Body and Mind** | d12 | 20 | +30 ft |

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 — ศิลปะการต่อสู้ (Martial Arts) ความสามารถหลักของคลาส

> ตราบที่คุณ **ไม่ใส่เกราะและไม่ถือโล่** คุณได้ประโยชน์เหล่านี้:
>
> | ผล | รายละเอียด |
> |---|---|
> | **Bonus Unarmed Strike** [แนะนำ] | เมื่อใช้ **Attack action** คุณสามารถโจมตีมือเปล่า **1 ครั้งเพิ่มด้วย Bonus Action** |
> | **Martial Arts Die** [แนะนำ] | **Unarmed Strike ทำดาเมจ = Martial Arts Die** (d6 d12 ตามเลเวล) แทนที่จะเป็น 1 |
> | **Dexterous Attacks** [แนะนำ] | ใช้ **DEX แทน STR** ในการทอยโจมตีและดาเมจของ **Unarmed Strike และ Monk Weapons** • และใช้ **DEX แทน STR** ในการคำนวณ **DC ของ Grapple/Shove** |

### อาวุธของ Monk (Monk Weapons)

**อาวุธที่นับเป็น Monk Weapon:**
- **Simple Melee Weapons ทั้งหมด** (Club, Dagger, Handaxe, Javelin, Light Hammer, Mace, Quarterstaff [แนะนำ], Sickle, Spear)
- **Martial Melee Weapons ที่มีคุณสมบัติ Light** (Scimitar, Shortsword [แนะนำ])
- ไม่นับ: อาวุธที่มีคุณสมบัติ **Heavy** หรือ **Two-Handed**

> **ถ้าใช้อาวุธ Monk Weapon ดาเมจใช้เต๋าที่มากกว่าระหว่างเต๋าอาวุธกับ Martial Arts Die**
> เช่น เลเวล 1 ใช้ **1d6 หรือ 1d8 สองมือ (Quarterstaff)** vs Martial Arts d6 ใช้ **1d8** ดีกว่า

> **แนะนำ: Quarterstaff** ถือสองมือได้ 1d8 + Mastery **ล้มศัตรู (Topple)** — และยังต่อยมือเปล่าเป็น Bonus Action ได้

---

### เลเวล 1 — การป้องกันไร้เกราะ (Unarmored Defense)

> **ตอนไม่ใส่เกราะและไม่ถือโล่: AC = 10 + DEX modifier + WIS modifier**

| ค่าพลัง | AC |
|---|---|
| DEX 16 (+3), WIS 14 (+2) | **15** |
| DEX 18 (+4), WIS 16 (+3) | **17** |
| DEX 20 (+5), WIS 20 (+5) | **20** |

---

### เลเวล 2 — สมาธินักพรต (Monk's Focus)

> คุณมี **Focus Points เท่ากับเลเวล Monk** — **ฟื้นทั้งหมดเมื่อ Short Rest หรือ Long Rest**
>
> ใช้ทำ 3 อย่างพื้นฐาน (Subclass จะให้ตัวเลือกเพิ่ม):

| ท่า | ต้นทุน | ผล |
|---|---|---|
| **Flurry of Blows** | **1 Focus** | **Bonus Action:** โจมตีมือเปล่า **2 ครั้ง** (แทน 1 ครั้ง) — เพิ่มเป็น **3 ครั้ง** ที่เลเวล 10 |
| **Patient Defense** | **ฟรี (Disengage)** หรือ **1 Focus (Disengage + Dodge)** | **Bonus Action:** ใช้ **Disengage** ฟรี • หรือใช้ 1 Focus เพื่อได้ทั้ง **Disengage และ Dodge** |
| **Step of the Wind** | **ฟรี (Dash)** หรือ **1 Focus (Dash + Disengage + กระโดดไกล ×2)** | **Bonus Action:** ใช้ **Dash** ฟรี • หรือใช้ 1 Focus เพื่อได้ **Dash + Disengage** และ **ระยะกระโดดเพิ่มเป็น 2 เท่า** |

> **กฎ 2024 บัฟใหญ่:** Patient Defense (Disengage) และ Step of the Wind (Dash) **ใช้ได้ฟรีโดยไม่เสีย Focus!**

---

### เลเวล 2 — การเคลื่อนที่ไร้เกราะ (Unarmored Movement)

> **Speed เพิ่มขึ้น 10 ฟุต** ตราบที่ไม่ใส่เกราะและไม่ถือโล่ (เพิ่มขึ้นตามตาราง จนถึง **+30 ฟุต** ที่เลเวล 18)

| เลเวล | Speed รวม (Species ปกติ 30 ฟุต) |
|---|---|
| 2 | **40 ฟุต** |
| 6 | **45 ฟุต** |
| 10 | **50 ฟุต** |
| 14 | **55 ฟุต** |
| 18 | **60 ฟุต** |

---

### เลเวล 2 — การเผาผลาญเหนือธรรมชาติ (Uncanny Metabolism) กฎใหม่ 2024

> **เมื่อคุณทอย Initiative** คุณสามารถ:
> - **ฟื้น Focus Points ทั้งหมด**
> - **และฟื้น HP เท่ากับ `1 Martial Arts Die + เลเวล Monk`**
>
> **ใช้ได้ 1 ครั้งต่อ Long Rest**

**ทำไมนี่คือการบัฟที่สำคัญที่สุดของกฎ 2024:** Monk ไม่ต้องกลัว Focus หมดกลางวันอีกต่อไป — เริ่มการต่อสู้สำคัญด้วยพลังเต็ม

---

### เลเวล 3 — ปัดป้องการโจมตี (Deflect Attacks)

> **Reaction:** เมื่อคุณถูกโจมตีด้วย **Bludgeoning, Piercing, หรือ Slashing damage**
> **ลดดาเมจลง `1d10 + DEX modifier + เลเวล Monk`**
>
> **ถ้าลดดาเมจลงเหลือ 0:** คุณสามารถใช้ **1 Focus Point** เพื่อ **โยนพลังกลับ** — เลือกศัตรู 1 ตัวในระยะ 5 ฟุต (หรือ 60 ฟุตถ้าเป็นการโจมตีระยะไกล) มันทอย **DEX Save (DC 8+DEX+Prof)** — **ล้มเหลว = รับ 2 Martial Arts Die + DEX modifier** เป็นดาเมจ Force

> **กฎ 2024 ขยายจาก "Deflect Missiles" (แค่ระยะไกล) เป็นทุกการโจมตีกายภาพ** — เป็นการบัฟที่ทรงพลังมาก

---

### เลเวล 4 — ตกช้า (Slow Fall)

> **Reaction:** เมื่อคุณกำลังตก **ลดดาเมจจากการตกลง `5 × เลเวล Monk`**

---

### เลเวล 5 — Extra Attack

> **เมื่อใช้ Attack action คุณโจมตีได้ 2 ครั้ง**

**ผลรวมการโจมตีต่อเทิร์นที่เลเวล 5:**
```
Attack action: ต่อย 2 ครั้ง (d8 + DEX แต่ละครั้ง)
+ Flurry of Blows (Bonus Action, 1 Focus): ต่อยอีก 2 ครั้ง
= โจมตี 4 ครั้งต่อเทิร์น!
```

---

### เลเวล 5 — การโจมตีที่ทำให้มึนงง (Stunning Strike)

> **1 ครั้งต่อเทิร์น** เมื่อคุณตีโดนด้วย **Monk Weapon หรือ Unarmed Strike**
> คุณสามารถใช้ **1 Focus Point** ให้เป้าหมายทอย **Constitution Saving Throw**
> **DC = 8 + WIS modifier + Proficiency Bonus**
>
> - **ล้มเหลว ติดสภาวะ Stunned จนถึงเริ่มเทิร์นหน้าของคุณ**
> - **สำเร็จ Speed ลดลงครึ่งหนึ่ง และการโจมตีครั้งถัดไปที่ตีมันได้ Advantage** (จนถึงเริ่มเทิร์นหน้าของคุณ)

> **กฎ 2024:** เพิ่ม "ผลเมื่อ Save สำเร็จ" ทำให้ Stunning Strike **ไม่เสียเปล่า** อีกต่อไป

**ทำไม Stunned ทรงพลังมาก:**
- ศัตรู **ทำอะไรไม่ได้เลย 1 เทิร์นเต็ม**
- **ล้มเหลวอัตโนมัติใน STR/DEX Save**
- **ทุกคนตีมันได้ Advantage**

> **ใช้กับบอส** — Stun บอส 1 เทิร์น = ทีมได้ตีฟรีทั้งรอบ

---

### เลเวล 6 — หมัดเสริมพลัง (Empowered Strikes)

> **Unarmed Strike ของคุณสามารถเปลี่ยนดาเมจเป็น Force** ได้ (แทน Bludgeoning)

**ทำไมดี:** **Force เป็นดาเมจที่มอนสเตอร์ต้านทานน้อยที่สุดในเกม** — Monk ไม่ต้องกลัวศัตรูที่มี Resistance ต่อการโจมตีกายภาพ

---

### เลเวล 7 — Evasion

> เมื่อทอย **DEX Save** เพื่อลดดาเมจครึ่ง: **สำเร็จ = 0 ดาเมจ, ล้มเหลว = ครึ่งเดียว**

---

### เลเวล 9 — การเคลื่อนที่แบบกายกรรม (Acrobatic Movement)

> ตราบที่ไม่ใส่เกราะและไม่ถือโล่ คุณสามารถ:
> - **เดินบนพื้นผิวแนวตั้ง** (กำแพง) และ **บนของเหลว** ในเทิร์นของคุณ โดยไม่ตก

---

### เลเวล 10 — สมาธิขั้นสูง (Heightened Focus)

> อัปเกรดท่าพื้นฐาน 3 ท่า:
>
> | ท่า | อัปเกรด |
> |---|---|
> | **Flurry of Blows** | โจมตี **3 ครั้ง** (แทน 2) |
> | **Patient Defense** | เมื่อใช้ 1 Focus ได้ **Temp HP = 2 Martial Arts Die** เพิ่มด้วย |
> | **Step of the Wind** | เมื่อใช้ 1 Focus **พาเพื่อนที่ยินยอมขนาด Large หรือเล็กกว่าไปด้วยได้** |

---

### เลเวล 10 — การฟื้นฟูตนเอง (Self-Restoration)

> - **เมื่อจบเทิร์นของคุณ ลบสภาวะ Charmed, Frightened, หรือ Poisoned ออกจากตัวเองได้ 1 อย่าง**
> - **คุณไม่ต้องกินอาหารหรือน้ำอีกต่อไป** (ยังกินได้ตามปกติ)

---

### เลเวล 13 — ปัดป้องพลังงาน (Deflect Energy)

> **Deflect Attacks ใช้ได้กับดาเมจทุกประเภท** (ไม่ใช่แค่กายภาพ) — รวมถึงไฟ สายฟ้า เย็น ฯลฯ

---

### เลเวล 14 — ผู้รอดชีวิตที่มีวินัย (Disciplined Survivor)

> - ได้ **Proficiency ใน Saving Throw ทุกประเภท**
> - **เมื่อทอย Saving Throw ล้มเหลว ใช้ 1 Focus Point เพื่อทอยใหม่** (ต้องใช้ผลใหม่)

---

### เลเวล 15 — สมาธิสมบูรณ์ (Perfect Focus)

> **เมื่อทอย Initiative และมี Focus Points เหลือไม่ถึง 4** (และไม่ได้ใช้ Uncanny Metabolism)
> **ฟื้น Focus Points ให้เป็น 4 ทันที**

---

### เลเวล 18 — การป้องกันขั้นสูงสุด (Superior Defense)

> **เมื่อเริ่มเทิร์นของคุณ** คุณสามารถใช้ **3 Focus Points** เพื่อได้:
> **Resistance ต่อดาเมจทุกประเภทยกเว้น Force** เป็นเวลา **1 นาที** (หรือจนกว่าคุณจะ Incapacitated)

---

### เลเวล 20 — กายและใจ (Body and Mind) — Capstone

> - **DEX และ WIS เพิ่มขึ้นอย่างละ 4**
> - **เพดานสูงสุดของทั้งสองค่ากลายเป็น 25**

**ผลลัพธ์:** DEX 25 (+7), WIS 25 (+7) **AC 24** โดยไม่ใส่เกราะ + Stunning Strike DC 21

---

## Subclasses (Monk Subclass) — เลือกที่เลเวล 3

Monk มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 6, 11, 17**

---

### 1. Warrior of the Open Hand — นักรบฝ่ามือเปิด

> **ธีม:** ศิลปะการต่อสู้บริสุทธิ์ — **แรงที่สุดและง่ายที่สุด**

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Open Hand Technique** | [แนะนำ] เมื่อตีโดนด้วย **Flurry of Blows** เลือกผลพิเศษ 1 อย่างต่อการตีแต่ละครั้ง:<br>• **Addle** — เป้าหมาย **ใช้ Reaction ไม่ได้** จนถึงเริ่มเทิร์นหน้าของคุณ<br>• **Push** — เป้าหมายทอย **STR Save** ล้มเหลว = **ผลักถอย 15 ฟุต**<br>• **Topple** — เป้าหมายทอย **DEX Save** ล้มเหลว = **Prone** |
| **6** | **Wholeness of Body** | **Bonus Action:** [แนะนำ] ฟื้น HP เท่ากับ **`2 Martial Arts Die + WIS modifier`** — ใช้ได้ **Prof Bonus ครั้ง/Long Rest** |
| **11** | **Fleet Step** | **เมื่อคุณใช้ Bonus Action ที่ไม่ใช่ Step of the Wind คุณได้ผลของ Step of the Wind ฟรีด้วย** |
| **17** | **Quivering Palm** | **ฝ่ามือสั่นสะเทือน** [แนะนำมาก] — ใช้ **4 Focus Points** เมื่อตีโดนด้วย Unarmed Strike ฝังการสั่นสะเทือนไว้ **23 วัน**<br>**Action ในภายหลัง:** สั่นสะเทือนทำงาน เป้าหมายทอย **CON Save** — **ล้มเหลว = ลดเหลือ 0 HP ทันที** • **สำเร็จ = รับ 10d12 Force damage** |

> **แนะนำมือใหม่ที่สุด** — Topple ทุกครั้งที่ Flurry of Blows = ล้มศัตรูให้ทีมได้ Advantage

---

### 2. Warrior of Shadow — นักรบเงามืด

> **ธีม:** Monk ผู้ควบคุมเงามืด — สายลอบเร้นและวาร์ป

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Shadow Arts** | • ได้ Cantrip **`Minor Illusion`** (ใช้ WIS)<br>• **หรือ +60 ถ้ามีอยู่แล้ว (Darkvision 60 ft)**<br>• **1 Focus:** [แนะนำ] ร่ายสเปล **`Darkness`** — และ **คุณมองเห็นผ่าน Darkness ของตัวเองได้** และเคลื่อนย้ายพื้นที่มืดได้ **30 ฟุต** เป็น Bonus Action |
| **6** | **Shadow Step** | **Bonus Action:** [แนะนำ] ถ้าคุณอยู่ใน **Dim Light หรือ Darkness** **วาร์ปได้ 60 ฟุต** ไปยังที่ที่มืดเหมือนกัน • **การโจมตี Melee ครั้งถัดไปได้ Advantage** |
| **11** | **Improved Shadow Step** | **Shadow Step ใช้ได้แม้อยู่ในที่สว่าง** • เมื่อวาร์ป **ใช้ Unarmed Strike ฟรี 1 ครั้งทันที** |
| **17** | **Cloak of Shadows** | **Magic action + 3 Focus:** [แนะนำมาก] กลายเป็น **Invisible 1 นาที** • ระหว่างนั้น **คุณยังคง Invisible แม้จะโจมตีหรือร่ายเวท** และได้ **Resistance ต่อทุกดาเมจยกเว้น Force และ Psychic** |

> **สายลอบเร้นที่ดีที่สุด** — วาร์ปได้ทุกเทิร์น + Advantage ฟรี

---

### 3. Warrior of the Elements — นักรบธาตุ

> **ธีม:** ควบคุมธาตุทั้ง 4 — เพิ่มระยะการโจมตีและทำดาเมจธาตุ

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Elemental Attunement** | **Bonus Action + 1 Focus:** [แนะนำ] เข้าโหมดธาตุ **10 นาที**<br>ระหว่างนั้น:<br>• **Reach ของ Unarmed Strike +10 ฟุต** [แนะนำ]<br>• **เปลี่ยนดาเมจ Unarmed Strike เป็น Acid, Cold, Fire, Lightning, หรือ Thunder ได้**<br>• เมื่อตีโดน **ผลักหรือดึงเป้าหมาย 10 ฟุต** ได้ (1 ครั้ง/เทิร์น) |
| **6** | **Elemental Burst** | **Magic action + 2 Focus:** เลือกจุดในระยะ 120 ฟุต **ทรงกลมรัศมี 20 ฟุต** — สิ่งมีชีวิตในนั้นทอย **DEX Save** — ล้มเหลว = **`2 Martial Arts Die` ดาเมจธาตุ** (สำเร็จ = ครึ่ง) |
| **11** | **Stride of the Elements** | ระหว่าง Elemental Attunement คุณได้ **Fly Speed และ Swim Speed = Speed** [แนะนำ] |
| **17** | **Elemental Epitome** | ระหว่าง Elemental Attunement คุณได้เพิ่ม:<br>• **Resistance ต่อธาตุที่เลือก** (เปลี่ยนได้ตอนเริ่มเทิร์น)<br>• **Speed +20 ฟุต**<br>• **1 ครั้ง/เทิร์น เมื่อตีโดนด้วย Unarmed Strike เพิ่ม `1 Martial Arts Die` ดาเมจธาตุ** |

> **Reach 15 ฟุตจากมือเปล่า** เป็นสิ่งที่ไม่มีคลาสไหนทำได้ — ตีศัตรูโดยที่มันตีเราไม่ถึง

---

### 4. Warrior of Mercy — นักรบเมตตา

> **ธีม:** ผู้รักษาและผู้ปลิดชีพ — Monk ที่รักษาเพื่อนได้

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Hand of Harm** | **1 ครั้ง/เทิร์น + 1 Focus:** เมื่อตีโดนด้วย Unarmed Strike เพิ่มดาเมจ **`1 Martial Arts Die + WIS modifier`** เป็น **Necrotic** |
| **3** | **Hand of Healing** | **Magic action + 1 Focus:** [แนะนำ] สัมผัสสิ่งมีชีวิตในระยะ 5 ฟุต ฟื้น **`1 Martial Arts Die + WIS modifier`** HP<br>**หรือ:** เมื่อใช้ **Flurry of Blows** สละการตี 1 ครั้งเพื่อรักษาแทน (ไม่เสีย Focus เพิ่ม) |
| **3** | **Implements of Mercy** | ได้ Proficiency ใน **Insight, Medicine** และ **Herbalism Kit** |
| **6** | **Physician's Touch** | • **Hand of Healing** ลบสภาวะ **Blinded, Deafened, Paralyzed, Poisoned, หรือ Stunned** ได้ 1 อย่างด้วย<br>• **Hand of Harm** ทำให้เป้าหมาย **Poisoned จนจบเทิร์นหน้าของคุณ** |
| **11** | **Flurry of Healing and Harm** | [แนะนำ] เมื่อใช้ **Flurry of Blows** **ใช้ Hand of Healing ได้โดยไม่เสีย Focus** (แทนการตีแต่ละครั้ง) และ **Hand of Harm ไม่เสีย Focus** (1 ครั้ง/เทิร์น) |
| **17** | **Hand of Ultimate Mercy** | **Action + 5 Focus:** [แนะนำมาก] สัมผัสศพที่ตายไม่เกิน 24 ชั่วโมง **ชุบชีวิตด้วย HP = `4 Martial Arts Die + WIS modifier`** และลบสภาวะทั้งหมด — ใช้ได้ 1 ครั้ง/Long Rest |

> **Monk ที่รักษาเพื่อนได้** — ทีมที่ไม่มี Cleric ได้ประโยชน์มาก

---

## เปรียบเทียบ 4 Subclass

| | **Open Hand** | **Shadow** | **Elements** | **Mercy** |
|---|---|---|---|---|
| **จุดเด่น** | ดาเมจ + ควบคุม | ลอบเร้น + วาร์ป | ระยะเอื้อม 15 ฟุต | รักษาเพื่อน |
| **ความยาก** | ง่ายสุด | กลาง | กลาง | กลาง |
| **ใช้ Focus** | น้อย | ปานกลาง | **มาก** | มาก |
| **ช่วยทีม** | กลาง | ต่ำ | กลาง | **สูงสุด** |
| **แนะนำมือใหม่** | **ใช่** | ใช่ | ไม่ (เปลือง Focus) | ใช่ |

---

## คำแนะนำการสร้าง Monk

### ค่าพลังที่ควรจัด

```
DEX สูงสุด (17 ตั้งแต่เลเวล 1 20)
WIS สูงรอง (14-16 20) กระทบทั้ง AC และ Stunning Strike DC
CON ปานกลาง (14)
STR / INT / CHA ต่ำได้
```

> **Monk เป็นคลาสที่ "MAD" (Multiple Ability Dependent)** — ต้องดัน 3 ค่า (DEX, WIS, CON) ทำให้เลเวลต่ำอ่อนกว่าคลาสอื่น แต่เลเวลสูงแรงมาก

### Species ที่แนะนำ
| Species | เหตุผล |
|---|---|
| **Elf (Wood)** [แนะนำมาก] | Speed 35 รวม Unarmored Movement = **65 ฟุตที่เลเวล 18** |
| **Human** [แนะนำ] | Feat ฟรี (`Tough` แก้ปัญหา HP น้อย) |
| **Goliath** [แนะนำ] | Speed 35 + Powerful Build (Grapple เก่ง) |
| **Halfling** | Luck + ซ่อนตัวเก่ง + ไม่มีปัญหาเรื่องอาวุธ Heavy |
| **Orc** | Adrenaline Rush (Dash ฟรี + Temp HP) |

### Background ที่แนะนำ
**Sailor** (STR/DEX/WIS) [แนะนำมาก] • **Wayfarer** (DEX/WIS/CHA) • **Guide** (DEX/CON/WIS) [แนะนำ]

### Feat ที่แนะนำ (เลเวล 4+)
| Feat | ทำไม |
|---|---|
| **Ability Score Improvement (DEX)** [แนะนำ] | ดัน DEX ถึง 20 ก่อน |
| **Ability Score Improvement (WIS)** [แนะนำ] | แล้วดัน WIS (AC + Stunning Strike DC) |
| **Tough** | แก้ปัญหา HP น้อย (d8 แต่ยืนแนวหน้า) |
| **Mobile** [แนะนำ] | Speed +10 + ไม่โดน Opportunity Attack |
| **Alert** | ไปก่อน = Stunning Strike ก่อน |
| **Grappler** | สายจับล็อกศัตรู (Monk ใช้ DEX ใน Grapple DC ได้!) |

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

| ผิด | ถูก |
|---|---|
| ใส่เกราะหรือถือโล่ | **เสีย Martial Arts, Unarmored Defense และ Unarmored Movement ทั้งหมด** |
| ใช้ Greatsword/Longbow | **ต้องเป็น Monk Weapon** (Simple Melee หรือ Martial Light) |
| ดัน WIS ต่ำเกินไป | **WIS กระทบทั้ง AC และ Stunning Strike DC** — ต้องดัน |
| ใช้ Focus หมดในศึกแรก | มี **Uncanny Metabolism** ฟื้นได้ 1 ครั้ง/วัน — เก็บไว้ใช้ตอนบอส |
| ใช้ Stunning Strike ใส่ศัตรูตัวเล็ก | **เก็บไว้ใช้กับบอสหรือศัตรูตัวอันตราย** |
| ยืนแนวหน้าเหมือน Fighter | Monk **HP d8** — เข้าไปตี Flurry แล้วใช้ Step of the Wind ถอย |

---

## สรุป Monk ในหนึ่งบรรทัด

> **โจมตี 4-5 ครั้งต่อเทิร์น + เร็วที่สุดในเกม (60 ฟุต) + Stunning Strike ทำให้บอสหยุดทั้งเทิร์น = คลาสที่คล่องตัวที่สุด แต่ต้องดันถึง 3 ค่าพลัง**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
