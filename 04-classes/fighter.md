# นักรบ (Fighter)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**ไฟท์เตอร์ / นักรบ (Fighter)** คือผู้เชี่ยวชาญการต่อสู้ทุกรูปแบบ ดาบ ธนู เกราะหนัก หรือแม้แต่เวทมนตร์ พวกเขา **โจมตีได้บ่อยที่สุดในเกม** และใช้อาวุธกับเกราะได้ทุกชนิด

**แนะนำอันดับ 1 สำหรับผู้เล่นครั้งแรก** กฎน้อยที่สุด ตัวแข็ง ตีแรง และ **ผิดพลาดได้** (เอา Feat ผิดก็ยังเล่นได้)

---

## ข้อมูลพื้นฐาน (Class Table)

- **Primary Ability** **Strength (STR)** หรือ **Dexterity (DEX)**
- **Hit Die** **d10**
- **HP เลเวล 1** **10 + CON modifier**
- **HP เลเวลถัดไป** **1d10 + CON** (หรือค่าคงที่ **6 + CON**)
- **Saving Throw Proficiency** **Strength, Constitution**
- **Armor Proficiency** **ครบทุกอย่าง (Light, Medium, Heavy Armor + Shield)**
- **Weapon Proficiency** Simple Weapons, **Martial Weapons**
- **Skill Proficiency** เลือก **2** จาก: **Acrobatics, Animal Handling, Athletics, History, Insight, Intimidation, Perception, Persuasion, Survival**
- **Weapon Mastery** **3 ชนิด** (มากที่สุดในเกม)
- **Subclass** เลือกที่ **เลเวล 3**

### อุปกรณ์เริ่มต้น

**เลือก A (สาย STR):** Chain Mail, Greatsword, Handaxe 2 อัน, Dungeoneer's Pack, **4 GP**
**เลือก B (สาย DEX):** Studded Leather Armor, Scimitar, Shortsword, Longbow + 20 Arrows, Dungeoneer's Pack, **11 GP**
**เลือก C:** **155 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

- **เลเวล 1** Proficiency Bonus +2, ได้ความสามารถ Fighting Style, Second Wind, Weapon Mastery, Second Wind 2, Weapon Mastery 3
- **เลเวล 2** Proficiency Bonus +2, ได้ความสามารถ 1 ครั้ง (Action Surge) [แนะนำ], Tactical Mind, Second Wind 2, Weapon Mastery 3
- **เลเวล 3** Proficiency Bonus +2, ได้ความสามารถ Fighter Subclass [แนะนำ], Second Wind 2, Weapon Mastery 3
- **เลเวล 4** Proficiency Bonus +2, ได้ความสามารถ Ability Score Improvement (ASI), Second Wind 3, Weapon Mastery 4
- **เลเวล 5** Proficiency Bonus +3, ได้ความสามารถ Extra Attack [แนะนำ], Tactical Shift, Second Wind 3, Weapon Mastery 4
- **เลเวล 6** Proficiency Bonus +3, ได้ความสามารถ ASI, Second Wind 3, Weapon Mastery 4
- **เลเวล 7** Proficiency Bonus +3, ได้ความสามารถ Subclass Feature, Second Wind 3, Weapon Mastery 4
- **เลเวล 8** Proficiency Bonus +3, ได้ความสามารถ ASI, Second Wind 3, Weapon Mastery 4
- **เลเวล 9** Proficiency Bonus +4, ได้ความสามารถ 1 ครั้ง (Indomitable), Tactical Master, Second Wind 3, Weapon Mastery 4
- **เลเวล 10** Proficiency Bonus +4, ได้ความสามารถ Subclass Feature, Second Wind 4, Weapon Mastery 5
- **เลเวล 11** Proficiency Bonus +4, ได้ความสามารถ โจมตี 3 ครั้ง (Two Extra Attacks) [แนะนำมาก], Second Wind 4, Weapon Mastery 5
- **เลเวล 12** Proficiency Bonus +4, ได้ความสามารถ ASI, Second Wind 4, Weapon Mastery 5
- **เลเวล 13** Proficiency Bonus +5, ได้ความสามารถ 2 ครั้ง (Indomitable), Studied Attacks, Second Wind 4, Weapon Mastery 5
- **เลเวล 14** Proficiency Bonus +5, ได้ความสามารถ ASI, Second Wind 4, Weapon Mastery 5
- **เลเวล 15** Proficiency Bonus +5, ได้ความสามารถ Subclass Feature, Second Wind 4, Weapon Mastery 5
- **เลเวล 16** Proficiency Bonus +5, ได้ความสามารถ ASI, Second Wind 4, Weapon Mastery 6
- **เลเวล 17** Proficiency Bonus +6, ได้ความสามารถ 2 ครั้ง (Action Surge), 3 ครั้ง (Indomitable), Second Wind 4, Weapon Mastery 6
- **เลเวล 18** Proficiency Bonus +6, ได้ความสามารถ Subclass Feature, Second Wind 4, Weapon Mastery 6
- **เลเวล 19** Proficiency Bonus +6, ได้ความสามารถ Epic Boon Feat, Second Wind 4, Weapon Mastery 6
- **เลเวล 20** Proficiency Bonus +6, ได้ความสามารถ โจมตี 4 ครั้ง (Three Extra Attacks), Second Wind 4, Weapon Mastery 6

**Fighter ได้ ASI/Feat มากที่สุดในเกม (7 ครั้ง)** เลเวล 4, 6, 8, 12, 14, 16 + Epic Boon เลเวล 19

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 สไตล์การต่อสู้ (Fighting Style)

คุณได้ **Fighting Style Feat 1 อัน** ตามที่เลือก
**เมื่อได้ ASI คุณสามารถเปลี่ยน Fighting Style เป็นอันอื่นได้**

** ตัวเลือกที่แนะนำ:**

- **ธนู (Archery)** [แนะนำ] **+2 ในการทอยโจมตีด้วยอาวุธระยะไกล** สายธนู/หน้าไม้
- **ป้องกัน (Defense)** [แนะนำ] **+1 AC** ตอนใส่เกราะ ทุกสายที่ใส่เกราะ
- **ประลอง (Dueling)** [แนะนำ] **+2 ดาเมจ** เมื่อถืออาวุธ Melee มือเดียว (ไม่ถืออาวุธอื่น) ดาบ+โล่
- **อาวุธใหญ่ (Great Weapon Fighting)** ทอยดาเมจได้ **1 หรือ 2 นับเป็น 3** (อาวุธ Two-Handed/Versatile) Greatsword, Greataxe
- **สองอาวุธ (Two-Weapon Fighting)** บวก Ability modifier ในดาเมจของการโจมตีมือสอง สองดาบ
- **สู้ในความมืด (Blind Fighting)** **Blindsight 10 ฟุต** สู้ในความมืด/หมอก
- **สกัดกั้น (Interception)** **Reaction:** ลดดาเมจที่เพื่อนได้รับ **1d10 + Prof Bonus** สายปกป้อง
- **ปกป้อง (Protection)** **Reaction:** ทำให้ศัตรูที่โจมตีเพื่อนในระยะ 5 ฟุตจากคุณ **เสียเปรียบ** (ต้องถือโล่) สายแทงก์
- **อาวุธขว้าง (Thrown Weapon Fighting)** **+2 ดาเมจ** เมื่อขว้างอาวุธ สายขว้าง
- **มือเปล่า (Unarmed Fighting)** Unarmed Strike ทำ **1d6** (1d8 ถ้าไม่ถืออาวุธ/โล่) สายต่อย

 ดูรายละเอียดทั้งหมดใน [Fighting Styles](../05-feats/fighting-styles.md)

---

### เลเวล 1 ลมหายใจที่สอง (Second Wind)

**Bonus Action:** ฟื้น HP เท่ากับ **1d10 + เลเวล Fighter**

**จำนวนครั้ง:** เริ่ม **2 ครั้ง** (เพิ่มเป็น 3 ที่เลเวล 4, 4 ที่เลเวล 10)
**ฟื้น:** **1 ครั้งเมื่อ Short Rest** และ **ทั้งหมดเมื่อ Long Rest**

**ทำไมดี:** รักษาตัวเองได้โดยไม่เสีย Action หลัก ยังตีในเทิร์นเดียวกันได้

---

### เลเวล 1 ความชำนาญอาวุธ (Weapon Mastery)

เลือกอาวุธ **3 ชนิด** ปลดล็อก **Mastery Property**
**เปลี่ยนตัวเลือกได้ทุกครั้งที่จบ Long Rest**

** ชุด Mastery ที่แนะนำ:**

- **สายอาวุธ 2 มือ (STR)** **Greatsword (Graze)** + **Maul (Topple)** + **Handaxe (Vex)**
- **สายดาบ+โล่ (STR)** **Longsword (Sap)** + **Battleaxe (Topple)** + **Javelin (Slow)**
- **สายธนู (DEX)** **Longbow (Slow)** + **Shortbow (Vex)** + **Rapier (Vex)**
- **สายสองอาวุธ (DEX)** **Scimitar (Nick)** + **Shortsword (Vex)** + **Rapier (Vex)**

**Nick มีค่ามาก** ทำให้โจมตีมือสองได้โดย**ไม่ต้องใช้ Bonus Action** = เอา Bonus Action ไปทำอย่างอื่นได้

 ดู Mastery ทั้ง 8 แบบใน [อุปกรณ์และอาวุธ](../01-basics/08-equipment.md)

---

### เลเวล 2 พลังฉับพลัน (Action Surge) Feature ที่โด่งดังที่สุดของ Fighter

**ในเทิร์นของคุณ ใช้ Action เพิ่มอีก 1 ครั้ง**

**จำนวนครั้ง:** **1 ครั้ง** (เพิ่มเป็น 2 ที่เลเวล 17)
**ฟื้น:** **Short Rest หรือ Long Rest**

**ทำไมนี่คือความสามารถที่ทรงพลังที่สุดของ Fighter:**

- 2 **2 ครั้ง**
- 5 **4 ครั้ง**
- 11 **6 ครั้ง**
- 20 **8 ครั้ง**

**เก็บ Action Surge ไว้ใช้กับบอส** 1 เทิร์นที่โจมตี 6-8 ครั้งสามารถจบการต่อสู้ได้เลย

---

### เลเวล 2 จิตยุทธวิธี (Tactical Mind)

**เมื่อคุณทอย Ability Check ล้มเหลว** คุณสามารถ**ใช้ Second Wind 1 ครั้ง** เพื่อ:
**ทอย d10 แล้วบวกเข้ากับผลรวมนั้น**

**ถ้ายังล้มเหลวอยู่ คุณไม่เสีย Second Wind**

**ทำไมดี:** Fighter ที่สกิลน้อย ได้โอกาสแก้ตัวในการทอยที่สำคัญ และไม่เสียอะไรถ้ายังไม่ผ่าน

---

### เลเวล 5 การโจมตีเพิ่ม (Extra Attack)

**เมื่อใช้ Attack action คุณโจมตีได้ 2 ครั้ง**

---

### เลเวล 5 ขยับตามยุทธวิธี (Tactical Shift)

**เมื่อคุณใช้ Second Wind** คุณสามารถ**เคลื่อนที่ได้ครึ่งหนึ่งของ Speed โดยไม่โดน Opportunity Attack**

---

### เลเวล 9 ไม่ยอมแพ้ (Indomitable)

**เมื่อคุณทอย Saving Throw ล้มเหลว** คุณสามารถ**ทอยใหม่ได้ พร้อมบวก +เลเวล Fighter** เข้าไปในผลใหม่ (ต้องใช้ผลใหม่)

**จำนวนครั้ง:** 1 ครั้ง (เลเวล 13 = 2 ครั้ง, เลเวล 17 = 3 ครั้ง)
**ฟื้น:** Long Rest

**ทำไมดี:** ช่วยแก้จุดอ่อนของ Fighter ที่ไม่ถนัด WIS/DEX/CHA Save **การบวกเลเวลเข้าไปทำให้แทบไม่พลาดในเลเวลสูง**

---

### เลเวล 9 ปรมาจารย์ยุทธวิธี (Tactical Master)

**เมื่อคุณโจมตีด้วยอาวุธที่คุณมี Weapon Mastery**
คุณสามารถ**เปลี่ยน Mastery ของการโจมตีครั้งนั้นเป็น Push, Sap, หรือ Slow แทนได้**

**ทำไมดี:** ยืดหยุ่นสูง เจอศัตรูตัวไหนก็เลือกผลที่เหมาะสมได้

---

### เลเวล 11 โจมตี 3 ครั้ง (Two Extra Attacks)

**เมื่อใช้ Attack action คุณโจมตีได้ 3 ครั้ง**

**นี่คือจุดที่ Fighter กลายเป็นคลาสดาเมจสูงสุดในเกม** ไม่มีคลาสอื่นตี 3 ครั้งที่เลเวล 11

---

### เลเวล 13 ศึกษาการโจมตี (Studied Attacks)

**เมื่อคุณโจมตีศัตรูแล้วพลาด** การโจมตีครั้งถัดไปของคุณต่อศัตรูตัวนั้น **มี Advantage** (จนจบเทิร์นถัดไปของคุณ)

**ทำไมดี:** พลาดครั้งเดียว = การันตีว่าครั้งถัดไปได้ Advantage ทำให้ดาเมจสม่ำเสมอมาก

---

### เลเวล 20 โจมตี 4 ครั้ง (Three Extra Attacks) Capstone

**เมื่อใช้ Attack action คุณโจมตีได้ 4 ครั้ง**

**+ Action Surge (2 ครั้ง) = โจมตีได้ 8 ครั้งใน 1 เทิร์น**

---

## Subclasses เลือกที่เลเวล 3

Fighter มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 7, 10, 15, 18**

---

### 1. Champion แชมเปี้ยน

**ธีม:** นักกีฬาผู้ฝึกฝนจนสมบูรณ์แบบ **ง่ายที่สุด เหมาะกับมือใหม่ที่สุด**

**เลเวล 3 Improved Critical**

**Critical Hit เกิดที่ 19-20** (แทน 20 อย่างเดียว) โอกาสคริติคอลเพิ่มเป็น 2 เท่า

**เลเวล 3 Remarkable Athlete**

ได้ Advantage ใน **Initiative** และ **Strength (Athletics)** Check • เมื่อทอย Advantage ในการทอย Str/Dex/Con Check สำเร็จ **เคลื่อนที่ได้ครึ่ง Speed ฟรี**

**เลเวล 7 Additional Fighting Style**

ได้ **Fighting Style Feat เพิ่มอีก 1 อัน**

**เลเวล 10 Heroic Warrior**

**ระหว่างการต่อสู้ ในตอนเริ่มเทิร์นของคุณ คุณได้ Heroic Inspiration** ถ้ายังไม่มี

**เลเวล 15 Superior Critical**

**Critical Hit เกิดที่ 18-20** โอกาสคริติคอล **15%**

**เลเวล 18 Survivor**

ได้ **Advantage ในการทอย Death Saving Throw** • และเมื่อเริ่มเทิร์นโดย HP เหลือไม่เกินครึ่ง **ฟื้น 5 + CON modifier HP**

**แนะนำมือใหม่ที่สุด** ไม่มีทรัพยากรให้จัดการ ไม่มีกฎซับซ้อน แค่ตี

---

### 2. Battle Master ปรมาจารย์การรบ

**ธีม:** นักยุทธศาสตร์ผู้เชี่ยวชาญท่าไม้ตาย **มีตัวเลือกเยอะที่สุด**

**เลเวล 3 Combat Superiority**

ได้ **Superiority Dice 4 ลูก (d8)** และเรียนรู้ **Maneuver 3 ท่า** • ฟื้นเมื่อ Short/Long Rest

**เลเวล 3 Student of War**

ได้ Proficiency ใน **Artisan's Tools 1 ชนิด** และ **Skill 1 อย่าง** จากรายการ Fighter

**เลเวล 7 Know Your Enemy**

**Bonus Action:** ศึกษาศัตรูที่มองเห็นในระยะ 30 ฟุต รู้ว่ามัน**มีค่า Ability สูงกว่าหรือต่ำกว่าคุณ** และรู้ **AC, Immunity, Resistance, Vulnerability** ของมัน ใช้ได้ Prof Bonus ครั้ง/Long Rest

**เลเวล 10 Improved Combat Superiority**

**Superiority Dice เป็น d10** และเรียนรู้ Maneuver เพิ่ม

**เลเวล 15 Relentless**

**เมื่อทอย Initiative และ Superiority Dice หมด ฟื้น 1 ลูกทันที**

**เลเวล 18 Ultimate Combat Superiority**

**Superiority Dice เป็น d12**

**Superiority Dice ที่ได้ตามเลเวล:** เลเวล 3 = 4 ลูก, เลเวล 7 = 5 ลูก, เลเวล 15 = 6 ลูก
**Maneuver ที่รู้:** เลเวล 3 = 3 ท่า, เลเวล 7 = 5 ท่า, เลเวล 10 = 7 ท่า, เลเวล 15 = 9 ท่า

#### Maneuvers ที่แนะนำ (จากทั้งหมด 16 ท่า)

- **ทุ่มล้ม (Trip Attack)** [แนะนำ] ตีโดน เพิ่มดาเมจ + เป้าหมายทอย STR Save ล้มเหลว = **Prone**
- **โจมตีแม่นยำ (Precision Attack)** [แนะนำ] **บวก Superiority Die เข้าไปในการทอยโจมตี** (ใช้หลังทอย ก่อนรู้ผล)
- **สวนกลับ (Riposte)** [แนะนำ] **Reaction:** เมื่อศัตรูตีเราพลาด โจมตีกลับทันที + เพิ่มดาเมจ
- **โจมตีข่มขวัญ (Menacing Attack)** ตีโดน เพิ่มดาเมจ + เป้าหมายทอย WIS Save ล้มเหลว = **Frightened**
- **ปลดอาวุธ (Disarming Attack)** ตีโดน เพิ่มดาเมจ + เป้าหมายทอย STR Save ล้มเหลว = **ทำอาวุธหล่น**
- **ผลัก (Pushing Attack)** ตีโดน เพิ่มดาเมจ + ผลักถอย 15 ฟุต
- **จัดตำแหน่ง (Maneuvering Attack)** ตีโดน เพิ่มดาเมจ + เพื่อน 1 คนเคลื่อนที่ครึ่ง Speed ฟรี ไม่โดน Opportunity Attack
- **ปลุกขวัญ (Rally)** **Bonus Action:** ให้ Temp HP กับเพื่อน = Superiority Die + CHA modifier
- **สั่งโจมตี (Commander's Strike)** สละการโจมตี 1 ครั้ง เพื่อนใช้ Reaction โจมตี 1 ครั้ง + เพิ่มดาเมจ
- **ย่างก้าวหลบหลีก (Evasive Footwork)** เมื่อเคลื่อนที่ **บวก Superiority Die ใน AC** จนกว่าจะหยุด

**ชุด Maneuver แนะนำสำหรับเลเวล 3:** Trip Attack + Precision Attack + Riposte

---

### 3. Eldritch Knight อัศวินเวทมนตร์

**ธีม:** นักรบผู้ผสานเวทมนตร์เข้ากับการต่อสู้ (Third Caster ใช้ **INT**)

**เลเวล 3 Spellcasting**

เรียนสเปลจากรายการ **เน้น **Abjuration** และ **Evocation** (Wizard)** ใช้ **INT** เป็นค่าร่ายเวท

**เลเวล 3 War Bond**

ผูกพันกับอาวุธ 2 ชิ้น **เรียกกลับมือด้วย Bonus Action** • ปลดอาวุธจากมือคุณไม่ได้

**เลเวล 7 War Magic**

เมื่อใช้ **Attack action** คุณสามารถ**แทนการโจมตี 1 ครั้ง ด้วยการร่าย Cantrip**

**เลเวล 10 Eldritch Strike**

เมื่อตีโดนด้วยอาวุธ เป้าหมาย **เสียเปรียบใน Saving Throw ของสเปลถัดไปที่คุณร่ายใส่มัน** (จนจบเทิร์นหน้าของคุณ)

**เลเวล 15 Arcane Charge**

เมื่อใช้ **Action Surge** **วาร์ปได้ 30 ฟุต**

**เลเวล 18 Improved War Magic**

เมื่อใช้ Attack action คุณสามารถ**แทนการโจมตี 1 ครั้ง ด้วยการร่ายสเปลระดับ 1 หรือ 2**

**ตาราง Spell Slot (Third Caster):**

- 3 2 3 2
- 4 2 4 3
- 7 2 5 4 2
- 10 **3** 6 4 3
- 13 3 8 4 3 2
- 16 3 10 4 3 3
- 19 4 12 4 3 3 1
- 20 4 13 4 3 3 1

** สเปลที่แนะนำ:**
- **Cantrip:** Booming Blade [แนะนำ], Green-Flame Blade, True Strike, Fire Bolt, Mage Hand
- **ระดับ 1:** **Shield** [แนะนำมาก] (+5 AC ด้วย Reaction), Absorb Elements, Magic Missile
- **ระดับ 2:** Misty Step [แนะนำ], Mirror Image, Shadow Blade
- **ระดับ 3:** Counterspell, Fly, Haste
- **ระดับ 4:** Greater Invisibility

---

### 4. Psi Warrior นักรบพลังจิต

**ธีม:** นักรบผู้ปลุกพลังจิต (Psionic) ตีแรงและมีลูกเล่นควบคุมสนามรบ

**เลเวล 3 Psionic Power**

ได้ **จำนวน = 2 คูณ Prof Bonus (Psionic Energy Dice)** ใช้กับความสามารถ 3 อย่าง:
- **Protective Field** **Reaction:** ลดดาเมจให้ตัวเองหรือเพื่อนในระยะ 30 ฟุต **1 เต๋า + INT modifier**
- **Psionic Strike** 1 ครั้ง/เทิร์น เมื่อตีโดน เพิ่มดาเมจ **1 เต๋า + INT modifier** เป็น **Force**
- **Telekinetic Movement** ใช้ **Bonus Action** ย้ายวัตถุหรือสิ่งมีชีวิตที่ยินยอม (ขนาด Large หรือเล็กกว่า) **ไป 30 ฟุต**

**เลเวล 7 Telekinetic Adept**

**Psi-Powered Leap** **Bonus Action:** ได้ **Fly Speed = 2 คูณ Speed** จนจบเทิร์น (ฟรี 1 ครั้ง/Long Rest หรือใช้ 1 เต๋า)
- **Telekinetic Thrust** เมื่อใช้ Psionic Strike เป้าหมายทอย **STR Save** ล้มเหลว = **Prone หรือ ผลัก 10 ฟุต**

**เลเวล 10 Guarded Mind**

**Resistance ต่อ Psychic damage** • เมื่อเริ่มเทิร์นโดยมีสภาวะ **Charmed หรือ Frightened** ใช้ 1 เต๋าเพื่อ**ลบสภาวะนั้นทันที**

**เลเวล 15 Bulwark of Force**

**Bonus Action:** ให้ตัวเองและเพื่อนได้ถึง Prof Bonus คน ในระยะ 30 ฟุต ได้ **Half Cover** เป็นเวลา 1 นาที (ฟรี 1 ครั้ง/Long Rest หรือใช้ 1 เต๋า)

**เลเวล 18 Telekinetic Master**

ได้สเปล **Telekinesis** ร่ายฟรี 1 ครั้ง/Long Rest (ใช้ INT) • ระหว่างที่รักษา Concentration ใช้ **Bonus Action** โจมตีด้วยอาวุธ 1 ครั้ง

**Psionic Energy Dice ตามเลเวล:** เลเวล 3 = d6, เลเวล 5 = d8, เลเวล 11 = d10, เลเวล 17 = d12
**ฟื้น:** 1 เต๋าเมื่อ Short Rest, ทั้งหมดเมื่อ Long Rest

---

## เปรียบเทียบ 4 Subclass

- **จุดเด่น** ง่ายสุด คริติคอลบ่อย ตัวเลือกเยอะสุด มีเวท มี Shield ป้องกันเพื่อน + Force damage
- **ความยาก** ง่ายสุด ยาก (จำ 9 ท่า) ยาก (จำเวท) กลาง
- **ค่าพลังที่ต้องมี** STR/DEX, CON STR/DEX, CON + **INT 13-16** + **INT 13-14**
- **ช่วยทีม** ต่ำ **สูง** กลาง **สูง**
- **แนะนำมือใหม่** **ใช่** หลังเล่นเป็นแล้ว ไม่ ใช่ (ถ้าชอบซัพพอร์ต)

---

## คำแนะนำการสร้าง Fighter

### แนวทางที่ 1: สายอาวุธหนัก (STR Fighter)

- STR 17 DEX 13 CON 15 INT 10 WIS 12 CHA 8
- Armor: Chain Mail Plate
- Weapon: Greatsword หรือ Maul
- Fighting Style: Great Weapon Fighting หรือ Defense
- Feat แนะนำ: Great Weapon Master [แนะนำ], ASI (STR)
- Weapon Mastery: Greatsword (Graze) + Maul (Topple) + Handaxe (Vex)

### แนวทางที่ 2: สายดาบ+โล่ (STR Fighter)

- STR 17 DEX 12 CON 16 INT 10 WIS 12 CHA 8
- Armor: Chain Mail + Shield Plate + Shield (AC 21 กับ Defense)
- Weapon: Longsword หรือ Battleaxe
- Fighting Style: Defense หรือ Dueling
- Feat แนะนำ: Sentinel [แนะนำ], Shield Master, ASI (STR)
- Weapon Mastery: Longsword (Sap) + Battleaxe (Topple) + Javelin (Slow)

### แนวทางที่ 3: สายธนู (DEX Fighter)

- STR 10 DEX 17 CON 15 INT 10 WIS 13 CHA 8
- Armor: Studded Leather Half Plate
- Weapon: Longbow (+ Rapier สำรอง)
- Fighting Style: Archery [แนะนำ] (+2 โจมตี)
- Feat แนะนำ: Sharpshooter [แนะนำ], Crossbow Expert, ASI (DEX)
- Weapon Mastery: Longbow (Slow) + Rapier (Vex) + Shortbow (Vex)

### Species ที่แนะนำ

- **Human** [แนะนำมาก] Feat ฟรี Fighter ใช้ Feat ได้คุ้มที่สุดในเกม
- **Dwarf** [แนะนำ] +1 HP ทุกเลเวล + Darkvision 120
- **Goliath** [แนะนำ] Speed 35 + Giant Ancestry (Hill's Tumble ล้มศัตรู)
- **Orc** Relentless Endurance + Adrenaline Rush
- **Elf (High)** Misty Step ช่วยเข้าถึงสายเวทศัตรู

### Background ที่แนะนำ
**Soldier** (STR/DEX/CON) [แนะนำมาก] • **Guard** (STR/INT/WIS) • **DEX/CON/INT ได้ Alert (Criminal)**

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

- ดัน **ทั้ง STR และ DEX** **เลือกอย่างเดียว** แล้วดันให้ถึง 20
- ใช้ Action Surge ทุกการต่อสู้ **เก็บไว้ใช้กับบอส** หรือจังหวะชี้เป็นชี้ตาย
- ลืมใช้ Weapon Mastery **บอก DM ทุกครั้งที่ตีโดน** ว่าใช้ Mastery อะไร
- ไม่ใช้ Second Wind จนตาย **ใช้เมื่อ HP เหลือครึ่ง** ไม่ใช่รอจนใกล้ตาย
- เลือก Eldritch Knight ตอนเป็นมือใหม่ เริ่มจาก **Champion** ก่อน

---

## สรุป Fighter ในหนึ่งบรรทัด

**โจมตีมากที่สุด (4 ครั้ง/เทิร์น) + ได้ Feat มากที่สุด (7 ครั้ง) + ใช้ได้ทุกอาวุธและเกราะ = คลาสที่ยืดหยุ่นที่สุดและง่ายที่สุดสำหรับมือใหม่**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
