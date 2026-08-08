# ขั้นตอนการสร้างตัวละคร (Character Creation)

[กลับสารบัญ](../README.md)

---

## ภาพรวม 8 ขั้นตอน

```
1. เลือก Class (คลาส/อาชีพ) ตัดสินว่าเล่นยังไง
2. เลือก Background (ภูมิหลัง) ให้ค่าพลัง + Feat + สกิล
3. เลือก Species (เผ่าพันธุ์) ให้ความสามารถพิเศษ
4. กำหนด Ability Scores (ค่าพลัง)
5. เลือก Alignment + บุคลิก บทบาทและนิสัย
6. คำนวณค่าต่าง ๆ (HP, AC, Initiative)
7. เลือกอุปกรณ์เริ่มต้น
8. เชื่อมโยงตัวละครเข้ากับกลุ่ม
```

> **เวลาที่ใช้:** มือใหม่ประมาณ 30-60 นาที (ใช้เว็บ D&D Beyond จะเร็วกว่ามาก)

---

## ขั้นที่ 1⃣ — เลือก คลาส/อาชีพ (Class)

**Class คือสิ่งที่กำหนดว่าคุณจะ "เล่น" ยังไงในเกม** เป็นการตัดสินใจที่สำคัญที่สุด

 **อ่านรายละเอียด:** [ภาพรวมคลาสทั้ง 12](../04-classes/00-classes-overview.md)

### เลือกจากสไตล์ที่ชอบ

| ถ้าคุณอยาก... | ลองคลาสนี้ |
|---|---|
| ตีแรง ยืนหน้า ไม่ต้องคิดเยอะ | **Barbarian**, **Fighter** |
| เก่งรอบด้าน มีของเล่นเยอะ | **Bard**, **Wizard** |
| รักษาเพื่อน + สู้ได้ | **Cleric**, **Paladin** |
| ลอบเร้น ตีคริติคอลหนัก | **Rogue** |
| ปล่อยเวทระเบิดใส่ศัตรู | **Wizard**, **Sorcerer** |
| อยู่กับธรรมชาติ แปลงร่างเป็นสัตว์ | **Druid**, **Ranger** |
| ต่อยเตะ ว่องไว | **Monk** |
| ทำสัญญากับสิ่งลึกลับ | **Warlock** |

### คลาสที่แนะนำสำหรับผู้เล่นครั้งแรก

| อันดับ | คลาส | เหตุผล |
|---|---|---|
| 1 | **Fighter** | กฎน้อยที่สุด ตัวแข็ง ทำอะไรก็ไม่พลาด |
| 2 | **Barbarian** | จำแค่ "กด Rage แล้วตี" ทนมาก |
| 3 | **Rogue** | ทำอะไรได้หลากหลาย ตีแรงด้วย Sneak Attack ไม่มีเวทให้จำ |
| 4 | **Cleric** | มีเวทแต่เตรียมใหม่ได้ทุกวัน แก้ผิดง่าย ทีมต้องการเสมอ |
| | **Wizard, Druid** | ทรงพลังมาก แต่ต้องจำสเปลเยอะ อาจงงตอนเริ่มต้น |

---

## ขั้นที่ 2⃣ — เลือก ภูมิหลัง (Background)

 **อ่านรายละเอียด:** [Background ทั้ง 16 แบบ](../03-backgrounds/00-backgrounds-overview.md)

**Background ในกฎ 2024 สำคัญกว่าเดิมมาก** เพราะให้ครบ 5 อย่าง:

| ได้อะไร | รายละเอียด |
|---|---|
| **Ability Score เพิ่ม** | เลือก **+2/+1** หรือ **+1/+1/+1** จาก 3 ค่าที่กำหนด |
| **Origin Feat** | Feat ฟรี 1 อย่างตั้งแต่เลเวล 1 |
| **Skill Proficiency** | 2 สกิล |
| **Tool Proficiency** | 1 เครื่องมือ |
| **Equipment** | ชุดอุปกรณ์ หรือรับเป็น **50 GP** แทน |

> **เลือก Background ที่ให้ค่าพลังตรงกับคลาสของคุณ** เช่น Wizard ควรเลือก Background ที่มี INT อยู่ในตัวเลือก (เช่น `Sage`, `Scribe`, `Artisan`)

> **สร้าง Background เองได้** ถ้า DM อนุญาต: เลือกค่าพลัง 3 ตัว + Origin Feat 1 + สกิล 2 + Tool 1 ตามที่อยากได้

---

## ขั้นที่ 3⃣ — เลือก เผ่าพันธุ์ (Species)

 **อ่านรายละเอียด:** [Species ทั้ง 10 เผ่า](../02-species/00-species-overview.md)

> **กฎ 2024: Species ไม่ให้ค่า Ability Score แล้ว** เลือกตามความสามารถพิเศษและความชอบได้เลย ไม่ต้องกังวลว่าจะ "เลือกผิด"

Species จะกำหนด:
- **ขนาด (Size)** — Small หรือ Medium
- **ความเร็ว (Speed)** — โดยทั่วไป 30 ฟุต (Goliath ได้ 35)
- **ความสามารถพิเศษ (Special Traits)** — เช่น Darkvision, ต้านทานธาตุ, สเปลฟรี

---

## ขั้นที่ 4⃣ — กำหนด Ability Scores

 **อ่านรายละเอียด:** [Ability Scores](03-ability-scores.md)

### ลำดับการทำ

```
1. ได้ค่าดิบ 6 ค่า (Standard Array / Point Buy / ทอยเต๋า)
2. จัดค่าใส่ช่อง — ค่าสูงสุดใส่ค่าหลักของคลาส
3. บวกค่าเพิ่มจาก Background
4. แปลงเป็น Modifier
```

### ตัวอย่างเต็ม: สร้าง Wizard

```
Class: Wizard (ค่าหลัก = INT)
Background: Sage (เลือกได้จาก CON, INT, WIS)

ขั้น 1-2: ใส่ Standard Array
  STR 8 DEX 14 CON 13 INT 15 WIS 12 CHA 10

ขั้น 3: บวกจาก Sage แบบ A (INT +2, CON +1)
  STR 8 DEX 14 CON 14 INT 17 WIS 12 CHA 10

ขั้น 4: แปลงเป็น Modifier
  STR −1 DEX +2 CON +2 INT +3 WIS +1 CHA 0
```

---

## ขั้นที่ 5⃣ — Alignment และบุคลิก

### แนวทางศีลธรรม (Alignment)

ตารางแนวทาง 9 ช่อง เกิดจาก 2 แกน: **ศีลธรรม (GoodEvil)** และ **ระเบียบ (LawfulChaotic)**

| | **ยึดกฎ (Lawful)** | **กลาง (Neutral)** | **เสรี (Chaotic)** |
|---|---|---|---|
| **Good**<br>(ดี) | **Lawful Good (LG)**<br>อัศวินผู้ยึดมั่นเกียรติ | **Neutral Good (NG)**<br>ผู้ทำดีโดยไม่สนกฎ | **Chaotic Good (CG)**<br>โรบินฮู้ด |
| **Neutral**<br>(กลาง) | **Lawful Neutral (LN)**<br>ผู้พิพากษาที่ยึดกฎเหนือทุกสิ่ง | **True Neutral (N)**<br>รักษาสมดุล ไม่ฝักใฝ่ | **Chaotic Neutral (CN)**<br>เสรีชนเอาแต่ใจ |
| **Evil**<br>(ชั่ว) | **Lawful Evil (LE)**<br>จอมเผด็จการมีระเบียบ | **Neutral Evil (NE)**<br>เห็นแก่ตัวสุดขั้ว | **Chaotic Evil (CE)**<br>ตัวป่วนบ้าคลั่ง |

> **โต๊ะส่วนใหญ่ไม่แนะนำให้เล่น Evil** เพราะมักทำให้กลุ่มแตกคอ ถ้าอยากเล่นให้คุยกับ DM และเพื่อนก่อน
> Alignment เป็นแค่ **แนวทาง ไม่ใช่กฎบังคับ** ตัวละครเปลี่ยนแปลงได้ตามเรื่องราว

### บุคลิก 4 ด้าน (Personal Characteristics)

จดสั้น ๆ 1-2 บรรทัดต่อข้อ ช่วยให้เล่นบทบาทง่ายขึ้นมาก:

| หัวข้อ | ตัวอย่าง |
|---|---|
| **นิสัยเด่น (Personality Trait)** | "ฉันพูดมากเวลาประหม่า" |
| **อุดมการณ์ (Ideal)** | "อิสรภาพสำคัญกว่าทุกสิ่ง" |
| **สิ่งผูกพัน (Bond)** | "ฉันต้องหาน้องสาวที่หายไปให้เจอ" |
| **จุดอ่อน (Flaw)** | "ฉันไม่เคยปฏิเสธการพนัน" |

> **Flaw คือของขวัญให้ DM** — ยิ่งจุดอ่อนชัด DM ยิ่งเขียนเนื้อเรื่องให้ตัวละครคุณได้ง่าย

---

## ขั้นที่ 6⃣ — คำนวณค่าต่าง ๆ

| ค่า | สูตร |
|---|---|
| **พลังชีวิต (Hit Points (HP))** | **เลเวล 1:** ค่าสูงสุดของ Hit Die + CON modifier |
| **ค่าป้องกัน (Armor Class (AC))** | ขึ้นกับเกราะที่ใส่ (ดูตารางล่าง) |
| **ลำดับการเล่น (Initiative)** | **+ DEX modifier** |
| **ความเร็ว (Speed)** | จาก Species (ปกติ 30 ฟุต) |
| **โบนัสความชำนาญ (Proficiency Bonus)** | เลเวล 1-4 = **+2** |
| **การรับรู้เฉื่อย (Passive Perception)** | **10 + Perception modifier** |
| **ค่าความยากต้านเวทของเรา (Spell Save DC)** | **8 + Proficiency + ค่าร่ายเวท modifier** |
| **โบนัสโจมตีด้วยเวท (Spell Attack Bonus)** | **Proficiency + ค่าร่ายเวท modifier** |

### HP เลเวล 1 ตามคลาส

| Hit Die | คลาส | HP เลเวล 1 |
|---|---|---|
| **d12** | Barbarian | **12 + CON** |
| **d10** | Fighter, Paladin, Ranger | **10 + CON** |
| **d8** | Bard, Cleric, Druid, Monk, Rogue, Warlock | **8 + CON** |
| **d6** | Sorcerer, Wizard | **6 + CON** |

### AC ตามเกราะ

| เกราะ | สูตร AC |
|---|---|
| ไม่ใส่เกราะ | **10 + DEX** |
| **เกราะเบา (Light Armor)** | **ค่าเกราะ + DEX เต็ม** |
| **เกราะกลาง (Medium Armor)** | **ค่าเกราะ + DEX (สูงสุด +2)** |
| **เกราะหนัก (Heavy Armor)** | **ค่าเกราะคงที่ (ไม่บวก DEX)** |
| **+ Shield** (โล่) | **+2** |
| **Unarmored Defense** (Barbarian) | **10 + DEX + CON** |
| **Unarmored Defense** (Monk) | **10 + DEX + WIS** |

---

## ขั้นที่ 7⃣ — เลือกอุปกรณ์เริ่มต้น

 **อ่านรายละเอียด:** [อุปกรณ์และอาวุธ](08-equipment.md)

มี 2 ทางเลือก:

| ทาง | วิธี | เหมาะกับ |
|---|---|---|
| **A** | เอาชุดสำเร็จรูปจาก **Class + Background** | มือใหม่ — เร็วและได้ของที่ใช้ได้จริง |
| **B** | รับเป็นเงิน (จำนวนตามคลาส) แล้วไปซื้อเอง | ผู้เล่นที่รู้ว่าตัวเองอยากได้อะไร |

> **อย่าลืมของสำคัญที่มือใหม่ชอบลืม:**
> - **Rope (เชือก) 50 ฟุต** — ใช้บ่อยมาก
> - **Torch (คบไฟ) / Lantern (ตะเกียง)** — ถ้าไม่มี Darkvision
> - **ยาฟื้นพลัง (Healing Potion)** — 50 GP ช่วยชีวิตได้จริง
> - **เสบียง (Rations)** — สำหรับการเดินทาง

---

## ขั้นที่ 8⃣ — เชื่อมตัวละครเข้ากับกลุ่ม

**ขั้นตอนที่มือใหม่ข้ามบ่อยที่สุด แต่สำคัญที่สุดต่อความสนุก**

ตอบคำถามพวกนี้ร่วมกับเพื่อนใน Session Zero:

- **ทำไมตัวละครฉันถึงออกผจญภัย?** (หาเงิน / ล้างแค้น / หนีอะไรบางอย่าง / อยากรู้อยากเห็น)
- **ฉันรู้จักใครในกลุ่มมาก่อนไหม?** (เพื่อนสมัยเด็ก / เคยช่วยชีวิตกัน / เพิ่งเจอในโรงเตี๊ยม)
- **ทำไมฉันถึงยอมเสี่ยงตายเพื่อคนกลุ่มนี้?**

> **หลีกเลี่ยง "ตัวละครหมาป่าเดียวดาย"** — ตัวละครที่ไม่สนใจใครเลย เล่นไปจะทำให้ทั้งโต๊ะอึดอัดและ DM เขียนเนื้อเรื่องให้ยาก

---

## Checklist ตรวจก่อนเริ่มเล่น

```
[ ] Ability Scores 6 ค่า + Modifier ครบ
[ ] HP เลเวล 1 คำนวณแล้ว
[ ] AC คำนวณแล้ว (รวมโล่ถ้ามี)
[ ] Initiative = DEX modifier
[ ] Speed
[ ] Proficiency Bonus = +2
[ ] Saving Throw ที่ถนัด 2 อย่าง (จากคลาส) ทำเครื่องหมายแล้ว
[ ] Skill Proficiency ทั้งหมด (จากคลาส + Background + Species) ทำเครื่องหมายแล้ว
[ ] Weapon / Armor / Tool Proficiency
[ ] Class Feature ของเลเวล 1 จดครบ
[ ] Species Traits จดครบ
[ ] Origin Feat จากBackground จดแล้ว
[ ] (ถ้าใช้เวท) Cantrip + Spell + Spell Slot + Spell Save DC + Spell Attack Bonus
[ ] (ถ้ามี Weapon Mastery) เลือกอาวุธที่จะใช้ Mastery แล้ว
[ ] อุปกรณ์ทั้งหมด + เงินที่เหลือ
[ ] Passive Perception
[ ] ชื่อตัวละคร + บุคลิก 4 ด้าน + Alignment
[ ] เหตุผลที่อยู่กับกลุ่มนี้
```

---

## ตัวอย่างตัวละครสำเร็จรูป (คัดลอกใช้ได้เลย)

### Fighter — "Bran ทหารผ่านศึก"

```
Class: Fighter (Level 1) | Species: Human | Background: Soldier

Ability Scores (Standard Array + Soldier แบบ A: STR+2, CON+1)
  STR 17 (+3) DEX 14 (+2) CON 15 (+2) INT 10 (0) WIS 12 (+1) CHA 8 (−1)

HP 12 (10 + CON 2) AC 18 (Chain Mail 16 + Shield 2) Speed 30 ft
Initiative +2 Proficiency Bonus +2 Passive Perception 11

Saving Throws: STR +5, CON +4
Skills: Athletics +5, Intimidation +1 (จาก Fighter)
        Athletics, Intimidation (จาก Soldier — ทับกัน เลือกสกิลอื่นแทนได้)
        จึงเลือก Perception +3, Survival +3 แทน
Tool: Gaming Set (จาก Soldier)

Class Features:
  • Fighting Style: Defense (+1 AC ตอนใส่เกราะ) ทำให้ AC เป็น 19
  • Second Wind (ฟื้น 1d10+1 HP, ใช้ได้ 2 ครั้ง)
  • Weapon Mastery 3 อย่าง: Longsword (Sap), Handaxe (Vex), Greatsword (Graze)

Species Traits (Human): Resourceful, Skillful, Versatile (เลือก Feat: Savage Attacker)
Origin Feat (จาก Soldier): Savage Attacker

Equipment: Chain Mail, Shield, Longsword, Handaxe, Light Crossbow + 20 bolts,
           Dungeoneer's Pack, Gaming Set, 4 GP
```

### Cleric — "Elara ผู้รับใช้แสงสว่าง"

```
Class: Cleric (Level 1) | Species: Aasimar | Background: Acolyte

Ability Scores (Standard Array + Acolyte แบบ A: WIS+2, CON+1)
  STR 12 (+1) DEX 10 (0) CON 15 (+2) INT 8 (−1) WIS 17 (+3) CHA 14 (+2)

HP 10 (8 + CON 2) AC 18 (Chain Mail 16 + Shield 2) Speed 30 ft
Initiative +0 Proficiency Bonus +2 Passive Perception 13

Saving Throws: WIS +5, CHA +4
Skills: Insight +5, Religion +1, Medicine +5, Persuasion +4
Tool: Calligrapher's Supplies

Spellcasting: WIS | Spell Save DC 13 | Spell Attack +5
  Cantrips (3): Guidance, Sacred Flame, Toll the Dead
  Prepared Spells (4): Cure Wounds, Bless, Guiding Bolt, Shield of Faith
  Spell Slots: Level 1 ×2

Class Features:
  • Divine Order: Protector (ได้ Martial Weapon + Heavy Armor Proficiency)

Species Traits (Aasimar): Celestial Resistance, Darkvision 60, Healing Hands, Light Bearer
Origin Feat (จาก Acolyte): Magic Initiate (Cleric)

Equipment: Chain Mail, Shield, Mace, Holy Symbol, Priest's Pack, 7 GP
```

---

## อ่านต่อ

- [ภาพรวมคลาสทั้ง 12](../04-classes/00-classes-overview.md)
- [ภาพรวม Species](../02-species/00-species-overview.md)
- [Background ทั้ง 16](../03-backgrounds/00-backgrounds-overview.md)
