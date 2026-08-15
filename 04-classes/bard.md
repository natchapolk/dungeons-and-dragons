# นักดนตรีเวท (Bard)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**บาร์ด / นักดนตรีเวท (Bard)** คือนักแสดงที่ร่ายเวทผ่านดนตรีและถ้อยคำ พวกเขาเป็นคลาสที่ เก่งรอบด้านที่สุดในเกม รักษาได้ ควบคุมได้ บัฟทีมได้ และเป็น หน้ากลุ่มในการเจรจา

Bard คือคลาส "Support ที่ดีที่สุด" Bardic Inspiration เปลี่ยนผลการทอยของทั้งทีม และ Magical Secrets ให้เข้าถึงสเปลจากทุกคลาส

---

## ข้อมูลพื้นฐาน (Class Table)

- **Primary Ability** **Charisma (CHA)**
- **Hit Die** d8
- **HP เลเวล 1** 8 + CON modifier
- **HP เลเวลถัดไป** 1d8 + CON (หรือค่าคงที่ 5 + CON)
- **Saving Throw Proficiency** **Dexterity, Charisma**
- **Armor Proficiency** Light Armor
- **Weapon Proficiency** Simple Weapons
- **Tool Proficiency** เครื่องดนตรี 3 ชนิด
- **Skill Proficiency** เลือก 3 อย่าง จากสกิลทั้งหมด 18 อย่าง (อิสระที่สุดในเกม)
- **Spellcasting Ability** **Charisma (CHA)**
- **Spellcasting Focus** **เครื่องดนตรี (Musical Instrument)**
- **Subclass (Bard College)** เลือกที่ เลเวล 3

### อุปกรณ์เริ่มต้น

**เลือก A:** Leather Armor, Dagger, Musical Instrument, Entertainer's Pack, 19 GP
**เลือก B:** 90 GP ไปซื้อเอง

---

## ความก้าวหน้าเลเวล 1 ถึง 20

- **เลเวล 1** Proficiency Bonus +2, ได้ความสามารถ Bardic Inspiration [แนะนำ], Spellcasting, Bardic Die d6, รู้ Cantrip 2, เตรียมสเปลได้ 4, Spell Slot ระดับ 1 จำนวน 2 ช่อง
- **เลเวล 2** Proficiency Bonus +2, ได้ความสามารถ Expertise [แนะนำ], Jack of All Trades, Bardic Die d6, รู้ Cantrip 2, เตรียมสเปลได้ 5, Spell Slot ระดับ 1 จำนวน 3 ช่อง
- **เลเวล 3** Proficiency Bonus +2, ได้ความสามารถ Bard College (Subclass) [แนะนำ], Bardic Die d6, รู้ Cantrip 2, เตรียมสเปลได้ 6, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 2 ช่อง
- **เลเวล 4** Proficiency Bonus +2, ได้ความสามารถ ASI, Bardic Die d6, รู้ Cantrip 3, เตรียมสเปลได้ 7, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง
- **เลเวล 5** Proficiency Bonus +3, ได้ความสามารถ Font of Inspiration [แนะนำมาก], Bardic Die d8, รู้ Cantrip 3, เตรียมสเปลได้ 9, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 2 ช่อง
- **เลเวล 6** Proficiency Bonus +3, ได้ความสามารถ Subclass Feature, Bardic Die d8, รู้ Cantrip 3, เตรียมสเปลได้ 10, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง
- **เลเวล 7** Proficiency Bonus +3, ได้ความสามารถ Countercharm, Bardic Die d8, รู้ Cantrip 3, เตรียมสเปลได้ 11, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 1 ช่อง
- **เลเวล 8** Proficiency Bonus +3, ได้ความสามารถ ASI, Bardic Die d8, รู้ Cantrip 3, เตรียมสเปลได้ 12, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 2 ช่อง
- **เลเวล 9** Proficiency Bonus +4, ได้ความสามารถ เพิ่ม 2 สกิล (Expertise), Bardic Die d8, รู้ Cantrip 3, เตรียมสเปลได้ 14, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 1 ช่อง
- **เลเวล 10** Proficiency Bonus +4, ได้ความสามารถ Magical Secrets [แนะนำมาก], Bardic Die d10, รู้ Cantrip 4, เตรียมสเปลได้ 15, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง
- **เลเวล 11** Proficiency Bonus +4, Bardic Die d10, รู้ Cantrip 4, เตรียมสเปลได้ 16, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง
- **เลเวล 12** Proficiency Bonus +4, ได้ความสามารถ ASI, Bardic Die d10, รู้ Cantrip 4, เตรียมสเปลได้ 16, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง
- **เลเวล 13** Proficiency Bonus +5, Bardic Die d10, รู้ Cantrip 4, เตรียมสเปลได้ 17, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง
- **เลเวล 14** Proficiency Bonus +5, ได้ความสามารถ Subclass Feature, Bardic Die d10, รู้ Cantrip 4, เตรียมสเปลได้ 17, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง
- **เลเวล 15** Proficiency Bonus +5, Bardic Die d12, รู้ Cantrip 4, เตรียมสเปลได้ 18, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง
- **เลเวล 16** Proficiency Bonus +5, ได้ความสามารถ ASI, Bardic Die d12, รู้ Cantrip 4, เตรียมสเปลได้ 18, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง
- **เลเวล 17** Proficiency Bonus +6, Bardic Die d12, รู้ Cantrip 4, เตรียมสเปลได้ 19, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 2 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง
- **เลเวล 18** Proficiency Bonus +6, ได้ความสามารถ Superior Inspiration [แนะนำ], Bardic Die d12, รู้ Cantrip 4, เตรียมสเปลได้ 20, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 3 ช่อง, Spell Slot ระดับ 6 จำนวน 1 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง
- **เลเวล 19** Proficiency Bonus +6, ได้ความสามารถ Epic Boon Feat, Bardic Die d12, รู้ Cantrip 4, เตรียมสเปลได้ 21, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 3 ช่อง, Spell Slot ระดับ 6 จำนวน 2 ช่อง, Spell Slot ระดับ 7 จำนวน 1 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง
- **เลเวล 20** Proficiency Bonus +6, ได้ความสามารถ Words of Creation, Bardic Die d12, รู้ Cantrip 4, เตรียมสเปลได้ 22, Spell Slot ระดับ 1 จำนวน 4 ช่อง, Spell Slot ระดับ 2 จำนวน 3 ช่อง, Spell Slot ระดับ 3 จำนวน 3 ช่อง, Spell Slot ระดับ 4 จำนวน 3 ช่อง, Spell Slot ระดับ 5 จำนวน 3 ช่อง, Spell Slot ระดับ 6 จำนวน 2 ช่อง, Spell Slot ระดับ 7 จำนวน 2 ช่อง, Spell Slot ระดับ 8 จำนวน 1 ช่อง, Spell Slot ระดับ 9 จำนวน 1 ช่อง

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 แรงบันดาลใจของบาร์ด (Bardic Inspiration) ความสามารถหลักของคลาส

**Bonus Action:** เลือกเพื่อนร่วมทีม 1 คนในระยะ 60 ฟุต (ที่ไม่ใช่ตัวคุณ)
มอบ **Bardic Inspiration Die (d6)** ให้

เพื่อนสามารถใช้ได้ภายใน 1 ชั่วโมง:
- ทอยเต๋าแล้ว บวกผลเข้ากับ d20 Test 1 ครั้ง (Attack Roll, Ability Check, หรือ Saving Throw)
- **ใช้ได้แม้หลังทอย d20 แล้ว** [แนะนำ] แต่ต้องใช้ก่อน DM บอกว่าสำเร็จหรือไม่

**จำนวนครั้ง:** เท่ากับ **ขั้นต่ำ 1 (Charisma modifier)**
**ฟื้น:** **เลเวล 1-4 (Long Rest)** Short Rest ด้วย (เลเวล 5+)

**ขนาดเต๋าตามเลเวล:**

- เลเวล 1 ถึง 4 ใช้เต๋า d6
- เลเวล 5 ถึง 9 ใช้เต๋า d8
- เลเวล 10 ถึง 14 ใช้เต๋า d10
- เลเวล 15 ถึง 20 ใช้เต๋า d12

**เวลาที่ควรใช้ที่สุด:** ให้ Fighter/Barbarian ตอนโจมตีบอส, ให้เพื่อนที่ทอย Saving Throw สำคัญ และ ให้ Rogue ตอน Stealth เข้าปราสาท

---

### เลเวล 1 Spellcasting

- ใช้ **Charisma** เป็นค่าร่ายเวท
- **Spell Save DC = 8 + CHA modifier + Proficiency Bonus**
- **Spell Attack = CHA modifier + Proficiency Bonus**
- เปลี่ยนสเปลที่เตรียมไว้ได้ 1 อัน ทุกครั้งที่เลื่อนเลเวล (ไม่ใช่ทุกวันเหมือน Cleric/Wizard)
- **Spellcasting Focus:** **เครื่องดนตรี**

---

### เลเวล 2 ความเชี่ยวชาญ (Expertise)

เลือก Skill 2 อย่าง ที่มี Proficiency บวก Proficiency Bonus สองเท่า
(ได้เพิ่มอีก 2 สกิลที่เลเวล 9)

**แนะนำ:** Persuasion [แนะนำมาก] + Deception (สายเจรจา) หรือ Perception + Stealth (สายสอดแนม)

---

### เลเวล 2 เป็ดที่ทำได้ทุกอย่าง (Jack of All Trades)

**บวก ครึ่งหนึ่งของ Proficiency Bonus (ปัดลง) ในการทอย Ability Check ทุกอย่างที่คุณ *ไม่มี* Proficiency**

ค่าที่บวกได้ในแต่ละเลเวล คือครึ่งหนึ่งของ Proficiency Bonus ปัดเศษลง มีดังนี้

- เลเวล 2 ถึง 8 บวก 1
- เลเวล 9 ถึง 16 บวก 2
- เลเวล 17 ถึง 20 บวก 3

**รวมถึงการทอย Initiative ด้วย!** Bard ทำอะไรก็ไม่ค่อยห่วย

---

### เลเวล 5 บ่อเกิดแรงบันดาลใจ (Font of Inspiration)

Bardic Inspiration ฟื้นทั้งหมดเมื่อจบ Short Rest หรือ Long Rest
และคุณสามารถใช้ Spell Slot 1 ช่อง เพื่อฟื้น Bardic Inspiration 1 ครั้งได้ (ฟรี, ไม่ใช้ Action) [แนะนำ]

**ทำไมนี่คือจุดเปลี่ยนของ Bard:** จากที่ต้องประหยัด กลายเป็น แจก Bardic Inspiration ได้แทบทุกเทิร์น

---

### เลเวล 7 ต้านมนตร์ (Countercharm)

**Reaction:** เมื่อคุณหรือเพื่อนในระยะ 30 ฟุต ทอย Saving Throw ล้มเหลว ต่อสภาวะ Charmed หรือ Frightened
ให้ทอยใหม่ได้ พร้อมบวก Bardic Inspiration Die (ต้องใช้ Bardic Inspiration 1 ครั้ง)

---

### เลเวล 10 ความลับแห่งเวทมนตร์ (Magical Secrets)

ตั้งแต่เลเวล 10 เป็นต้นไป เมื่อคุณเตรียมสเปล
คุณสามารถเลือกจากรายการเวทของ Bard, Cleric, Druid, และ Wizard ได้ทั้งหมด!

ทำไมนี่คือ Feature ที่ทำให้ Bard เป็นคลาสที่ทรงพลังที่สุด:

- **Counterspell** [แนะนำอย่างยิ่ง] Wizard
- **Fireball** [แนะนำมาก] Wizard
- **Spirit Guardians** [แนะนำอย่างยิ่ง] Cleric
- **Revivify** [แนะนำมาก] Cleric
- **Wall of Force** [แนะนำอย่างยิ่ง] Wizard
- **Conjure Animals** Druid
- **Healing Word / Mass Heal** Cleric
- **Wish** (เลเวล 17!) [แนะนำอย่างยิ่ง] Wizard

กฎ 2024 เปลี่ยนจากกฎเก่าอย่างมาก เมื่อก่อนเลือกได้แค่ 2 สเปลถาวร แต่ตอนนี้ เข้าถึงได้ทั้ง 4 รายการเวทเลย

---

### เลเวล 18 แรงบันดาลใจเหนือชั้น (Superior Inspiration)

เมื่อคุณทอย Initiative ฟื้น Bardic Inspiration ให้เหลืออย่างน้อย 2 ครั้ง

---

### เลเวล 20 วจนะแห่งการสร้าง (Words of Creation) Capstone

- Power Word Heal และ Power Word Kill เตรียมไว้เสมอ (ไม่นับโควตา)
- เมื่อร่ายสเปลทั้งสอง สามารถกำหนดเป้าหมายเพิ่มอีก 1 ตัว [แนะนำ] ที่อยู่ในระยะ 10 ฟุตจากเป้าหมายแรก

---

## Subclasses (Bard College) เลือกที่เลเวล 3

Bard มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ เลเวล 3, 6, 14

---

### 1. College of Lore วิทยาลัยแห่งตำนาน

**ธีม:** นักสะสมความรู้และความลับ สายเวทและซัพพอร์ตที่แข็งแรงที่สุด

**เลเวล 3 Bonus Proficiencies**

ได้ Skill Proficiency เพิ่ม 3 อย่าง ตามที่เลือก

**เลเวล 3 Cutting Words**

**Reaction:** [แนะนำมาก] เมื่อศัตรูในระยะ 60 ฟุตทอย Attack Roll, Ability Check, หรือ Damage Roll ลบ Bardic Inspiration Die ออกจากผลนั้น (ใช้หลังทอย ก่อนรู้ผล)

**เลเวล 6 Magical Discoveries**

[แนะนำ] เรียนรู้สเปล 2 อัน จากรายการ Cleric, Druid, หรือ Wizard (ระดับที่ร่ายได้) เตรียมไว้เสมอ ไม่นับโควตา

**เลเวล 14 Peerless Skill**

เมื่อคุณทอย Ability Check หรือ Attack Roll ล้มเหลว บวก Bardic Inspiration Die เข้าไป [แนะนำ] (ถ้ายังล้มเหลว ไม่เสีย Bardic Inspiration)

**แนะนำที่สุดโดยรวม** Cutting Words ทำให้บอสตีพลาดหรือทำดาเมจน้อยลงได้ตลอด

---

### 2. College of Valor วิทยาลัยแห่งวีรกรรม

**ธีม:** Bard นักรบ ร้องเพลงสงครามและลุยเอง

**เลเวล 3 Combat Inspiration**

[แนะนำ] ผู้ที่มี Bardic Inspiration สามารถใช้เพื่อ:
- **เพิ่มดาเมจ** ของการโจมตี (ใช้หลังทอยดาเมจ)
- **หรือเพิ่ม AC** เมื่อถูกโจมตี (**Reaction**, ใช้ก่อนรู้ผล)

**เลเวล 3 Martial Training**

[แนะนำ] ได้ Proficiency ใน **Martial Weapons** และ **Medium Armor + Shield** และ และใช้ เครื่องดนตรีเป็น Spellcasting Focus ขณะถืออาวุธได้

**เลเวล 6 Extra Attack**

**โจมตีได้ 2 ครั้ง** [แนะนำมาก] และ และสามารถแทนการโจมตี 1 ครั้ง ด้วยการร่าย Cantrip ที่มี Casting Time เป็น Action

**เลเวล 14 Battle Magic**

หลังจากร่ายสเปลระดับ 1 ขึ้นไปด้วย Action ใช้ Bonus Action โจมตีด้วยอาวุธ 1 ครั้ง [แนะนำ]

**สายที่ยืนแนวหน้าได้** AC 17-18 (Half Plate + Shield) + โจมตี 2 ครั้ง

---

### 3. College of Dance วิทยาลัยแห่งการเต้นรำ

**ธีม:** ผู้เคลื่อนไหวอย่างสง่างาม คล่องแคล่วและป้องกันตัวเก่ง

**เลเวล 3 Dazzling Footwork**

[แนะนำ] ตราบที่ไม่ใส่เกราะและไม่ถือโล่:
- **AC = 10 + DEX + CHA** [แนะนำ]
- Unarmed Strike ใช้ DEX และทำดาเมจ = Bardic Inspiration Die + DEX (เป็น Bludgeoning)
- 1 ครั้ง/เทิร์น: เมื่อตีโดนด้วย Unarmed Strike เพิ่มดาเมจ Bardic Inspiration Die

**เลเวล 6 Inspiring Movement**

**Reaction:** เมื่อศัตรูเข้ามาใกล้เพื่อนในระยะ 5 ฟุต คุณเคลื่อนที่ครึ่ง Speed และเพื่อนเคลื่อนที่ครึ่ง Speed ด้วย (ไม่โดน Opportunity Attack)

**เลเวล 6 Tandem Footwork**

[แนะนำ] เมื่อทอย Initiative คุณและเพื่อนในระยะ 30 ฟุต บวก Bardic Inspiration Die ในการทอย Initiative (ใช้ Bardic Inspiration 1 ครั้ง)

**เลเวล 14 Leading Evasion**

[แนะนำมาก] เมื่อทอย **DEX Save** เพื่อลดดาเมจครึ่ง สำเร็จ = 0, ล้มเหลว = ครึ่ง และ และเพื่อนในระยะ 5 ฟุตได้ผลนี้ด้วย!

**สายที่มี AC สูงที่สุดของ Bard** DEX 20 + CHA 20 = **AC 20** โดยไม่ใส่เกราะ

---

### 4. College of Glamour วิทยาลัยแห่งมนตร์เสน่ห์

**ธีม:** Bard ผู้ได้รับพลังจาก Feywild ควบคุมและป้องกันทีมได้ดีที่สุด

**เลเวล 3 Beguiling Magic**

[แนะนำ] และ ได้สเปล **Charm Person** และ **Mirror Image** เตรียมไว้เสมอ
- หลังร่ายสเปล Enchantment หรือ Illusion: ทำให้สิ่งมีชีวิตในระยะ 60 ฟุตทอย **WIS Save** ล้มเหลว = Charmed หรือ Frightened 1 นาที (ใช้ได้ Prof Bonus ครั้ง/Long Rest)

**เลเวล 3 Mantle of Inspiration**

Bonus Action + Bardic Inspiration 1 ครั้ง: [แนะนำมาก] ให้เพื่อนได้ถึง CHA modifier คน ในระยะ 60 ฟุต:
- Temp HP = 2 คูณ Bardic Inspiration Die
- และเคลื่อนที่ได้ทันทีเท่ากับ Speed โดยไม่โดน Opportunity Attack

**เลเวล 6 Mantle of Majesty**

**Bonus Action:** [แนะนำ] ร่าย Command ฟรี (ไม่เสีย Slot) และ ร่ายซ้ำได้ทุกเทิร์นด้วย Bonus Action เป็นเวลา 1 นาที ใช้ได้ 1 ครั้ง/Long Rest (หรือใช้ Spell Slot ระดับ 3)

**เลเวล 14 Unbreakable Majesty**

**Bonus Action:** [แนะนำมาก] เข้าสู่สภาวะสง่างาม 1 นาที:
- ศัตรูที่จะโจมตีคุณต้องทอย CHA Save ล้มเหลว = ต้องเปลี่ยนเป้าหมายและเสีย Action นั้น
- ถ้าสำเร็จ = มันเสียเปรียบในการโจมตีคุณทั้งเทิร์น
- ใช้ได้ 1 ครั้ง/Short Rest

สายป้องกันตัวและควบคุมที่ดีที่สุด Unbreakable Majesty ทำให้ศัตรูตีคุณไม่ได้เลย

---

## เปรียบเทียบ 4 Subclass

- **จุดเด่น** ซัพพอร์ต+เวทดีสุด ยืนแนวหน้าได้ AC สูง + คล่อง ควบคุม+ป้องกัน
- **ความยาก** ง่าย ง่าย กลาง กลาง
- **ช่วยทีม** สูงสุด กลาง สูง สูงสุด
- **แนะนำมือใหม่** ใช่ ใช่ ใช่ ใช่

---
---

## เวทของ Bard

Bard ใช้ค่า CHA ในการร่ายเวท

Spell Save DC เท่ากับ 8 บวก Proficiency Bonus บวก CHA modifier ส่วน Spell Attack Bonus เท่ากับ Proficiency Bonus บวก CHA modifier

รายการเวททั้งหมดของคลาสนี้ พร้อมรายละเอียดว่าร่ายด้วยอะไร ระยะเท่าไหร่ และให้ผลยังไง ย้ายไปอยู่ที่ [เวทของนักดนตรีเวท (Bard)](../10-spells/class-lists/bard.md) แล้ว

ในไฟล์นั้นมีหัวข้อ "สเปลที่แนะนำสำหรับมือใหม่" อยู่ท้ายไฟล์ ซึ่งบอกว่าแต่ละระดับควรเอาอันไหนก่อน

ถ้าอยากดูสเปลเรียงตามระดับแทนที่จะเรียงตามคลาส ให้ดูที่ [รายละเอียดสเปล](../10-spells/00-spells-overview.md)

---

## คำแนะนำการสร้าง Bard

### ค่าพลังที่ควรจัด

- CHA สูงสุดเสมอ (17 20)
- DEX สูงรอง (14-16) AC (Light Armor) และ Initiative
- CON ปานกลาง (14) HP และ Concentration
- WIS ถ้าเหลือ
- INT / STR ต่ำได้ (Jack of All Trades ช่วยชดเชย)

### Species ที่แนะนำ

- **มนุษย์ (Human)** [แนะนำ] Feat ฟรี
- **ฮาล์ฟลิง (Halfling)** [แนะนำ] Luck (ทอย 1 ใหม่) Bard ทอยเยอะมาก
- **ลูกหลานปีศาจ (Tiefling)** [แนะนำ] สเปลฟรีเข้าธีม + CHA
- **ลูกหลานสวรรค์ (Aasimar)** Healing Hands + Necrotic Shroud (ใช้ CHA)
- **โนม (Gnome)** Advantage ใน INT/WIS/CHA Save
- **เอลฟ์ (Elf) สาย High** Cantrip + Misty Step ฟรี

### Background ที่แนะนำ
**Charlatan** (DEX/CON/CHA) [แนะนำมาก] ตรงเป๊ะทั้ง 3 ค่า, **STR/DEX/CHA ได้ Musician (Entertainer)** [แนะนำ] เข้าธีม, **Noble** (STR/INT/CHA) และ **Wayfarer** (DEX/WIS/CHA)

### Feat ที่แนะนำ (เลเวล 4+)

- **Ability Score Improvement (CHA)** [แนะนำมาก] ดัน CHA ถึง 20 กระทบทั้ง Spell DC และจำนวน Bardic Inspiration
- **War Caster** [แนะนำ] Advantage ในการรักษา Concentration
- **Resilient (Constitution)** [แนะนำ] Proficiency ใน CON Save
- **Fey Touched** [แนะนำ] +1 CHA + Misty Step + สเปลระดับ 1
- **Inspiring Leader** [แนะนำ] ให้ Temp HP ทั้งทีม (ใช้ CHA)
- **Lucky** ช่วยชีวิต
- **Skulker** ถ้าเล่นสายสอดแนม

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

- เก็บ Bardic Inspiration ไว้ไม่ใช้ แจกให้หมด เลเวล 5+ ฟื้นทุก Short Rest แล้ว
- ให้ Bardic Inspiration ก่อนเพื่อนทอย ให้ล่วงหน้าได้ แต่เพื่อนสามารถใช้หลังทอย d20 แล้ว บอกเพื่อนให้รอดูก่อน
- พยายามตีด้วยอาวุธ Bard มี Proficiency แค่ Simple Weapon ใช้ Cantrip Vicious Mockery ดีกว่า (ยกเว้น College of Valor/Dance)
- ไม่เลือก Expertise ใน Persuasion Bard คือหน้ากลุ่ม Persuasion + Deception ควรมี Expertise
- ลืมว่ามี Magical Secrets ที่เลเวล 10 วางแผนล่วงหน้า จะเอา Counterspell หรือ Spirit Guardians ดี
- ยืนแนวหน้า HP d8 + Light Armor ยืนกลางแนว

---

## สรุป Bard ในหนึ่งบรรทัด

Bardic Inspiration เปลี่ยนผลการทอยของทั้งทีม + Jack of All Trades ทำให้ทำอะไรก็ไม่ห่วย + Magical Secrets เข้าถึงสเปลจาก 4 คลาส = คลาสที่เก่งรอบด้านที่สุดในเกม

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
