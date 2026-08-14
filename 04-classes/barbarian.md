# นักรบคลั่ง (Barbarian)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**บาร์บาเรียน / นักรบคลั่ง (Barbarian)** คือนักรบที่เปลี่ยนความโกรธเป็นพลัง เมื่อเข้าสู่ **โหมดคลั่ง (Rage)** พวกเขาจะตีแรงขึ้น ทนขึ้น และแทบไม่มีอะไรหยุดได้

**แนะนำสำหรับผู้เล่นใหม่ (อันดับ 2)** จำแค่ "กด Rage แล้ววิ่งเข้าไปตี" ก็เล่นได้แล้ว และเป็นคลาสที่ **ทนที่สุดในเกม**

---

## ข้อมูลพื้นฐาน (Class Table)

- **ค่าหลัก (Primary Ability)** **Strength (STR)**
- **Hit Die** **d12** (สูงสุดในเกม)
- **HP เลเวล 1** **12 + CON modifier**
- **HP เลเวลถัดไป** **1d12 + CON** (หรือค่าคงที่ **7 + CON**)
- **Saving Throw Proficiency** **Strength, Constitution**
- **Armor Proficiency** Light Armor, Medium Armor, **Shield**
- **Weapon Proficiency** Simple Weapons, **Martial Weapons**
- **Skill Proficiency** เลือก **2** จาก: **Animal Handling, Athletics, Intimidation, Nature, Perception, Survival**
- **Weapon Mastery** **2 ชนิด** (เปลี่ยนได้ตอน Long Rest)
- **Subclass** เลือกที่ **เลเวล 3**

### อุปกรณ์เริ่มต้น

**เลือก A:** Greataxe, Handaxe 4 อัน, Explorer's Pack, **15 GP**
**เลือก B:** **75 GP** ไปซื้อเอง

---

## ความก้าวหน้าเลเวล 1 ถึง 20

- **เลเวล 1** Proficiency Bonus +2, ได้ความสามารถ Rage, Unarmored Defense, Weapon Mastery, Rages (ครั้ง/วัน) 2, Rage Damage +2, Weapon Mastery 2
- **เลเวล 2** Proficiency Bonus +2, ได้ความสามารถ Danger Sense, Reckless Attack, Rages (ครั้ง/วัน) 2, Rage Damage +2, Weapon Mastery 2
- **เลเวล 3** Proficiency Bonus +2, ได้ความสามารถ Primal Path (Subclass) [แนะนำ], Primal Knowledge, Rages (ครั้ง/วัน) 3, Rage Damage +2, Weapon Mastery 2
- **เลเวล 4** Proficiency Bonus +2, ได้ความสามารถ Ability Score Improvement (ASI), Rages (ครั้ง/วัน) 3, Rage Damage +2, Weapon Mastery 3
- **เลเวล 5** Proficiency Bonus +3, ได้ความสามารถ Extra Attack [แนะนำ], Fast Movement, Rages (ครั้ง/วัน) 3, Rage Damage +2, Weapon Mastery 3
- **เลเวล 6** Proficiency Bonus +3, ได้ความสามารถ Subclass Feature, Rages (ครั้ง/วัน) 4, Rage Damage +2, Weapon Mastery 3
- **เลเวล 7** Proficiency Bonus +3, ได้ความสามารถ Feral Instinct, Instinctive Pounce, Rages (ครั้ง/วัน) 4, Rage Damage +2, Weapon Mastery 3
- **เลเวล 8** Proficiency Bonus +3, ได้ความสามารถ ASI, Rages (ครั้ง/วัน) 4, Rage Damage +2, Weapon Mastery 3
- **เลเวล 9** Proficiency Bonus +4, ได้ความสามารถ Brutal Strike, Rages (ครั้ง/วัน) 4, Rage Damage +3, Weapon Mastery 3
- **เลเวล 10** Proficiency Bonus +4, ได้ความสามารถ Subclass Feature, Rages (ครั้ง/วัน) 4, Rage Damage +3, Weapon Mastery 4
- **เลเวล 11** Proficiency Bonus +4, ได้ความสามารถ Relentless Rage [แนะนำ], Rages (ครั้ง/วัน) 4, Rage Damage +3, Weapon Mastery 4
- **เลเวล 12** Proficiency Bonus +4, ได้ความสามารถ ASI, Rages (ครั้ง/วัน) 5, Rage Damage +3, Weapon Mastery 4
- **เลเวล 13** Proficiency Bonus +5, ได้ความสามารถ Improved Brutal Strike, Rages (ครั้ง/วัน) 5, Rage Damage +3, Weapon Mastery 4
- **เลเวล 14** Proficiency Bonus +5, ได้ความสามารถ Subclass Feature, Rages (ครั้ง/วัน) 5, Rage Damage +3, Weapon Mastery 4
- **เลเวล 15** Proficiency Bonus +5, ได้ความสามารถ Persistent Rage, Rages (ครั้ง/วัน) 5, Rage Damage +3, Weapon Mastery 4
- **เลเวล 16** Proficiency Bonus +5, ได้ความสามารถ ASI, Rages (ครั้ง/วัน) 5, Rage Damage +4, Weapon Mastery 4
- **เลเวล 17** Proficiency Bonus +6, ได้ความสามารถ Improved Brutal Strike, Rages (ครั้ง/วัน) 6, Rage Damage +4, Weapon Mastery 4
- **เลเวล 18** Proficiency Bonus +6, ได้ความสามารถ Indomitable Might, Rages (ครั้ง/วัน) 6, Rage Damage +4, Weapon Mastery 4
- **เลเวล 19** Proficiency Bonus +6, ได้ความสามารถ Epic Boon Feat, Rages (ครั้ง/วัน) 6, Rage Damage +4, Weapon Mastery 4
- **เลเวล 20** Proficiency Bonus +6, ได้ความสามารถ Primal Champion, Rages (ครั้ง/วัน) ไม่จำกัด, Rage Damage +4, Weapon Mastery 4

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 โหมดคลั่ง (Rage) ความสามารถหลักของคลาส

**เข้าสู่โหมด:** ใช้ **Bonus Action** ต้องไม่ใส่ **Heavy Armor**
**ระยะเวลา:** คงอยู่ **จนจบเทิร์นหน้าของคุณ** เท่านั้น แล้วต้อง**ต่ออายุทีละรอบ** ยืดได้**สูงสุด 10 นาที** (กฎ 2014 เพดานอยู่ที่ 1 นาที)

**ระหว่างที่ Rage คุณได้:**

- **Damage Resistance** **Resistance ต่อ Bludgeoning, Piercing, และ Slashing damage** (รับดาเมจกายภาพครึ่งเดียว!)
- **Rage Damage** **+2 ดาเมจ** เมื่อโจมตีด้วยอาวุธหรือ Unarmed Strike **ที่ใช้ STR แล้วทำดาเมจโดน** และ เพิ่มเป็น **+3 ที่เลเวล 9** และ **+4 ที่เลเวล 16**
- **Strength Advantage** **Advantage ในการทอย Strength Check และ Strength Saving Throw**
- **Subclass Feature** ปลดล็อกความสามารถของ Subclass บางอย่าง

**การต่ออายุ Rage (จุดที่มือใหม่พลาดบ่อยที่สุด):**

Rage **ไม่ได้ติดยาว 10 นาทีทันทีที่กด** มันอยู่แค่ถึงจบเทิร์นหน้าของคุณ ถ้าอยากให้อยู่ต่อ ในเทิร์นของคุณต้องทำ **อย่างใดอย่างหนึ่ง** ต่อไปนี้:

- **ทอย Attack Roll ใส่ศัตรู** วิธีปกติ ทอยก็พอ ไม่ต้องตีโดน
- **บังคับให้ศัตรูทอย Saving Throw** เช่นใช้ Weapon Mastery หรือความสามารถของ Subclass
- **ใช้ Bonus Action ต่ออายุ Rage** ทางออกเมื่อเทิร์นนั้นเข้าไม่ถึงศัตรู

ทำครบ 1 ใน 3 อย่างนี้ Rage จะยืดออกไปอีกจนจบเทิร์นหน้า ทำซ้ำไปเรื่อย ๆ ได้จนถึงเพดาน **10 นาที = 100 รอบ** (1 รอบ = 6 วินาที) ซึ่งยาวกว่าการต่อสู้ปกติมาก การต่อสู้ทั่วไปจบใน 3-5 รอบเท่านั้น

**Rage จบเมื่อ:**
- **คุณไม่ได้ทำ 1 ใน 3 อย่างข้างบนในเทิร์นของคุณ** (สาเหตุที่เจอบ่อยที่สุด)
- คุณใส่ **Heavy Armor** หรือถูก **Incapacitated**
- ครบเพดาน **10 นาที (100 รอบ)**

**หมายเหตุกฎ 2024:** กฎ 2014 มีข้อ "สั่งจบ Rage เองด้วย Bonus Action" แต่กฎ 2024 ตัดข้อนี้ออกจาก Rage พื้นฐานแล้ว ถ้าอยากให้จบก็แค่ไม่ต่ออายุ (ความสามารถ **Persistent Rage** เลเวล 15 ถึงจะพูดถึงการสั่งจบเองอีกครั้ง) จุดนี้ควรเช็คกับหน้า Rage ในหนังสือต้นฉบับยืนยันอีกรอบ

**จำนวนครั้ง:** เริ่มที่ **2 ครั้ง/วัน** ฟื้น **1 ครั้งเมื่อ Short Rest** และ **ทั้งหมดเมื่อ Long Rest**

**ข้อจำกัดสำคัญ:** ระหว่าง Rage คุณ **ร่ายเวทไม่ได้ และรักษา Concentration ไม่ได้**

---

### เลเวล 1 การป้องกันไร้เกราะ (Unarmored Defense)

**ตอนไม่ใส่เกราะใด ๆ: AC = 10 + DEX modifier + CON modifier**
**ถือ Shield ได้ (บวก +2 เพิ่ม)**

**เปรียบเทียบ AC:**

- DEX 14 (+2), CON 16 (+3) ไม่ใส่เกราะ **15**
- + Shield **17**
- DEX 16 (+3), CON 18 (+4) ไม่ใส่เกราะ + Shield **19**
- Half Plate (15 + DEX max 2) + Shield **19** (แต่ Stealth เสียเปรียบ)

**มือใหม่แนะนำ:** ช่วงเลเวลต่ำถ้า DEX/CON ยังไม่สูง **ใส่ Medium Armor + Shield ก็ได้** (Rage ยังใช้ได้ปกติ) พอเลเวลสูงค่อยเปลี่ยนมา Unarmored Defense

---

### เลเวล 1 ความชำนาญอาวุธ (Weapon Mastery)

เลือกอาวุธ **2 ชนิด** ที่คุณมี Proficiency ปลดล็อก **Mastery Property** ของอาวุธนั้น
**เปลี่ยนตัวเลือกได้ทุกครั้งที่จบ Long Rest**

** Mastery ที่แนะนำสำหรับ Barbarian:**

- **Greataxe** **Cleave** ตีโดน โจมตีศัตรูอีกตัวข้าง ๆ ฟรี (1 ครั้ง/เทิร์น)
- **Maul** **Topple** ตีโดน ศัตรูทอย CON Save ล้มเหลว = **Prone** ทีมได้ Advantage หมด [แนะนำ]
- **Greatsword** **Graze** ตีพลาด ยังทำดาเมจ = STR modifier
- **Handaxe** **Vex** ตีโดน การโจมตีครั้งถัดไปต่อเป้าหมายนั้นได้ **Advantage**
- **Halberd** **Cleave** Reach 10 ฟุต + ตีศัตรูข้าง ๆ

**แนะนำที่สุด: Maul (Topple) + Greataxe (Cleave)**

 ดู Mastery ทั้ง 8 แบบใน [อุปกรณ์และอาวุธ](../01-basics/08-equipment.md)

---

### เลเวล 2 สัมผัสอันตราย (Danger Sense)

**Advantage ในการทอย Dexterity Saving Throw** ตราบที่คุณ **ไม่ถูก Incapacitated**

**ทำไมดี:** DEX Save เป็น Save ที่เจอบ่อยที่สุด (Fireball, กับดัก, ลมหายใจมังกร) และเมื่อรวมกับ Rage Resistance คุณแทบไม่เจ็บเลย

---

### เลเวล 2 โจมตีบ้าบิ่น (Reckless Attack)

**เมื่อเริ่มเทิร์นของคุณ** คุณสามารถเลือกโจมตีแบบบ้าบิ่นได้

- **การโจมตีระยะประชิดที่ใช้ STR ทั้งหมดในเทิร์นนี้มี Advantage**
- **แต่ศัตรูที่โจมตีคุณก็ได้ Advantage เช่นกัน** (จนถึงเริ่มเทิร์นหน้าของคุณ)

**ทำไมดี:** Barbarian มี Resistance จาก Rage อยู่แล้ว **การถูกตีบ่อยขึ้นจึงคุ้มกับการที่เราตีโดนบ่อยขึ้นมาก**

**เกือบทุกเทิร์นควรใช้ Reckless Attack** ยกเว้นตอน HP เหลือน้อย หรือสู้ศัตรูที่ตีแรงมาก

---

### เลเวล 3 ปัญญาปฐมภูมิ (Primal Knowledge)

- ได้ **Skill Proficiency เพิ่ม 1 อย่าง** จากรายการสกิลของ Barbarian
- **ระหว่าง Rage:** [แนะนำ] คุณสามารถใช้ **STR แทน DEX/CON/INT/WIS/CHA** ในการทอย Ability Check ของสกิลเหล่านี้: **Acrobatics, Intimidation, Perception, Stealth, Survival**

**ทำไมดี:** ทำให้ **Intimidation ใช้ STR ได้** Barbarian ที่ CHA ต่ำก็ขู่คนเก่ง!

---

### เลเวล 5 การโจมตีเพิ่ม (Extra Attack)

**เมื่อใช้ Attack action คุณโจมตีได้ 2 ครั้ง แทนที่จะเป็น 1 ครั้ง**

**ทำไมสำคัญ:** ดาเมจต่อเทิร์นเพิ่มขึ้นเกือบ 2 เท่า และ Rage Damage บวกทุกครั้ง

---

### เลเวล 5 ความเร็วสูง (Fast Movement)

**Speed เพิ่มขึ้น 10 ฟุต** ตราบที่ไม่ใส่ **Heavy Armor**

---

### เลเวล 7 สัญชาตญาณป่า (Feral Instinct)

**Advantage ในการทอย Initiative**

---

### เลเวล 7 ทะยานตามสัญชาตญาณ (Instinctive Pounce)

**เมื่อคุณใช้ Bonus Action เข้า Rage** คุณสามารถ**เคลื่อนที่ได้ทันทีเป็นระยะครึ่งหนึ่งของ Speed**

**ทำไมดี:** เข้าถึงศัตรูได้ไวขึ้นมากในเทิร์นแรกของการต่อสู้ (Rage + วิ่ง 15 ฟุตฟรี + Movement ปกติ 40 ฟุต + Attack)

---

### เลเวล 9 การโจมตีโหดเหี้ยม (Brutal Strike)

**เมื่อคุณใช้ Reckless Attack** คุณสามารถ**สละ Advantage ของการโจมตี 1 ครั้ง** เพื่อ:

- เพิ่มดาเมจ **1d10**
- **และ** ใช้ผลพิเศษ 1 อย่าง:

- **Forceful Blow** **ผลักเป้าหมายถอย 15 ฟุต** ในทิศทางตรง แล้วคุณเคลื่อนที่ตามได้ไม่เกินครึ่ง Speed (ไม่ใช้ Movement)
- **Hamstring Blow** **ลด Speed ของเป้าหมาย 15 ฟุต** จนถึงเริ่มเทิร์นหน้าของคุณ

**เลเวล 13 และ 17** (Improved Brutal Strike) จะเพิ่มดาเมจและตัวเลือกใหม่

---

### เลเวล 11 ความคลั่งไม่สิ้นสุด (Relentless Rage)

**ถ้า HP ของคุณลดเหลือ 0 ระหว่าง Rage และคุณไม่ตายทันที**
คุณสามารถทอย **CON Saving Throw DC 10** **สำเร็จ HP กลับมาเท่ากับ 2 เท่าของเลเวล Barbarian**

- **ทุกครั้งที่ใช้ DC เพิ่มขึ้น 5** (10 15 20...)
- **DC รีเซ็ตเมื่อคุณจบ Short Rest หรือ Long Rest**

**เปลี่ยนจากกฎ 2014:** กฎเดิม HP กลับมาแค่ **1** เท่านั้น กฎ 2024 ให้ **2 คูณ เลเวล** เลเวล 11 คือกลับมา **22 HP**, เลเวล 20 คือ **40 HP**

**ทำไมนี่คือหนึ่งใน Feature ที่โด่งดังที่สุด:** Barbarian แทบล้มไม่ลง สู้ต่อได้เรื่อย ๆ แม้ HP หมด และรอบนี้ไม่ได้ลุกมาแบบตีทีเดียวก็ล้มอีกด้วย

---

### เลเวล 13 Improved Brutal Strike

Brutal Strike เพิ่มดาเมจเป็น **2d10** และเพิ่มตัวเลือกใหม่:

- **Staggering Blow** เป้าหมาย **เสียเปรียบใน Saving Throw ครั้งถัดไป** และ **ใช้ Reaction ไม่ได้** จนถึงเริ่มเทิร์นหน้าของคุณ
- **Sundering Blow** การโจมตีครั้งถัดไปของ**เพื่อนร่วมทีม**ต่อเป้าหมายนั้น **+5 ในการทอยโจมตี**

---

### เลเวล 15 ความคลั่งอมตะ (Persistent Rage)

**เมื่อทอย Initiative คุณสามารถฟื้นคืน Rage ที่ใช้ไปแล้วทั้งหมดทันที** ใช้ได้ **1 ครั้งต่อ Long Rest**
**และ Rage ของคุณจะคงอยู่ครบ 10 นาทีโดยไม่ต้องต่ออายุทีละรอบอีกต่อไป** จบก่อนเวลาเฉพาะเมื่อคุณถูก Incapacitated, ใส่ Heavy Armor, หรือสั่งจบเอง

**ทำไมดี:** ตั้งแต่เลเวล 15 เป็นต้นไป **ไม่ต้องกังวลว่าจะ "ลืมตีในเทิร์นนี้" แล้ว Rage หลุด** อีกเลย และการฟื้น Rage ทั้งหมดตอนทอย Initiative แปลว่าถ้าวันนั้นเจอศึกหนักติดกัน คุณแทบไม่มีวันหมด Rage

---

### เลเวล 17 ครั้งที่ 2 (Improved Brutal Strike)

Brutal Strike เพิ่มดาเมจเป็น **3d10** และ**ใช้ผลพิเศษได้ 2 อย่างพร้อมกัน** (ต้องสละ Advantage 2 ครั้ง)

---

### เลเวล 18 พละกำลังอันไม่ยอมแพ้ (Indomitable Might)

**เมื่อทอย Strength Check หรือ Strength Saving Throw** ถ้าผลรวมน้อยกว่า **ค่า STR ของคุณ**
**ให้ใช้ค่า STR แทนผลรวมนั้น**

**ตัวอย่าง:** STR 22 ทอย Athletics ได้ผลรวม 15 **นับเป็น 22 แทน**

---

### เลเวล 20 แชมป์ปฐมภูมิ (Primal Champion) Capstone

- **STR และ CON เพิ่มขึ้นอย่างละ 4**
- **เพดานสูงสุดของทั้งสองค่ากลายเป็น 25** (แทนที่จะเป็น 20)
- (พร้อมกับความก้าวหน้าเลเวล 20 ที่ให้ **Rage ไม่จำกัดครั้ง**)

**ผลลัพธ์:** STR 25 (+7), CON 25 (+7) HP มหาศาล + AC สูง + ดาเมจสูงสุด

---

## Subclasses (Primal Path) เลือกที่เลเวล 3

Barbarian มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 6, 10, 14**

---

### 1. Path of the Berserker วิถีนักรบบ้าคลั่ง

**ธีม:** ความบ้าคลั่งบริสุทธิ์ ดาเมจล้วน ๆ เข้าใจง่ายที่สุด

**เลเวล 3 Frenzy**

ระหว่าง Rage เมื่อโจมตีแบบ Reckless Attack ให้เพิ่มดาเมจ **1d6** (เพิ่มเป็น 2d6 ที่เลเวล 9, 3d6 ที่ 13, 4d6 ที่ 17) **1 ครั้ง/เทิร์น**

**เลเวล 6 Mindless Rage**

ระหว่าง Rage คุณ **ภูมิคุ้มกันสภาวะ Charmed และ Frightened**

**เลเวล 10 Retaliation**

**Reaction:** เมื่อรับดาเมจจากศัตรูในระยะ 5 ฟุต โจมตีกลับ 1 ครั้ง

**เลเวล 14 Intimidating Presence**

**Bonus Action:** สิ่งมีชีวิตที่เลือกในระยะ 30 ฟุต ทอย **WIS Save (DC = 8+STR+Prof)** ล้มเหลว = **Frightened 1 นาที** ใช้ได้ Prof Bonus ครั้ง/Long Rest

**แนะนำมือใหม่ที่สุด** เพิ่มดาเมจตรง ๆ ไม่มีกฎซับซ้อน

---

### 2. Path of the Wild Heart วิถีหัวใจป่า

**ธีม:** เชื่อมโยงกับวิญญาณสัตว์ เน้นความหลากหลายและการช่วยทีม

**เลเวล 3 Animal Speaker**

ร่าย Beast Sense และ Speak with Animals ได้แบบ **Ritual** โดยไม่ใช้ Spell Slot

**เลเวล 3 Rage of the Wilds**

เมื่อเข้า Rage เลือกวิญญาณ 1 ตัว:
- **Bear** Resistance ต่อทุกดาเมจ ยกเว้น Force, Necrotic, Psychic, Radiant
- **Eagle** ได้ **Disengage + Dash เป็น Bonus Action ฟรี**
- **Wolf** เพื่อนได้ **Advantage** เมื่อตีศัตรูในระยะ 5 ฟุตจากคุณ

**เลเวล 6 Aspect of the Wilds**

เลือกพร 1 อย่าง (เปลี่ยนได้ตอน Long Rest):
- **Owl** Darkvision 60 ft (หรือ +60 ถ้ามีอยู่แล้ว)
- **Panther** **Climb Speed = Speed**
- **Salmon** **Swim Speed = Speed**

**เลเวล 10 Nature Speaker**

ร่าย Commune with Nature ได้แบบ Ritual

**เลเวล 14 Power of the Wilds**

เมื่อ Rage เลือกเพิ่ม 1 อย่าง:
- **Falcon** **Fly Speed = Speed** (ถ้าไม่ใส่ Medium/Heavy Armor)
- **Lion** ศัตรูในระยะ 5 ฟุตที่ตีคนอื่นที่ไม่ใช่คุณ **เสียเปรียบ**
- **Ram** เมื่อตีโดน ทำให้เป้าหมาย **Prone** ได้

**สายที่ยืดหยุ่นที่สุด** Bear Rage ทำให้ทนสุด, Wolf ช่วยทีม, Eagle เคลื่อนที่คล่อง

---

### 3. Path of the World Tree วิถีต้นไม้โลก

**ธีม:** เชื่อมโยงกับ Yggdrasil ต้นไม้จักรวาล เน้น Temp HP และการช่วยทีมด้วยการวาร์ป

**เลเวล 3 Vitality of the Tree**

**เมื่อเข้า Rage:** ได้ **Temp HP = เลเวล Barbarian** และ **เมื่อเริ่มเทิร์นระหว่าง Rage:** ให้ Temp HP กับเพื่อน 1 คนในระยะ 10 ฟุต (ทอย **d6 จำนวนเท่ากับครึ่งเลเวล Barbarian**)

**เลเวล 6 Branches of the Tree**

**Reaction:** เมื่อศัตรูในระยะ 30 ฟุตเริ่มเทิร์น มันทอย **STR Save** ล้มเหลว = **วาร์ปมาที่ว่างในระยะ 5 ฟุตจากคุณ** และ **Speed = 0** ในเทิร์นนั้น

**เลเวล 10 Battering Roots**

อาวุธ Melee ที่มี **Heavy หรือ Versatile** ได้ **Reach +10 ฟุต** และเมื่อตีโดน ใช้ Mastery **Push** หรือ **Topple** ได้ฟรี (นอกเหนือจาก Mastery ปกติ)

**เลเวล 14 Travel Along the Tree**

**Bonus Action ระหว่าง Rage:** วาร์ปตัวเองไปได้ **60 ฟุต** และ หรือใช้ **Rage 1 ครั้ง** วาร์ปไป **150 ฟุต** พร้อมเพื่อนได้ถึง 6 คนในระยะ 10 ฟุต

**สายซัพพอร์ตที่ดีที่สุดของ Barbarian** Temp HP ให้ทีมทุกเทิร์น + ดึงศัตรูออกจากเพื่อนสายเวท

---

### 4. Path of the Zealot วิถีผู้คลั่งศาสนา

**ธีม:** นักรบผู้ได้รับพลังจากเทพเจ้า ตายยากที่สุด

**เลเวล 3 Divine Fury**

**1 ครั้ง/เทิร์น ระหว่าง Rage:** เมื่อตีโดนด้วยอาวุธ เพิ่มดาเมจ **1d6 + ครึ่งเลเวล Barbarian** เป็น **Necrotic หรือ Radiant** (เลือกตอนเลเวล 3)

**เลเวล 3 Warrior of the Gods**

มี **คลังเต๋าฟื้นฟู d12** เท่ากับ Prof Bonus **Bonus Action:** ใช้เต๋ากี่ลูกก็ได้เพื่อฟื้น HP และ ฟื้นคลังเมื่อ Long Rest

**เลเวล 6 Fanatical Focus**

**1 ครั้งต่อ Rage:** เมื่อทอย Saving Throw ล้มเหลว **ทอยใหม่ได้ +4**

**เลเวล 10 Zealous Presence**

**Bonus Action:** เพื่อนได้ถึง 10 คนในระยะ 60 ฟุต ได้ **Advantage ในการทอย Attack Roll และ Saving Throw** จนถึงเริ่มเทิร์นหน้าของคุณ ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Rage 1 ครั้งเพื่อใช้อีกรอบ)

**เลเวล 14 Rage Beyond Death**

**ระหว่าง Rage: HP ที่เหลือ 0 ไม่ทำให้คุณหมดสติ** คุณยังทอย Death Save แต่**ยังสู้ต่อได้ตามปกติ** จนกว่า Rage จะจบ (ถ้าล้มเหลว 3 ครั้ง = ตายเมื่อ Rage จบ)

**สายที่ตายยากที่สุด** เลเวล 14 คือคุณ "ยืนสู้ได้แม้ตายไปแล้ว"

---

## เปรียบเทียบ 4 Subclass

- **จุดเด่น** ดาเมจสูงสุด ยืดหยุ่นสุด ซัพพอร์ตทีม ตายยากสุด
- **ความยาก** ง่ายสุด กลาง กลาง ง่าย
- **ช่วยทีม** ต่ำ กลาง **สูงสุด** สูง
- **แนะนำมือใหม่** **ใช่** ใช่ ใช่

---

## คำแนะนำการสร้าง Barbarian

### ค่าพลังที่ควรจัด

- STR สูงสุด (17-18 ตั้งแต่เลเวล 1)
- CON สูงรอง (14-16)
- DEX ปานกลาง (12-14) ใช้กับ AC และ Initiative
- WIS ถ้าเหลือ (WIS Save เจอบ่อย)
- CHA / INT ต่ำได้

### Species ที่แนะนำ

- **ลูกหลานยักษ์ (Goliath)** [แนะนำมาก] Speed 35 + Powerful Build + Giant Ancestry เข้าธีมและแรง
- **ออร์ค (Orc)** [แนะนำมาก] Relentless Endurance + Adrenaline Rush = ทนสุด ๆ
- **คนแคระ (Dwarf)** [แนะนำ] +1 HP ทุกเลเวล + ต้านพิษ
- **มนุษย์ (Human)** Feat ฟรี (Tough = +2 HP/เลเวล)
- **คนมังกร (Dragonborn)** Breath Weapon ใช้แทนการโจมตีได้

### Background ที่แนะนำ
**Soldier** (STR/DEX/CON) [แนะนำ], **STR/CON/WIS ได้ Tough (Farmer)** และ **Guard** (STR/INT/WIS)

### Feat ที่แนะนำ (เลเวล 4+)

- **Great Weapon Master** [แนะนำ] ตีคริติคอลหรือฆ่าศัตรู โจมตีเพิ่มด้วย Bonus Action
- **Ability Score Improvement (STR)** [แนะนำ] ดัน STR ให้ถึง 20 ก่อนอย่างอื่น
- **Tough** +2 HP ต่อเลเวล
- **Charger** วิ่งเข้าชนแรง
- **Resilient (Wisdom)** แก้จุดอ่อน WIS Save
- **Grappler** สายจับล็อกศัตรู

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

- ใส่ Heavy Armor **Rage จะใช้ไม่ได้!** ใส่ได้แค่ Light/Medium
- ลืมกด Rage ก่อนเข้าสู้ กด Rage เป็น Bonus Action ในเทิร์นแรกเสมอ
- คิดว่ากด Rage แล้วติดยาว 10 นาที **ไม่ใช่** Rage อยู่แค่ถึงจบเทิร์นหน้า ต้องโจมตีศัตรู / บังคับให้ศัตรูทอย Save / ใช้ Bonus Action ต่ออายุ ในทุกเทิร์น 10 นาทีคือ**เพดานสูงสุด**
- เทิร์นที่วิ่งเข้าหาศัตรูไม่ทัน แล้วปล่อย Rage หลุด ใช้ **Bonus Action ต่ออายุ Rage** ในเทิร์นนั้นแทน
- นับ Rage Damage ให้การโจมตีที่ใช้ DEX **ได้เฉพาะการโจมตีที่ใช้ STR** ขว้าง Handaxe ได้ (ใช้ STR) แต่ยิงธนูไม่ได้
- ไม่ใช้ Reckless Attack ใช้แทบทุกเทิร์น เรามี Resistance อยู่แล้ว
- ดัน DEX แทน CON **CON สำคัญกว่า** เพราะเพิ่มทั้ง HP และ AC (Unarmored Defense)
- ร่ายเวทระหว่าง Rage **ทำไม่ได้** Barbarian ไม่ควร Multiclass กับสายเวท

---

## สรุป Barbarian ในหนึ่งบรรทัด

**กด Rage วิ่งเข้าไป Reckless Attack ตี = ทนที่สุด ตีแรง และเล่นง่ายที่สุดในเกม**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
