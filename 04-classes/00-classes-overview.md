# คลาส/อาชีพ (ภาพรวมทั้ง 12 คลาส ที่เลเวล 1) (Classes)

[กลับสารบัญ](../README.md)

---

## Class คืออะไร?

**คลาส/อาชีพ (Class)** คือ **สิ่งที่กำหนดว่าตัวละครของคุณทำอะไรได้ในเกม** — เป็นการตัดสินใจที่สำคัญที่สุดตอนสร้างตัวละคร

Class กำหนด:
- **พลังชีวิตต่อเลเวล (Hit Die)**
- **Proficiency** ที่ได้ (อาวุธ เกราะ สกิล Saving Throw)
- **ความสามารถพิเศษ (Features)** ทุกเลเวลตั้งแต่ 1 ถึง 20
- **ใช้เวทได้หรือไม่** และใช้ค่า Ability ตัวไหน
- **สายย่อย (Subclass)** ที่เลือกได้ตอนเลเวล 3

> **กฎ 2024: ทุกคลาสเลือก Subclass ที่ "เลเวล 3" เหมือนกันหมด** (เมื่อก่อนแต่ละคลาสต่างกัน)

---

## ตารางเปรียบเทียบทั้ง 12 คลาส ที่เลเวล 1

| Class | Hit Die | HP Lv.1 | ค่าหลัก | Save ที่ถนัด | เกราะ | ใช้เวท? | ความยาก |
|---|---|---|---|---|---|---|---|
| **[นักรบคลั่ง (Barbarian)](barbarian.md)** | **d12** | 12+CON | STR | STR, CON | Light, Medium, Shield | ไม่ | ง่าย |
| **[นักดนตรีเวท (Bard)](bard.md)** | d8 | 8+CON | CHA | DEX, CHA | Light | Full | กลาง |
| **[นักบวช (Cleric)](cleric.md)** | d8 | 8+CON | WIS | WIS, CHA | Light, Medium, Shield | Full | กลาง |
| **[ดรูอิด (Druid)](druid.md)** | d8 | 8+CON | WIS | INT, WIS | Light, Shield | Full | ยาก |
| **[นักรบ (Fighter)](fighter.md)** | **d10** | 10+CON | STR/DEX | STR, CON | **ทุกชนิด + Shield** | ไม่ | ง่ายที่สุด |
| **[นักพรตหมัด (Monk)](monk.md)** | d8 | 8+CON | DEX+WIS | STR, DEX | ไม่ใส่ | ไม่ | กลาง |
| **[อัศวินศักดิ์สิทธิ์ (Paladin)](paladin.md)** | **d10** | 10+CON | STR+CHA | WIS, CHA | **ทุกชนิด + Shield** | Half | กลาง |
| **[พรานป่า (Ranger)](ranger.md)** | **d10** | 10+CON | DEX+WIS | STR, DEX | Light, Medium, Shield | Half | กลาง |
| **[โจร/นักลอบสังหาร (Rogue)](rogue.md)** | d8 | 8+CON | DEX | DEX, INT | Light | ไม่ | ง่าย |
| **[จอมเวทสายเลือด (Sorcerer)](sorcerer.md)** | **d6** | 6+CON | CHA | CON, CHA | ไม่ | Full | กลาง |
| **[ผู้ทำสัญญา (Warlock)](warlock.md)** | d8 | 8+CON | CHA | WIS, CHA | Light | Pact | กลาง |
| **[พ่อมด (Wizard)](wizard.md)** | **d6** | 6+CON | INT | INT, WIS | ไม่ | Full | ยาก |

---

## บทบาทในทีม (Party Roles)

ทีมที่ดีควรมีบทบาทเหล่านี้ครบ (คนหนึ่งทำได้หลายบทบาท)

| บทบาท | ทำหน้าที่ | คลาสที่ทำได้ดี |
|---|---|---|
| **แนวหน้า (Tank / Frontline)** | ยืนรับดาเมจ ปกป้องคนอื่น | **Barbarian**, **Fighter**, **Paladin** |
| **ตัวทำดาเมจ (Damage Dealer (DPS))** | สร้างความเสียหายสูงสุด | **Rogue**, **Fighter**, **Barbarian**, **Sorcerer**, **Warlock** |
| **ผู้รักษา/สนับสนุน (Healer / Support)** | ฟื้น HP แก้สภาวะ บัฟทีม | **Cleric**, **Bard**, **Druid**, **Paladin** |
| **ผู้ควบคุมสนามรบ (Controller)** | จำกัดการเคลื่อนที่ ทำให้ศัตรูไร้ประสิทธิภาพ | **Wizard**, **Druid**, **Bard**, **Sorcerer** |
| **สายสกิล/หน่วยสอดแนม (Skill Monkey / Scout)** | ซ่อนตัว หากับดัก เจรจา | **Rogue**, **Bard**, **Ranger** |

> **ทีม 4 คนที่สมดุลที่สุด:** Fighter/Barbarian (แนวหน้า) + Cleric (รักษา) + Rogue (สกิล+ดาเมจ) + Wizard (ควบคุม)
> **ไม่มี Healer จะเล่นยากมาก** — ถ้าทีมไม่มีใครรักษาได้ ควรมีคนเอา Feat `Healer` และซื้อ Healing Potion เยอะ ๆ

---
---

# รายละเอียดแต่ละคลาส ที่เลเวล 1

---

## Barbarian — นักรบคลั่ง

> **นักรบผู้ปลดปล่อยความโกรธเป็นพลัง** ทนที่สุดในเกม เข้าโหมด **Rage** แล้วแทบตายยาก

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | **d12** (สูงสุดในเกม) |
| **HP เลเวล 1** | **12 + CON modifier** |
| **ค่าหลัก** | **ค่ารอง: CON (STR)** |
| **Saving Throw Proficiency** | **STR, CON** |
| **Armor** | Light, Medium, **Shield** |
| **Weapons** | Simple, **Martial** |
| **Skills** | เลือก **2** จาก: Animal Handling, Athletics, Intimidation, Nature, Perception, Survival |
| **Weapon Mastery** | **2 ชนิด** |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Rage** [แนะนำ] | **Bonus Action:** เข้าโหมดคลั่ง — **Resistance ต่อ Bludgeoning/Piercing/Slashing**, **+2 ดาเมจ STR**, **Advantage ใน STR Check และ STR Save** — ใช้ได้ **2 ครั้ง/Long Rest** |
| **Unarmored Defense** | ตอนไม่ใส่เกราะ: **AC = 10 + DEX + CON** (ใส่โล่ได้) |
| **Weapon Mastery** | ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด |

### อุปกรณ์เริ่มต้น
**Greataxe, ×4 Handaxe, Explorer's Pack, 15 GP** — หรือ **75 GP**

** [อ่านรายละเอียดเต็ม เลเวล 1-20](barbarian.md)**

---

## Bard — นักดนตรีเวท

> **นักแสดงผู้ร่ายเวทด้วยเสียงเพลง** เก่งรอบด้านที่สุดในเกม — รักษาได้ ควบคุมได้ เจรจาเก่ง

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | d8 |
| **HP เลเวล 1** | **8 + CON modifier** |
| **ค่าหลัก** | **CHA** |
| **Saving Throw Proficiency** | **DEX, CHA** |
| **Armor** | Light |
| **Weapons** | Simple |
| **Tools** | **เครื่องดนตรี 3 ชนิด** |
| **Skills** | เลือก **3 อย่างจากสกิลทั้งหมด** (อิสระที่สุดในเกม) |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Bardic Inspiration** [แนะนำ] | **Bonus Action:** ให้เพื่อนในระยะ 60 ฟุต ได้ **d6** — เพื่อนเอาไปบวกใน **d20 Test 1 ครั้ง** (ใช้หลังทอยแต่ก่อนรู้ผล) — ใช้ได้ **เท่ากับ CHA modifier/Long Rest** |
| **Spellcasting** | **Cantrip 2 อัน** + **สเปลระดับ 1 เตรียมได้ 4 อัน** + **Spell Slot ระดับ 1 ×2** |

### อุปกรณ์เริ่มต้น
**Leather Armor, Dagger, Musical Instrument, Entertainer's Pack, 19 GP** — หรือ **90 GP**

** [อ่านรายละเอียดเต็ม + รายการเวท](bard.md)**

---

## Cleric — นักบวช

> **ผู้รับใช้เทพเจ้า** ผู้รักษาที่ดีที่สุด แต่ก็สู้ได้ด้วย ทีมแทบทุกทีมอยากได้

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | d8 |
| **HP เลเวล 1** | **8 + CON modifier** |
| **ค่าหลัก** | **WIS** |
| **Saving Throw Proficiency** | **WIS, CHA** |
| **Armor** | Light, Medium, **Shield** |
| **Weapons** | Simple |
| **Skills** | เลือก **2** จาก: History, Insight, Medicine, Persuasion, Religion |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Spellcasting** | **Cantrip 3 อัน** + **เตรียมสเปลระดับ 1 ได้ 4 อัน** (เลือกจากรายการ Cleric ทั้งหมด เปลี่ยนได้ทุก Long Rest) + **Spell Slot ระดับ 1 ×2** |
| **Divine Order** [แนะนำ] | เลือก 1 แบบ:<br>• **Protector** — ได้ Proficiency **สายยืนหน้า (Martial Weapon + Heavy Armor)**<br>• **Thaumaturge** — ได้ **Cantrip เพิ่ม 1 อัน** และ **+WIS modifier ใน Religion/Arcana Check** (สายเวท) |

### อุปกรณ์เริ่มต้น
**Chain Shirt, Shield, Mace, Holy Symbol, Priest's Pack, 7 GP** — หรือ **110 GP**

** [อ่านรายละเอียดเต็ม + รายการเวท](cleric.md)**

---

## Druid — ดรูอิด

> **ผู้พิทักษ์ธรรมชาติ** แปลงร่างเป็นสัตว์ได้ (Wild Shape) และมีเวทควบคุมสนามรบที่ทรงพลัง

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | d8 |
| **HP เลเวล 1** | **8 + CON modifier** |
| **ค่าหลัก** | **WIS** |
| **Saving Throw Proficiency** | **INT, WIS** |
| **Armor** | Light, **Shield** |
| **Weapons** | Simple |
| **Tools** | Herbalism Kit |
| **Skills** | เลือก **2** จาก: Arcana, Animal Handling, Insight, Medicine, Nature, Perception, Religion, Survival |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Spellcasting** | **Cantrip 2 อัน** + **เตรียมสเปลระดับ 1 ได้ 4 อัน** + **Spell Slot ระดับ 1 ×2** |
| **Druidic** | รู้ภาษาลับ **Druidic** — ทิ้งข้อความที่คนอื่นอ่านไม่ออก และรู้ Cantrip `Speak with Animals` (ร่ายแบบ Ritual ได้) |
| **Primal Order** [แนะนำ] | เลือก 1 แบบ:<br>• **Magician** — ได้ **Cantrip เพิ่ม 1 อัน** และ **+WIS modifier ใน Arcana/Nature Check**<br>• **Warden** — ได้ Proficiency **สายสู้ (Martial Weapon + Medium Armor)** |

### อุปกรณ์เริ่มต้น
**Leather Armor, Shield, Sickle, Druidic Focus, Herbalism Kit, Explorer's Pack, 9 GP** — หรือ **50 GP**

> **Druid ยากสำหรับมือใหม่** — Wild Shape (เลเวล 2) ต้องจำสถิติสัตว์ และรายการเวทใหญ่มาก

** [อ่านรายละเอียดเต็ม + รายการเวท](druid.md)**

---

## Fighter — นักรบ

> **ผู้เชี่ยวชาญการต่อสู้ทุกรูปแบบ** ตีบ่อยที่สุด ยืดหยุ่นที่สุดในสายรบ

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | **d10** |
| **HP เลเวล 1** | **10 + CON modifier** |
| **ค่าหลัก** | **STR** หรือ **DEX** |
| **Saving Throw Proficiency** | **STR, CON** |
| **Armor** | **ทุกชนิด (Light, Medium, Heavy) + Shield** |
| **Weapons** | Simple, **Martial** |
| **Skills** | เลือก **2** จาก: Acrobatics, Animal Handling, Athletics, History, Insight, Intimidation, Perception, Persuasion, Survival |
| **Weapon Mastery** | **3 ชนิด** (มากที่สุดในเกม) |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Fighting Style** [แนะนำ] | ได้ **Fighting Style Feat 1 อัน** (Archery, Defense, Dueling, Great Weapon Fighting ฯลฯ) |
| **Second Wind** [แนะนำ] | **Bonus Action:** ฟื้น **1d10 + เลเวล Fighter** HP — ใช้ได้ **2 ครั้ง** (ฟื้นเมื่อ Short Rest) |
| **Weapon Mastery** | ปลดล็อกคุณสมบัติพิเศษของอาวุธ **3 ชนิด** |

### อุปกรณ์เริ่มต้น
**Chain Mail, Greatsword, ×2 Handaxe, Dungeoneer's Pack, 4 GP**
หรือ **Studded Leather, Scimitar, Shortsword, Longbow + 20 Arrows, Dungeoneer's Pack, 11 GP** — หรือ **155 GP**

> **แนะนำอันดับ 1 สำหรับมือใหม่** — จำน้อยที่สุด ตัวแข็ง ตีแรง ผิดพลาดได้

** [อ่านรายละเอียดเต็ม เลเวล 1-20](fighter.md)**

---

## Monk — นักพรตหมัด

> **นักสู้ที่ควบคุมพลังภายใน (Ki/Focus)** เร็วที่สุด โจมตีถี่ที่สุด ไม่ต้องใช้อาวุธหรือเกราะ

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | d8 |
| **HP เลเวล 1** | **8 + CON modifier** |
| **ค่าหลัก** | **DEX และ WIS** (ต้องสูงทั้งคู่) |
| **Saving Throw Proficiency** | **STR, DEX** |
| **Armor** | ไม่มี (ไม่ควรใส่) |
| **Weapons** | Simple + **Martial Weapon ที่มีคุณสมบัติ Light** |
| **Tools** | เครื่องมือช่างหรือเครื่องดนตรี 1 ชนิด |
| **Skills** | เลือก **2** จาก: Acrobatics, Athletics, History, Insight, Religion, Stealth |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Martial Arts** [แนะนำ] | • **Unarmed Strike ทำ 1d6** (แทน 1)<br>• ใช้ **DEX แทน STR** ในการโจมตีมือเปล่าและอาวุธ Monk<br>• **Bonus Action:** โจมตีมือเปล่าเพิ่ม 1 ครั้ง หลังใช้ Attack action |
| **Unarmored Defense** | ตอนไม่ใส่เกราะและไม่ถือโล่: **AC = 10 + DEX + WIS** |

### อุปกรณ์เริ่มต้น
**Spear, ×5 Dart, Artisan's Tools/Musical Instrument, Explorer's Pack, 11 GP** — หรือ **50 GP**

> **Monk ต้องดันทั้ง DEX และ WIS** — ยากในเลเวลต่ำ แต่แรงมากในเลเวลสูง

** [อ่านรายละเอียดเต็ม เลเวล 1-20](monk.md)**

---

## Paladin — อัศวินศักดิ์สิทธิ์

> **นักรบผู้สาบานตนต่ออุดมการณ์** ตีแรง ทน รักษาเพื่อน และมีออร่าบัฟทั้งทีม

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | **d10** |
| **HP เลเวล 1** | **10 + CON modifier** |
| **ค่าหลัก** | **STR และ CHA** |
| **Saving Throw Proficiency** | **WIS, CHA** |
| **Armor** | **ทุกชนิด + Shield** |
| **Weapons** | Simple, **Martial** |
| **Skills** | เลือก **2** จาก: Athletics, Insight, Intimidation, Medicine, Persuasion, Religion |
| **Weapon Mastery** | **2 ชนิด** |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Lay On Hands** [แนะนำ] | มี **คลัง HP = 5 × เลเวล Paladin** (เลเวล 1 = 5 HP) — **Bonus Action:** สัมผัสแล้วฟื้น HP ให้ใคร ๆ ก็ได้ • ใช้ 5 HP เพื่อ**แก้พิษหรือโรค** 1 อย่าง • ฟื้นเมื่อ Long Rest |
| **Spellcasting** | **เตรียมสเปลระดับ 1 ได้ 2 อัน** + **Spell Slot ระดับ 1 ×2** (ไม่มี Cantrip) |
| **Weapon Mastery** | ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด |

### อุปกรณ์เริ่มต้น
**Chain Mail, Shield, Longsword, ×6 Javelin, Holy Symbol, Priest's Pack, 9 GP** — หรือ **150 GP**

> **เลเวล 2 (Divine Smite)** คือความสามารถที่ทำให้ Paladin ตีแรงที่สุดในเกมช่วงหนึ่ง

** [อ่านรายละเอียดเต็ม + รายการเวท](paladin.md)**

---

## Ranger — พรานป่า

> **นักล่าผู้เชี่ยวชาญถิ่นทุรกันดาร** ผสมการต่อสู้ การติดตาม และเวทธรรมชาติ

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | **d10** |
| **HP เลเวล 1** | **10 + CON modifier** |
| **ค่าหลัก** | **DEX และ WIS** |
| **Saving Throw Proficiency** | **STR, DEX** |
| **Armor** | Light, Medium, **Shield** |
| **Weapons** | Simple, **Martial** |
| **Skills** | เลือก **3** จาก: Animal Handling, Athletics, Insight, Investigation, Nature, Perception, Stealth, Survival |
| **Weapon Mastery** | **2 ชนิด** |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Spellcasting** | **สเปลระดับ 1 เตรียมได้ 2 อัน** + **Spell Slot ระดับ 1 ×2** |
| **Favored Enemy** [แนะนำ] | **`Hunter's Mark` เป็นสเปลที่เตรียมไว้เสมอ** (ไม่นับโควตา) และร่ายฟรีได้ **เท่ากับ Proficiency Bonus ต่อ Long Rest** โดยไม่ใช้ Spell Slot |
| **Weapon Mastery** | ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด |

### อุปกรณ์เริ่มต้น
**Studded Leather, Scimitar, Shortsword, Longbow + 20 Arrows, Druidic Focus, Explorer's Pack, 7 GP** — หรือ **150 GP**

** [อ่านรายละเอียดเต็ม + รายการเวท](ranger.md)**

---

## Rogue — โจร/นักลอบสังหาร

> **ผู้เชี่ยวชาญการลอบเร้นและการโจมตีจุดอ่อน** ดาเมจต่อครั้งสูงมาก และเก่งสกิลที่สุดในเกม

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | d8 |
| **HP เลเวล 1** | **8 + CON modifier** |
| **ค่าหลัก** | **DEX** |
| **Saving Throw Proficiency** | **DEX, INT** |
| **Armor** | Light |
| **Weapons** | Simple + **Martial Weapon ที่มีคุณสมบัติ Finesse หรือ Light** |
| **Tools** | **Thieves' Tools** |
| **Skills** | เลือก **4** จาก: Acrobatics, Athletics, Deception, Insight, Intimidation, Investigation, Perception, Performance, Persuasion, Sleight of Hand, Stealth (มากที่สุดในเกม) |
| **Weapon Mastery** | **2 ชนิด** |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Expertise** [แนะนำ] | เลือก **2 สกิล** ที่มี Proficiency **บวก Proficiency Bonus สองเท่า** |
| **Sneak Attack** [แนะนำมาก] | **1 ครั้ง/เทิร์น:** เพิ่มดาเมจ **1d6** เมื่อโจมตีด้วยอาวุธ **Finesse หรือ Ranged** และ (มี Advantage **หรือ** มีเพื่อนอยู่ในระยะ 5 ฟุตจากเป้าหมาย) |
| **Thieves' Cant** | ภาษาลับของโจร + รู้ภาษาอื่นเพิ่ม 1 ภาษา |
| **Weapon Mastery** | ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด |

### อุปกรณ์เริ่มต้น
**Leather Armor, ×2 Dagger, Shortsword, Shortbow + 20 Arrows, Thieves' Tools, Burglar's Pack, 8 GP** — หรือ **100 GP**

> **แนะนำสำหรับมือใหม่ที่อยากตีแรง** — ไม่มีเวทให้จำ แต่ทำได้หลากหลาย

** [อ่านรายละเอียดเต็ม เลเวล 1-20](rogue.md)**

---

## Sorcerer — จอมเวทสายเลือด

> **ผู้มีเวทมนตร์ไหลอยู่ในสายเลือด** ไม่ต้องเรียน แต่ดัดแปลงเวทได้ตามใจด้วย **Metamagic**

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | **d6** (น้อยที่สุด) |
| **HP เลเวล 1** | **6 + CON modifier** |
| **ค่าหลัก** | **CHA** |
| **Saving Throw Proficiency** | **CON, CHA** |
| **Armor** | ไม่มี |
| **Weapons** | Simple |
| **Skills** | เลือก **2** จาก: Arcana, Deception, Insight, Intimidation, Persuasion, Religion |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Spellcasting** | **Cantrip 4 อัน** (มากที่สุดที่เลเวล 1) + **เตรียมสเปลระดับ 1 ได้ 2 อัน** + **Spell Slot ระดับ 1 ×2** |
| **Innate Sorcery** [แนะนำ] | **Bonus Action:** เข้าโหมดเวทล้น **1 นาที** — **+1 Spell Save DC** และ **Advantage ในการทอย Spell Attack ทั้งหมด** — ใช้ได้ **2 ครั้ง/Long Rest** |

### อุปกรณ์เริ่มต้น
**Spear, ×2 Dagger, Arcane Focus, Dungeoneer's Pack, 28 GP** — หรือ **50 GP**

** [อ่านรายละเอียดเต็ม + รายการเวท](sorcerer.md)**

---

## Warlock — ผู้ทำสัญญา

> **ผู้แลกเปลี่ยนบางอย่างกับสิ่งเหนือธรรมชาติเพื่อพลัง** ยิงกระสุนแรง ๆ ไม่กี่นัด แต่**เติมได้ทุก Short Rest**

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | d8 |
| **HP เลเวล 1** | **8 + CON modifier** |
| **ค่าหลัก** | **CHA** |
| **Saving Throw Proficiency** | **WIS, CHA** |
| **Armor** | Light |
| **Weapons** | Simple |
| **Skills** | เลือก **2** จาก: Arcana, Deception, History, Intimidation, Investigation, Nature, Religion |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Eldritch Invocations** [แนะนำ] | ได้ **Invocation 1 อย่าง** — ความสามารถเวทถาวรที่เลือกเองได้ (เปลี่ยนได้ตอนเลื่อนเลเวล) |
| **Pact Magic** [แนะนำ] | **Cantrip 2 อัน** + **เตรียมสเปลได้ 2 อัน** + **Spell Slot ×1** — **Slot ฟื้นทุก Short Rest** [แนะนำ] และ**เป็นระดับสูงสุดที่มีเสมอ** |

### อุปกรณ์เริ่มต้น
**Leather Armor, Sickle, ×2 Dagger, Arcane Focus, Book, Scholar's Pack, 15 GP** — หรือ **100 GP**

> **Invocation `Agonizing Blast`** (เลเวล 2) + Cantrip `Eldritch Blast` = การโจมตีระยะไกลที่ดีที่สุดในเกม

** [อ่านรายละเอียดเต็ม + รายการเวท](warlock.md)**

---

## Wizard — พ่อมด

> **ผู้ศึกษาเวทมนตร์จากตำรา** มีเวทหลากหลายที่สุดในเกม และทรงพลังที่สุดในเลเวลสูง

### ข้อมูลพื้นฐาน

| หัวข้อ | ค่า |
|---|---|
| **Hit Die** | **d6** |
| **HP เลเวล 1** | **6 + CON modifier** |
| **ค่าหลัก** | **INT** |
| **Saving Throw Proficiency** | **INT, WIS** |
| **Armor** | ไม่มี |
| **Weapons** | Simple |
| **Skills** | เลือก **2** จาก: Arcana, History, Insight, Investigation, Medicine, Nature, Religion |

### Features เลเวล 1
| Feature | ทำอะไร |
|---|---|
| **Spellcasting** | **Cantrip 3 อัน** + **Spellbook มีสเปลระดับ 1 จำนวน 6 อัน** **เตรียมได้ 4 อัน** + **Spell Slot ระดับ 1 ×2** |
| **Ritual Adept** [แนะนำ] | ร่ายสเปลที่มีแท็ก **[Ritual]** จาก **Spellbook ได้เลย โดยไม่ต้องเตรียมไว้** |
| **Arcane Recovery** [แนะนำ] | **1 ครั้ง/วัน** หลัง **Short Rest** ฟื้น **Spell Slot ที่มีระดับรวมกันไม่เกินครึ่งเลเวล Wizard (ปัดขึ้น)** |

### อุปกรณ์เริ่มต้น
**×2 Dagger, Arcane Focus, Robe, Spellbook, Scholar's Pack, 5 GP** — หรือ **55 GP**

> **HP น้อยที่สุด (6+CON) และไม่มีเกราะ** — ต้องยืนหลังแนวเสมอ

** [อ่านรายละเอียดเต็ม + รายการเวท](wizard.md)**

---
---

## เลือกคลาสยังไงดี? (คู่มือตัดสินใจ)

### แผนผังช่วยเลือก

```
คุณอยากเล่นแบบไหน?

A. อยากตีศัตรูตรง ๆ ไม่อยากจำกฎเยอะ
   - อยากทนที่สุด Barbarian
   - อยากยืดหยุ่นที่สุด Fighter [แนะนำมือใหม่]
   - อยากตีแรงจัด ๆ ตอนสำคัญ Paladin

B. อยากลอบเร้น หลบซ่อน ตีจุดอ่อน
   - ไม่อยากใช้เวท Rogue [แนะนำมือใหม่]
   - อยากมีเวทบ้าง Ranger

C. อยากใช้เวทมนตร์
   - อยากมีเวทเยอะที่สุด Wizard
   - อยากยิงเวทซ้ำ ๆ ไม่หมด Warlock
   - อยากดัดแปลงเวท Sorcerer
   - อยากรักษาเพื่อน Cleric [แนะนำมือใหม่]
   - อยากอยู่กับธรรมชาติ Druid

D. อยากเก่งทุกอย่าง เข้าสังคมเก่ง Bard

E. อยากต่อยเตะ วิ่งเร็ว Monk
```

### สรุปคำแนะนำสำหรับผู้เล่นครั้งแรก

| ต้องการ | เลือก |
|---|---|
| **ง่ายที่สุด ผิดพลาดได้** | **Fighter** |
| **ทนที่สุด แค่กด Rage แล้วตี** | **Barbarian** |
| **สนุก หลากหลาย ไม่ต้องจำเวท** | **Rogue** |
| **มีเวทแต่แก้ไขง่าย (เตรียมใหม่ทุกวัน)** | **Cleric** |
| **อยากเป็นตัวหลักของทีมทางสังคม** | **Bard** |
| **หลีกเลี่ยงถ้าเป็นครั้งแรก** | **ต้องจำเวทเยอะมาก (Wizard, Druid)** |

---

## อ่านต่อ

- [ขั้นตอนการสร้างตัวละคร](../01-basics/04-character-creation.md)
- [Background ทั้ง 16](../03-backgrounds/00-backgrounds-overview.md)
- [กฎการร่ายเวท](../01-basics/07-spellcasting-rules.md)
- [อาวุธและ Weapon Mastery](../01-basics/08-equipment.md)
