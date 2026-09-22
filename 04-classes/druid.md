# ดรูอิด (Druid)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**ดรูอิด (Druid)** คือผู้พิทักษ์ธรรมชาติที่ดึงพลังจากโลกธรรมชาติมาใช้ พวกเขา **แปลงร่างเป็นสัตว์ได้ (Wild Shape)** และมีเวทควบคุมสนามรบที่ทรงพลังที่สุดในเกม

**ไม่แนะนำสำหรับผู้เล่นครั้งแรก** เพราะต้องจำทั้งรายการเวทขนาดใหญ่ และ สถิติของสัตว์ที่แปลงร่างเป็น แต่ถ้าเล่นเป็นแล้วคือคลาสที่ยืดหยุ่นที่สุดคลาสหนึ่ง

---

## ข้อมูลพื้นฐาน (Class Table)

- **Primary Ability** **Wisdom (WIS)**
- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **HP เลเวลถัดไป** 1d8 + CON (หรือค่าคงที่ 5 + CON)
- **Saving Throw Proficiency** **Intelligence, Wisdom**
- **Armor Proficiency** Light Armor, **Medium ได้จาก Primal Order: Warden (Shield)**
- **Weapon Proficiency** Simple Weapons (Martial ได้จาก Primal Order: Warden)
- **Tool Proficiency** **Herbalism Kit**
- **Skill Proficiency** เลือก 2 จาก: **Arcana, Animal Handling, Insight, Medicine, Nature, Perception, Religion, Survival**
- **Spellcasting Ability** **Wisdom (WIS)**
- **Spellcasting Focus** **กิ่งมิสเซิลโท ไม้เท้า ไม้เท้ายอด (Druidic Focus)**
- **Subclass (Druid Circle)** เลือกที่ เลเวล 3

กฎ 2024 ยกเลิกข้อห้ามใส่เกราะโลหะแล้ว Druid ใส่เกราะโลหะได้ตามปกติ (เมื่อก่อนห้าม)

### อุปกรณ์เริ่มต้น

**เลือก A** รับของชุดนี้

- **เกราะหนัง (Leather Armor)** ให้ AC 11 บวก DEX เต็มจำนวน ทำจากหนังสัตว์จึงไม่ผิดหลักของ Druid
- **โล่ (Shield)** ให้ AC เพิ่ม 2 ต้องใช้มือถือ 1 ข้าง
- **เคียว (Sickle)** ดาเมจ 1d4 Slashing ความชำนาญ Nick แต่ Druid ไม่ได้ระบบความชำนาญอาวุธ จึงใช้เป็นอาวุธสำรองเท่านั้น
- **สื่อเวทดรูอิด (Druidic Focus)** แบบไม้เท้าไม้ เป็น Spellcasting Focus ของ Druid และใช้ตีเป็นไม้พลองได้ด้วย
- **ชุดสมุนไพร (Herbalism Kit)** ใช้ทำยาฟื้นพลังเองและช่วยรักษาพิษ
- **ชุดนักสำรวจ (Explorer's Pack)** มีที่นอน เสบียง เชือก และคบไฟครบ
- เงินติดตัว 9 GP

**เลือก B** รับเงิน 50 GP ไปซื้อของเอง

แนะนำอย่างยิ่งสำหรับมือใหม่ ให้เลือก A เพราะเงิน 50 GP ซื้อของทั้งชุดนี้ไม่ได้ครบ
ข้อควรระวัง กฎ 2024 ยังห้าม Druid ใส่เกราะหรือถือโล่ที่ทำจากโลหะ ให้เช็คกับ DM ว่าโต๊ะนี้ถือกฎนี้เคร่งแค่ไหน

---

## ความก้าวหน้าเลเวล 1 ถึง 20

- **เลเวล 1** Proficiency Bonus +2, ได้ความสามารถ Spellcasting, Druidic, Primal Order [แนะนำ], รู้ Cantrip 2, เตรียมสเปลได้ 4, Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **เลเวล 2** Proficiency Bonus +2, ได้ความสามารถ Wild Shape [แนะนำมาก], Wild Companion, Wild Shape 2, รู้ Cantrip 2, เตรียมสเปลได้ 5, Spell Slot ระดับ 1 จำนวน 3 ช่อง
- **เลเวล 3** Proficiency Bonus +2, ได้ความสามารถ Druid Circle (Subclass) [แนะนำ], Wild Shape 2, รู้ Cantrip 2, เตรียมสเปลได้ 6, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 2 ช่อง
- **เลเวล 4** Proficiency Bonus +2, ได้ความสามารถ ASI, Wild Shape 2, รู้ Cantrip 3, เตรียมสเปลได้ 7, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง
- **เลเวล 5** Proficiency Bonus +3, ได้ความสามารถ Wild Resurgence, Wild Shape 2, รู้ Cantrip 3, เตรียมสเปลได้ 9, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 2 ช่อง
- **เลเวล 6** Proficiency Bonus +3, ได้ความสามารถ Subclass Feature, Wild Shape 3, รู้ Cantrip 3, เตรียมสเปลได้ 10, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง
- **เลเวล 7** Proficiency Bonus +3, ได้ความสามารถ Elemental Fury [แนะนำ], Wild Shape 3, รู้ Cantrip 3, เตรียมสเปลได้ 11, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 1 ช่อง
- **เลเวล 8** Proficiency Bonus +3, ได้ความสามารถ ASI, Wild Shape 3, รู้ Cantrip 3, เตรียมสเปลได้ 12, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 2 ช่อง
- **เลเวล 9** Proficiency Bonus +4, Wild Shape 3, รู้ Cantrip 3, เตรียมสเปลได้ 14, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 1 ช่อง
- **เลเวล 10** Proficiency Bonus +4, ได้ความสามารถ Subclass Feature, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 15, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง
- **เลเวล 11** Proficiency Bonus +4, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 16, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง
- **เลเวล 12** Proficiency Bonus +4, ได้ความสามารถ ASI, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 16, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง
- **เลเวล 13** Proficiency Bonus +5, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 17, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง
- **เลเวล 14** Proficiency Bonus +5, ได้ความสามารถ Subclass Feature, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 17, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง
- **เลเวล 15** Proficiency Bonus +5, ได้ความสามารถ Improved Elemental Fury, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 18, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง
- **เลเวล 16** Proficiency Bonus +5, ได้ความสามารถ ASI, Wild Shape 3, รู้ Cantrip 4, เตรียมสเปลได้ 18, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง
- **เลเวล 17** Proficiency Bonus +6, Wild Shape 4, รู้ Cantrip 4, เตรียมสเปลได้ 19, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง
- **เลเวล 18** Proficiency Bonus +6, ได้ความสามารถ Beast Spells [แนะนำ], Wild Shape 4, รู้ Cantrip 4, เตรียมสเปลได้ 20, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 3 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง
- **เลเวล 19** Proficiency Bonus +6, ได้ความสามารถ Epic Boon Feat, Wild Shape 4, รู้ Cantrip 4, เตรียมสเปลได้ 21, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 3 ช่อง, Spell Slot ระดับ 6 จำนวน 2 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง
- **เลเวล 20** Proficiency Bonus +6, ได้ความสามารถ Archdruid, Wild Shape 4, รู้ Cantrip 4, เตรียมสเปลได้ 22, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 3 ช่อง, Spell Slot ระดับ 6 จำนวน 2 ช่อง, Spell Slot ระดับ 7 จำนวน 2 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 Spellcasting

- ใช้ **Wisdom** เป็นค่าร่ายเวท
- **Spell Save DC = 8 + WIS modifier + Proficiency Bonus**
- **Spell Attack = WIS modifier + Proficiency Bonus**
- เตรียมสเปลใหม่ได้ทั้งหมดทุกครั้งที่จบ Long Rest [แนะนำ] เลือกจาก รายการเวท Druid ทั้งหมด

---

### เลเวล 1 ภาษาลับดรูอิด (Druidic)

- คุณรู้ภาษา **Druidic** ภาษาลับที่มีแต่ Druid เท่านั้นที่เข้าใจ
- **ทิ้งข้อความลับไว้ได้** คนอื่นเห็นแต่ไม่รู้ว่าเป็นข้อความ (ต้องทอย **Perception DC 15** ถึงจะสังเกตเห็น) และอ่านไม่ออกหากไม่มีเวทช่วย
- **ได้ Cantrip Speak with Animals** [แนะนำ] และร่ายแบบ **Ritual** ได้ (ไม่เสีย Spell Slot)

---

### เลเวล 1 ระเบียบปฐมภูมิ (Primal Order) กฎใหม่ 2024

เลือก 1 แบบ (เปลี่ยนไม่ได้):

- **นักเวท (Magician)** Cantrip เพิ่ม 1 อัน จากรายการ Druid บวก WIS modifier (ขั้นต่ำ +1) ในการทอย Arcana และ Nature Check สายเวท เน้นร่ายเวทและความรู้
- **ผู้พิทักษ์ (Warden)** Proficiency ใน Martial Weapons และ Medium Armor สายสู้ ยืนแนวหน้าได้

**แนะนำมือใหม่: Warden** Medium Armor + Shield = AC 17 ทำให้ไม่ตายง่ายระหว่างเรียนรู้

---

### เลเวล 2 แปลงร่างสัตว์ป่า (Wild Shape) ความสามารถหลักของคลาส

**Bonus Action:** แปลงร่างเป็น **สัตว์ (Beast)** ที่คุณเคยเห็นมาก่อน

- **ระยะเวลา** ครึ่งหนึ่งของเลเวล Druid ชั่วโมง (ปัดลง, ขั้นต่ำ 1 ชั่วโมง)
- **จำนวนครั้ง** 2 ครั้ง (3 ที่เลเวล 6, 4 ที่เลเวล 17) ฟื้นทุก **Short Rest** และ **Long Rest**
- **กลับร่างเดิม** **Bonus Action** หรืออัตโนมัติเมื่อ HP ของร่างสัตว์เหลือ 0 หรือหมดสติ

### ข้อจำกัดของสัตว์ที่แปลงได้

**เลเวล 2-3 CR 1/4**

บิน, ว่ายน้ำ

**เลเวล 4-7 CR 1/2**

บิน

**เลเวล 8+ CR 1**

 (บินและว่ายน้ำได้)

### กฎขณะอยู่ในร่างสัตว์

**สิ่งที่ใช้ของสัตว์:**
- **HP และ Hit Dice** (แยกจาก HP จริงของคุณ ดาเมจส่วนเกินจึงทะลุมาที่ HP จริง)
- **AC, Speed, ค่า STR / DEX / CON**
- **ความสามารถพิเศษของสัตว์** (Darkvision, Keen Smell, Pack Tactics ฯลฯ)

**สิ่งที่ยังใช้ของคุณ:**
- **ค่า INT / WIS / CHA**
- Proficiency Bonus, Skill Proficiency, Saving Throw Proficiency ของคุณ (ใช้ค่าที่ดีกว่า)
- บุคลิก ความทรงจำ และความสามารถในการคิด

**ข้อจำกัด:**
- **ร่ายเวทไม่ได้** (จนกว่าจะถึงเลเวล 18 Beast Spells)
- **พูดภาษาไม่ได้** (แต่ยังสื่อสารด้วยท่าทางได้)
- อุปกรณ์ที่สวมใส่จะหลอมรวมเข้ากับร่าง ใช้ไม่ได้จนกว่าจะกลับร่าง (แต่ไม่หาย)

**ใช้ Wild Shape ทำอะไรได้บ้าง:**
- **สอดแนม** แปลงเป็นหนู แมว นก แล้วแอบเข้าไปในค่ายศัตรู
- **HP สำรอง** HP ของร่างสัตว์เป็นเหมือนโล่เพิ่ม
- **เดินทาง** แปลงเป็นม้าให้เพื่อนขี่ / เป็นปลาว่ายข้ามแม่น้ำ
- **สู้** เฉพาะ **Circle of the Moon** เท่านั้นที่ Wild Shape ใช้สู้ได้จริง

---

### เลเวล 2 เพื่อนร่วมทางแห่งป่า (Wild Companion)

ใช้ Wild Shape 1 ครั้ง เพื่อร่ายสเปล Find Familiar โดยไม่เสีย Spell Slot และไม่ต้องใช้ Material Component
(Familiar ที่ได้จะหายไปเมื่อคุณ Long Rest)

Familiar ใช้ Help action ให้คุณหรือเพื่อนได้ Advantage คุ้มมากกับการเสีย Wild Shape 1 ครั้ง

---

### เลเวล 5 พลังป่าคืนกลับ (Wild Resurgence)

- **1 ครั้งต่อเทิร์น:** ถ้า Wild Shape เหลือ 0 ครั้ง ใช้ Spell Slot 1 ช่อง เพื่อฟื้น Wild Shape 1 ครั้ง (ไม่ใช้ Action)
- **หรือ 1 ครั้งต่อ Long Rest:** ใช้ Wild Shape 1 ครั้ง เพื่อฟื้น Spell Slot ระดับ 1

---

### เลเวล 7 ความเกรี้ยวกราดแห่งธาตุ (Elemental Fury)

เลือก 1 แบบ (เปลี่ยนไม่ได้):

- **Potent Spellcasting** บวก WIS modifier ในดาเมจของ Cantrip ทุกอัน
- **Primal Strike** 1 ครั้ง/เทิร์น: เมื่อคุณตีโดนด้วย **อาวุธ** หรือ **การโจมตีของร่างสัตว์ (Wild Shape)** เพิ่มดาเมจ 1d8 เป็น Cold, Fire, Lightning, หรือ Thunder

Circle of the Moon เลือก Primal Strike และ Circle อื่น ๆ เลือก Potent Spellcasting

---

### เลเวล 15 Improved Elemental Fury

**Potent Spellcasting:** ระยะของ Cantrip ที่มีระยะ 10 ฟุตขึ้นไป เพิ่มขึ้นเป็น 2 เท่า
**Primal Strike:** ดาเมจเพิ่มเป็น 2d8

---

### เลเวล 18 เวทมนตร์แห่งสัตว์ (Beast Spells)

คุณสามารถร่ายเวทได้ในขณะที่อยู่ในร่าง Wild Shape
(ยังไม่สามารถใช้องค์ประกอบ **Material** ที่ระบุราคาหรือถูกใช้ไปได้)

---

### เลเวล 20 อัครดรูอิด (Archdruid) Capstone

- **Wild Shape ใช้ได้ไม่จำกัดครั้ง** [แนะนำ] (ยังใช้ **Bonus Action** เหมือนเดิม)
- เมื่อทอย Initiative ฟื้น Spell Slot ที่ใช้ไปแล้ว รวมระดับไม่เกิน WIS modifier [แนะนำ] (ใช้ได้ 1 ครั้ง/Long Rest)
- **Longevity (อายุยืน):** [แนะนำ] ทุกครั้งที่จบ Long Rest คุณสามารถลดอายุร่างกายลง 1d10 ปี (แต่ไม่ต่ำกว่าวัยผู้ใหญ่)

---

## Subclasses (Druid Circle) เลือกที่เลเวล 3

Druid มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ เลเวล 3, 6, 10, 14

---

### 1. Circle of the Land วงแหวนแห่งผืนดิน

**ธีม:** Druid ผู้ผูกพันกับภูมิประเทศหนึ่ง ๆ สายเวทที่มีสเปลเยอะที่สุด

**เลเวล 3 Circle Spells**

[แนะนำ] เลือกภูมิประเทศ 1 แบบ (**Arid / Polar / Temperate / Tropical**) ได้สเปลชุดนั้น เตรียมไว้เสมอ (เปลี่ยนภูมิประเทศได้ตอน Long Rest)

**เลเวล 3 Land's Aid**

**ใช้ Wild Shape 1 ครั้ง:** [แนะนำ] เลือกจุดในระยะ 60 ฟุต ทรงกลม 10 ฟุต ศัตรูทอย **CON Save** ล้มเหลว = 2d6 Necrotic (สำเร็จ = ครึ่ง) และ และเพื่อน 1 คนในพื้นที่ฟื้น 2d6 HP

**เลเวล 6 Natural Recovery**

[แนะนำมาก] และ ร่ายสเปล Circle Spell 1 อันได้ฟรี โดยไม่เสีย Slot (1 ครั้ง/Long Rest)
- หลัง Short Rest: ฟื้น Spell Slot รวมระดับไม่เกินครึ่งเลเวล Druid (1 ครั้ง/Long Rest)

**เลเวล 10 Nature's Ward**

**ภูมิคุ้มกันสภาวะ Poisoned** [แนะนำ] และ Resistance ต่อดาเมจธาตุตามภูมิประเทศที่เลือก (Arid=Fire, Polar=Cold, Temperate=Lightning, Tropical=Poison)

**เลเวล 14 Nature's Sanctuary**

**ใช้ Wild Shape 1 ครั้ง:** [แนะนำมาก] สร้างพื้นที่ศักดิ์สิทธิ์รัศมี 15 ฟุต 1 นาที คุณและเพื่อนในพื้นที่ได้ Half Cover และ Resistance ต่อธาตุของภูมิประเทศ

**Circle Spells ตามภูมิประเทศ**

คุณเลือกภูมิประเทศ 1 แบบจาก 4 แบบ แล้วได้สเปลของภูมิประเทศนั้นเป็นสเปลที่เตรียมไว้เสมอ
สเปลเหล่านี้ไม่นับโควตาการเตรียมสเปลปกติ และเปลี่ยนภูมิประเทศได้ทุกครั้งที่จบ Long Rest
ข้างล่างแยกเป็นหัวข้อย่อยของแต่ละภูมิประเทศ แล้วบอกทีละเลเวลว่าได้สเปลอะไร

**ภูมิประเทศแห้งแล้ง (Arid)** ธาตุประจำคือ Fire

- เลเวล 3 ได้ Burning Hands, Blur, Fire Bolt และ Fireball
- เลเวล 5 ได้ Blight
- เลเวล 7 ได้ Wall of Stone
- เลเวล 9 ได้ Wall of Fire

**ภูมิประเทศขั้วโลก (Polar)** ธาตุประจำคือ Cold

- เลเวล 3 ได้ Fog Cloud, Hold Person, Ray of Frost และ Sleet Storm
- เลเวล 5 ได้ Ice Storm
- เลเวล 7 ได้ Cone of Cold
- เลเวล 9 ได้ Wall of Ice

**ภูมิประเทศเขตอบอุ่น (Temperate)** ธาตุประจำคือ Lightning

- เลเวล 3 ได้ Misty Step, Shocking Grasp, Sleep และ Lightning Bolt
- เลเวล 5 ได้ Freedom of Movement
- เลเวล 7 ได้ Tree Stride
- เลเวล 9 ได้ Wall of Force ซึ่งบางฉบับระบุไม่ตรงกัน ให้เช็คกับหนังสือต้นฉบับ

**ภูมิประเทศเขตร้อน (Tropical)** ธาตุประจำคือ Poison

- เลเวล 3 ได้ Acid Splash, Ray of Sickness, Web และ Stinking Cloud
- เลเวล 5 ได้ Polymorph
- เลเวล 7 ได้ Insect Plague
- เลเวล 9 ได้ Wall of Thorns

**สายที่ยืดหยุ่นที่สุด** เปลี่ยนภูมิประเทศได้ทุกวันตามภารกิจ

---

### 2. Circle of the Moon วงแหวนแห่งดวงจันทร์

**ธีม:** Druid นักรบที่ต่อสู้ในร่างสัตว์ สายเดียวที่ Wild Shape สู้ได้จริง

**เลเวล 3 Circle Forms**

[แนะนำมาก] ขณะอยู่ในร่าง Wild Shape:
- แปลงเป็นสัตว์ CR สูงสุด = ครึ่งเลเวล Druid (ปัดลง) สูงกว่าปกติมาก
- **AC ขั้นต่ำ = 13 + WIS modifier**
- **Temp HP = 3 คูณ เลเวล Druid** ทุกครั้งที่แปลง

**เลเวล 3 Circle Spells**

ได้สเปล เตรียมไว้เสมอ: Lv3 Cure Wounds, Moonbeam, Starry Wisp, Lv5 Conjure Animals, Lv7 Fount of Moonlight, Lv9 Mass Cure Wounds

**เลเวล 6 Improved Circle Forms**

[แนะนำ] และ การโจมตีของร่างสัตว์นับเป็น Magical
- ใช้ WIS modifier แทนค่าของสัตว์ในการทอยโจมตีและดาเมจได้

**เลเวล 10 Moonlight Step**

**Bonus Action:** [แนะนำ] วาร์ป 30 ฟุต + การโจมตีครั้งถัดไปในเทิร์นนี้ได้ Advantage ใช้ได้ Prof Bonus ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 2)

**เลเวล 14 Lunar Form**

[แนะนำมาก] และ 1 ครั้ง/เทิร์น: การโจมตีในร่างสัตว์ เพิ่มดาเมจ 2d10 Radiant
- เมื่อใช้ Moonlight Step พาเพื่อน 1 คนวาร์ปไปด้วยได้

**แนะนำสำหรับผู้เล่นที่อยากตี** เป็นสายที่แข็งแรงและเข้าใจง่ายที่สุดของ Druid
แต่ต้องเตรียมสถิติสัตว์ไว้ล่วงหน้า ไม่งั้นเกมจะช้ามาก

---

### 3. Circle of the Sea วงแหวนแห่งท้องทะเล

**ธีม:** Druid แห่งมหาสมุทรและพายุ ดาเมจต่อเนื่องรอบตัว

**เลเวล 3 Wrath of the Sea**

Bonus Action + ใช้ Wild Shape 1 ครั้ง: [แนะนำมาก] สร้างออร่าทะเลรอบตัว 10 นาที
- **Bonus Action ทุกเทิร์น:** เลือกศัตรู 1 ตัวในระยะ 5 ฟุต ทอย **CON Save** ล้มเหลว = WIS modifier ลูก d6 Cold damage + ผลักถอย 15 ฟุต

**เลเวล 3 Circle Spells**

ได้สเปล เตรียมไว้เสมอ: Lv3 Fog Cloud, Gust of Wind, Ray of Frost, Shatter, Thunderwave, Lv5 Lightning Bolt, Water Breathing, Lv7 Control Water, Ice Storm, Lv9 Conjure Elemental, Hold Monster

**เลเวล 6 Aquatic Affinity**

[แนะนำ] และ ระยะออร่าเพิ่มเป็น 10 ฟุต
- ได้ Swim Speed เท่ากับ Speed

**เลเวล 10 Stormborn**

[แนะนำ] ระหว่างที่ออร่าทำงาน:
- ได้ Fly Speed เท่ากับ Speed
- Resistance ต่อ Cold, Lightning, และ Thunder damage

**เลเวล 14 Oceanic Gift**

**ให้ออร่าแก่เพื่อนแทนตัวเองได้** [แนะนำ] (เพื่อนใช้ Bonus Action สั่งงานเอง โดยใช้ WIS modifier ของคุณ) และ และสร้างออร่าให้ทั้งคุณและเพื่อนพร้อมกันได้ ถ้าใช้ Wild Shape 2 ครั้ง

สายที่ยืนกลางวงศัตรูแล้วดาเมจอัตโนมัติ คล้าย Spirit Guardians แต่ผลักศัตรูได้ด้วย

---

### 4. Circle of the Stars วงแหวนแห่งหมู่ดาว

**ธีม:** Druid นักโหราศาสตร์ สายที่ยืดหยุ่นและ "โกง" ที่สุด

**เลเวล 3 Star Map**

ได้ แผนที่ดาว (Spellcasting Focus), ได้สเปล **Guidance** และ **Guiding Bolt** เตรียมไว้เสมอ และ ร่าย Guiding Bolt ฟรีได้ Prof Bonus ครั้ง/Long Rest

**เลเวล 3 Starry Form**

Bonus Action + ใช้ Wild Shape 1 ครั้ง: [แนะนำมาก] แปลงเป็นร่างดาว 10 นาที (เปล่งแสง 10 ฟุต) เลือก 1 กลุ่มดาว (เปลี่ยนได้ทุกครั้งที่ใช้ Bonus Action):
- **นักธนู (Archer)** Bonus Action: ยิงลำแสง 1 ครั้ง ระยะ 60 ฟุต 1d8 + WIS Radiant
- **จอกศักดิ์สิทธิ์ (Chalice)** ทุกครั้งที่คุณร่ายสเปลรักษา เพื่อนอีก 1 คนในระยะ 30 ฟุตฟื้น 1d8 + WIS HP
- **มังกร (Dragon)** [แนะนำมาก] เมื่อทอย Concentration Save หรือ INT/WIS Check ที่ได้ผลต่ำกว่า 10 นับเป็น 10

**เลเวล 6 Cosmic Omen**

[แนะนำมาก] หลัง Long Rest ให้ทอย d6 เพื่อดูลางของวัน:
- **เลขคู่ = Weal (ลางดี)** **Reaction:** เมื่อสิ่งมีชีวิตในระยะ 30 ฟุตทอย Attack Roll / Ability Check / Save บวก 1d6
- **เลขคี่ = Woe (ลางร้าย)** **Reaction:** ลบ 1d6
- ใช้ได้ Prof Bonus ครั้ง/Long Rest

เลเวล 10 Twinkling Constellations

[แนะนำ] และ Archer และ Chalice เพิ่มดาเมจ/การรักษาเป็น 2d8
- Dragon ได้ Fly Speed 20 ฟุต (บินอยู่กับที่ได้)
- เปลี่ยนกลุ่มดาวได้ทุกครั้งที่เริ่มเทิร์นของคุณ (ฟรี)

**เลเวล 14 Full of Stars**

[แนะนำมาก] ขณะอยู่ใน Starry Form Resistance ต่อ Bludgeoning, Piercing, และ Slashing damage

สายที่ทรงพลังที่สุดในเชิงตัวเลข Cosmic Omen บวก/ลบ 1d6 ได้หลายครั้งต่อวัน และ Dragon form ทำให้ แทบไม่มีทางเสีย Concentration

---

## เปรียบเทียบ 4 Subclass

- **จุดเด่น** สเปลเยอะสุด + ฟื้น Slot สู้ในร่างสัตว์ ดาเมจรอบตัวต่อเนื่อง ควบคุมการทอยเต๋า
- **ความยาก** กลาง ยาก (ต้องจำสถิติสัตว์) ง่าย กลาง
- **ช่วยทีม** สูง ต่ำ กลาง สูงสุด
- **แนะนำมือใหม่** ใช่ ใช่ (ถ้าเตรียมสถิติไว้) ใช่ ใช่

---
---

## เวทของ Druid

Druid ใช้ค่า WIS ในการร่ายเวท

Spell Save DC เท่ากับ 8 บวก Proficiency Bonus บวก WIS modifier ส่วน Spell Attack Bonus เท่ากับ Proficiency Bonus บวก WIS modifier

รายการเวททั้งหมดของคลาสนี้ พร้อมรายละเอียดว่าร่ายด้วยอะไร ระยะเท่าไหร่ และให้ผลยังไง ย้ายไปอยู่ที่ [เวทของดรูอิด (Druid)](../10-spells/class-lists/druid.md) แล้ว

ในไฟล์นั้นมีหัวข้อ "สเปลที่แนะนำสำหรับมือใหม่" อยู่ท้ายไฟล์ ซึ่งบอกว่าแต่ละระดับควรเอาอันไหนก่อน

ถ้าอยากดูสเปลเรียงตามระดับแทนที่จะเรียงตามคลาส ให้ดูที่ [รายละเอียดสเปล](../10-spells/00-spells-overview.md)

---

## คำแนะนำการสร้าง Druid

### แนวทางที่ 1: สายเวท (Caster Druid)

- WIS 17 CON 15 DEX 14 INT 10 STR 10 CHA 8
- Primal Order: Magician
- Armor: Leather + Shield (AC 14)
- Cantrip: Guidance, Thorn Whip
- Subclass: Circle of the Stars หรือ Circle of the Land
- Elemental Fury (เลเวล 7): Potent Spellcasting

### แนวทางที่ 2: สายสู้ (Warden Druid)

- WIS 17 CON 15 DEX 14 STR 12 INT 10 CHA 8
- Primal Order: Warden (ได้ Medium Armor + Martial Weapon)
- Armor: Half Plate + Shield (AC 19)
- Cantrip: Shillelagh (ตีด้วย WIS!), Guidance
- Subclass: Circle of the Sea หรือ Circle of the Moon
- Elemental Fury (เลเวล 7): Primal Strike

### Species ที่แนะนำ

- **เอลฟ์ (Elf) สาย Wood** [แนะนำมาก] เข้าธีมเต็ม + Speed 35 + Pass Without Trace ฟรี
- **คนแคระ (Dwarf)** [แนะนำ] +1 HP ทุกเลเวล + Darkvision 120
- **มนุษย์ (Human)** [แนะนำ] Feat ฟรี
- **ฮาล์ฟลิง (Halfling)** Luck (ทอย 1 ใหม่)
- **ลูกหลานยักษ์ (Goliath)** Speed 35 + ทน

### Background ที่แนะนำ
**Guide** (DEX/CON/WIS) [แนะนำมาก] ตรงเป๊ะ + ได้ Magic Initiate (Druid), **Sage** (CON/INT/WIS), **STR/CON/WIS ได้ Tough (Farmer)** และ **Hermit** (CON/WIS/CHA)

### Feat ที่แนะนำ (เลเวล 4+)

- **Ability Score Improvement (WIS)** [แนะนำมาก] ดัน WIS ถึง 20 ก่อนอย่างอื่น
- **War Caster** [แนะนำมาก] Advantage ในการรักษา Concentration (สเปล Druid ส่วนใหญ่ใช้ Concentration)
- **Resilient (Constitution)** [แนะนำ] Proficiency ใน CON Save
- **Tough** +2 HP ต่อเลเวล
- **Telekinetic** ผลักศัตรูเป็น Bonus Action + เพิ่ม WIS
- **Fey Touched** +1 WIS + Misty Step

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

- คิดว่า Wild Shape ใช้สู้ได้ทุก Circle มีแค่ Circle of the Moon ที่สู้ได้ Circle อื่นใช้ Wild Shape เพื่อสอดแนม/หนี/แลกเป็นความสามารถอื่น
- เล่น Circle of the Moon โดยไม่เตรียมสถิติสัตว์ จดสถิติสัตว์ 2-3 ตัวที่ใช้บ่อยไว้ล่วงหน้า ไม่งั้นเกมจะช้ามาก
- ร่ายสเปล Concentration ทับกัน Druid มีสเปล Concentration เยอะมาก เลือกอันเดียวแล้วรักษาให้ดี
- ลืมว่ากฎ 2024 ใส่เกราะโลหะได้แล้ว ใส่ได้แล้ว ไม่ต้องหา Studded Leather อีก
- ไม่ใช้ Guidance นอกการต่อสู้ ใช้ทุกครั้งที่เพื่อนทอย Ability Check +1d4 ฟรี
- ปล่อย CON ต่ำ CON กระทบทั้ง HP และการรักษา Concentration

---

## สรุป Druid ในหนึ่งบรรทัด

แปลงร่างเป็นสัตว์ได้ + มีสเปลควบคุมสนามรบที่ดีที่สุด + รักษาเพื่อนได้ = คลาสที่ยืดหยุ่นที่สุดในเกม แต่ต้องจำทั้งเวทและสถิติสัตว์

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
