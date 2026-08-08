# ผู้ทำสัญญา (Warlock)

[กลับหน้ารวมคลาส](00-classes-overview.md) | [สารบัญ](../README.md)

---

## ภาพรวม

**วอร์ล็อค / ผู้ทำสัญญา (Warlock)** คือผู้ที่แลกเปลี่ยนบางอย่างกับสิ่งเหนือธรรมชาติ (**Patron / ผู้อุปถัมภ์**) เพื่อแลกกับพลัง พวกเขามี **Spell Slot น้อยมาก แต่เป็นระดับสูงสุดเสมอ และฟื้นทุก Short Rest**

> **Warlock เล่นง่ายกว่าสายเวทอื่นมาก** — เพราะการโจมตีหลักคือ **Cantrip `Eldritch Blast`** ที่ร่ายได้ไม่จำกัด ส่วน Spell Slot เก็บไว้ใช้ตอนสำคัญ

---

## ข้อมูลพื้นฐาน (Class Table)

| หัวข้อ | ค่า |
|---|---|
| **Primary Ability** | **Charisma (CHA)** |
| **Hit Die** | **d8** |
| **HP เลเวล 1** | **8 + CON modifier** |
| **HP เลเวลถัดไป** | **1d8 + CON** (หรือค่าคงที่ **5 + CON**) |
| **Saving Throw Proficiency** | **Wisdom, Charisma** |
| **Armor Proficiency** | Light Armor |
| **Weapon Proficiency** | Simple Weapons |
| **Skill Proficiency** | เลือก **2** จาก: **Arcana, Deception, History, Intimidation, Investigation, Nature, Religion** |
| **Spellcasting Ability** | **Charisma (CHA)** |
| **Spellcasting Focus** | **Arcane Focus** |
| **Subclass (Otherworldly Patron)** | เลือกที่ **เลเวล 3** |

### อุปกรณ์เริ่มต้น

**เลือก A:** Leather Armor, Sickle, ×2 Dagger, Arcane Focus (ลูกแก้ว), Book (ตำราลึกลับ), Scholar's Pack, **15 GP**
**เลือก B:** **100 GP** ไปซื้อเอง

---

## ตารางความก้าวหน้าเลเวล 1-20

| เลเวล | Prof | Features | Invocations | Cantrips | เตรียม<br>สเปล | Spell<br>Slots | ระดับ<br>Slot |
|---|---|---|---|---|---|---|---|
| **1** | +2 | **Eldritch Invocations** [แนะนำ], **Pact Magic** [แนะนำมาก] | **1** | **2** | 2 | **1** | **1** |
| **2** | +2 | **Magical Cunning** | **3** | 2 | 3 | **2** | 1 |
| **3** | +2 | **Otherworldly Patron (Subclass)** [แนะนำ] | 3 | 2 | 4 | 2 | **2** |
| **4** | +2 | **ASI** | 3 | **3** | 5 | 2 | 2 |
| **5** | **+3** | — | **4** | 3 | 6 | 2 | **3** |
| **6** | +3 | **Subclass Feature** | 4 | 3 | 7 | 2 | 3 |
| **7** | +3 | — | **5** | 3 | 8 | 2 | **4** |
| **8** | +3 | **ASI** | 5 | 3 | 9 | 2 | 4 |
| **9** | **+4** | **Contact Patron** | **6** | 3 | 10 | 2 | **5** |
| **10** | +4 | **Subclass Feature** | 6 | **4** | 10 | 2 | 5 |
| **11** | +4 | **ระดับ 6 (Mystic Arcanum)** [แนะนำ] | 6 | 4 | 11 | **3** | 5 |
| **12** | +4 | **ASI** | **7** | 4 | 11 | 3 | 5 |
| **13** | **+5** | **ระดับ 7 (Mystic Arcanum)** [แนะนำ] | 7 | 4 | 12 | 3 | 5 |
| **14** | +5 | **Subclass Feature** | 7 | 4 | 12 | 3 | 5 |
| **15** | +5 | **ระดับ 8 (Mystic Arcanum)** [แนะนำ] | **8** | 4 | 13 | 3 | 5 |
| **16** | +5 | **ASI** | 8 | 4 | 13 | 3 | 5 |
| **17** | **+6** | **ระดับ 9 (Mystic Arcanum)** [แนะนำ] | 8 | 4 | 14 | **4** | 5 |
| **18** | +6 | — | **9** | 4 | 14 | 4 | 5 |
| **19** | +6 | **Epic Boon Feat** | 9 | 4 | 15 | 4 | 5 |
| **20** | +6 | **Eldritch Master** | 9 | 4 | 15 | 4 | 5 |

---

## เข้าใจ Pact Magic ก่อน (ระบบเวทที่ต่างจากทุกคลาส)

```
คลาสสายเวทอื่น (Wizard, Cleric ฯลฯ)
  - Slot เยอะ มีหลายระดับ เช่น ระดับ 1 จำนวน 4 ช่อง, ระดับ 2 จำนวน 3 ช่อง
  - ฟื้นเมื่อ Long Rest เท่านั้น

Warlock (Pact Magic)
  - Slot น้อยมาก มีแค่ 1-4 ช่อง
  - แต่ทุกช่องเป็นระดับสูงสุดที่มีเสมอ
  - ฟื้นทุก Short Rest
```

**ตัวอย่างที่เลเวล 5:**
- **Wizard เลเวล 5:** Slot ระดับ 1 ×4, ระดับ 2 ×3, ระดับ 3 ×2 = 9 ช่อง (ฟื้นตอน Long Rest)
- **Warlock เลเวล 5:** Slot **ระดับ 3 ×2** เท่านั้น — แต่ **ฟื้นทุก Short Rest** (พัก 3 ครั้ง = ได้ใช้ 6 ช่อง/วัน)

> **วิธีเล่น Warlock ที่ถูกต้อง:**
> 1. **โจมตีปกติด้วย `Eldritch Blast`** (ฟรี ไม่จำกัด)
> 2. **เก็บ Spell Slot ไว้ใช้กับสเปลควบคุมหรือดาเมจสูง** เท่านั้น
> 3. **ผลักดันให้ทีมพัก Short Rest บ่อย ๆ** — Warlock ได้ประโยชน์มากที่สุด

---

## Features ทีละเลเวล (รายละเอียด)

---

### เลเวล 1 — เวทแห่งพันธสัญญา (Pact Magic)

> - ใช้ **Charisma** เป็นค่าร่ายเวท
> - **Spell Save DC = 8 + CHA modifier + Proficiency Bonus**
> - **Spell Attack = CHA modifier + Proficiency Bonus**
> - **เปลี่ยนสเปลที่เตรียมไว้ได้ 1 อัน ทุกครั้งที่เลื่อนเลเวล**
> - **Spell Slot ฟื้นทั้งหมดเมื่อจบ Short Rest หรือ Long Rest** [แนะนำ]
> - **Spell Slot ทุกช่องเป็นระดับสูงสุดที่มีเสมอ** [แนะนำ] (สเปลระดับต่ำจะแรงขึ้นอัตโนมัติ)

---

### เลเวล 1 — มนตราลึกลับ (Eldritch Invocations) ความสามารถหลักของคลาส

> เลือก **Invocation** ตามจำนวนในตาราง — เป็น**ความสามารถถาวรที่กำหนดรูปแบบการเล่นของคุณ**
> **เปลี่ยนตัวเลือกได้ 1 อย่างทุกครั้งที่เลื่อนเลเวล** [แนะนำ]

 **ดูรายการ Invocation ทั้งหมดในหัวข้อถัดไป**

---

### เลเวล 2 — เล่ห์เหลี่ยมเวทมนตร์ (Magical Cunning)

> **ทำพิธี 1 นาที ฟื้น Spell Slot เท่ากับ `ครึ่งหนึ่งของจำนวน Slot สูงสุด (ปัดขึ้น)`**
> **ใช้ได้ 1 ครั้งต่อ Long Rest**

**ทำไมดี:** เท่ากับได้ Short Rest เพิ่มฟรี 1 ครั้งต่อวัน โดยใช้เวลาแค่ 1 นาที (ไม่ใช่ 1 ชั่วโมง)

---

### เลเวล 9 — ติดต่อผู้อุปถัมภ์ (Contact Patron)

> - ได้สเปล **`Contact Other Plane`** เตรียมไว้เสมอ
> - **ร่ายฟรี 1 ครั้งต่อ Long Rest** โดยไม่เสีย Slot — และเมื่อร่ายแบบนี้ **คุณติดต่อ Patron ของคุณโดยตรง จึงไม่ต้องทอย Save** (ปกติต้องทอย INT Save ไม่งั้นเสียสติ)

---

### เลเวล 11 — มนตราลี้ลับ (Mystic Arcanum)

> เลือก **สเปลระดับ 6 จำนวน 1 อัน** จากรายการ Warlock
> **ร่ายได้ฟรี 1 ครั้งต่อ Long Rest โดยไม่เสีย Spell Slot**
>
> **ได้เพิ่มตามเลเวล:**

| เลเวล | ได้สเปลระดับ |
|---|---|
| **11** | **6** |
| **13** | **7** |
| **15** | **8** |
| **17** | **9** |

> **นี่คือวิธีที่ Warlock เข้าถึงสเปลระดับสูง** — เพราะ Pact Magic Slot สูงสุดแค่ระดับ 5
> **เปลี่ยนตัวเลือกได้ทุกครั้งที่เลื่อนเลเวล**

---

### เลเวล 20 — อาจารย์แห่งมนตราลึกลับ (Eldritch Master) — Capstone

> **ใช้เวลา 1 นาที อ้อนวอน Patron ฟื้น Pact Magic Slot ทั้งหมด**
> **ใช้ได้ 1 ครั้งต่อ Long Rest** (นอกเหนือจาก Magical Cunning)

---
---

# มนตราลึกลับทั้งหมด (Eldritch Invocations)

> **Prereq** = เงื่อนไขที่ต้องมีก่อนถึงจะเลือกได้

---

## Pact Boon — พันธสัญญา 3 แบบ (เลือก 1 ก่อนเป็นอันดับแรก)

Invocation 3 อันนี้เป็น "แกนหลัก" ที่กำหนดสไตล์การเล่น — **ควรเลือก 1 อันตั้งแต่แรก**

### Pact of the Blade — พันธสัญญาแห่งดาบ

> **Bonus Action:** สร้าง **อาวุธพันธสัญญา (Pact Weapon)** ในมือ — เป็นอาวุธ Melee ชนิดใดก็ได้ที่คุณเลือก
>
> - **ใช้ CHA แทน STR/DEX ในการทอยโจมตีและดาเมจ** [แนะนำ]
> - **นับเป็น Magical Weapon**
> - **ได้ Proficiency ในอาวุธนั้นโดยอัตโนมัติ**
> - **หายไปเมื่ออยู่ห่างเกิน 5 ฟุตนานกว่า 1 นาที** (เรียกกลับได้ตลอด)
> - **ผูกอาวุธวิเศษที่มีอยู่แล้วให้เป็น Pact Weapon ได้** (ใช้เวลา 1 ชั่วโมง)

**เหมาะกับ:** ผู้เล่นที่อยากตีด้วยอาวุธ — **สาย "Hexblade" คลาสสิก**

---

### Pact of the Chain — พันธสัญญาแห่งโซ่ตรวน

> คุณได้สเปล **`Find Familiar`** เตรียมไว้เสมอ และ **ร่ายฟรีได้โดยไม่เสีย Slot** (1 ครั้ง/Long Rest)
>
> - **Familiar เลือกร่างพิเศษได้:** [แนะนำ] **Imp, Pseudodragon, Quasit, Skeleton, Slaad Tadpole, หรือ Sprite** (นอกเหนือจากสัตว์ปกติ)
> - **เมื่อคุณใช้ Attack action คุณสามารถสละการโจมตี 1 ครั้ง เพื่อให้ Familiar โจมตี 1 ครั้งแทน** [แนะนำ] (ใช้ Reaction ของมัน)

**เหมาะกับ:** ผู้เล่นสายสอดแนม/ยุทธวิธี — Familiar ทั้งช่วยสอดแนม ทั้งใช้ Help action

---

### Pact of the Tome — พันธสัญญาแห่งตำรา

> คุณได้ **ตำราเงามืด (Book of Shadows)**:
>
> - **Cantrip 3 อัน** [แนะนำ] จากรายการเวทของ **คลาสใดก็ได้** (ใช้ CHA ร่าย)
> - **สเปลระดับ 1 ที่มีแท็ก [Ritual] จำนวน 2 อัน** [แนะนำ] จากคลาสใดก็ได้ — **ร่ายแบบ Ritual ได้ฟรี**
> - **เปลี่ยนตัวเลือกได้ทุกครั้งที่เลื่อนเลเวล**
> - ถ้าหนังสือหาย สร้างใหม่ได้ด้วยพิธี 1 ชั่วโมง

**เหมาะกับ:** ผู้เล่นที่อยากมีเครื่องมือหลากหลาย — เอา `Guidance` (Cleric), `Mage Hand`, `Minor Illusion` + Ritual `Find Familiar`, `Detect Magic`

---

## Invocations สำหรับ สำคัญที่สุด (Eldritch Blast)

| Invocation | Prereq | ผล |
|---|---|---|
| **ระเบิดทรมาน (Agonizing Blast)** [แนะนำอย่างยิ่ง] | มี Cantrip โจมตีที่ใช้ Spell Attack | **บวก CHA modifier ในดาเมจของ Cantrip นั้นทุกลำ** |
| **ระเบิดผลักดัน (Repelling Blast)** [แนะนำมาก] | มี `Eldritch Blast` | เมื่อตีโดนด้วย `Eldritch Blast` **ผลักเป้าหมายถอย 10 ฟุต** (ต่อลำ) |
| **หอกลึกลับ (Eldritch Spear)** | มี `Eldritch Blast` | **ระยะของ `Eldritch Blast` เพิ่มเป็น 300 ฟุต** |

> **`Agonizing Blast` คือ Invocation ที่แทบทุก Warlock ต้องเอา**
> ```
> เลเวล 5, CHA 18 (+4): Eldritch Blast = 2 ลำ × (1d10 + 4) = ~19 ดาเมจ/เทิร์น (ฟรี ไม่จำกัด!)
> เลเวล 11: 3 ลำ = ~28 ดาเมจ | เลเวล 17: 4 ลำ = ~38 ดาเมจ
> ```
> **`Repelling Blast` ผลักได้ 4 ลำ × 10 ฟุต = 40 ฟุต** — ผลักบอสตกเหว หรือดันออกจากเพื่อน

---

## Invocations สำหรับ Pact of the Blade

| Invocation | Prereq | ผล |
|---|---|---|
| **ดาบกระหาย (Thirsting Blade)** [แนะนำอย่างยิ่ง] | เลเวล 5, Pact of the Blade | **โจมตีด้วย Pact Weapon ได้ 2 ครั้ง** [แนะนำ] (Extra Attack) |
| **ฟาดฟันลึกลับ (Eldritch Smite)** [แนะนำมาก] | เลเวล 5, Pact of the Blade | เมื่อตีโดนด้วย Pact Weapon **ใช้ Spell Slot เพื่อเพิ่มดาเมจ `1d8 Force ต่อระดับ Slot +1d8`** และ **ทำให้เป้าหมาย Prone** (ถ้าเป็น Huge หรือเล็กกว่า) |
| **ผู้ดื่มชีวิต (Lifedrinker)** [แนะนำมาก] | เลเวล 9, Pact of the Blade | **1 ครั้ง/เทิร์น:** [แนะนำ] เพิ่มดาเมจ **`CHA modifier` เป็น Necrotic, Psychic, หรือ Radiant** และ **คุณฟื้น HP เท่ากับดาเมจนั้น** |
| **ดาบกลืนกิน (Devouring Blade)** [แนะนำอย่างยิ่ง] | เลเวล 12, Thirsting Blade | **โจมตีด้วย Pact Weapon ได้ 3 ครั้ง** [แนะนำ] |

> **ชุด Pact of the Blade:** `Pact of the Blade` `Thirsting Blade` (Lv5) `Eldritch Smite` (Lv5) `Lifedrinker` (Lv9) `Devouring Blade` (Lv12)

---

## Invocations สำหรับ Pact of the Chain

| Invocation | Prereq | ผล |
|---|---|---|
| **พรแห่งเจ้าโซ่ (Investment of the Chain Master)** [แนะนำมาก] | เลเวล 5, Pact of the Chain | Familiar ได้: **Fly หรือ Swim Speed 40 ฟุต** • **การโจมตีของมันนับเป็น Magical** • **สั่งมันด้วย Bonus Action** • **ศัตรูที่ Save ต่อ Familiar ใช้ DC ของคุณ** • **Reaction: ให้มัน Resistance ต่อดาเมจ** |
| **ของขวัญแห่งผู้ไม่ตาย (Gift of the Ever-Living Ones)** [แนะนำ] | Pact of the Chain | เมื่อคุณฟื้น HP ขณะที่ Familiar อยู่ในระยะ 100 ฟุต **ใช้ค่าสูงสุดของเต๋าทุกลูก** |

---

## Invocations สำหรับ Pact of the Tome

| Invocation | Prereq | ผล |
|---|---|---|
| **ตำราความลับโบราณ (Book of Ancient Secrets)** [แนะนำ] | Pact of the Tome | **เพิ่มสเปล Ritual ใน Book of Shadows ได้อีก** (คัดลอกจาก Scroll หรือ Spellbook ที่หาเจอ) |

---

## Invocations สายป้องกันและใช้ประโยชน์

| Invocation | Prereq | ผล |
|---|---|---|
| **ตาปีศาจ (Devil's Sight)** [แนะนำอย่างยิ่ง] | — | **มองเห็นในความมืดปกติและ Magical Darkness ได้ไกล 120 ฟุต** [แนะนำ] |
| **เกราะเงา (Armor of Shadows)** [แนะนำมาก] | — | **ร่าย `Mage Armor` ใส่ตัวเองได้ไม่จำกัด โดยไม่เสีย Slot** [แนะนำ] (AC 13 + DEX) |
| **จิตลึกลับ (Eldritch Mind)** [แนะนำมาก] | — | **Advantage ในการทอย Concentration Save ทั้งหมด** [แนะนำ] |
| **พลังปีศาจ (Fiendish Vigor)** [แนะนำ] | — | **ร่าย `False Life` ใส่ตัวเองได้ไม่จำกัด** (ได้ Temp HP **สูงสุด 4+4 = 8** เสมอ) |
| **หน้ากากพันหน้า (Mask of Many Faces)** [แนะนำ] | — | **ร่าย `Disguise Self` ได้ไม่จำกัด** |
| **นิมิตหมอก (Misty Visions)** | — | **ร่าย `Silent Image` ได้ไม่จำกัด** |
| **กระโดดข้ามภพ (Otherworldly Leap)** | — | **ร่าย `Jump` ใส่ตัวเองได้ไม่จำกัด** |
| **สายตาสองจิต (Gaze of Two Minds)** | — | สัมผัสสิ่งมีชีวิตที่ยินยอม **มองและได้ยินผ่านประสาทสัมผัสของมัน** |
| **บทเรียนจากปฐมชน (Lessons of the First Ones)** [แนะนำ] | — | **ได้ Origin Feat 1 อย่าง** [แนะนำ] (เอาซ้ำได้ แต่ต้องเลือก Feat ใหม่) |
| **(ดูด้านบน) (Pact of the Blade / Chain / Tome)** | — | เลือก Pact Boon |

---

## Invocations เลเวลสูง

| Invocation | Prereq | ผล |
|---|---|---|
| **ก้าวย่างลอยฟ้า (Ascendant Step)** [แนะนำ] | เลเวล 5 | **ร่าย `Levitate` ใส่ตัวเองได้ไม่จำกัด** |
| **ของขวัญแห่งห้วงลึก (Gift of the Depths)** | เลเวล 5 | **หายใจใต้น้ำได้ + Swim Speed = Speed** • ร่าย `Water Breathing` ฟรี 1 ครั้ง/Long Rest |
| **ผู้เชี่ยวชาญพันร่าง (Master of Myriad Forms)** [แนะนำ] | เลเวล 5 | **ร่าย `Alter Self` ได้ไม่จำกัด** |
| **หนึ่งเดียวกับเงา (One with Shadows)** [แนะนำมาก] | เลเวล 5 | **ร่าย `Invisibility` ใส่ตัวเองได้ไม่จำกัด** [แนะนำ] |
| **เสียงกระซิบจากหลุมศพ (Whispers of the Grave)** | เลเวล 7 | **ร่าย `Speak with Dead` ได้ไม่จำกัด** |
| **นิมิตแดนไกล (Visions of Distant Realms)** | เลเวล 15 | **ร่าย `Arcane Eye` ได้ไม่จำกัด** |
| **ตาแม่มด (Witch Sight)** [แนะนำ] | เลเวล 15 | **เห็นรูปร่างที่แท้จริง** ของสิ่งที่แปลงร่างหรือใช้ภาพลวงตา ในระยะ 30 ฟุต |

---

## ชุด Invocation ที่แนะนำ

### สาย ยิง Eldritch Blast (Blaster) — แนะนำมือใหม่ที่สุด

| เลเวล | Invocation ที่มี |
|---|---|
| 1 | `Agonizing Blast` |
| 2 | + `Devil's Sight` + `Armor of Shadows` |
| 5 | + `Repelling Blast` |
| 7 | + `Eldritch Mind` |
| 9 | + `One with Shadows` |

### สาย ตีด้วยอาวุธ (Blade)

| เลเวล | Invocation ที่มี |
|---|---|
| 1 | `Pact of the Blade` |
| 2 | + `Agonizing Blast` + `Armor of Shadows` |
| 5 | + `Thirsting Blade` |
| 7 | + `Eldritch Smite` |
| 9 | + `Lifedrinker` |
| 12 | + `Devouring Blade` |

---

## Subclasses (Otherworldly Patron) — เลือกที่เลเวล 3

Warlock มี Subclass 4 สายใน PHB 2024 ได้ Feature ที่ **เลเวล 3, 6, 10, 14**
**ทุก Subclass ให้ชุดสเปลที่เตรียมไว้เสมอ (ไม่นับโควตา)**

---

### 1. Fiend Patron — ผู้อุปถัมภ์ปีศาจ

> **ธีม:** ทำสัญญากับ Devil หรือ Demon — **สายที่ทนที่สุดและง่ายที่สุด**

**Fiend Spells (เตรียมไว้เสมอ):**

| เลเวล | สเปล |
|---|---|
| 3 | `Burning Hands`, `Command`, `Scorching Ray`, `Suggestion` |
| 5 | `Fireball`, `Stinking Cloud` |
| 7 | `Fire Shield`, `Wall of Fire` |
| 9 | `Geas`, `Insect Plague` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Dark One's Blessing** | **เมื่อคุณทำให้ศัตรูเหลือ 0 HP** [แนะนำมาก] (หรือเมื่อเริ่มการต่อสู้) **ได้ Temp HP = `CHA modifier + เลเวล Warlock`** |
| **6** | **Dark One's Own Luck** | [แนะนำมาก] เมื่อทอย **Ability Check หรือ Saving Throw** **บวก `1d10`** เข้าไป (ใช้หลังทอย ก่อนรู้ผล) — ใช้ได้ **Prof Bonus ครั้ง/Long Rest** |
| **10** | **Fiendish Resilience** | [แนะนำ] เลือก **Damage Type 1 ประเภท** (เปลี่ยนได้ทุก Short/Long Rest) **ได้ Resistance ต่อธาตุนั้น** |
| **14** | **Hurl Through Hell** | **1 ครั้ง/เทิร์น** [แนะนำมาก] เมื่อตีโดน เป้าหมายทอย **CHA Save** — ล้มเหลว = **หายไปสู่นรก จนถึงจบเทิร์นหน้าของคุณ** แล้วกลับมาพร้อมรับ **`8d10 Psychic damage`** — ใช้ได้ Prof Bonus ครั้ง/Long Rest |

> **แนะนำมือใหม่ที่สุด** — Temp HP ฟรีทุกครั้งที่ฆ่าศัตรู ทำให้ Warlock ที่ HP d8 อยู่รอดได้

---

### 2. Celestial Patron — ผู้อุปถัมภ์สวรรค์

> **ธีม:** ทำสัญญากับสิ่งมีชีวิตสวรรค์ — **Warlock ที่รักษาเพื่อนได้**

**Celestial Spells (เตรียมไว้เสมอ):**

| เลเวล | สเปล |
|---|---|
| 3 | `Aid`, `Cure Wounds`, `Guiding Bolt`, `Lesser Restoration` |
| 5 | `Daylight`, `Revivify` |
| 7 | `Guardian of Faith`, `Wall of Fire` |
| 9 | `Greater Restoration`, `Summon Celestial` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Healing Light** | [แนะนำมาก] มี **คลังเต๋า `d6` จำนวน `1 + เลเวล Warlock`** — **Bonus Action:** ใช้เต๋าได้ถึง `CHA modifier` ลูก เพื่อฟื้น HP ให้ตัวเองหรือเพื่อนในระยะ 60 ฟุต • ฟื้นคลังเมื่อ Long Rest |
| **3** | **Bonus Cantrips** | ได้ Cantrip **`Light`** และ **`Sacred Flame`** ฟรี |
| **6** | **Radiant Soul** | [แนะนำมาก] • **Resistance ต่อ Radiant damage**<br>• **1 ครั้ง/เทิร์น:** [แนะนำ] เมื่อสเปลของคุณทำ **Radiant หรือ Fire damage** **เพิ่มดาเมจ `CHA modifier`** |
| **10** | **Celestial Resilience** | **เมื่อจบ Short Rest หรือ Long Rest:** [แนะนำ] คุณและเพื่อนได้ถึง 5 คนได้ **Temp HP**<br>• คุณ: `เลเวล Warlock + CHA modifier`<br>• เพื่อน: `ครึ่งเลเวล Warlock + CHA modifier` |
| **14** | **Searing Vengeance** | [แนะนำมาก] เมื่อคุณกำลังจะทอย **Death Saving Throw** **ฟื้นทันทีด้วย HP = ครึ่งหนึ่งของ HP สูงสุด + ลุกขึ้นยืน** • และศัตรูในระยะ 30 ฟุตทอย **CON Save** — ล้มเหลว = **`2d8 + CHA modifier` Radiant + Blinded** — ใช้ได้ 1 ครั้ง/Long Rest |

> **สายซัพพอร์ตที่ดีที่สุดของ Warlock** — Healing Light ทำให้ทีมที่ไม่มี Cleric อยู่รอดได้

---

### 3. Archfey Patron — ผู้อุปถัมภ์เจ้าแห่งภูตพราย

> **ธีม:** ทำสัญญากับผู้ปกครองแห่ง Feywild — **สายควบคุมและหลบหลีก**

**Archfey Spells (เตรียมไว้เสมอ):**

| เลเวล | สเปล |
|---|---|
| 3 | `Calm Emotions`, `Faerie Fire`, `Misty Step`, `Phantasmal Force`, `Sleep` |
| 5 | `Blink`, `Plant Growth` |
| 7 | `Dominate Beast`, `Greater Invisibility` |
| 9 | `Dominate Person`, `Seeming` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Steps of the Fey** | **ร่าย `Misty Step` ได้ `Prof Bonus` ครั้ง/Long Rest โดยไม่เสีย Slot** [แนะนำมาก] • [แนะนำ] และทุกครั้งที่ร่าย เลือกผลเพิ่ม 1 อย่าง:<br>**Refreshing Step** — คุณหรือเพื่อน 1 คนที่มองเห็น **ได้ Temp HP = `1d10 + CHA modifier`**<br>**Taunting Step** — ศัตรูในระยะ 5 ฟุตจากจุดที่คุณหายไป ทอย **WIS Save** — ล้มเหลว = **เสียเปรียบเมื่อโจมตีคนอื่นที่ไม่ใช่คุณ** จนจบเทิร์นหน้า |
| **6** | **Misty Escape** | **Reaction:** [แนะนำมาก] เมื่อได้รับดาเมจ **ร่าย `Steps of the Fey` ทันทีเพื่อวาร์ปหนี** และ **ได้ Resistance ต่อดาเมจนั้น** |
| **10** | **Beguiling Defenses** | [แนะนำ] • **ภูมิคุ้มกันสภาวะ Charmed**<br>• **Reaction:** [แนะนำ] เมื่อศัตรูพยายามทำให้คุณ Charmed **สะท้อนกลับ** — มันทอย **WIS Save** — ล้มเหลว = **`2d10 Psychic` และ Charmed โดยคุณ 1 นาที** |
| **14** | **Bewitching Magic** | **หลังจากร่ายสเปล Enchantment หรือ Illusion ด้วย Action ใช้ Bonus Action ร่าย `Misty Step` ฟรี** [แนะนำมาก] (ไม่เสีย Slot และไม่นับโควตา) |

> **สายที่หนีเก่งที่สุด** — วาร์ปได้หลายครั้งต่อวัน แถมได้ Temp HP หรือทำให้ศัตรูเสียเปรียบทุกครั้ง

---

### 4. Great Old One Patron — ผู้อุปถัมภ์อสูรกายโบราณ

> **ธีม:** ทำสัญญากับสิ่งมีชีวิตนอกจักรวาลที่ไม่อาจเข้าใจได้ — **สายพลังจิตและควบคุม**

**Psychic Spells (เตรียมไว้เสมอ):**

| เลเวล | สเปล |
|---|---|
| 3 | `Detect Thoughts`, `Dissonant Whispers`, `Phantasmal Force`, `Tasha's Hideous Laughter` |
| 5 | `Clairvoyance`, `Hunger of Hadar` |
| 7 | `Confusion`, `Summon Aberration` |
| 9 | `Modify Memory`, `Telekinesis` |

| เลเวล | Feature | ทำอะไร |
|---|---|---|
| **3** | **Awakened Mind** | **สื่อสารทางจิตกับสิ่งมีชีวิตที่มองเห็นในระยะ 30 ฟุต** [แนะนำ] (มันไม่จำเป็นต้องรู้ภาษาเดียวกัน แต่ต้องเข้าใจภาษาอย่างน้อย 1 ภาษา) |
| **3** | **Psychic Spells** | [แนะนำมาก] • **เมื่อสเปล Warlock ของคุณทำดาเมจ เปลี่ยนเป็น Psychic ได้**<br>• **ร่ายสเปล Enchantment หรือ Illusion โดยไม่ต้องใช้องค์ประกอบ Verbal และ Somatic** [แนะนำ] (ร่ายเงียบ ๆ ไม่มีใครรู้!) |
| **6** | **Clairvoyant Combatant** | **Bonus Action:** [แนะนำมาก] เลือกศัตรู 1 ตัวที่สื่อสารทางจิตด้วย **คุณมี Advantage ในการโจมตีมัน** และ **มันเสียเปรียบเมื่อโจมตีคุณ** เป็นเวลา 1 นาที — ใช้ได้ Prof Bonus ครั้ง/Long Rest |
| **10** | **Eldritch Hex** | [แนะนำ] ได้สเปล **`Hex`** เตรียมไว้เสมอ • **ศัตรูที่ติด `Hex` ของคุณ เสียเปรียบในการทอย Saving Throw ต่อค่าที่คุณเลือกใน Hex** [แนะนำ] |
| **14** | **Create Thrall** | **Magic action:** [แนะนำมาก] สัมผัสสิ่งมีชีวิตที่ **Incapacitated** มันทอย **WIS Save** — ล้มเหลว = **Charmed โดยคุณอย่างถาวร** จนกว่าจะถูก `Remove Curse` • คุณสื่อสารทางจิตกับมันได้ข้ามระยะทางในมิติเดียวกัน |

> **สายที่แข็งแรงที่สุดในเชิงกลยุทธ์** — Psychic Spells ทำให้ร่ายเวทได้โดยไม่มีใครรู้ = ทรงพลังมากในการเล่นบทบาท

---

## เปรียบเทียบ 4 Subclass

| | **Fiend** | **Celestial** | **Archfey** | **Great Old One** |
|---|---|---|---|---|
| **จุดเด่น** | **ทนที่สุด (Temp HP)** | **รักษาเพื่อนได้** | วาร์ป + ควบคุม | ร่ายเวทเงียบ + พลังจิต |
| **ความยาก** | ง่ายสุด | ง่าย | กลาง | กลาง |
| **ช่วยทีม** | ต่ำ | **สูงสุด** | สูง | กลาง |
| **แนะนำมือใหม่** | **ใช่** | **ใช่** | ใช่ | ใช่ |

---
---

# รายการเวทของ Warlock (Warlock Spell List)

> **[C] = Concentration** | **[R] = Ritual** | [แนะนำ] = แนะนำ
> **Warlock มีสเปลน้อยที่สุดในบรรดา Full Caster** — ต้องเลือกสเปลที่ใช้ได้หลายสถานการณ์

---

## Cantrips

| Cantrip | ทำอะไร |
|---|---|
| **ระเบิดลึกลับ (Eldritch Blast)** [แนะนำอย่างยิ่ง] | Spell Attack ระยะ 120 ฟุต — **1d10 Force**<br>**ยิงเพิ่มเป็น 2 ลำที่เลเวล 5, 3 ลำที่เลเวล 11, 4 ลำที่เลเวล 17** [แนะนำ]<br> **Cantrip ที่ดีที่สุดในเกม เมื่อรวมกับ `Agonizing Blast`** |
| **ระฆังมรณะ (Toll the Dead)** [แนะนำ] | WIS Save — **1d8 Necrotic** (**1d12** ถ้า HP ไม่เต็ม) |
| **สัมผัสเยือกเย็น (Chill Touch)** | Spell Attack — **1d10 Necrotic** + เป้าหมายฟื้น HP ไม่ได้ |
| **พ่นพิษ (Poison Spray)** | CON Save — **1d12 Poison** |
| **เสียงกัมปนาท (Thunderclap)** | CON Save — **1d6 Thunder** รอบตัว 5 ฟุต |
| **มือเวท (Mage Hand)** [แนะนำ] | มือลอยระยะ 30 ฟุต |
| **ภาพลวงตาเล็ก (Minor Illusion)** [แนะนำ] | สร้างภาพหรือเสียงลวง |
| **มายากลจิ๊บจ๊อย (Prestidigitation)** [แนะนำ] | เอฟเฟกต์เวทเล็ก ๆ |
| **มิตรภาพ (Friends)** | Advantage ใน CHA Check ต่อ 1 ตัว |
| **ปัดใบมีด (Blade Ward)** | Resistance กายภาพจนจบเทิร์นหน้า |
| **โจมตีแม่นยำ (True Strike)** [แนะนำ] | โจมตีด้วยอาวุธโดยใช้ CHA แทน (ดีสำหรับ Pact of the Blade ก่อนเลเวล 5) |

> **แนะนำ 2 อันแรก:** `Eldritch Blast` [แนะนำอย่างยิ่ง] (บังคับ!) + `Minor Illusion` หรือ `Prestidigitation`

---

## สเปลระดับ 1

| สเปล | ทำอะไร |
|---|---|
| **คำสาป (Hex)** [แนะนำอย่างยิ่ง] [C] | **Bonus Action:** ทำเครื่องหมายศัตรู **+1d6 Necrotic ทุกครั้งที่คุณตีมัน** + **มันเสียเปรียบใน Ability Check ของค่าที่คุณเลือก** • ถ้ามันตาย **ย้ายเครื่องหมายได้ด้วย Bonus Action** |
| **เกราะแห่งอกาธิส (Armor of Agathys)** [แนะนำมาก] | **Temp HP 5** + **ศัตรูที่ตีคุณระยะประชิดรับ 5 Cold damage**<br>**แรงขึ้นตามระดับ Slot** [แนะนำ] (Slot ระดับ 5 = Temp HP 25 + สวน 25!) |
| **คำสาปแห่งนรก (Hellish Rebuke)** [แนะนำมาก] | **Reaction:** เมื่อถูกทำดาเมจ **2d10 Fire** ใส่ผู้ทำร้าย (DEX Save ครึ่ง) |
| **แขนแห่งฮาดาร์ (Arms of Hadar)** [แนะนำ] | รอบตัว 10 ฟุต — STR Save — **2d6 Necrotic** + **ล้มเหลว = ใช้ Reaction ไม่ได้** |
| **สายฟ้าแม่มด (Witch Bolt)** [C] | **1d12 Lightning** + Action ทุกเทิร์นทำ 1d12 ซ้ำ |
| **เสน่ห์ (Charm Person)** | Humanoid — Charmed 1 ชั่วโมง |
| **หัวเราะน่าเกลียด (Tasha's Hideous Laughter)** [แนะนำ] [C] | WIS Save — ล้มเหลว = **Prone + Incapacitated** |
| **คำสาปแช่ง (Bane)** [C] | ศัตรู 3 ตัว **−1d4 ในการทอยโจมตีและ Save** |
| **ถอยรวดเร็ว (Expeditious Retreat)** [C] | Bonus Action Dash ทุกเทิร์น |
| **ป้องกันดีชั่ว (Protection from Evil and Good)** [C] | ป้องกันจากสิ่งมีชีวิตนอกมิติ |
| **เข้าใจภาษา (Comprehend Languages)** [R] | อ่านและเข้าใจทุกภาษา |
| **อักษรลวงตา (Illusory Script)** [R] | เขียนข้อความที่คนอื่นอ่านไม่ออก |
| **พูดกับสัตว์ (Speak with Animals)** [R] | สื่อสารกับสัตว์ |
| **คนรับใช้ล่องหน (Unseen Servant)** [R] | สร้างพลังล่องหนที่ทำงานให้ |

> **แนะนำ 2 อันแรก (เลเวล 1 เตรียมได้แค่ 2!):** `Hex` [แนะนำอย่างยิ่ง] + `Armor of Agathys` [แนะนำมาก] (หรือ `Hellish Rebuke`)

---

## สเปลระดับ 2 — ได้ที่เลเวล 3

| สเปล | ทำอะไร |
|---|---|
| **ก้าวหมอก (Misty Step)** [แนะนำอย่างยิ่ง] | **Bonus Action: วาร์ป 30 ฟุต** |
| **ตรึงมนุษย์ (Hold Person)** [แนะนำมาก] [C] | WIS Save — ล้มเหลว = **Paralyzed** |
| **ล่องหน (Invisibility)** [แนะนำมาก] [C] | เป้าหมาย Invisible 1 ชั่วโมง |
| **ความมืด (Darkness)** [แนะนำมาก] [C] | ทรงกลม 15 ฟุตมืดสนิท<br> **คอมโบคลาสสิก:** `Darkness` + `Devil's Sight` = **คุณเห็นศัตรู แต่ศัตรูไม่เห็นคุณ** Advantage ทุกการโจมตี + ศัตรูตีคุณเสียเปรียบ |
| **ชักจูง (Suggestion)** [แนะนำมาก] [C] | WIS Save — ล้มเหลว = ทำตามคำแนะนำ 8 ชั่วโมง |
| **ภาพสะท้อน (Mirror Image)** [แนะนำ] | สร้างภาพลวงตา 3 ตัว |
| **แตกสลาย (Shatter)** [แนะนำ] | ทรงกลม 10 ฟุต — 3d8 Thunder |
| **หนามจิต (Mind Spike)** [C] | 3d8 Psychic + รู้ตำแหน่งเป้าหมาย 1 ชั่วโมง |
| **มงกุฎบ้าคลั่ง (Crown of Madness)** [C] | ควบคุมให้เป้าหมายโจมตีพวกเดียวกัน |
| **เมฆมีดสั้น (Cloud of Daggers)** [C] | ลูกบาศก์ 5 ฟุต — 4d4 Slashing |
| **ลำแสงอ่อนแรง (Ray of Enfeeblement)** [C] | เป้าหมายทำดาเมจอาวุธครึ่งเดียว |
| **สะกดใจ (Enthrall)** | ศัตรูเสียเปรียบใน Perception Check |
| **ปีนแบบแมงมุม (Spider Climb)** [C] | เดินบนกำแพงและเพดาน |

> **แนะนำ:** `Misty Step` [แนะนำอย่างยิ่ง] + `Darkness` [แนะนำมาก] (ถ้ามี `Devil's Sight`) + `Hold Person` [แนะนำมาก]

---

## สเปลระดับ 3 — ได้ที่เลเวล 5

| สเปล | ทำอะไร |
|---|---|
| **ขัดขวางเวท (Counterspell)** [แนะนำอย่างยิ่ง] | **Reaction:** ยกเลิกสเปลที่ศัตรูกำลังร่าย |
| **ลวดลายสะกดจิต (Hypnotic Pattern)** [แนะนำอย่างยิ่ง] [C] | ลูกบาศก์ 30 ฟุต — **Charmed + Incapacitated** |
| **ความหิวโหยแห่งฮาดาร์ (Hunger of Hadar)** [แนะนำมาก] [C] | ทรงกลม 20 ฟุตแห่งความมืดว่างเปล่า — **2d6 Cold เมื่อเริ่มเทิร์นในนั้น** + **2d6 Acid เมื่อจบเทิร์น** + **Blinded** + Difficult Terrain |
| **บิน (Fly)** [แนะนำมาก] | **Fly Speed 60 ฟุต** |
| **ความกลัว (Fear)** [แนะนำ] [C] | กรวย 30 ฟุต — Frightened + ทิ้งของ + วิ่งหนี |
| **สลายเวท (Dispel Magic)** [แนะนำ] | ยกเลิกสเปลระดับ 3 หรือต่ำกว่า |
| **สัมผัสดูดเลือด (Vampiric Touch)** [C] | 3d6 Necrotic + **ฟื้น HP ครึ่งหนึ่งของดาเมจ** |
| **ร่างหมอก (Gaseous Form)** [C] | กลายเป็นหมอก — Resistance กายภาพ |
| **ภาพใหญ่ (Major Image)** [C] | ภาพลวงตา 20 ฟุต พร้อมเสียงและกลิ่น |
| **วงเวท (Magic Circle)** | กักขังสิ่งมีชีวิตนอกมิติ |
| **ลบคำสาป (Remove Curse)** | ลบคำสาปออกจากคนหรือของ |
| **เรียกอันเดด (Summon Undead)** [C] | เรียกวิญญาณอันเดดมาช่วยรบ 1 ชั่วโมง |
| **ภาษา (Tongues)** | เข้าใจและพูดทุกภาษา |

> **แนะนำ:** `Counterspell` [แนะนำอย่างยิ่ง] + `Hypnotic Pattern` [แนะนำอย่างยิ่ง] + `Hunger of Hadar` [แนะนำมาก] (แรงมากเพราะ Slot Warlock เป็นระดับสูงเสมอ)

---

## สเปลระดับ 4 — ได้ที่เลเวล 7

| สเปล | ทำอะไร |
|---|---|
| **ประตูมิติ (Dimension Door)** [แนะนำมาก] | วาร์ป 500 ฟุต พร้อมเพื่อน 1 คน |
| **เนรเทศ (Banishment)** [แนะนำมาก] [C] | CHA Save — ล้มเหลว = หายไป 1 นาที (ถ้ามาจากมิติอื่น = ไม่กลับมาเลย) |
| **เหี่ยวเฉา (Blight)** [แนะนำ] | **8d8 Necrotic** |
| **เสน่ห์อสูร (Charm Monster)** | สิ่งมีชีวิตใดก็ได้ — Charmed 1 ชั่วโมง |
| **ภูมิประเทศลวง (Hallucinatory Terrain)** | เปลี่ยนภาพภูมิประเทศ 150 ฟุต |
| **เรียกอสูรกาย (Summon Aberration)** [C] | เรียกสิ่งมีชีวิต Aberration มาช่วยรบ |

---

## สเปลระดับ 5 — ได้ที่เลเวล 9 (ระดับสูงสุดของ Pact Magic)

| สเปล | ทำอะไร |
|---|---|
| **ไฟฟ้าลัดวงจรสมอง (Synaptic Static)** [แนะนำอย่างยิ่ง] | ทรงกลม 20 ฟุต — **8d6 Psychic** + **−1d6 ในการทอยโจมตีและ Check** |
| **ตรึงอสูร (Hold Monster)** [แนะนำมาก] [C] | สิ่งมีชีวิตใดก็ได้ — **Paralyzed** |
| **พายุรัศมี (Jallarzi's Storm of Radiance)** [แนะนำ] [C] | ทรงกระบอก 10 ฟุต — **3d8 Radiant** + ทำลาย Concentration + Blinded/Deafened |
| **หลอกล่อ (Mislead)** [C] | Invisible + ภาพลวงตาที่ควบคุมได้ |
| **สอดส่อง (Scrying)** [C] | มองเห็นเป้าหมายที่อยู่ไกล |
| **ความฝัน (Dream)** | ปรากฏตัวในฝันของคนที่รู้จัก |
| **ติดต่อมิติอื่น (Contact Other Plane)** [R] | ถามคำถามกับสิ่งมีชีวิตในมิติอื่น (ได้ฟรีจาก Contact Patron) |
| **ผูกมัดข้ามมิติ (Planar Binding)** | บังคับสิ่งมีชีวิตนอกมิติให้รับใช้ |
| **วงวาร์ป (Teleportation Circle)** | สร้างประตูวาร์ป |

---

## Mystic Arcanum — สเปลระดับ 6-9 (ร่ายฟรี 1 ครั้ง/Long Rest)

### ระดับ 6 (เลเวล 11)
| สเปล | ทำอะไร |
|---|---|
| **Arcane Gate** [แนะนำมาก] | สร้างประตูวาร์ป 2 บานที่เชื่อมกัน (ระยะ 500 ฟุต) |
| **Summon Fiend** [แนะนำมาก] [C] | เรียกปีศาจทรงพลังมาร่วมรบ 1 ชั่วโมง |
| **Circle of Death** [แนะนำ] | ทรงกลม 60 ฟุต — **8d6 Necrotic** |
| **Mass Suggestion** [แนะนำ] | ชักจูงคน 12 คนพร้อมกัน (24 ชั่วโมง) |
| **True Seeing** | เห็นทะลุภาพลวงตา เห็นสิ่งล่องหน |
| **Eyebite** [C] | ทำให้เป้าหมาย Asleep / Panicked / Sickened |
| **Flesh to Stone** [C] | เป้าหมายกลายเป็นหิน (Petrified) |
| **Create Undead** | สร้าง Ghoul ควบคุมได้ |
| **Investiture of Flame / Ice / Stone / Wind** [C] | ร่างกลายเป็นธาตุ — ได้ความสามารถและ Resistance |
| **Scatter** | วาร์ปสิ่งมีชีวิต 5 ตัวไปที่อื่น |

### ระดับ 7 (เลเวล 13)
| สเปล | ทำอะไร |
|---|---|
| **Forcecage** [แนะนำอย่างยิ่ง] | **กรงพลังที่หนีไม่ได้** — สเปลควบคุมที่ดีที่สุดในเกม |
| **Finger of Death** [แนะนำมาก] | **7d8+30 Necrotic** — ถ้าตายกลายเป็น Zombie รับใช้ |
| **Plane Shift** [แนะนำ] | วาร์ปตัวเองและเพื่อน 8 คนไปมิติอื่น |
| **Etherealness** | เข้าสู่มิติ Ethereal (เดินทะลุกำแพง) |
| **Power Word Fortify** | แจก Temp HP รวม 120 ให้ 6 คน |

### ระดับ 8 (เลเวล 15)
| สเปล | ทำอะไร |
|---|---|
| **Dominate Monster** [แนะนำอย่างยิ่ง] [C] | **ควบคุมสิ่งมีชีวิตใดก็ได้** |
| **Power Word Stun** [แนะนำมาก] | เป้าหมายที่ HP ≤ 150 **Stunned ทันที** ไม่ต้องทอย |
| **Glibness** [แนะนำ] | ทุกการทอย CHA Check **นับเป็นอย่างน้อย 15** + เครื่องจับเท็จตรวจไม่พบ |
| **Befuddlement** | INT และ CHA ของเป้าหมายกลายเป็น 1 (เดิมชื่อ Feeblemind) |
| **Demiplane** | สร้างประตูไปยังมิติส่วนตัว |

### ระดับ 9 (เลเวล 17)
| สเปล | ทำอะไร |
|---|---|
| **Foresight** [แนะนำอย่างยิ่ง] | เป้าหมาย **Advantage ในทุก d20 Test** + ศัตรูโจมตีมันเสียเปรียบ **8 ชั่วโมง** |
| **Power Word Kill** [แนะนำมาก] | เป้าหมายที่ **HP ≤ 100 ตายทันที** |
| **True Polymorph** [แนะนำมาก] | แปลงสิ่งมีชีวิตหรือวัตถุเป็นอะไรก็ได้ (ถาวรได้) |
| **Imprisonment** [แนะนำ] | ขังเป้าหมายไว้ตลอดกาล (6 แบบ) |
| **Weird** [C] | Phantasmal Killer แบบพื้นที่ — 4d10 Psychic ต่อเทิร์น + Frightened |
| **Astral Projection** | ส่งวิญญาณตัวเองและเพื่อน 8 คนไปมิติ Astral |
| **Gate** [C] | เปิดประตูมิติ / เรียกสิ่งมีชีวิตที่รู้จักชื่อ |

> **แนะนำ Mystic Arcanum:** ระดับ 6 `Arcane Gate` • ระดับ 7 `Forcecage` [แนะนำอย่างยิ่ง] • ระดับ 8 `Dominate Monster` [แนะนำอย่างยิ่ง] • ระดับ 9 `Foresight` [แนะนำอย่างยิ่ง]

---

## คำแนะนำการสร้าง Warlock

### แนวทางที่ 1: ยิง Eldritch Blast (Blaster Warlock) — แนะนำมือใหม่

```
CHA 17 CON 15 DEX 14 WIS 12 INT 10 STR 8
Armor: Leather (หรือใช้ Invocation `Armor of Shadows` AC 13+DEX)
Cantrip: Eldritch Blast [แนะนำ] + Minor Illusion
Invocation: Agonizing Blast [แนะนำ] Devil's Sight Repelling Blast
Subclass: Fiend Patron (Temp HP ฟรี)
สเปล: Hex, Armor of Agathys, Misty Step, Darkness, Counterspell, Hypnotic Pattern
```

### แนวทางที่ 2: ตีด้วยอาวุธ (Blade Warlock)

```
CHA 17 CON 15 DEX 14 WIS 12 INT 10 STR 8
Armor: Leather (+ `Armor of Shadows`)
Invocation: Pact of the Blade Agonizing Blast Thirsting Blade (Lv5) Eldritch Smite (Lv7)
Subclass: Fiend Patron (ทนที่สุด) หรือ Celestial (รักษาตัวเอง)
Pact Weapon: Greatsword หรือ Rapier (ใช้ CHA ตี!)
```

> **Blade Warlock ก่อนเลเวล 5 จะอ่อนกว่า Blaster มาก** เพราะยังไม่มี `Thirsting Blade` — แนะนำใช้ `Eldritch Blast` เป็นหลักไปก่อน

### Species ที่แนะนำ
| Species | เหตุผล |
|---|---|
| **Tiefling** [แนะนำมาก] | เข้าธีมสมบูรณ์แบบ + สเปลฟรี + Fire Resistance |
| **Elf (Drow)** [แนะนำมาก] | ได้ `Darkness` ฟรี + Darkvision 120 (คอมโบกับ `Devil's Sight`) |
| **Human** [แนะนำ] | Feat ฟรี |
| **Aasimar** | Healing Hands + Necrotic Shroud (ใช้ CHA) |
| **Dwarf** | +1 HP ทุกเลเวล |
| **Gnome** | Advantage ใน INT/WIS/CHA Save |

### Background ที่แนะนำ
**Charlatan** (DEX/CON/CHA) [แนะนำมาก] — ตรงเป๊ะ • **Acolyte** (INT/WIS/CHA) • **Merchant** (CON/INT/CHA) • **ถ้าเน้นความรู้ (Sage)**

### Feat ที่แนะนำ (เลเวล 4+)
| Feat | ทำไม |
|---|---|
| **Ability Score Improvement (CHA)** [แนะนำมาก] | ดัน CHA ถึง 20 — กระทบทั้ง Spell DC และดาเมจ `Agonizing Blast` |
| **War Caster** [แนะนำมาก] | Advantage ในการรักษา Concentration (`Hex` ใช้ Concentration!) |
| **Resilient (Constitution)** [แนะนำ] | Proficiency ใน CON Save |
| **Eldritch Adept** | ได้ Invocation เพิ่ม 1 อย่าง |
| **Fey Touched** / **Shadow Touched** | +1 CHA + สเปลนอกรายการ Warlock |
| **Tough** | +2 HP ต่อเลเวล |
| **Spell Sniper** | เพิ่มระยะ + ไม่สนที่กำบัง (สาย Blaster) |

### ข้อผิดพลาดที่มือใหม่ทำบ่อย

| ผิด | ถูก |
|---|---|
| ใช้ Spell Slot ร่ายสเปลทุกเทิร์น | **มีแค่ 1-4 ช่อง!** — ยิง `Eldritch Blast` เป็นหลัก เก็บ Slot ไว้ตอนสำคัญ |
| ไม่เอา `Agonizing Blast` | **บังคับเอา** — เป็น Invocation ที่เพิ่มดาเมจมากที่สุดในเกม |
| ไม่ผลักดันให้ทีมพัก Short Rest | **Warlock ได้ประโยชน์จาก Short Rest มากที่สุด** — บอกทีมเสมอ |
| ลืมร่าย `Hex` ตอนเริ่มสู้ | ร่ายเป็น Bonus Action เทิร์นแรก — **+1d6 ทุกลำของ Eldritch Blast!** |
| ร่ายสเปล Concentration อื่นทับ `Hex` | **จะเสีย `Hex`** — เลือกอย่างใดอย่างหนึ่ง |
| เล่น Pact of the Blade ตั้งแต่เลเวล 1 โดยไม่รู้ว่าอ่อนจนถึงเลเวล 5 | **ใช้ `Eldritch Blast` ไปก่อน** จนได้ `Thirsting Blade` |
| ลืมว่า Slot เป็นระดับสูงสุดเสมอ | **`Armor of Agathys` ที่ Slot ระดับ 5 = Temp HP 25 + สวน 25** — แรงมาก |

---

## สรุป Warlock ในหนึ่งบรรทัด

> **`Eldritch Blast` + `Agonizing Blast` ยิงได้ไม่จำกัดตลอดวัน + Spell Slot น้อยแต่ระดับสูงสุดเสมอและฟื้นทุก Short Rest + Invocation ปรับแต่งได้ = คลาสสายเวทที่เล่นง่ายที่สุดและไม่มีวัน "หมดกระสุน"**

---

[กลับหน้ารวมคลาส](00-classes-overview.md)
