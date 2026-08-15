# คลาส/อาชีพ (ภาพรวมทั้ง 12 คลาส ที่เลเวล 1) (Classes)

[กลับสารบัญ](../README.md)

---

## Class คืออะไร?

**คลาส/อาชีพ (Class)** คือ สิ่งที่กำหนดว่าตัวละครของคุณทำอะไรได้ในเกม เป็นการตัดสินใจที่สำคัญที่สุดตอนสร้างตัวละคร

Class กำหนด:
- **พลังชีวิตต่อเลเวล (Hit Die)**
- **Proficiency** ที่ได้ (อาวุธ เกราะ สกิล Saving Throw)
- **ความสามารถพิเศษ (Features)** ทุกเลเวลตั้งแต่ 1 ถึง 20
- **ใช้เวทได้หรือไม่** และใช้ค่า Ability ตัวไหน
- **สายย่อย (Subclass)** ที่เลือกได้ตอนเลเวล 3

กฎ 2024: ทุกคลาสเลือก Subclass ที่ "เลเวล 3" เหมือนกันหมด (เมื่อก่อนแต่ละคลาสต่างกัน)

---

## รายการเปรียบเทียบทั้ง 12 คลาส ที่เลเวล 1

แต่ละรายการข้างล่างบอก 7 อย่างเรียงตามลำดับเดียวกันทุกคลาส คือ Hit Die, HP ที่เลเวล 1,
ค่าพลังหลัก, Saving Throw ที่ถนัด, ความชำนาญเกราะ, ระดับการร่ายเวท และความยากสำหรับมือใหม่

- **[นักรบคลั่ง (Barbarian)](barbarian.md)** Hit Die d12 ซึ่งสูงที่สุดในเกม HP ที่เลเวล 1 คือ 12 บวก CON modifier ค่าพลังหลัก STR Saving Throw ที่ถนัด STR และ CON ความชำนาญเกราะ Light, Medium และ Shield ร่ายเวทไม่ได้ ความยากสำหรับมือใหม่ ง่าย
- **[นักดนตรีเวท (Bard)](bard.md)** Hit Die d8 HP ที่เลเวล 1 คือ 8 บวก CON modifier ค่าพลังหลัก CHA Saving Throw ที่ถนัด DEX และ CHA ความชำนาญเกราะ Light เป็น Full Caster ความยากสำหรับมือใหม่ กลาง
- **[นักบวช (Cleric)](cleric.md)** Hit Die d8 HP ที่เลเวล 1 คือ 8 บวก CON modifier ค่าพลังหลัก WIS Saving Throw ที่ถนัด WIS และ CHA ความชำนาญเกราะ Light, Medium และ Shield เป็น Full Caster ความยากสำหรับมือใหม่ กลาง
- **[ดรูอิด (Druid)](druid.md)** Hit Die d8 HP ที่เลเวล 1 คือ 8 บวก CON modifier ค่าพลังหลัก WIS Saving Throw ที่ถนัด INT และ WIS ความชำนาญเกราะ Light และ Shield เป็น Full Caster ความยากสำหรับมือใหม่ ยาก
- **[นักรบ (Fighter)](fighter.md)** Hit Die d10 HP ที่เลเวล 1 คือ 10 บวก CON modifier ค่าพลังหลัก STR หรือ DEX Saving Throw ที่ถนัด STR และ CON ความชำนาญเกราะ ทุกชนิดรวมทั้ง Shield ร่ายเวทไม่ได้ ความยากสำหรับมือใหม่ ง่ายที่สุด
- **[นักพรตหมัด (Monk)](monk.md)** Hit Die d8 HP ที่เลเวล 1 คือ 8 บวก CON modifier ค่าพลังหลัก DEX และ WIS Saving Throw ที่ถนัด STR และ DEX ไม่ใส่เกราะ ร่ายเวทไม่ได้ ความยากสำหรับมือใหม่ กลาง
- **[อัศวินศักดิ์สิทธิ์ (Paladin)](paladin.md)** Hit Die d10 HP ที่เลเวล 1 คือ 10 บวก CON modifier ค่าพลังหลัก STR และ CHA Saving Throw ที่ถนัด WIS และ CHA ความชำนาญเกราะ ทุกชนิดรวมทั้ง Shield เป็น Half Caster ความยากสำหรับมือใหม่ กลาง
- **[พรานป่า (Ranger)](ranger.md)** Hit Die d10 HP ที่เลเวล 1 คือ 10 บวก CON modifier ค่าพลังหลัก DEX และ WIS Saving Throw ที่ถนัด STR และ DEX ความชำนาญเกราะ Light, Medium และ Shield เป็น Half Caster ความยากสำหรับมือใหม่ กลาง
- **[โจร (Rogue)](rogue.md)** Hit Die d8 HP ที่เลเวล 1 คือ 8 บวก CON modifier ค่าพลังหลัก DEX Saving Throw ที่ถนัด DEX และ INT ความชำนาญเกราะ Light ร่ายเวทไม่ได้ ความยากสำหรับมือใหม่ ง่าย
- **[จอมเวทสายเลือด (Sorcerer)](sorcerer.md)** Hit Die d6 ซึ่งน้อยที่สุดในเกม HP ที่เลเวล 1 คือ 6 บวก CON modifier ค่าพลังหลัก CHA Saving Throw ที่ถนัด CON และ CHA ไม่มีความชำนาญเกราะ เป็น Full Caster ความยากสำหรับมือใหม่ กลาง
- **[ผู้ทำสัญญา (Warlock)](warlock.md)** Hit Die d8 HP ที่เลเวล 1 คือ 8 บวก CON modifier ค่าพลังหลัก CHA Saving Throw ที่ถนัด WIS และ CHA ความชำนาญเกราะ Light ใช้ระบบร่ายเวทแบบ Pact Magic ความยากสำหรับมือใหม่ กลาง
- **[พ่อมด (Wizard)](wizard.md)** Hit Die d6 ซึ่งน้อยที่สุดในเกม HP ที่เลเวล 1 คือ 6 บวก CON modifier ค่าพลังหลัก INT Saving Throw ที่ถนัด INT และ WIS ไม่มีความชำนาญเกราะ เป็น Full Caster ความยากสำหรับมือใหม่ ยาก

---

## บทบาทในทีม (Party Roles)

ทีมที่ดีควรมีบทบาทเหล่านี้ครบ (คนหนึ่งทำได้หลายบทบาท)

- **แนวหน้า (Tank / Frontline)** ยืนรับดาเมจ ปกป้องคนอื่น **Barbarian**, **Fighter**, **Paladin**
- **ตัวทำดาเมจ (Damage Dealer (DPS))** สร้างความเสียหายสูงสุด **Rogue**, **Fighter**, **Barbarian**, **Sorcerer**, **Warlock**
- **ผู้รักษา/สนับสนุน (Healer / Support)** ฟื้น HP แก้สภาวะ บัฟทีม **Cleric**, **Bard**, **Druid**, **Paladin**
- **ผู้ควบคุมสนามรบ (Controller)** จำกัดการเคลื่อนที่ ทำให้ศัตรูไร้ประสิทธิภาพ **Wizard**, **Druid**, **Bard**, **Sorcerer**
- **สายสกิล/หน่วยสอดแนม (Skill Monkey / Scout)** ซ่อนตัว หากับดัก เจรจา **Rogue**, **Bard**, **Ranger**

**ทีม 4 คนที่สมดุลที่สุด:** Fighter/Barbarian (แนวหน้า) + Cleric (รักษา) + Rogue (สกิล+ดาเมจ) + Wizard (ควบคุม)
**ไม่มี Healer จะเล่นยากมาก** ถ้าทีมไม่มีใครรักษาได้ ควรมีคนเอา Feat Healer และซื้อ Healing Potion เยอะ ๆ

---
---

# รายละเอียดแต่ละคลาส ที่เลเวล 1

---

## นักรบคลั่ง (Barbarian)

นักรบผู้ปลดปล่อยความโกรธเป็นพลัง ทนที่สุดในเกม เข้าโหมด **Rage** แล้วแทบตายยาก

### ข้อมูลพื้นฐานของนักรบคลั่ง

- **Hit Die** d12 (สูงสุดในเกม)
- **HP เลเวล 1** 12 + CON modifier
- **ค่าหลัก** **ค่ารอง: CON (STR)**
- **Saving Throw Proficiency** **STR, CON**
- **Armor** Light, Medium, **Shield**
- **Weapons** Simple, **Martial**
- **Skills** เลือก 2 จาก: Animal Handling, Athletics, Intimidation, Nature, Perception, Survival
- **Weapon Mastery** 2 ชนิด

### Features เลเวล 1 ของนักรบคลั่ง

- **Rage** [แนะนำ] **Bonus Action:** เข้าโหมดคลั่ง Resistance ต่อ Bludgeoning/Piercing/Slashing, +2 ดาเมจ STR, Advantage ใน STR Check และ STR Save ใช้ได้ 2 ครั้ง/Long Rest
- **Unarmored Defense** ตอนไม่ใส่เกราะ: **AC = 10 + DEX + CON** (ใส่โล่ได้)
- **Weapon Mastery** ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด

### อุปกรณ์เริ่มต้นของนักรบคลั่ง
Greataxe, Handaxe 4 อัน, Explorer's Pack, 15 GP หรือ 75 GP

** [อ่านรายละเอียดเต็ม เลเวล 1-20](barbarian.md)**

---

## นักดนตรีเวท (Bard)

**นักแสดงผู้ร่ายเวทด้วยเสียงเพลง** เก่งรอบด้านที่สุดในเกม รักษาได้ ควบคุมได้ เจรจาเก่ง

### ข้อมูลพื้นฐานของนักดนตรีเวท

- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **ค่าหลัก** **CHA**
- **Saving Throw Proficiency** **DEX, CHA**
- **Armor** Light
- **Weapons** Simple
- **Tools** เครื่องดนตรี 3 ชนิด
- **Skills** เลือก 3 อย่างจากสกิลทั้งหมด (อิสระที่สุดในเกม)

### Features เลเวล 1 ของนักดนตรีเวท

- **Bardic Inspiration** [แนะนำ] **Bonus Action:** ให้เพื่อนในระยะ 60 ฟุต ได้ d6 เพื่อนเอาไปบวกใน d20 Test 1 ครั้ง (ใช้หลังทอยแต่ก่อนรู้ผล) ใช้ได้ เท่ากับ CHA modifier/Long Rest
- **Spellcasting** Cantrip 2 อัน + สเปลระดับ 1 เตรียมได้ 4 อัน + Spell Slot ระดับ 1 จำนวน 2 ช่อง

### อุปกรณ์เริ่มต้นของนักดนตรีเวท
**Leather Armor, Dagger, Musical Instrument, Entertainer's Pack, 19 GP** หรือ 90 GP

** [อ่านรายละเอียดเต็ม + รายการเวท](bard.md)**

---

## นักบวช (Cleric)

**ผู้รับใช้เทพเจ้า** ผู้รักษาที่ดีที่สุด แต่ก็สู้ได้ด้วย ทีมแทบทุกทีมอยากได้

### ข้อมูลพื้นฐานของนักบวช

- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **ค่าหลัก** **WIS**
- **Saving Throw Proficiency** **WIS, CHA**
- **Armor** Light, Medium, **Shield**
- **Weapons** Simple
- **Skills** เลือก 2 จาก: History, Insight, Medicine, Persuasion, Religion

### Features เลเวล 1 ของนักบวช

- **Spellcasting** Cantrip 3 อัน + เตรียมสเปลระดับ 1 ได้ 4 อัน (เลือกจากรายการ Cleric ทั้งหมด เปลี่ยนได้ทุก Long Rest) + Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **Divine Order** [แนะนำ] เลือก 1 แบบ: **Protector** ได้ Proficiency **สายยืนหน้า (Martial Weapon + Heavy Armor)** **Thaumaturge** ได้ Cantrip เพิ่ม 1 อัน และ +WIS modifier ใน Religion/Arcana Check (สายเวท)

### อุปกรณ์เริ่มต้นของนักบวช
**Chain Shirt, Shield, Mace, Holy Symbol, Priest's Pack, 7 GP** หรือ 110 GP

** [อ่านรายละเอียดเต็ม + รายการเวท](cleric.md)**

---

## ดรูอิด (Druid)

**ผู้พิทักษ์ธรรมชาติ** แปลงร่างเป็นสัตว์ได้ (Wild Shape) และมีเวทควบคุมสนามรบที่ทรงพลัง

### ข้อมูลพื้นฐานของดรูอิด

- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **ค่าหลัก** **WIS**
- **Saving Throw Proficiency** **INT, WIS**
- **Armor** Light, **Shield**
- **Weapons** Simple
- **Tools** Herbalism Kit
- **Skills** เลือก 2 จาก: Arcana, Animal Handling, Insight, Medicine, Nature, Perception, Religion, Survival

### Features เลเวล 1 ของดรูอิด

- **Spellcasting** Cantrip 2 อัน + เตรียมสเปลระดับ 1 ได้ 4 อัน + Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **Druidic** รู้ภาษาลับ **Druidic** ทิ้งข้อความที่คนอื่นอ่านไม่ออก และรู้ Cantrip Speak with Animals (ร่ายแบบ Ritual ได้)
- **Primal Order** [แนะนำ] เลือก 1 แบบ: **Magician** ได้ Cantrip เพิ่ม 1 อัน และ +WIS modifier ใน Arcana/Nature Check **Warden** ได้ Proficiency **สายสู้ (Martial Weapon + Medium Armor)**

### อุปกรณ์เริ่มต้นของดรูอิด
**Leather Armor, Shield, Sickle, Druidic Focus, Herbalism Kit, Explorer's Pack, 9 GP** หรือ 50 GP

**Druid ยากสำหรับมือใหม่** Wild Shape (เลเวล 2) ต้องจำสถิติสัตว์ และรายการเวทใหญ่มาก

** [อ่านรายละเอียดเต็ม + รายการเวท](druid.md)**

---

## นักรบ (Fighter)

**ผู้เชี่ยวชาญการต่อสู้ทุกรูปแบบ** ตีบ่อยที่สุด ยืดหยุ่นที่สุดในสายรบ

### ข้อมูลพื้นฐานของนักรบ

- **Hit Die** d10
- **HP เลเวล 1** 10 + CON modifier
- **ค่าหลัก** **STR** หรือ **DEX**
- **Saving Throw Proficiency** **STR, CON**
- **Armor** **ทุกชนิด (Light, Medium, Heavy) + Shield**
- **Weapons** Simple, **Martial**
- **Skills** เลือก 2 จาก: Acrobatics, Animal Handling, Athletics, History, Insight, Intimidation, Perception, Persuasion, Survival
- **Weapon Mastery** 3 ชนิด (มากที่สุดในเกม)

### Features เลเวล 1 ของนักรบ

- **Fighting Style** [แนะนำ] ได้ Fighting Style Feat 1 อัน (Archery, Defense, Dueling, Great Weapon Fighting ฯลฯ)
- **Second Wind** [แนะนำ] **Bonus Action:** ฟื้น 1d10 + เลเวล Fighter HP ใช้ได้ 2 ครั้ง (ฟื้นเมื่อ Short Rest)
- **Weapon Mastery** ปลดล็อกคุณสมบัติพิเศษของอาวุธ 3 ชนิด

### อุปกรณ์เริ่มต้นของนักรบ
Chain Mail, Greatsword, Handaxe 2 อัน, Dungeoneer's Pack, 4 GP
หรือ **Studded Leather, Scimitar, Shortsword, Longbow + 20 Arrows, Dungeoneer's Pack, 11 GP** หรือ 155 GP

**แนะนำอันดับ 1 สำหรับมือใหม่** จำน้อยที่สุด ตัวแข็ง ตีแรง ผิดพลาดได้

** [อ่านรายละเอียดเต็ม เลเวล 1-20](fighter.md)**

---

## นักพรตหมัด (Monk)

**นักสู้ที่ควบคุมพลังภายใน (Ki/Focus)** เร็วที่สุด โจมตีถี่ที่สุด ไม่ต้องใช้อาวุธหรือเกราะ

### ข้อมูลพื้นฐานของนักพรตหมัด

- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **ค่าหลัก** DEX และ WIS (ต้องสูงทั้งคู่)
- **Saving Throw Proficiency** **STR, DEX**
- **Armor** ไม่มี (ไม่ควรใส่)
- **Weapons** Simple + Martial Weapon ที่มีคุณสมบัติ Light
- **Tools** เครื่องมือช่างหรือเครื่องดนตรี 1 ชนิด
- **Skills** เลือก 2 จาก: Acrobatics, Athletics, History, Insight, Religion, Stealth

### Features เลเวล 1 ของนักพรตหมัด

- **Martial Arts** [แนะนำ] Unarmed Strike ทำ 1d6 (แทน 1) ใช้ DEX แทน STR ในการโจมตีมือเปล่าและอาวุธ Monk **Bonus Action:** โจมตีมือเปล่าเพิ่ม 1 ครั้ง หลังใช้ Attack action
- **Unarmored Defense** ตอนไม่ใส่เกราะและไม่ถือโล่: **AC = 10 + DEX + WIS**

### อุปกรณ์เริ่มต้นของนักพรตหมัด
Spear, Dart 5 อัน, Artisan's Tools/Musical Instrument, Explorer's Pack, 11 GP หรือ 50 GP

**Monk ต้องดันทั้ง DEX และ WIS** ยากในเลเวลต่ำ แต่แรงมากในเลเวลสูง

** [อ่านรายละเอียดเต็ม เลเวล 1-20](monk.md)**

---

## อัศวินศักดิ์สิทธิ์ (Paladin)

**นักรบผู้สาบานตนต่ออุดมการณ์** ตีแรง ทน รักษาเพื่อน และมีออร่าบัฟทั้งทีม

### ข้อมูลพื้นฐานของอัศวินศักดิ์สิทธิ์

- **Hit Die** d10
- **HP เลเวล 1** 10 + CON modifier
- **ค่าหลัก** STR และ CHA
- **Saving Throw Proficiency** **WIS, CHA**
- **Armor** ทุกชนิด + Shield
- **Weapons** Simple, **Martial**
- **Skills** เลือก 2 จาก: Athletics, Insight, Intimidation, Medicine, Persuasion, Religion
- **Weapon Mastery** 2 ชนิด

### Features เลเวล 1 ของอัศวินศักดิ์สิทธิ์

- **Lay On Hands** [แนะนำ] มี คลัง HP = 5 คูณ เลเวล Paladin (เลเวล 1 = 5 HP) **Bonus Action:** สัมผัสแล้วฟื้น HP ให้ใคร ๆ ก็ได้, ใช้ 5 HP เพื่อแก้พิษหรือโรค 1 อย่าง และ ฟื้นเมื่อ Long Rest
- **Spellcasting** เตรียมสเปลระดับ 1 ได้ 2 อัน + Spell Slot ระดับ 1 จำนวน 2 ช่อง (ไม่มี Cantrip)
- **Weapon Mastery** ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด

### อุปกรณ์เริ่มต้นของอัศวินศักดิ์สิทธิ์
Chain Mail, Shield, Longsword, Javelin 6 อัน, Holy Symbol, Priest's Pack, 9 GP หรือ 150 GP

**เลเวล 2 (Divine Smite)** คือความสามารถที่ทำให้ Paladin ตีแรงที่สุดในเกมช่วงหนึ่ง

** [อ่านรายละเอียดเต็ม + รายการเวท](paladin.md)**

---

## พรานป่า (Ranger)

นักล่าผู้เชี่ยวชาญถิ่นทุรกันดาร ผสมการต่อสู้ การติดตาม และเวทธรรมชาติ

### ข้อมูลพื้นฐานของพรานป่า

- **Hit Die** d10
- **HP เลเวล 1** 10 + CON modifier
- **ค่าหลัก** DEX และ WIS
- **Saving Throw Proficiency** **STR, DEX**
- **Armor** Light, Medium, **Shield**
- **Weapons** Simple, **Martial**
- **Skills** เลือก 3 จาก: Animal Handling, Athletics, Insight, Investigation, Nature, Perception, Stealth, Survival
- **Weapon Mastery** 2 ชนิด

### Features เลเวล 1 ของพรานป่า

- **Spellcasting** สเปลระดับ 1 เตรียมได้ 2 อัน + Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **Favored Enemy** [แนะนำ] Hunter's Mark เป็นสเปลที่เตรียมไว้เสมอ (ไม่นับโควตา) และร่ายฟรีได้ เท่ากับ Proficiency Bonus ต่อ Long Rest โดยไม่ใช้ Spell Slot
- **Weapon Mastery** ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด

### อุปกรณ์เริ่มต้นของพรานป่า
**Studded Leather, Scimitar, Shortsword, Longbow + 20 Arrows, Druidic Focus, Explorer's Pack, 7 GP** หรือ 150 GP

** [อ่านรายละเอียดเต็ม + รายการเวท](ranger.md)**

---

## โจร/นักลอบสังหาร (Rogue)

ผู้เชี่ยวชาญการลอบเร้นและการโจมตีจุดอ่อน ดาเมจต่อครั้งสูงมาก และเก่งสกิลที่สุดในเกม

### ข้อมูลพื้นฐานของโจร/นักลอบสังหาร

- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **ค่าหลัก** **DEX**
- **Saving Throw Proficiency** **DEX, INT**
- **Armor** Light
- **Weapons** Simple + Martial Weapon ที่มีคุณสมบัติ Finesse หรือ Light
- **Tools** **Thieves' Tools**
- **Skills** เลือก 4 จาก: Acrobatics, Athletics, Deception, Insight, Intimidation, Investigation, Perception, Performance, Persuasion, Sleight of Hand, Stealth (มากที่สุดในเกม)
- **Weapon Mastery** 2 ชนิด

### Features เลเวล 1 ของโจร/นักลอบสังหาร

- **Expertise** [แนะนำ] เลือก 2 สกิล ที่มี Proficiency บวก Proficiency Bonus สองเท่า
- **Sneak Attack** [แนะนำมาก] 1 ครั้ง/เทิร์น: เพิ่มดาเมจ 1d6 เมื่อโจมตีด้วยอาวุธ Finesse หรือ Ranged และ (มี Advantage หรือ มีเพื่อนอยู่ในระยะ 5 ฟุตจากเป้าหมาย)
- **Thieves' Cant** ภาษาลับของโจร + รู้ภาษาอื่นเพิ่ม 1 ภาษา
- **Weapon Mastery** ปลดล็อกคุณสมบัติพิเศษของอาวุธ 2 ชนิด

### อุปกรณ์เริ่มต้นของโจร/นักลอบสังหาร
Leather Armor, Dagger 2 อัน, Shortsword, Shortbow + 20 Arrows, Thieves' Tools, Burglar's Pack, 8 GP หรือ 100 GP

**แนะนำสำหรับมือใหม่ที่อยากตีแรง** ไม่มีเวทให้จำ แต่ทำได้หลากหลาย

** [อ่านรายละเอียดเต็ม เลเวล 1-20](rogue.md)**

---

## จอมเวทสายเลือด (Sorcerer)

**ผู้มีเวทมนตร์ไหลอยู่ในสายเลือด** ไม่ต้องเรียน แต่ดัดแปลงเวทได้ตามใจด้วย **Metamagic**

### ข้อมูลพื้นฐานของจอมเวทสายเลือด

- **Hit Die** d6 (น้อยที่สุด)
- **HP เลเวล 1** 6 + CON modifier
- **ค่าหลัก** **CHA**
- **Saving Throw Proficiency** **CON, CHA**
- **Armor** ไม่มี
- **Weapons** Simple
- **Skills** เลือก 2 จาก: Arcana, Deception, Insight, Intimidation, Persuasion, Religion

### Features เลเวล 1 ของจอมเวทสายเลือด

- **Spellcasting** Cantrip 4 อัน (มากที่สุดที่เลเวล 1) + เตรียมสเปลระดับ 1 ได้ 2 อัน + Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **Innate Sorcery** [แนะนำ] **Bonus Action:** เข้าโหมดเวทล้น 1 นาที +1 Spell Save DC และ Advantage ในการทอย Spell Attack ทั้งหมด ใช้ได้ 2 ครั้ง/Long Rest

### อุปกรณ์เริ่มต้นของจอมเวทสายเลือด
Spear, Dagger 2 อัน, Arcane Focus, Dungeoneer's Pack, 28 GP หรือ 50 GP

** [อ่านรายละเอียดเต็ม + รายการเวท](sorcerer.md)**

---

## ผู้ทำสัญญา (Warlock)

ผู้แลกเปลี่ยนบางอย่างกับสิ่งเหนือธรรมชาติเพื่อพลัง ยิงกระสุนแรง ๆ ไม่กี่นัด แต่เติมได้ทุก Short Rest

### ข้อมูลพื้นฐานของผู้ทำสัญญา

- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **ค่าหลัก** **CHA**
- **Saving Throw Proficiency** **WIS, CHA**
- **Armor** Light
- **Weapons** Simple
- **Skills** เลือก 2 จาก: Arcana, Deception, History, Intimidation, Investigation, Nature, Religion

### Features เลเวล 1 ของผู้ทำสัญญา

- **Eldritch Invocations** [แนะนำ] ได้ Invocation 1 อย่าง ความสามารถเวทถาวรที่เลือกเองได้ (เปลี่ยนได้ตอนเลื่อนเลเวล)
- **Pact Magic** [แนะนำ] Cantrip 2 อัน + เตรียมสเปลได้ 2 อัน + Spell Slot จำนวน 1 ช่อง Slot ฟื้นทุก Short Rest [แนะนำ] และเป็นระดับสูงสุดที่มีเสมอ

### อุปกรณ์เริ่มต้นของผู้ทำสัญญา
Leather Armor, Sickle, Dagger 2 อัน, Arcane Focus, Book, Scholar's Pack, 15 GP หรือ 100 GP

**Invocation Agonizing Blast** (เลเวล 2) + Cantrip Eldritch Blast = การโจมตีระยะไกลที่ดีที่สุดในเกม

** [อ่านรายละเอียดเต็ม + รายการเวท](warlock.md)**

---

## พ่อมด (Wizard)

**ผู้ศึกษาเวทมนตร์จากตำรา** มีเวทหลากหลายที่สุดในเกม และทรงพลังที่สุดในเลเวลสูง

### ข้อมูลพื้นฐานของพ่อมด

- **Hit Die** d6
- **HP เลเวล 1** 6 + CON modifier
- **ค่าหลัก** **INT**
- **Saving Throw Proficiency** **INT, WIS**
- **Armor** ไม่มี
- **Weapons** Simple
- **Skills** เลือก 2 จาก: Arcana, History, Insight, Investigation, Medicine, Nature, Religion

### Features เลเวล 1 ของพ่อมด

- **Spellcasting** Cantrip 3 อัน + Spellbook มีสเปลระดับ 1 จำนวน 6 อัน เตรียมได้ 4 อัน + Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **Ritual Adept** [แนะนำ] ร่ายสเปลที่มีแท็ก **[Ritual]** จาก Spellbook ได้เลย โดยไม่ต้องเตรียมไว้
- **Arcane Recovery** [แนะนำ] 1 ครั้ง/วัน หลัง **Short Rest** ฟื้น Spell Slot ที่มีระดับรวมกันไม่เกินครึ่งเลเวล Wizard (ปัดขึ้น)

### อุปกรณ์เริ่มต้นของพ่อมด
Dagger 2 อัน, Arcane Focus, Robe, Spellbook, Scholar's Pack, 5 GP หรือ 55 GP

HP น้อยที่สุด (6+CON) และไม่มีเกราะ ต้องยืนหลังแนวเสมอ

** [อ่านรายละเอียดเต็ม + รายการเวท](wizard.md)**

---
---

## เลือกคลาสยังไงดี? (คู่มือตัดสินใจ)

### แผนผังช่วยเลือก

- คุณอยากเล่นแบบไหน?

- A. อยากตีศัตรูตรง ๆ ไม่อยากจำกฎเยอะ
- อยากทนที่สุด Barbarian
- อยากยืดหยุ่นที่สุด Fighter [แนะนำมือใหม่]
- อยากตีแรงจัด ๆ ตอนสำคัญ Paladin

- B. อยากลอบเร้น หลบซ่อน ตีจุดอ่อน
- ไม่อยากใช้เวท Rogue [แนะนำมือใหม่]
- อยากมีเวทบ้าง Ranger

- C. อยากใช้เวทมนตร์
- อยากมีเวทเยอะที่สุด Wizard
- อยากยิงเวทซ้ำ ๆ ไม่หมด Warlock
- อยากดัดแปลงเวท Sorcerer
- อยากรักษาเพื่อน Cleric [แนะนำมือใหม่]
- อยากอยู่กับธรรมชาติ Druid

- D. อยากเก่งทุกอย่าง เข้าสังคมเก่ง Bard

- E. อยากต่อยเตะ วิ่งเร็ว Monk

### สรุปคำแนะนำสำหรับผู้เล่นครั้งแรก

- **ง่ายที่สุด ผิดพลาดได้** **Fighter**
- **ทนที่สุด แค่กด Rage แล้วตี** **Barbarian**
- **สนุก หลากหลาย ไม่ต้องจำเวท** **Rogue**
- มีเวทแต่แก้ไขง่าย (เตรียมใหม่ทุกวัน) **Cleric**
- **อยากเป็นตัวหลักของทีมทางสังคม** **Bard**
- **หลีกเลี่ยงถ้าเป็นครั้งแรก** **ต้องจำเวทเยอะมาก (Wizard, Druid)**

---

## อ่านต่อ

- [ขั้นตอนการสร้างตัวละคร](../01-basics/04-character-creation.md)
- [Background ทั้ง 16](../03-backgrounds/00-backgrounds-overview.md)
- [กฎการร่ายเวท](../01-basics/07-spellcasting-rules.md)
- [อาวุธและ Weapon Mastery](../01-basics/08-equipment.md)

---

## สรุปคลาสทั้ง 12 ในหนึ่งบรรทัด

คลาสคือสิ่งที่กำหนดว่าตัวละครทำอะไรได้ในการต่อสู้ โดยมือใหม่ที่อยากเล่นง่ายให้เลือกนักรบ (Fighter) หรือนักรบคลั่ง (Barbarian) ส่วนคนที่อยากลองร่ายเวทให้เริ่มที่นักบวช (Cleric)

---

[กลับสารบัญ](../README.md)
