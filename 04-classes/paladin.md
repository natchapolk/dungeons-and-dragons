# อัศวินศักดิ์สิทธิ์ (Paladin)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**พาลาดิน / อัศวินศักดิ์สิทธิ์ (Paladin)** คือนักรบผู้สาบานตนต่ออุดมการณ์ พลังของพวกเขามาจาก **คำสาบาน (Oath)** ไม่ใช่จากเทพเจ้าโดยตรง พวกเขาตีแรง ทนมาก รักษาเพื่อนได้ และมี **ออร่า (Aura)** ที่บัฟทั้งทีม

Paladin คือคลาสที่ "ทำได้ทุกอย่าง" แนวหน้า + ดาเมจ + รักษา + บัฟทีม แต่ต้องดัน 3 ค่าพลัง (STR, CHA, CON)

---

## ข้อมูลพื้นฐาน (Class Table)

- **Primary Ability** **Strength (STR)** และ **Charisma (CHA)**
- **Hit Die** d10
- **HP เลเวล 1** 10 + CON modifier
- **HP เลเวลถัดไป** 1d10 + CON (หรือค่าคงที่ 6 + CON)
- **Saving Throw Proficiency** **Wisdom, Charisma**
- **Armor Proficiency** **ครบทุกอย่าง (Light, Medium, Heavy Armor + Shield)**
- **Weapon Proficiency** Simple Weapons, **Martial Weapons**
- **Skill Proficiency** เลือก 2 จาก: **Athletics, Insight, Intimidation, Medicine, Persuasion, Religion**
- **Weapon Mastery** 2 ชนิด
- **Spellcasting Ability** **Charisma (CHA)**
- **Subclass (Sacred Oath)** เลือกที่ เลเวล 3

### อุปกรณ์เริ่มต้น

**เลือก A** รับของชุดนี้

- **เกราะโซ่ (Chain Mail)** ให้ AC 16 คงที่ ไม่บวก DEX ต้องมี STR อย่างน้อย 13 ไม่งั้น Speed ลด 10 ฟุต
- **โล่ (Shield)** ให้ AC เพิ่ม 2 รวมกับเกราะโซ่แล้วได้ AC 18 ซึ่งสูงที่สุดที่ตัวละครเลเวล 1 ทำได้
- **ดาบยาว (Longsword)** ดาเมจ 1d8 Slashing ความชำนาญ Sap ทำให้ศัตรูที่โดนตีเสียเปรียบในการโจมตีครั้งถัดไป
- **หอกซัด (Javelin)** 6 อัน ดาเมจ 1d6 Piercing ความชำนาญ Slow ขว้างได้ไกล 30 ฟุต ใช้ลด Speed ศัตรูที่กำลังวิ่งเข้ามา
- **สัญลักษณ์ศักดิ์สิทธิ์ (Holy Symbol)** เป็น Spellcasting Focus ของ Paladin
- **ชุดนักบวช (Priest's Pack)** มีน้ำมนต์ ชุดคลุม และเสบียง
- เงินติดตัว 9 GP

**เลือก B** รับเงิน 150 GP ไปซื้อของเอง

แนะนำอย่างยิ่งสำหรับมือใหม่ ให้เลือก A เพราะเกราะโซ่กับโล่รวมกันราคา 85 GP
และของที่เหลือในชุดนี้อีกประมาณ 50 GP ทำให้เลือก A คุ้มกว่าเงิน 150 GP
เหมือน Cleric ให้ขอ DM ว่าขอสัญลักษณ์ศักดิ์สิทธิ์แบบ **ตราบนโล่ (Emblem)** จะได้ถือดาบและโล่พร้อมร่ายเวทได้

---

## ความก้าวหน้าเลเวล 1 ถึง 20

- **เลเวล 1** Proficiency Bonus +2, ได้ความสามารถ Lay On Hands, Spellcasting, Weapon Mastery, เตรียมสเปลได้ 2, Slot 1 2
- **เลเวล 2** Proficiency Bonus +2, ได้ความสามารถ Fighting Style, Paladin's Smite [แนะนำ], เตรียมสเปลได้ 3, Slot 1 2
- **เลเวล 3** Proficiency Bonus +2, ได้ความสามารถ Channel Divinity [แนะนำ], Sacred Oath (Subclass), Channel Divinity 2, เตรียมสเปลได้ 4, Slot 1 3
- **เลเวล 4** Proficiency Bonus +2, ได้ความสามารถ ASI, Channel Divinity 2, เตรียมสเปลได้ 5, Slot 1 3
- **เลเวล 5** Proficiency Bonus +3, ได้ความสามารถ Extra Attack [แนะนำ], Faithful Steed, Channel Divinity 2, เตรียมสเปลได้ 6, Slot 1 4, Slot 2 2
- **เลเวล 6** Proficiency Bonus +3, ได้ความสามารถ Aura of Protection [แนะนำมาก], Channel Divinity 2, เตรียมสเปลได้ 6, Slot 1 4, Slot 2 2
- **เลเวล 7** Proficiency Bonus +3, ได้ความสามารถ Subclass Feature, Channel Divinity 2, เตรียมสเปลได้ 7, Slot 1 4, Slot 2 3
- **เลเวล 8** Proficiency Bonus +3, ได้ความสามารถ ASI, Channel Divinity 2, เตรียมสเปลได้ 7, Slot 1 4, Slot 2 3
- **เลเวล 9** Proficiency Bonus +4, ได้ความสามารถ Abjure Foes, Channel Divinity 3, เตรียมสเปลได้ 9, Slot 1 4, Slot 2 3, Slot 3 2
- **เลเวล 10** Proficiency Bonus +4, ได้ความสามารถ Aura of Courage [แนะนำ], Channel Divinity 3, เตรียมสเปลได้ 9, Slot 1 4, Slot 2 3, Slot 3 2
- **เลเวล 11** Proficiency Bonus +4, ได้ความสามารถ Radiant Strikes [แนะนำ], Channel Divinity 3, เตรียมสเปลได้ 10, Slot 1 4, Slot 2 3, Slot 3 3
- **เลเวล 12** Proficiency Bonus +4, ได้ความสามารถ ASI, Channel Divinity 3, เตรียมสเปลได้ 10, Slot 1 4, Slot 2 3, Slot 3 3
- **เลเวล 13** Proficiency Bonus +5, Channel Divinity 3, เตรียมสเปลได้ 11, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 1
- **เลเวล 14** Proficiency Bonus +5, ได้ความสามารถ Restoring Touch, Channel Divinity 3, เตรียมสเปลได้ 11, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 1
- **เลเวล 15** Proficiency Bonus +5, ได้ความสามารถ Subclass Feature, Channel Divinity 3, เตรียมสเปลได้ 12, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 2
- **เลเวล 16** Proficiency Bonus +5, ได้ความสามารถ ASI, Channel Divinity 3, เตรียมสเปลได้ 12, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 2
- **เลเวล 17** Proficiency Bonus +6, Channel Divinity 3, เตรียมสเปลได้ 14, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 3, Slot 5 1
- **เลเวล 18** Proficiency Bonus +6, ได้ความสามารถ 30 ฟุต (Aura Expansion) [แนะนำ], Channel Divinity 3, เตรียมสเปลได้ 14, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 3, Slot 5 1
- **เลเวล 19** Proficiency Bonus +6, ได้ความสามารถ Epic Boon Feat, Channel Divinity 3, เตรียมสเปลได้ 15, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 3, Slot 5 2
- **เลเวล 20** Proficiency Bonus +6, ได้ความสามารถ Subclass Capstone, Channel Divinity 3, เตรียมสเปลได้ 15, Slot 1 4, Slot 2 3, Slot 3 3, Slot 4 3, Slot 5 2

**Paladin ไม่มี Cantrip** ใช้เฉพาะสเปลที่ต้องใช้ Slot

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 มือแห่งการเยียวยา (Lay On Hands)

คุณมี **คลังพลังรักษา (Healing Pool) = 5 คูณ เลเวล Paladin** HP

**Bonus Action:** สัมผัสสิ่งมีชีวิต ดึง HP จากคลังมาฟื้นให้เท่าไหร่ก็ได้

**หรือ:** ใช้ 5 HP จากคลัง เพื่อ ลบสภาวะ Poisoned ออกจากเป้าหมาย

**ฟื้นคลัง:** Long Rest

- เลเวล 1 คลังพลังรักษามี 5 HP
- เลเวล 5 คลังพลังรักษามี 25 HP
- เลเวล 10 คลังพลังรักษามี 50 HP
- เลเวล 20 คลังพลังรักษามี 100 HP

Lay On Hands ไม่ฟื้นสภาวะอื่นนอกจาก Poisoned และไม่ให้ Temp HP

---

### เลเวล 1 Spellcasting

- ใช้ **Charisma** เป็นค่าร่ายเวท
- **Spell Save DC = 8 + CHA modifier + Proficiency Bonus**
- **Spell Attack = CHA modifier + Proficiency Bonus**
- เตรียมสเปลใหม่ได้ทุกครั้งที่จบ Long Rest (เลือกจากรายการ Paladin ทั้งหมด)
- **Spellcasting Focus:** **ติดบนโล่ได้! (Holy Symbol)**

---

### เลเวล 1 Weapon Mastery

เลือกอาวุธ 2 ชนิด ปลดล็อก Mastery Property

** แนะนำ:** **Longsword (Sap)** + **Javelin (Slow)** สำหรับสายดาบ+โล่
หรือ **Greatsword (Graze)** + **Maul (Topple)** สำหรับสาย 2 มือ

---

### เลเวล 2 Fighting Style

ได้ Fighting Style Feat 1 อัน

** แนะนำสำหรับ Paladin:**

- **Defense** (+1 AC) [แนะนำ] ทุกสาย Paladin ใส่เกราะเสมอ
- **+2 ดาเมจ (Dueling)** [แนะนำ] สายดาบ+โล่
- **Great Weapon Fighting** สายอาวุธ 2 มือ
- **Protection** สายปกป้องเพื่อน (Reaction ทำให้ศัตรูที่ตีเพื่อนเสียเปรียบ)
- **Blessed Warrior** [แนะนำ] ได้ Cantrip จากรายการ Cleric 2 อัน แก้ปัญหาที่ Paladin ไม่มี Cantrip

---

### เลเวล 2 การฟาดฟันศักดิ์สิทธิ์ (Paladin's Smite) ความสามารถที่โด่งดังที่สุด

กฎ 2024 เปลี่ยน Divine Smite เป็น "สเปลระดับ 1" แทนที่จะเป็นความสามารถอิสระ

**Paladin's Smite ให้:**
- สเปล Divine Smite เป็นสเปลที่เตรียมไว้เสมอ (ไม่นับโควตา)
- ร่ายได้ฟรี 1 ครั้งต่อ Long Rest โดยไม่เสีย Spell Slot

### สเปล ระดับ 1, Evocation (Divine Smite)

- **Casting Time** **Bonus Action** ใช้ทันทีหลังจากที่คุณตีโดนด้วยอาวุธ Melee หรือ Unarmed Strike
- **Range** Self
- **ผล** เพิ่มดาเมจ 2d8 Radiant ให้การโจมตีนั้น
- **เพิ่มดาเมจ** +1d8 ต่อระดับ Slot ที่สูงขึ้น
- **โบนัสพิเศษ** +1d8 เพิ่มอีก ถ้าเป้าหมายเป็น Fiend (ปีศาจ) หรือ Undead (อันเดด)

ดาเมจของ Divine Smite แยกตามระดับ Spell Slot ที่ใช้

รายการข้างล่างบอกทีละระดับ Slot ว่าได้ดาเมจเท่าไหร่ ตัวเลขในวงเล็บคือค่าเฉลี่ย
ค่าแรกคือดาเมจใส่เป้าหมายทั่วไป ค่าที่สองคือดาเมจใส่ Fiend (ปีศาจ) หรือ Undead (อันเดด) ซึ่งได้ 1d8 เพิ่ม

- ใช้ Slot ระดับ 1 ได้ 2d8 เฉลี่ย 9 ส่วนใส่ปีศาจหรืออันเดดได้ 3d8 เฉลี่ย 13.5
- ใช้ Slot ระดับ 2 ได้ 3d8 เฉลี่ย 13.5 ส่วนใส่ปีศาจหรืออันเดดได้ 4d8 เฉลี่ย 18
- ใช้ Slot ระดับ 3 ได้ 4d8 เฉลี่ย 18 ส่วนใส่ปีศาจหรืออันเดดได้ 5d8 เฉลี่ย 22.5
- ใช้ Slot ระดับ 4 ได้ 5d8 เฉลี่ย 22.5 ส่วนใส่ปีศาจหรืออันเดดได้ 6d8 เฉลี่ย 27
- ใช้ Slot ระดับ 5 ได้ 6d8 เฉลี่ย 27 ส่วนใส่ปีศาจหรืออันเดดได้ 7d8 เฉลี่ย 31.5

จุดที่เปลี่ยนจากกฎเก่า (สำคัญมาก):
- **ใช้ Bonus Action** ไม่สามารถใช้ Smite หลายครั้งในเทิร์นเดียวได้อีกแล้ว (เมื่อก่อนทำได้)
- **นับเป็นสเปล** ร่ายสเปลอื่นด้วย Action ในเทิร์นเดียวกันไม่ได้ (ยกเว้น Cantrip)
- **1 ครั้งต่อเทิร์นเท่านั้น**

**กลยุทธ์:** เก็บ Slot ไว้ Smite ตอน **Critical Hit** ดาเมจคูณสอง!

---

### เลเวล 3 พลังแห่งเทพ (Channel Divinity)

ใช้พลังศักดิ์สิทธิ์เพื่อสร้างผลพิเศษ ใช้ได้ 2 ครั้ง (3 ครั้งที่เลเวล 9)
ฟื้น: 1 ครั้งเมื่อ Short Rest, ทั้งหมดเมื่อ Long Rest

ทุก Paladin ได้ 1 อย่างพื้นฐาน:

- **Divine Sense** **Bonus Action:** จนถึงจบเทิร์นหน้า คุณรู้ตำแหน่งของ Celestial, Fiend, และ Undead ทุกตัวในระยะ 60 ฟุต ที่ไม่มี Total Cover และรู้ชนิดของมัน

+ Channel Divinity เพิ่มจาก Subclass (ดูส่วน Subclass)

---

### เลเวล 5 Extra Attack

**โจมตีได้ 2 ครั้ง** เมื่อใช้ Attack action

---

### เลเวล 5 พาหนะผู้ภักดี (Faithful Steed)

- สเปล Find Steed เป็นสเปลที่เตรียมไว้เสมอ (ไม่นับโควตา)
- **ร่ายฟรี 1 ครั้งต่อ Long Rest** โดยไม่เสีย Spell Slot

---

### เลเวล 6 ออร่าแห่งการปกป้อง (Aura of Protection) Feature ที่ทรงพลังที่สุดของ Paladin

คุณและเพื่อนร่วมทีมทุกคนในระยะ 10 ฟุตจากคุณ (30 ฟุตที่เลเวล 18)
ได้โบนัสในการทอย Saving Throw ทั้งหมด เท่ากับ CHA modifier ของคุณ (ขั้นต่ำ +1)

ต้องไม่ถูก Incapacitated

ทำไมนี่คือ Feature ที่ทีมทุกทีมอยากได้:

รายการข้างล่างบอกว่า ถ้า CHA ของคุณสูงขึ้น ทั้งทีมจะได้โบนัส Saving Throw เท่าไหร่

- CHA 16 ซึ่งให้ modifier +3 ทีมได้โบนัส Saving Throw +3
- CHA 18 ซึ่งให้ modifier +4 ทีมได้โบนัส Saving Throw +4
- CHA 20 ซึ่งให้ modifier +5 ทีมได้โบนัส Saving Throw +5

+5 ในทุก Saving Throw ของทุกคนในทีม = ทีมแทบไม่โดนสเปลควบคุมของศัตรูเลย
นี่คือเหตุผลที่ผู้เล่นหลายคน Multiclass 2 เลเวล Paladin เพื่อเอา Smite หรือ 6-7 เลเวล เพื่อเอา Aura นี้

---

### เลเวล 9 ขับไล่ศัตรู (Abjure Foes)

**Channel Divinity + Magic action:** เลือกสิ่งมีชีวิตได้ถึง Prof Bonus ตัว ในระยะ 60 ฟุต
ทอย **WIS Save** ล้มเหลว = Frightened 1 นาที

ระหว่าง Frightened: ทำได้แค่ Action หรือ Bonus Action อย่างใดอย่างหนึ่ง และ เคลื่อนที่ไม่ได้
(จบทันทีเมื่อได้รับดาเมจ)

---

### เลเวล 10 ออร่าแห่งความกล้าหาญ (Aura of Courage)

คุณและเพื่อนร่วมทีมในระยะ Aura ของคุณ ภูมิคุ้มกันสภาวะ Frightened
(ถ้ามีสภาวะอยู่แล้วจะถูกระงับชั่วคราวขณะอยู่ในออร่า)

---

### เลเวล 11 การโจมตีเปล่งรัศมี (Radiant Strikes)

การโจมตีด้วยอาวุธ Melee และ Unarmed Strike ของคุณทุกครั้ง
เพิ่มดาเมจ 1d8 Radiant โดยอัตโนมัติ

**ทำไมดี:** ดาเมจฟรีทุกครั้ง ไม่เสียทรัพยากรอะไรเลย

- เลเวล 11 โจมตี 2 ครั้ง = +2d8 Radiant ฟรีทุกเทิร์น (~9 ดาเมจ)

---

### เลเวล 14 สัมผัสฟื้นฟู (Restoring Touch)

**เมื่อใช้ Lay On Hands** คุณสามารถใช้ 5 HP จากคลัง เพื่อลบสภาวะ 1 อย่าง:
Blinded, Charmed, Deafened, Frightened, Paralyzed, หรือ Stunned
(ลบได้หลายอย่างในครั้งเดียว โดยจ่าย 5 HP ต่อสภาวะ)

---

### เลเวล 18 ขยายออร่า (Aura Expansion)

ระยะ Aura ทั้งหมดของคุณเพิ่มจาก 10 ฟุต เป็น 30 ฟุต

---

## Subclasses (Sacred Oath) เลือกที่เลเวล 3

Paladin มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ เลเวล 3, 7, 15, 20
ทุก Subclass ให้ "Oath Spells" ที่เตรียมไว้เสมอ (ไม่นับโควตา)

---

### 1. Oath of Devotion คำสาบานแห่งความภักดี

**ธีม:** อัศวินผู้ยึดมั่นในเกียรติ ความยุติธรรม และความจริง (Paladin แบบคลาสสิก)

**Oath Spells:**

- เลเวล 3 ได้ Protection from Evil and Good, Shield of Faith
- เลเวล 5 ได้ Aid, Zone of Truth
- เลเวล 9 ได้ Beacon of Hope, Dispel Magic
- เลเวล 13 ได้ Freedom of Movement, Guardian of Faith
- เลเวล 17 ได้ Commune, Flame Strike

**เลเวล 3 Sacred Weapon (Channel Divinity)**

**Bonus Action:** อาวุธของคุณเปล่งแสง 10 นาที:
- **บวก CHA modifier ในการทอยโจมตี** (ขั้นต่ำ +1)
- อาวุธนับเป็น **Magical**
- เปล่งแสง Bright Light 20 ฟุต + Dim Light 20 ฟุต

**เลเวล 7 Aura of Devotion**

[แนะนำ] คุณและเพื่อนในระยะ Aura ภูมิคุ้มกันสภาวะ Charmed

**เลเวล 15 Smite of Protection**

[แนะนำ] เมื่อคุณร่าย Divine Smite คุณและเพื่อนในระยะ Aura ได้ Half Cover จนกว่าจะเริ่มเทิร์นหน้าของคุณ

**เลเวล 20 Holy Nimbus**

**Bonus Action:** เข้าสู่สภาวะศักดิ์สิทธิ์ 10 นาที:
- เปล่ง Bright Light 30 ฟุต
- 1 ครั้ง/เทิร์น เมื่อศัตรูเริ่มเทิร์นในแสง หรือเข้ามาในแสง รับ 10 Radiant damage
- Advantage ในการทอย Saving Throw ต่อสเปลที่ร่ายโดย Fiend และ Undead
- ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5)

**แนะนำมือใหม่** Sacred Weapon แก้ปัญหาการตีพลาด เข้าใจง่าย

---

### 2. Oath of Glory คำสาบานแห่งเกียรติยศ

**ธีม:** วีรบุรุษผู้แสวงหาความยิ่งใหญ่ (แบบเทพนิยายกรีก) เน้นความเร็วและการช่วยทีม

**Oath Spells:**

- เลเวล 3 ได้ Guiding Bolt, Heroism
- เลเวล 5 ได้ Enhance Ability, Magic Weapon
- เลเวล 9 ได้ Haste, Protection from Energy
- เลเวล 13 ได้ Compulsion, Freedom of Movement
- เลเวล 17 ได้ Commune, Flame Strike

**เลเวล 3 Peerless Athlete (Channel Divinity)**

**Bonus Action:** 1 ชั่วโมง Advantage ใน Athletics และ Acrobatics Check, ยกของได้เป็น 2 เท่า และ ระยะกระโดด +10 ฟุต

**เลเวล 3 Inspiring Smite (Channel Divinity)**

**Bonus Action** [แนะนำ] ทันทีหลังร่าย Divine Smite แจก Temp HP รวม 2d8 + เลเวล Paladin ให้ตัวเองและเพื่อนในระยะ 30 ฟุต (แบ่งได้ตามใจ)

**เลเวล 7 Aura of Alacrity**

**Speed ของคุณ +10 ฟุต** [แนะนำ] และ เพื่อนที่เริ่มเทิร์นในระยะ 10 ฟุตจากคุณ ได้ Speed +10 ฟุต จนจบเทิร์น

**เลเวล 15 Glorious Defense**

**Reaction:** [แนะนำ] เมื่อคุณหรือเพื่อนในระยะ 10 ฟุตถูกโจมตี บวก CHA modifier ใน AC ของการโจมตีนั้น ถ้าทำให้พลาด โจมตีกลับ 1 ครั้งทันที ใช้ได้ Prof Bonus ครั้ง/Long Rest

**เลเวล 20 Living Legend**

**Bonus Action: 10 นาที**:
- Advantage ในการทอย Charisma Check ทั้งหมด
- 1 ครั้ง/เทิร์น: การโจมตีที่พลาด นับเป็นโดนแทน
- เมื่อทอย Saving Throw ล้มเหลว ทอยใหม่ได้ (1 ครั้ง/เทิร์น)
- ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5)

สายที่ช่วยทีมด้านความเร็วและ Temp HP ได้ดีที่สุด

---

### 3. Oath of the Ancients คำสาบานแห่งบรรพกาล

**ธีม:** อัศวินผู้พิทักษ์แสงสว่าง ชีวิต และความงามในโลก (ธีมธรรมชาติ/Fey)

**Oath Spells:**

- เลเวล 3 ได้ Ensnaring Strike, Speak with Animals
- เลเวล 5 ได้ Misty Step, Moonbeam
- เลเวล 9 ได้ Plant Growth, Protection from Energy
- เลเวล 13 ได้ Ice Storm, Stoneskin
- เลเวล 17 ได้ Commune with Nature, Tree Stride

**เลเวล 3 Nature's Wrath (Channel Divinity)**

**Magic action:** สิ่งมีชีวิตที่เลือกในระยะ 15 ฟุต ทอย **STR Save** ล้มเหลว = Restrained (ถูกตรึงด้วยเถาวัลย์) 1 นาที (ทอยใหม่ได้ทุกจบเทิร์น)

**เลเวล 7 Aura of Warding**

[แนะนำมาก] คุณและเพื่อนในระยะ Aura ได้ Resistance ต่อ Necrotic, Psychic, และ Radiant damage

**เลเวล 15 Undying Sentinel**

เมื่อ HP ลดเหลือ 0 แต่ไม่ตายทันที HP เหลือ 1 แทน [แนะนำ] (ใช้ได้ 1 ครั้ง/Long Rest) และ และคุณ ไม่แก่ตัวลงอีกต่อไป

**เลเวล 20 Elder Champion**

**Bonus Action:** แปลงร่างเป็นสิ่งมีชีวิตแห่งธรรมชาติ 10 นาที:
- ฟื้น 10 HP เมื่อเริ่มเทิร์นของคุณ
- ร่ายสเปล Paladin ที่มี Casting Time เป็น Action ใช้ Bonus Action แทนได้
- ศัตรูในระยะ 10 ฟุต เสียเปรียบในการทอย Saving Throw ต่อสเปลและ Channel Divinity ของคุณ
- ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5)

Aura of Warding เป็นหนึ่งใน Aura ที่ทรงพลังที่สุดในเกม Resistance 3 ธาตุให้ทั้งทีม

---

### 4. Oath of Vengeance คำสาบานแห่งการล้างแค้น

**ธีม:** ผู้ตามล่าความชั่วร้ายโดยไม่สนวิธีการ ดาเมจสูงที่สุด

**Oath Spells:**

- เลเวล 3 ได้ Bane, Hunter's Mark
- เลเวล 5 ได้ Hold Person, Misty Step
- เลเวล 9 ได้ Haste, Protection from Energy
- เลเวล 13 ได้ Banishment, Dimension Door
- เลเวล 17 ได้ Hold Monster, Scrying

**เลเวล 3 Vow of Enmity (Channel Divinity)**

**Bonus Action:** [แนะนำมาก] เลือกศัตรู 1 ตัวในระยะ 30 ฟุต คุณมี Advantage ในการโจมตีมันทุกครั้ง เป็นเวลา 1 นาที (ถ้ามันตายก่อน ย้ายไปตัวใหม่ได้ด้วย Bonus Action)

**เลเวล 7 Relentless Avenger**

เมื่อคุณตีโดนด้วย **Opportunity Attack** เคลื่อนที่ได้ครึ่ง Speed ทันที โดยไม่โดน Opportunity Attack

**เลเวล 15 Soul of Vengeance**

**Reaction:** [แนะนำ] เมื่อศัตรูที่ติด **Vow of Enmity** โจมตีหรือร่ายเวท โจมตีมัน 1 ครั้งทันที

**เลเวล 20 Avenging Angel**

**Bonus Action:** งอกปีก 10 นาที:
- **Fly Speed 60 ฟุต**
- ศัตรูที่เริ่มเทิร์นในระยะ 30 ฟุต ทอย WIS Save ล้มเหลว = Frightened 1 นาที และ การโจมตีของคุณต่อมันมี Advantage
- ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 5)

**สายดาเมจสูงสุด** Vow of Enmity ให้ Advantage ตลอด = คริติคอลบ่อย = Smite แรง

---

## เปรียบเทียบ 4 Subclass

- **จุดเด่น** ไม่พลาด + ต้าน Charm ความเร็ว + Temp HP Resistance 3 ธาตุ ดาเมจสูงสุด
- **ความยาก** ง่าย กลาง ง่าย ง่าย
- **ช่วยทีม** สูง สูงสุด สูงสุด ต่ำ
- **แนะนำมือใหม่** ใช่ ใช่ ใช่ ใช่ (สายตี)

---
---

## เวทของ Paladin

Paladin ใช้ค่า CHA ในการร่ายเวท

Spell Save DC เท่ากับ 8 บวก Proficiency Bonus บวก CHA modifier ส่วน Spell Attack Bonus เท่ากับ Proficiency Bonus บวก CHA modifier

รายการเวททั้งหมดของคลาสนี้ พร้อมรายละเอียดว่าร่ายด้วยอะไร ระยะเท่าไหร่ และให้ผลยังไง ย้ายไปอยู่ที่ [เวทของอัศวินศักดิ์สิทธิ์ (Paladin)](../10-spells/class-lists/paladin.md) แล้ว

ในไฟล์นั้นมีหัวข้อ "สเปลที่แนะนำสำหรับมือใหม่" อยู่ท้ายไฟล์ ซึ่งบอกว่าแต่ละระดับควรเอาอันไหนก่อน

ถ้าอยากดูสเปลเรียงตามระดับแทนที่จะเรียงตามคลาส ให้ดูที่ [รายละเอียดสเปล](../10-spells/00-spells-overview.md)

---

## คำแนะนำการสร้าง Paladin

### ค่าพลังที่ควรจัด

- STR สูงสุด (16-17) สำหรับโจมตี
- CHA สูงรอง (14-16) สำคัญมาก! กระทบ Aura of Protection และ Spell DC
- CON ปานกลาง (14)
- WIS ถ้าเหลือ
- DEX / INT ต่ำได้ (ใส่ Heavy Armor ไม่ต้องใช้ DEX)

**Paladin เป็นคลาส MAD** (ต้องดัน 3 ค่า) เลเวลต่ำอาจรู้สึกอ่อน แต่เลเวล 6+ (Aura of Protection) จะแรงมาก
**แนวทางทางเลือก: DEX Paladin** ใช้ DEX + CHA แทน แล้วใส่ Half Plate + Rapier

### Species ที่แนะนำ

- **ลูกหลานสวรรค์ (Aasimar)** [แนะนำมาก] เข้าธีมสมบูรณ์แบบ + Celestial Revelation (บินได้/ทำ Frightened) + CHA สูง
- **มนุษย์ (Human)** [แนะนำ] Feat ฟรี
- **ดรากอนบอร์น (Dragonborn)** [แนะนำ] Breath Weapon แทนการโจมตีได้ + บินได้เลเวล 5
- **ลูกหลานยักษ์ (Goliath)** Speed 35 + Giant Ancestry
- **คนแคระ (Dwarf)** +1 HP ทุกเลเวล

### Background ที่แนะนำ
**Noble** (STR/INT/CHA) [แนะนำมาก] (Background เดียวที่ให้ทั้ง STR และ CHA), **Entertainer** (STR/DEX/CHA) และ **INT/WIS/CHA เข้าธีม (Acolyte)**

### Feat ที่แนะนำ (เลเวล 4+)

- **Ability Score Improvement (CHA)** [แนะนำมาก] CHA กระทบ Aura ที่บัฟทั้งทีม
- **Great Weapon Master** [แนะนำ] สายอาวุธ 2 มือ
- **Polearm Master** [แนะนำ] Bonus Attack ด้วยด้ามอาวุธ (แต่ชนกับ Smite ที่ใช้ Bonus Action)
- **Sentinel** [แนะนำ] หยุดศัตรูที่พยายามผ่านเราไปหาเพื่อน
- **Inspiring Leader** ให้ Temp HP ทั้งทีม (ใช้ CHA)
- **War Caster** Advantage ในการรักษา Concentration

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

- ปล่อย CHA ต่ำ CHA คือหัวใจของ Paladin Aura of Protection บัฟทั้งทีม
- ใช้ Smite ทุกครั้งที่ตีโดน เก็บ Slot ไว้ใช้ตอน Critical Hit หรือกับบอส
- ลืมว่า Smite ใช้ Bonus Action (กฎ 2024) ร่ายสเปลอื่นด้วย Action ในเทิร์นเดียวกันไม่ได้
- ยืนห่างจากทีม ยืนใกล้ทีมเสมอ เพื่อให้ Aura of Protection ครอบคลุม
- ลืมใช้ Lay On Hands เป็นการรักษาที่ ไม่เสีย Spell Slot ใช้ให้หมดทุกวัน

---

## สรุป Paladin ในหนึ่งบรรทัด

ตีแรงจัดด้วย Divine Smite + ทนเหมือน Fighter + รักษาเพื่อนได้ + Aura of Protection บัฟ Save ทั้งทีม = คลาสที่ทำได้ทุกอย่าง แต่ต้องดัน STR, CHA, CON

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
