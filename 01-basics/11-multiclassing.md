# การเล่นหลายคลาส (Multiclassing)

[สารบัญ](../README.md)

---

## Multiclassing คืออะไร

**การเล่นหลายคลาส (Multiclassing)** คือการเอาเลเวลของคลาสมากกว่า 1 คลาสมารวมกันในตัวละครเดียว

> **เป็นกฎเสริม (Optional Rule)** — ต้องได้รับอนุญาตจาก DM ก่อน โต๊ะจำนวนมากไม่อนุญาต

> **ไม่แนะนำสำหรับผู้เล่นครั้งแรก** — Multiclass ทำให้ตัวละครอ่อนลงได้ง่ายกว่าที่คิด เพราะเสียความสามารถสำคัญที่ได้ตอนเลเวลสูงของคลาสเดียว

---

## เงื่อนไขค่าพลังขั้นต่ำ

**ต้องมีค่าพลังถึงเกณฑ์ของ ทั้งคลาสเดิม และ คลาสใหม่**

| คลาส | ค่าที่ต้องมีอย่างน้อย 13 |
|---|---|
| **Barbarian** | STR |
| **Bard** | CHA |
| **Cleric** | WIS |
| **Druid** | WIS |
| **Fighter** | STR **หรือ** DEX |
| **Monk** | DEX **และ** WIS |
| **Paladin** | STR **และ** CHA |
| **Ranger** | DEX **และ** WIS |
| **Rogue** | DEX |
| **Sorcerer** | CHA |
| **Warlock** | CHA |
| **Wizard** | INT |

> **ตัวอย่าง:** อยากเล่น Fighter แล้วเพิ่ม Wizard ต้องมี **(STR หรือ DEX) 13 ขึ้นไป และ INT 13 ขึ้นไป**

---

## สิ่งที่ได้และไม่ได้เมื่อเพิ่มคลาสใหม่

### สิ่งที่ได้

| ได้ | รายละเอียด |
|---|---|
| **Hit Dice** | เพิ่ม Hit Die ของคลาสใหม่ตามเลเวลที่ลง |
| **HP** | ทอย Hit Die ของคลาสใหม่ + CON modifier (ไม่ได้ค่าสูงสุดเหมือนเลเวล 1) |
| **Class Features** | ได้ Feature ของคลาสใหม่ตามเลเวลของคลาสนั้น (เริ่มจากเลเวล 1) |
| **Proficiency บางส่วน** | ดูตารางด้านล่าง — **ได้ไม่ครบเหมือนตอนเริ่มคลาสแรก** |

### สิ่งที่ไม่ได้

| ไม่ได้ | เหตุผล |
|---|---|
| **HP สูงสุดของ Hit Die** | ค่าสูงสุดได้เฉพาะเลเวล 1 ของตัวละครเท่านั้น |
| **Saving Throw Proficiency** | ได้เฉพาะจากคลาสแรกเท่านั้น |
| **จำนวน Skill เต็ม** | ได้แค่ตามตารางด้านล่าง |
| **อุปกรณ์เริ่มต้น** | ไม่ได้เลย ต้องซื้อเอง |

---

## Proficiency ที่ได้เมื่อเพิ่มคลาส (ไม่ครบเหมือนคลาสแรก)

| คลาสที่เพิ่ม | Proficiency ที่ได้ |
|---|---|
| **Barbarian** | Shield, Simple Weapons, Martial Weapons |
| **Bard** | Light Armor, **Skill 1 อย่าง** (เลือกอิสระ), เครื่องดนตรี 1 ชนิด |
| **Cleric** | Light Armor, Medium Armor, Shield |
| **Druid** | Light Armor, Shield |
| **Fighter** | Light Armor, Medium Armor, Shield, Simple Weapons, Martial Weapons |
| **Monk** | Simple Weapons, Martial Weapons ที่มีคุณสมบัติ Light |
| **Paladin** | Light Armor, Medium Armor, Shield, Simple Weapons, Martial Weapons |
| **Ranger** | Light Armor, Medium Armor, Shield, Simple Weapons, Martial Weapons, **Skill 1 อย่าง** จากรายการ Ranger |
| **Rogue** | Light Armor, Thieves' Tools, **Skill 1 อย่าง** จากรายการ Rogue |
| **Sorcerer** | ไม่ได้อะไรเลย |
| **Warlock** | Light Armor, Simple Weapons |
| **Wizard** | ไม่ได้อะไรเลย |

> **ระวังเรื่อง Heavy Armor** — ไม่มีคลาสไหนให้ Heavy Armor Proficiency ตอน Multiclass
> ถ้าอยากใส่ Plate ต้องเริ่มด้วย Fighter หรือ Paladin เป็นคลาสแรก หรือเอา Feat `Heavily Armored`

---

## กฎที่ใช้เลเวลตัวละครรวม กับกฎที่ใช้เลเวลคลาส

**นี่คือจุดที่สับสนที่สุดของ Multiclass**

| ใช้ **เลเวลตัวละครรวม** | ใช้ **เลเวลของคลาสนั้น ๆ** |
|---|---|
| **Proficiency Bonus** | Feature ทุกอย่างของคลาส (Rage, Sneak Attack, Channel Divinity) |
| **ASI / Feat** (เลเวล 4, 8, 12, 16, 19 ของ**คลาสนั้น** ไม่ใช่รวม) | ระดับ Cantrip ที่แรงขึ้น (ใช้เลเวลตัวละครรวม) |
| **ค่า XP ที่ต้องใช้เลื่อนเลเวล** | จำนวนสเปลที่เตรียมได้ |
| **ระดับ Cantrip** (แรงขึ้นที่เลเวล 5, 11, 17) | ระดับ Subclass ที่ปลดล็อก |

> **จุดที่พลาดบ่อย:** ASI ได้ตาม **เลเวลของคลาสนั้น** ไม่ใช่เลเวลรวม
> Fighter 4 / Wizard 4 = **ได้ ASI 2 ครั้ง** (Fighter เลเวล 4 ครั้งหนึ่ง, Wizard เลเวล 4 อีกครั้งหนึ่ง)
> แต่ Fighter 2 / Wizard 2 / Rogue 4 = **ได้ ASI 1 ครั้ง** (จาก Rogue เลเวล 4 เท่านั้น)

---

## Spell Slot ของ Multiclass (ส่วนที่ซับซ้อนที่สุด)

### ขั้นตอนคำนวณ

```
1. นับ "เลเวลผู้ร่ายเวท" (Spellcaster Level) จากทุกคลาสที่ใช้เวท
2. เอาผลรวมไปดูตาราง Spell Slot ของ Full Caster
3. Warlock คิดแยกต่างหาก (ไม่รวมในนี้)
```

### วิธีนับเลเวลผู้ร่ายเวท

| ประเภท | คลาส | นับเท่าไหร่ |
|---|---|---|
| **Full Caster** | Bard, Cleric, Druid, Sorcerer, Wizard | **เลเวลเต็ม** |
| **Half Caster** | Paladin, Ranger | **ครึ่งหนึ่ง (ปัดขึ้น)** |
| **Third Caster** | Eldritch Knight (Fighter), Arcane Trickster (Rogue) | **หนึ่งในสาม (ปัดขึ้น)** |
| **ไม่นับ** | Warlock | คิดแยกด้วยระบบ Pact Magic |

> **ข้อควรตรวจสอบ:** กฎ 2024 ให้ Paladin และ Ranger มีสเปลตั้งแต่เลเวล 1 (ต่างจากกฎ 2014 ที่เริ่มเลเวล 2)
> การปัดขึ้นหรือปัดลงในตารางนี้เป็นจุดที่ควร**ยืนยันกับหนังสือต้นฉบับหรือ DM** ก่อนใช้จริง

### ตัวอย่างการนับ

```
ตัวอย่างที่ 1: Wizard 5 / Cleric 3
  Wizard 5 (เต็ม) + Cleric 3 (เต็ม) = เลเวลผู้ร่ายเวท 8
  ได้ Spell Slot เท่ากับ Full Caster เลเวล 8

ตัวอย่างที่ 2: Paladin 6 / Sorcerer 2
  Paladin 6 หารสอง = 3 + Sorcerer 2 (เต็ม) = เลเวลผู้ร่ายเวท 5
  ได้ Spell Slot เท่ากับ Full Caster เลเวล 5 (มี Slot ระดับ 3)

ตัวอย่างที่ 3: Fighter (Eldritch Knight) 6 / Wizard 4
  Fighter 6 หารสาม = 2 + Wizard 4 (เต็ม) = เลเวลผู้ร่ายเวท 6
  ได้ Spell Slot เท่ากับ Full Caster เลเวล 6
```

### สิ่งสำคัญที่ต้องเข้าใจ

| ประเด็น | รายละเอียด |
|---|---|
| **Slot เป็นของกลาง แต่สเปลไม่ใช่** | คุณใช้ Slot ระดับ 5 ร่ายสเปล Cleric ก็ได้ ร่ายสเปล Wizard ก็ได้ |
| **จำนวนสเปลที่เตรียมได้คิดแยกคลาส** | Wizard 5 เตรียมได้ตามตาราง Wizard เลเวล 5 · Cleric 3 เตรียมได้ตามตาราง Cleric เลเวล 3 |
| **ค่าร่ายเวทแยกกัน** | สเปล Wizard ใช้ INT · สเปล Cleric ใช้ WIS — **Spell Save DC ต่างกัน** |
| **Slot อาจสูงกว่าสเปลที่มี** | Paladin 6 / Sorcerer 2 มี Slot ระดับ 3 แต่รู้สเปลแค่ระดับ 1 — ใช้ Slot ระดับ 3 ร่ายสเปลระดับ 1 ได้ (แรงขึ้น) |

### Warlock คิดแยกต่างหาก

> **Pact Magic Slot ของ Warlock เป็นคนละกองกับ Spell Slot ปกติ**
> ถ้าเล่น Warlock 3 / Sorcerer 5 คุณจะมี:
> - **Pact Magic Slot 2 ช่อง ระดับ 2** (ฟื้นทุก Short Rest)
> - **Spell Slot ปกติเท่ากับ Full Caster เลเวล 5** (ฟื้นเมื่อ Long Rest)
> - **ใช้ Slot ทั้งสองกองร่ายสเปลของทั้งสองคลาสได้**

---

## Feature ที่ไม่สะสมกัน

| Feature | กฎ |
|---|---|
| **Extra Attack** | **ไม่สะสม** — Fighter 5 / Ranger 5 ก็ยังโจมตี 2 ครั้ง ไม่ใช่ 3 |
| **Unarmored Defense** | **เลือกได้แค่แบบเดียว** — Barbarian (10+DEX+CON) หรือ Monk (10+DEX+WIS) |
| **Channel Divinity** | จำนวนครั้งของ Cleric และ Paladin **คิดแยกกัน** แต่ใช้ตัวเลือกร่วมกันได้ |
| **Sneak Attack** | ใช้เลเวล Rogue เท่านั้น |
| **Rage** | ใช้เลเวล Barbarian เท่านั้น |

---

## ผสมคลาสยอดนิยม (Popular Multiclass)

### ผสมที่ได้ผลจริง

| ผสม | ทำไมดี | เลเวลที่แนะนำ |
|---|---|---|
| **Paladin + Warlock** [แนะนำ] | ทั้งคู่ใช้ CHA · Warlock Slot ฟื้นทุก Short Rest เอาไป Divine Smite ได้ | Paladin 6 / Warlock 2+ |
| **Paladin + Sorcerer** | ทั้งคู่ใช้ CHA · Sorcerer แปลง Sorcery Point เป็น Slot ไป Smite | Paladin 6 / Sorcerer 6+ |
| **Fighter + Rogue** | Action Surge + Sneak Attack · ทั้งคู่ใช้ DEX | Fighter 2-3 / Rogue ที่เหลือ |
| **Fighter + Barbarian** | Action Surge + Rage · ทั้งคู่ใช้ STR/CON | Barbarian 5+ / Fighter 2 |
| **Cleric + Wizard** | เข้าถึงรายการเวทสองรายการ | Cleric 1-2 (ได้เกราะและ Shield) / Wizard ที่เหลือ |
| **Warlock + Wizard** | Warlock Slot ฟื้นเร็ว + สเปลหลากหลายของ Wizard | Warlock 2 / Wizard ที่เหลือ |
| **Rogue + Ranger** | ทั้งคู่ใช้ DEX/WIS · Sneak Attack + Hunter's Mark | Rogue ที่เหลือ / Ranger 3-5 |
| **Sorcerer + Warlock** | ทั้งคู่ใช้ CHA · เติม Sorcery Point จาก Pact Slot | Sorcerer ที่เหลือ / Warlock 2-3 |

### การ "แวะ" (Dip) — เอาแค่ 1-2 เลเวล

| แวะ | ได้อะไร | เหมาะกับ |
|---|---|---|
| **Fighter 1** | Fighting Style + Second Wind + Heavy Armor + Martial Weapons | สายเวทที่อยากใส่เกราะ |
| **Fighter 2** | + **Action Surge** (โจมตี 2 เท่าใน 1 เทิร์น) | ทุกคลาสที่ตี |
| **Cleric 1** | Light/Medium Armor + Shield + สเปล Cleric + Divine Order | Wizard, Sorcerer ที่อยากทน |
| **Warlock 2** | Pact Magic (ฟื้นทุก Short Rest) + Invocation 3 อัน | Paladin, Sorcerer |
| **Rogue 1** | Expertise 2 สกิล + Sneak Attack 1d6 | สาย DEX ทุกคลาส |
| **Rogue 2** | + **Cunning Action** (Dash/Disengage/Hide เป็น Bonus Action) | ทุกคลาสที่อยากคล่อง |
| **Barbarian 1-2** | Rage (Resistance กายภาพ) + Reckless Attack | Fighter สาย STR |
| **Sorcerer 1** | Innate Sorcery + Cantrip 4 อัน | Warlock, Bard |

> **การแวะ 1-2 เลเวลมักคุ้มกว่าการแบ่งครึ่ง** เพราะเลเวล 1-2 ของทุกคลาสให้ของเยอะที่สุด

---

## ราคาที่ต้องจ่ายเมื่อ Multiclass

| เสียอะไร | ตัวอย่าง |
|---|---|
| **ความสามารถระดับสูงของคลาสหลัก** | Wizard 20 ได้ `Wish` และ Signature Spells · Wizard 17/Fighter 3 ไม่ได้ |
| **สเปลระดับ 6-9 ช้าลงมาก** | Cleric 10 / Wizard 10 มี Slot ระดับ 6 แค่ 1 ช่อง แทนที่จะมีถึงระดับ 9 |
| **Extra Attack ครั้งที่ 2 และ 3** | Fighter 11 ตี 3 ครั้ง · Fighter 5 / Rogue 6 ตีแค่ 2 ครั้ง |
| **ค่าพลังหลักโตช้า** | ต้องแบ่ง ASI ไปดันหลายค่า |
| **Capstone เลเวล 20** | ไม่มีทางได้เลยถ้า Multiclass |

> **หลักตัดสินง่าย ๆ:** ถ้าไม่แน่ใจว่าคุ้มไหม แปลว่า**ไม่คุ้ม** — เล่นคลาสเดียวให้ถึงเลเวล 20 จะแรงกว่าเกือบทุกกรณี

---

## ตัวอย่างตัวละคร Multiclass ที่สมบูรณ์

### Paladin 6 / Warlock 4 (เลเวลตัวละคร 10)

```
ชื่อ: Kael ผู้สาบานต่อเงามืด
Species: Aasimar Background: Noble

ค่าพลัง
  STR 18 (+4) DEX 10 (0) CON 14 (+2) INT 8 (-1) WIS 12 (+1) CHA 18 (+4)

HP 84 AC 20 (Plate + Shield) Speed 30 ft
Proficiency Bonus +4 (จากเลเวลตัวละครรวม 10)

Saving Throw Proficiency: WIS, CHA (จากคลาสแรก Paladin เท่านั้น)

ความสามารถจาก Paladin 6
  Lay On Hands (คลัง 30 HP)
  Divine Smite (สเปลระดับ 1 เตรียมไว้เสมอ)
  Extra Attack
  Aura of Protection (+4 Save ให้ทุกคนในระยะ 10 ฟุต)
  Fighting Style: Defense

ความสามารถจาก Warlock 4
  Pact Magic: Slot ระดับ 2 จำนวน 2 ช่อง (ฟื้นทุก Short Rest)
  Eldritch Invocations 3 อย่าง
  Subclass: Fiend Patron (Dark One's Blessing)

Spell Slot
  Pact Magic: ระดับ 2 × 2 ช่อง (ฟื้นทุก Short Rest)
  ปกติ: เลเวลผู้ร่ายเวท = Paladin 6 หารสอง = 3
               ได้ Slot ระดับ 1 × 4, ระดับ 2 × 2

วิธีเล่น
  ใช้ Pact Slot ระดับ 2 ไป Divine Smite (3d8 ต่อครั้ง) แล้วพัก Short Rest เติม
  ทำให้ Smite ได้บ่อยกว่า Paladin ปกติมาก
```

### Rogue 3 / Fighter 2 (เลเวลตัวละคร 5)

```
ชื่อ: Vex นักลอบสังหารผู้ผ่านศึก
Species: Wood Elf Background: Criminal

ค่าพลัง
  STR 10 (0) DEX 18 (+4) CON 14 (+2) INT 12 (+1) WIS 13 (+1) CHA 8 (-1)

HP 38 AC 16 (Studded Leather + DEX) Speed 35 ft
Proficiency Bonus +3

Saving Throw Proficiency: DEX, INT (จากคลาสแรก Rogue)

ความสามารถจาก Rogue 3
  Sneak Attack 2d6
  Expertise: Stealth, Thieves' Tools
  Cunning Action (Bonus Action: Dash / Disengage / Hide)
  Subclass: Thief (Fast Hands, Second-Story Work)

ความสามารถจาก Fighter 2
  Fighting Style: Archery (+2 โจมตีระยะไกล)
  Second Wind (ฟื้น 1d10+2)
  Action Surge (Action เพิ่ม 1 ครั้ง)
  Weapon Mastery 3 ชนิด

วิธีเล่น
  Action Surge ทำให้โจมตี 2 ครั้งใน 1 เทิร์น
  แต่ Sneak Attack ยังได้แค่ 1 ครั้งต่อเทิร์น จึงเพิ่มโอกาสว่าจะตีโดนอย่างน้อย 1 ครั้ง
```

---

## รายการตรวจก่อน Multiclass

```
[ ] DM อนุญาตให้ Multiclass แล้ว
[ ] ค่าพลังถึงเกณฑ์ 13 ของทั้งสองคลาส
[ ] รู้ว่าจะเสียอะไรจากคลาสหลัก (Extra Attack, สเปลระดับสูง, Capstone)
[ ] คำนวณ Spell Slot ใหม่แล้ว (ถ้าเป็นสายเวท)
[ ] รู้ว่าจะไม่ได้ Saving Throw Proficiency จากคลาสใหม่
[ ] รู้ว่าจะไม่ได้ Heavy Armor Proficiency ถ้าคลาสแรกไม่ได้ให้
[ ] มีแผนชัดว่าจะลงเลเวลไหนที่คลาสไหน จนถึงเลเวล 12 เป็นอย่างน้อย
```

---

## สรุป Multiclassing ในหนึ่งบรรทัด

> **ต้องมีค่าพลัง 13 ทั้งสองคลาส · Proficiency Bonus ใช้เลเวลรวม แต่ Feature ใช้เลเวลคลาส · การแวะ 1-2 เลเวลมักคุ้มกว่าแบ่งครึ่ง · และถ้าไม่แน่ใจว่าคุ้มไหม แปลว่าไม่คุ้ม**

---

[สารบัญ](../README.md)
