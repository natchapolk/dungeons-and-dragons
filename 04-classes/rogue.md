# โจร / นักลอบสังหาร (Rogue)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**โร้ก / โจร (Rogue)** คือผู้เชี่ยวชาญการลอบเร้น การหลบหลีก และการโจมตีจุดอ่อน พวกเขา **ดาเมจต่อครั้งสูงมาก** ด้วย **Sneak Attack** และเป็นคลาสที่ เก่งสกิลที่สุดในเกม

แนะนำสำหรับผู้เล่นใหม่ (อันดับ 3) ไม่มีเวทให้จำ แต่มีสิ่งที่ทำได้หลากหลายมาก และตีแรงตั้งแต่เลเวล 1

---

## ข้อมูลพื้นฐาน (Class Table)

- **Primary Ability** **Dexterity (DEX)**
- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **HP เลเวลถัดไป** 1d8 + CON (หรือค่าคงที่ 5 + CON)
- **Saving Throw Proficiency** **Dexterity, Intelligence**
- **Armor Proficiency** Light Armor
- **Weapon Proficiency** Simple Weapons + Martial Weapon ที่มีคุณสมบัติ Finesse หรือ Light
- **Tool Proficiency** **Thieves' Tools**
- **Skill Proficiency** เลือก 4 จาก: **มากที่สุดในเกม (Acrobatics, Athletics, Deception, Insight, Intimidation, Investigation, Perception, Performance, Persuasion, Sleight of Hand, Stealth)**
- **Weapon Mastery** 2 ชนิด
- **Subclass** เลือกที่ เลเวล 3

### อุปกรณ์เริ่มต้น

**เลือก A** รับของชุดนี้

- **เกราะหนัง (Leather Armor)** ให้ AC 11 บวก DEX เต็มจำนวน และไม่กระทบการทอย Stealth
- **มีดสั้น (Dagger)** 2 เล่ม ดาเมจ 1d4 Piercing ความชำนาญ Nick คุณสมบัติ Finesse และขว้างได้ไกล 20 ฟุต
- **ดาบสั้น (Shortsword)** ดาเมจ 1d6 Piercing ความชำนาญ Vex คุณสมบัติ Finesse จึงใช้ DEX ทอยได้
- **ธนูสั้น (Shortbow)** ดาเมจ 1d6 Piercing ความชำนาญ Vex ยิงได้ไกล 80 ฟุต พร้อม **ลูกธนู (Arrows)** 20 ดอก
- **เครื่องมือโจร (Thieves' Tools)** ราคา 25 GP ใช้สะเดาะกุญแจและปลดกับดัก Rogue มี Proficiency กับอันนี้ตั้งแต่เลเวล 1
- **ชุดโจร (Burglar's Pack)** มีลูกปืนกลม กระดิ่ง เชือกเส้นเล็ก และตะเกียงมีฝา เหมาะกับการย่องและวางกับดักสัญญาณ
- เงินติดตัว 8 GP

**เลือก B** รับเงิน 100 GP ไปซื้อของเอง

แนะนำอย่างยิ่งสำหรับมือใหม่ ให้เลือก A เพราะเครื่องมือโจรอย่างเดียวราคา 25 GP
และชุดโจรอีก 16 GP รวมกับของที่เหลือแล้วเกิน 100 GP อยู่แล้ว

ข้อควรระวัง ถ้าเลือก B แล้วลืมซื้อเครื่องมือโจร ทีมทั้งทีมจะติดอยู่หน้าประตูล็อก
เพราะ Rogue มักเป็นคนเดียวในทีมที่มี Proficiency กับเครื่องมือนี้

---

## ความก้าวหน้าเลเวล 1 ถึง 20

- **เลเวล 1** Proficiency Bonus +2, ได้ความสามารถ Expertise, Sneak Attack, Thieves' Cant, Weapon Mastery, Sneak Attack 1d6
- **เลเวล 2** Proficiency Bonus +2, ได้ความสามารถ Cunning Action [แนะนำ], Sneak Attack 1d6
- **เลเวล 3** Proficiency Bonus +2, ได้ความสามารถ Rogue Subclass [แนะนำ], Steady Aim, Sneak Attack 2d6
- **เลเวล 4** Proficiency Bonus +2, ได้ความสามารถ Ability Score Improvement (ASI), Sneak Attack 2d6
- **เลเวล 5** Proficiency Bonus +3, ได้ความสามารถ Cunning Strike [แนะนำ], Uncanny Dodge, Sneak Attack 3d6
- **เลเวล 6** Proficiency Bonus +3, ได้ความสามารถ เพิ่ม 2 สกิล (Expertise), Sneak Attack 3d6
- **เลเวล 7** Proficiency Bonus +3, ได้ความสามารถ Evasion [แนะนำ], Reliable Talent, Sneak Attack 4d6
- **เลเวล 8** Proficiency Bonus +3, ได้ความสามารถ ASI, Sneak Attack 4d6
- **เลเวล 9** Proficiency Bonus +4, ได้ความสามารถ Subclass Feature, Sneak Attack 5d6
- **เลเวล 10** Proficiency Bonus +4, ได้ความสามารถ ASI, Sneak Attack 5d6
- **เลเวล 11** Proficiency Bonus +4, ได้ความสามารถ Improved Cunning Strike, Sneak Attack 6d6
- **เลเวล 12** Proficiency Bonus +4, ได้ความสามารถ ASI, Sneak Attack 6d6
- **เลเวล 13** Proficiency Bonus +5, ได้ความสามารถ Subclass Feature, Sneak Attack 7d6
- **เลเวล 14** Proficiency Bonus +5, ได้ความสามารถ Devious Strikes, Sneak Attack 7d6
- **เลเวล 15** Proficiency Bonus +5, ได้ความสามารถ Slippery Mind, Sneak Attack 8d6
- **เลเวล 16** Proficiency Bonus +5, ได้ความสามารถ ASI, Sneak Attack 8d6
- **เลเวล 17** Proficiency Bonus +6, ได้ความสามารถ Subclass Feature, Sneak Attack 9d6
- **เลเวล 18** Proficiency Bonus +6, ได้ความสามารถ Elusive, Sneak Attack 9d6
- **เลเวล 19** Proficiency Bonus +6, ได้ความสามารถ Epic Boon Feat, Sneak Attack 10d6
- **เลเวล 20** Proficiency Bonus +6, ได้ความสามารถ Stroke of Luck, Sneak Attack 10d6

**Rogue ได้ ASI/Feat 6 ครั้ง** (เลเวล 4, 8, 10, 12, 16 + Epic Boon 19) มากเป็นอันดับ 2 รองจาก Fighter

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 การโจมตีลับ (Sneak Attack) ความสามารถหลักของคลาส

**1 ครั้งต่อเทิร์น** คุณสามารถเพิ่มดาเมจ 1d6 เมื่อโจมตีโดน โดยต้องเข้าเงื่อนไขทั้ง 2 ข้อ:

**เงื่อนไขที่ 1 อาวุธ:** ต้องใช้อาวุธที่มีคุณสมบัติ **Finesse** หรือ **Ranged**

เงื่อนไขที่ 2 สถานการณ์ (อย่างใดอย่างหนึ่ง):
- คุณมี **Advantage** ในการโจมตีครั้งนั้น
- มีเพื่อนร่วมทีมอยู่ในระยะ 5 ฟุตจากเป้าหมาย และคุณไม่มี Disadvantage

**ดาเมจตามเลเวล:**

**เลเวล 1 1d6**

3.5

**เลเวล 5 3d6**

10.5

**เลเวล 11 6d6**

21

**เลเวล 17 9d6**

31.5

**เลเวล 20 10d6**

**35**

**จุดที่มือใหม่พลาดบ่อย:**
- **1 ครั้งต่อเทิร์น เท่านั้น** (ไม่ใช่ต่อ Action) แต่ใช้ในเทิร์นของศัตรูได้ด้วย ถ้าคุณมี Reaction Attack!
- **ไม่จำเป็นต้องซ่อนตัว** แค่มีเพื่อนยืนติดศัตรูก็พอ
- **ใช้กับ Opportunity Attack ได้**
- Critical Hit เต๋า Sneak Attack ก็คูณสองด้วย

### อาวุธที่ใช้ Sneak Attack ได้

- **ประชิด (Finesse)** **Rapier** [แนะนำ] (1d8, Vex), **Shortsword** [แนะนำ] (1d6, Vex), Dagger (1d4, Nick), Scimitar (1d6, Nick), Whip (1d4, Slow), Dart
- **Ranged** **Shortbow** [แนะนำ] (1d6, Vex), **Hand Crossbow** [แนะนำ] (1d6, Vex), Light Crossbow, Sling, Blowgun

แนะนำที่สุด: Rapier (ประชิด) + Shortbow หรือ Hand Crossbow (ระยะไกล)

---

### เลเวล 1 ความเชี่ยวชาญ (Expertise)

เลือก Skill 2 อย่าง ที่คุณมี Proficiency บวก Proficiency Bonus สองเท่า
(ได้เพิ่มอีก 2 สกิลที่เลเวล 6)

** สกิลที่แนะนำสำหรับ Expertise:**

- 1 **Stealth** [แนะนำมาก] หัวใจของ Rogue ซ่อนตัวเพื่อได้ Advantage = ได้ Sneak Attack
- 2 **Perception** [แนะนำ] ใช้บ่อยที่สุดในเกม + เพิ่ม Passive Perception
- 3 **Thieves' Tools** [แนะนำ] (นับเป็น Tool แต่ Expertise ใช้ได้) เปิดกุญแจ ปลดกับดัก
- 4 **Investigation** หาความลับ กับดัก
- 5 **Sleight of Hand** ล้วงกระเป๋า ซ่อนของ
- 6 **Deception / Persuasion** ถ้าเป็น "หน้ากลุ่ม" ในการเจรจา

**ตัวอย่าง:** เลเวล 5 (Prof +3) มี DEX 18 (+4) + Expertise ใน Stealth
**Stealth = 1d20 + 4 + 6 = 1d20 + 10** (ทอยขั้นต่ำ 11!)

---

### เลเวล 1 ภาษาลับโจร (Thieves' Cant)

- คุณรู้ **Thieves' Cant** ภาษาลับที่ใช้สื่อสารกันในโลกใต้ดิน (คำแสลง สัญลักษณ์ ท่าทาง)
- ใช้เวลาสื่อสารนานกว่าปกติ 4 เท่า แต่คนนอกไม่มีทางเข้าใจ
- **ได้ภาษาอื่นเพิ่มอีก 1 ภาษา** ตามที่เลือก

---

### เลเวล 1 Weapon Mastery

เลือกอาวุธ 2 ชนิด ปลดล็อก Mastery Property (เปลี่ยนได้ตอน Long Rest)

** แนะนำ:** **Rapier (Vex)** + **Shortbow (Vex)**

**ทำไม Vex ดีที่สุดสำหรับ Rogue:**

- เทิร์นที่ 1: ตีโดน ได้ Vex
- เทิร์นที่ 2: การโจมตีต่อเป้าหมายนั้นได้ Advantage การันตี Sneak Attack!

---

### เลเวล 2 การกระทำเจ้าเล่ห์ (Cunning Action)

ในเทิร์นของคุณ ใช้ Bonus Action เพื่อทำอย่างใดอย่างหนึ่ง:

- **Dash** เพิ่มระยะเคลื่อนที่อีกเท่าตัว
- **Disengage** เคลื่อนที่ออกโดยไม่โดน Opportunity Attack
- **Hide** ซ่อนตัว (DC 15 Stealth) ได้สภาวะ **Invisible**

ทำไมนี่คือ Feature ที่เปลี่ยนเกม:
- **โจมตี + ซ่อนตัว ในเทิร์นเดียว** เทิร์นหน้าโจมตีจากที่ซ่อน = Advantage = Sneak Attack แน่นอน
- **โจมตี + ถอนตัว** ตีแล้วหนีโดยไม่โดนสวน
- Rogue กลายเป็นคลาสที่ เคลื่อนที่คล่องที่สุดในเกม

---

### เลเวล 3 เล็งนิ่ง (Steady Aim)

**Bonus Action:** ได้ Advantage ในการทอยโจมตีครั้งถัดไป ในเทิร์นนี้
แลกกับ: Speed = 0 จนจบเทิร์นนี้ (ต้องไม่ได้เคลื่อนที่มาก่อนในเทิร์นนี้)

**ทำไมดี:** การันตี Sneak Attack ทุกเทิร์น แม้จะไม่มีเพื่อนยืนติดศัตรูและไม่มีที่ซ่อน เหมาะกับ Rogue สายธนู มากที่สุด

---

### เลเวล 5 การโจมตีเจ้าเล่ห์ (Cunning Strike) กฎใหม่ 2024

**เมื่อคุณทำ Sneak Attack** คุณสามารถ สละเต๋า Sneak Attack บางลูก เพื่อสร้างผลพิเศษ

- **Poison** 1d6 เป้าหมายทอย **CON Save** ล้มเหลว = Poisoned 1 นาที (ทอยใหม่ได้ทุกจบเทิร์นของมัน) และ ต้องมี **Poisoner's Kit**
- **Trip** 1d6 ถ้าเป้าหมาย Large หรือเล็กกว่า ทอย **DEX Save** ล้มเหลว = **Prone**
- **Withdraw** 1d6 คุณเคลื่อนที่ได้ครึ่ง Speed ทันที โดยไม่โดน Opportunity Attack

DC ของ Save = 8 + DEX modifier + Proficiency Bonus

**ทำไมดี:** เปลี่ยน "ดาเมจส่วนเกิน" เป็น "การควบคุมสนามรบ" ได้ตามสถานการณ์

**Trip ทรงพลังที่สุด** ทำให้ศัตรู Prone เพื่อนที่ตีระยะประชิดได้ Advantage หมด

---

### เลเวล 5 การหลบเหนือธรรมชาติ (Uncanny Dodge)

**Reaction:** เมื่อศัตรูที่คุณมองเห็นโจมตีคุณโดน
ลดดาเมจจากการโจมตีนั้นลงครึ่งหนึ่ง

**ทำไมดี:** ช่วยชีวิตได้จริง โดยเฉพาะกับ Critical Hit ที่ดาเมจสูง

---

### เลเวล 7 การหลบหลีก (Evasion)

เมื่อคุณต้องทอย DEX Saving Throw เพื่อลดดาเมจครึ่งหนึ่ง (เช่น Fireball, ลมหายใจมังกร)

- **สำเร็จ รับดาเมจ 0**
- **ล้มเหลว รับดาเมจแค่ครึ่งเดียว**

**ทำไมดี:** ทำให้ Rogue แทบไม่กลัวสเปลระเบิดพื้นที่เลย

---

### เลเวล 7 ความสามารถที่เชื่อถือได้ (Reliable Talent)

เมื่อคุณทอย Ability Check โดยใช้สกิล/เครื่องมือที่มี Proficiency
ถ้าทอย d20 ได้ 9 หรือน้อยกว่า นับเป็น 10

ทำไมนี่คือ Feature ที่ทรงพลังมาก:

- Stealth +10 (Expertise) ทอยได้ 3 นับเป็น 10 ผลรวม 20
- ค่าต่ำสุดที่เป็นไปได้ 20 (ไม่มีทางน้อยกว่านี้)

Rogue เลเวล 7+ ที่มี Expertise แทบไม่มีวันล้มเหลวในสกิลที่ถนัด

---

### เลเวล 11 Improved Cunning Strike

ใช้ Cunning Strike ได้ 2 ผลพร้อมกัน (ต้องสละเต๋าตามต้นทุนของทั้งคู่)

---

### เลเวล 14 การโจมตีชั่วร้าย (Devious Strikes)

Cunning Strike ได้ตัวเลือกใหม่ที่แรงขึ้น:

- **Daze** 2d6 เป้าหมายทอย **CON Save** ล้มเหลว = จนถึงจบเทิร์นหน้าของมัน ทำได้แค่ Action หรือ Bonus Action อย่างใดอย่างหนึ่ง (ไม่ได้ทั้งคู่) และ ใช้ Reaction ไม่ได้
- **Knock Out** 6d6 เป้าหมายทอย **CON Save** ล้มเหลว = Unconscious 1 นาที (จบเมื่อโดนดาเมจหรือมีคนปลุก)
- **Obscure** 3d6 เป้าหมายทอย **DEX Save** ล้มเหลว = Blinded จนจบเทิร์นหน้าของมัน

---

### เลเวล 15 จิตลื่นไหล (Slippery Mind)

ได้ Proficiency ใน Wisdom Saving Throw และ Charisma Saving Throw

**ทำไมดี:** แก้จุดอ่อนที่ใหญ่ที่สุดของ Rogue WIS Save ที่โดน Hold Person, Dominate บ่อย

---

### เลเวล 18 จับไม่ติด (Elusive)

**ตราบที่คุณไม่ถูก Incapacitated**
ไม่มีการโจมตีใดที่ทอยใส่คุณได้ด้วย Advantage

**ทำไมดี:** ศัตรูไม่มีทางได้ Advantage ใส่คุณเลย ป้องกันได้ทั้งการซุ่มโจมตี, Prone, Restrained ฯลฯ

---

### เลเวล 20 จังหวะโชคดี (Stroke of Luck) Capstone

หลังจากที่คุณทอย d20 Test ล้มเหลว
คุณสามารถ**เปลี่ยนผลการทอยนั้นเป็น 20 (Natural 20)** ได้ทันที

ใช้ได้ 1 ครั้ง ฟื้นเมื่อ Short Rest หรือ Long Rest

**ทำไมดี:** Critical Hit ตามใจสั่ง Rogue เลเวล 20 คริติคอลด้วย 20d6 Sneak Attack

---

## Subclasses (Roguish Archetype) เลือกที่เลเวล 3

Rogue มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ เลเวล 3, 9, 13, 17

---

### 1. Thief จอมโจร

**ธีม:** โจรตัวจริง ปีนป่าย ล้วงกระเป๋า ใช้ของวิเศษได้ทุกชนิด

**เลเวล 3 Fast Hands**

**Bonus Action:** ใช้ **Sleight of Hand** เพื่อล้วงกระเป๋า/ใช้ Thieves' Tools ปลดกับดักหรือเปิดกุญแจ และ หรือใช้ **เช่นดื่มยา ใช้ของ (Utilize action)**

**เลเวล 3 Second-Story Work**

[แนะนำ] ได้ **Climb Speed = Speed** และ และเมื่อกระโดดไกล บวกระยะเพิ่ม = DEX modifier (ฟุต)

**เลเวล 9 Supreme Sneak**

เมื่อใช้ **Cunning Strike: Withdraw** ให้ใช้ Hide action ฟรี ด้วย และ ต้นทุน Withdraw ลดเหลือ 0 เต๋า

**เลเวล 13 Use Magic Device**

[แนะนำมาก] และ ใช้ Magic Item ทุกชนิดได้ แม้จะไม่ตรงเงื่อนไข (คลาส/Attunement)
- **Scroll:** ร่ายสเปลจาก Spell Scroll ได้ถึงระดับ 1-2 (ทอย DC 10 + ระดับสเปลถ้าสูงกว่า)
- **Charges:** ใช้ของที่มี Charge ทอย d6, ออก 6 = ไม่เสีย Charge
- **Attunement:** Attune ของวิเศษได้ 4 ชิ้น (แทน 3)

**เลเวล 17 Thief's Reflexes**

ในรอบแรกของการต่อสู้ คุณได้ 2 เทิร์น [แนะนำมาก] (เทิร์นแรกตาม Initiative ปกติ, เทิร์นที่สองที่ Initiative - 10)

**แนะนำมือใหม่** เข้าใจง่าย มีประโยชน์ทั้งในและนอกการต่อสู้

---

### 2. Assassin นักลอบสังหาร

**ธีม:** ฆาตกรมืออาชีพ โจมตีเทิร์นแรกแรงมหาศาล

**เลเวล 3 Assassinate**

[แนะนำ] และ Advantage ในการทอย Initiative
- **ในเทิร์นแรกของการต่อสู้:** คุณมี **Advantage** ในการโจมตีศัตรูที่ยังไม่ได้เล่นเทิร์น
- ถ้าตีโดนในเทิร์นแรกนั้น เพิ่มดาเมจเท่ากับเลเวล Rogue

**เลเวล 3 Assassin's Tools**

ได้ **Poisoner's Kit** และ **Disguise Kit** พร้อม Proficiency

**เลเวล 9 Infiltration Expertise**

ใช้เวลา 7 วัน + 25 GP สร้างตัวตนปลอมที่สมบูรณ์แบบ และ ปลอมตัวเป็นตัวตนนั้นได้ในเวลา 1 นาที

**เลเวล 13 Envenom Weapons**

เมื่อใช้ **Cunning Strike: Poison** เพิ่มดาเมจ 2d6 Poison เข้าไปด้วย

**เลเวล 17 Death Strike**

[แนะนำมาก] ในเทิร์นแรกของการต่อสู้ เมื่อคุณตีโดนศัตรูที่ **Surprised** มันทอย **CON Save (DC 8+DEX+Prof)** ล้มเหลว = ดาเมจ 2 เท่า

**แรงที่สุดตอนเปิดฉาก** แต่ถ้าการต่อสู้ยืดเยื้อจะเหลือแค่ Rogue ปกติ

---

### 3. Arcane Trickster จอมเวทเจ้าเล่ห์

**ธีม:** โจรที่ใช้เวทมนตร์หลอกล่อ (Third Caster ใช้ **INT**)

**เลเวล 3 Spellcasting**

เรียนสเปลจากรายการ เน้น Illusion และ Enchantment** (Wizard)** ใช้ **INT**

**เลเวล 3 Mage Hand Legerdemain**

[แนะนำ] ได้ Cantrip Mage Hand, มือลอย **มองไม่เห็น**, ใช้มือ ล้วงกระเป๋า / เปิดกุญแจ / ใช้ Thieves' Tools ระยะไกลได้ และ ควบคุมด้วย **Bonus Action**

**เลเวล 9 Magical Ambush**

[แนะนำ] ถ้าคุณ **Invisible** ต่อเป้าหมายตอนร่ายเวทใส่มัน มันเสียเปรียบในการทอย Saving Throw ของเวทนั้น

**เลเวล 13 Versatile Trickster**

**Bonus Action:** ใช้ Mage Hand กวนใจศัตรูในระยะ 5 ฟุตจากมือ คุณได้ Advantage ในการโจมตีศัตรูนั้นจนจบเทิร์น

**เลเวล 17 Spell Thief**

**Reaction:** [แนะนำมาก] เมื่อศัตรูร่ายเวทใส่คุณ มันทอย Save ตามค่าร่ายเวทของคุณ ล้มเหลว = สเปลนั้นไม่มีผล และคุณขโมยสเปลนั้นมาใช้ได้ 8 ชั่วโมง (ศัตรูใช้สเปลนั้นไม่ได้ระหว่างนั้น) ใช้ได้ 1 ครั้ง/Long Rest

**ความก้าวหน้าการร่ายเวท (Third Caster)** ใช้ค่าเดียวกับ Eldritch Knight ทุกประการ
ดูรายการทีละเลเวลได้ที่หัวข้อ Subclass ข้อ 3 Eldritch Knight อัศวินเวทมนตร์ ใน [นักรบ (Fighter)](fighter.md)

** สเปลที่แนะนำ:**
- **Cantrip:** Mage Hand (ได้ฟรี), Minor Illusion [แนะนำ], Booming Blade [แนะนำ], Prestidigitation
- **ระดับ 1:** **Find Familiar** [แนะนำมาก] (Familiar ยืนติดศัตรู = ได้ Sneak Attack ตลอด!), Shield [แนะนำ], Disguise Self, Silvery Barbs
- **ระดับ 2:** Invisibility [แนะนำ], Mirror Image, Misty Step
- **ระดับ 3:** Fly, Hypnotic Pattern (ถ้ามีเข้าถึง)
- **ระดับ 4:** Greater Invisibility [แนะนำมาก] (Advantage ตลอด = Sneak Attack ทุกเทิร์น)

Find Familiar คือคอมโบเด็ดของ Arcane Trickster ส่ง Familiar ไปยืนติดศัตรู แล้วคุณได้เงื่อนไข Sneak Attack ทุกเทิร์นโดยไม่ต้องพึ่งเพื่อน

---

### 4. Soulknife ดาบวิญญาณ

**ธีม:** Rogue พลังจิต สร้างมีดพลังจิตและอ่านใจคน

**เลเวล 3 Psionic Power**

ได้ **จำนวน = 2 คูณ Prof Bonus (Psionic Energy Dice)**:
- **Psi-Bolstered Knack** เมื่อทอย Ability Check ที่มี Proficiency ล้มเหลว บวก 1 เต๋าเข้าไป (ถ้ายังล้มเหลว ไม่เสียเต๋า)
- **Psychic Whispers** สื่อสารทางจิตกับสิ่งมีชีวิตได้ (ฟรี 1 ครั้ง/Long Rest)

**เลเวล 3 Psychic Blades**

[แนะนำ] สร้าง มีดพลังจิต ด้วย Magic action:
- เป็นอาวุธ **Simple Melee, Finesse, Thrown (60/120)** ทำ 1d6 Psychic
- หลังโจมตีด้วย Psychic Blade ใช้ Bonus Action สร้างอีกเล่มโจมตีซ้ำ (ดาเมจ 1d4 + Ability modifier)
- ไม่ต้องพกอาวุธ ไม่มีวันถูกปลดอาวุธ

**เลเวล 9 Soul Blades**

**Homing Strikes** เมื่อโจมตีด้วย Psychic Blade พลาด ใช้ 1 เต๋าบวกเข้าไปในการทอย (ถ้ายังพลาด ไม่เสียเต๋า)
- **Psychic Teleportation** **Bonus Action:** ขว้างมีดแล้ว วาร์ปไปที่นั่น (ระยะ = 1 เต๋า 10 เท่า ฟุต)

**เลเวล 13 Psychic Veil**

**Magic action:** กลายเป็น Invisible 1 ชั่วโมง (จบเมื่อโจมตีหรือทำให้ศัตรูทอย Save) ฟรี 1 ครั้ง/Long Rest หรือใช้ 1 เต๋า

**เลเวล 17 Rend Mind**

[แนะนำมาก] เมื่อทำ Sneak Attack ด้วย Psychic Blade ใช้ 3 เต๋า ให้เป้าหมายทอย **WIS Save** ล้มเหลว = Stunned 1 นาที (ทอยใหม่ได้ทุกจบเทิร์นของมัน)

**Psionic Energy Dice ตามเลเวล:** เลเวล 3 = d6, เลเวล 5 = d8, เลเวล 11 = d10, เลเวล 17 = d12
**ฟื้น:** 1 เต๋าเมื่อ **1 ครั้ง/Long Rest (Bonus Action)** หรือทั้งหมดเมื่อ **Long Rest**

**สายที่ทนที่สุดในระยะยาว** ไม่ต้องพึ่งอาวุธ ไม่ต้องพึ่งสภาพแวดล้อม

---

## เปรียบเทียบ 4 Subclass

- **จุดเด่น** ยืดหยุ่น ใช้ของวิเศษ เปิดฉากแรงมาก มีเวทหลอกล่อ ไม่พึ่งอุปกรณ์
- **ความยาก** ง่าย ง่าย ยาก (จำเวท) กลาง
- **ค่าพลังที่ต้องมี** DEX, CON DEX, CON + **INT 14+** DEX, CON
- **นอกการต่อสู้** สูงมาก สูง (ปลอมตัว) สูงมาก กลาง
- **แนะนำมือใหม่** ใช่ ใช่ ไม่ ใช่

---

## คำแนะนำการสร้าง Rogue

### ค่าพลังที่ควรจัด

- DEX สูงสุดเสมอ (17 ตั้งแต่เลเวล 1 ดันถึง 20)
- CON สูงรอง (14) HP น้อยและอยู่ใกล้ศัตรู
- WIS ปานกลาง (12-14) WIS Save เป็นจุดอ่อน
- INT สูงถ้าเล่น Arcane Trickster (14+)
- CHA ถ้าเป็นหน้ากลุ่ม
- STR ต่ำได้

### Species ที่แนะนำ

- **ฮาล์ฟลิง (Halfling)** [แนะนำมาก] **ซ่อนหลังเพื่อน = Sneak Attack ทุกเทิร์น (Naturally Stealthy)** + **Luck**
- **เอลฟ์ (Elf) สาย Wood** [แนะนำ] Speed 35 + Pass Without Trace + Perception
- **Elf (Drow)** [แนะนำ] Darkvision 120 ft + Faerie Fire (ให้ Advantage ทั้งทีม)
- **โนม (Gnome)** Advantage ใน INT/WIS/CHA Save + Small ซ่อนง่าย
- **มนุษย์ (Human)** Feat ฟรี (Alert = ไปก่อนศัตรู)
- **ออร์ค (Orc) / คนแคระ (Dwarf)** Darkvision 120 ft

### Background ที่แนะนำ
**DEX/CON/INT ได้ Alert (Criminal)** [แนะนำมาก], **DEX/WIS/CHA ได้ Lucky (Wayfarer)** และ **Charlatan** (DEX/CON/CHA)

### Feat ที่แนะนำ (เลเวล 4+)

- **Ability Score Improvement (DEX)** [แนะนำ] ดัน DEX ถึง 20 ก่อนอย่างอื่น
- **Alert** [แนะนำ] ไปก่อนศัตรู = Sneak Attack ก่อน
- **Skulker** [แนะนำ] ซ่อนตัวเก่งขึ้น + ไม่เปิดเผยตำแหน่งเมื่อยิงพลาด
- **Piercer** ทอยเต๋าดาเมจ Piercing ใหม่ได้ 1 ลูก
- **Resilient (Wisdom)** แก้จุดอ่อน WIS Save
- **Crossbow Expert** ใช้ Hand Crossbow ในระยะประชิดได้ไม่เสียเปรียบ
- **Mobile** Speed +10 + ไม่โดน Opportunity Attack จากคนที่เราตี

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

- ใช้ Greatsword/Longsword ต้องเป็นอาวุธ Finesse หรือ Ranged ไม่งั้นไม่ได้ Sneak Attack
- คิดว่าต้องซ่อนตัวถึงจะ Sneak Attack ได้ มีเพื่อนยืนติดศัตรูก็พอ
- พยายาม Sneak Attack หลายครั้งต่อเทิร์น 1 ครั้ง/เทิร์นเท่านั้น (แต่ใช้ในเทิร์นศัตรูได้ด้วย Reaction)
- ลืมใช้ Cunning Action ทุกเทิร์น Bonus Action ต้องใช้เสมอ Hide, Disengage, หรือ Dash
- ยืนแนวหน้ารับดาเมจ Rogue HP d8 และเกราะ Light ตี แล้วถอย
- ไม่เอา Expertise ใน Stealth Stealth คือหัวใจ ต้องมี Expertise

---

## สรุป Rogue ในหนึ่งบรรทัด

**ดาเมจต่อครั้งสูงมาก (Sneak Attack) + เก่งสกิลที่สุดในเกม (Expertise + Reliable Talent) + คล่องตัวที่สุด (Cunning Action) = คลาสที่ทำได้ทุกอย่างโดยไม่ต้องจำเวท**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
