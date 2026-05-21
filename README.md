# 🐉 Dragon Warrior Monsters 2 (DQM2) - Super Breeding & Walkthrough Companion App

[English Version Below / รายละเอียดภาษาอังกฤษอยู่ด้านล่าง]

---

## 🇹🇭 ภาษาไทย (Thai Description)

ยินดีต้อนรับสู่ **DQM2 Companion App** — เว็บแอปพลิเคชันออฟไลน์แบบพรีเมียม (Single Page Application) ที่สร้างขึ้นสำหรับผู้เล่น **Dragon Warrior Monsters 2: Cobi's Journey / Tara's Adventure** ที่จะช่วยยกระดับประสบการณ์การเล่นของคุณแบบรอบด้าน ทั้งการค้นหาสูตรผสมพันธุ์ การวิเคราะห์สายพันธุ์เชิงลึก และการดูคู่มือเนื้อหาภาษาไทยอย่างละเอียด!

แอปนี้พัฒนาขึ้นโดยใช้ **Pure HTML5, Vanilla CSS และ Vanilla JavaScript** ไม่มีการดึง Libraries ภายนอก ทำให้เปิดใช้งานได้รวดเร็วทันใจ ปลอดภัย และใช้งานแบบออฟไลน์ได้ 100% ออกแบบมาให้เข้ากับหน้าจอโทรศัพท์มือถือเป็นหลัก (Responsive Mobile-first, Max-width: 520px) พร้อมความหรูหราสไตล์ **Dark Glassmorphism UI**

### 🎯 ฟีเจอร์เด่นหลัก (Key Features)

1. **🧪 ระบบเช็คสูตรผสม (Breed Checker & Calculator)**:
   - กรอกชื่อมอนสเตอร์ตัวพ่อและตัวแม่เพื่อดูผลลัพธ์การผสมพันธุ์ล่วงหน้าได้ทันที
   - รองรับทั้งการประมวลผลตามระบบตารางหลักของตระกูล (Family Fallback) และการดึงข้อมูลจาก **974 สูตรลับเฉพาะ (Specific Recipes)** เช่น การผสมบอสใหญ่และมอนสเตอร์ระดับสูง

2. **🎒 ระบบจัดทีมและการคำนวณอัตโนมัติ (My Party & Auto-Combiner)**:
   - บันทึกมอนสเตอร์ที่มีอยู่ ระบุเพศ (**Male ♂** / **Female ♀**) 
   - ระบบเก็บข้อมูลอัตโนมัติในเบราว์เซอร์ (**localStorage**) ข้อมูลไม่หายเมื่อรีเฟรชหน้าเว็บ
   - **Auto Breeding Combiner**: สแกนคลังมอนสเตอร์ของคุณโดยอัตโนมัติ และแสดงรายการมอนสเตอร์ทั้งหมดที่คุณสามารถผสมได้ทันที พร้อมปุ่มลัดส่งไปยังหน้าเช็คสูตร

3. **🌿 แผนผังลำดับพันธุ์แบบจีโนมิกส์ (Recursive Breeding Tree Chart)**:
   - แสดงลำดับสายการผสมพันธุ์ขึ้นไปทีละชั้นในรูปแบบผังแนวตั้ง (Vertical Flow Chart)
   - **Interactive controls**: สามารถคลิกเลือกเปลี่ยนสูตรย่อยของพ่อแม่มอนสเตอร์ในตัวผัง หรือเลือกสลับสถานะระหว่าง "จับในป่า (Wild Catch)" กับ "ผสมขึ้นมา (Breed)" ได้ตามต้องการ
   - **Leaf Materials count**: คำนวณจำนวนวัตถุดิบฐานที่ต้องใช้ทั้งหมดในการผลิตมอนสเตอร์เป้าหมายตัวนี้แบบสดๆ!

4. **📖 คลังข้อมูลมอนสเตอร์ 312 ตัว (Monster Directory)**:
   - รายชื่อมอนสเตอร์ครบถ้วนทั้ง 312 ตัวในเกม แยกตามกลุ่มตระกูลอย่างสวยงาม
   - ค้นหาแบบรวดเร็วเฉียบคม (Fuzzy Search) พร้อมแสดงค่าสเตตัสเริ่มต้น, อัตราการเติบโต, สกิลติดตัว และ **พิกัดการจับในป่า (Wild Catch Locations) กว่า 148 จุด**
   - มีระบบ Badge `🎒 Owned` และสามารถกดติ๊กเพศ ♂/♀ เพื่อเพิ่มเข้าคลังได้ทันทีจากหน้านี้

5. **🗺️ คู่มือการเล่นและเป้าหมายในเกม (Interactive Walkthrough Checklist)**:
   - แปลเนื้อหาจากบทสรุปอันเลื่องชื่อของ *Jimeous* เป็นภาษาไทยทั้งหมด โดยเก็บคำเฉพาะ (ชื่อมอนสเตอร์, สกิล, ไอเทม, แผนที่) เป็นภาษาอังกฤษ เพื่อการค้นหาที่แม่นยำ
   - ระบบเช็คลิสต์เป้าหมายหลักแต่ละบท (Chapter Milestone Checklist) เซฟลงเบราว์เซอร์อัตโนมัติ
   - แสดงตารางสเตตัสบอส ค่า HP, MP, ATK, DEF, AGL, INT, สกิลของบอส และแผนการเล่นเอาชนะบอสแบบละเอียด
   - มอนสเตอร์ที่ปรากฏในคู่มือสามารถคลิกเพื่อเปิดดูรายละเอียดและสเตตัสเพื่อวิเคราะห์ต่อได้ทันที!

---

## 🇺🇸 English Description

Welcome to **DQM2 Companion App** — a premium, highly interactive, offline-first single page web companion tailored for **Dragon Warrior Monsters 2: Cobi's Journey / Tara's Adventure**. Designed with a luxurious mobile-first glassmorphic dark theme, this tool compiles advanced recursive algorithms and rich master walkthroughs into an incredibly responsive experience under 520px.

### 🎯 Key Features

1. **🧪 Breed Checker & Simulator**:
   - Evaluate parent offsprings instantly using a hybrid search engine.
   - Accurately checks family charts and evaluates **974 specific advanced recipes** (including high-tier Demon Lords/bosses).

2. **🎒 Owned Party Checklist & Sync System**:
   - Manage your owned monsters easily with quick inline `♂` and `♀` gender toggles.
   - Synchronized seamlessly across the checklist, directory, and inventory tabs.
   - Saved automatically with browser `localStorage` persistence.
   - **Auto-combiner**: Automatically cross-references opposite-gender inventory cards to output every offspring combination you can make *right now*.

3. **🌿 Interactive Breeding Tree Flow-Chart**:
   - Renders a multi-level recursive path for advanced monsters vertically.
   - Click parents in the tree to toggle between "Catch in Wild" (leaf node) or expand their breeding recipes.
   - Cycle through alternative recipe formulas in real-time.
   - Auto-aggregates a **Base Materials Shopping List** showing how many wild monsters you need to catch to achieve the final outcome.

4. **📖 312-Monster directory**:
   - Searchable library of all 312 monsters with fuzzy search.
   - Features exact starting stats, growth rates, natural skills, and **148 specific wild catch locations** directly mapped from GameFAQs guides.

5. **🗺️ GameFAQs Master Walkthrough**:
   - Full 7-chapter walkthrough localization (Thai summaries, keeping English proper nouns for seamless database compatibility).
   - Dynamic checkbox objectives saved on the fly.
   - Complete boss fight stats panels (HP, MP, ATK, DEF, AGL, INT, skills) and specific strategy guidelines.
   - Embedded catchable monster badges linked directly to their stats card.

---

## 🚀 วิธีการเข้าใช้งาน (How to Use)

1. ดาวน์โหลดไฟล์ทั้งหมดลงในคอมพิวเตอร์ของคุณ
2. ดับเบิลคลิกเปิดไฟล์ `index.html` บนเบราว์เซอร์ใดก็ได้ (Chrome, Firefox, Safari, Edge)
3. ใช้งานได้ทันที 100% โดยไม่ต้องเชื่อมต่ออินเทอร์เน็ต!

*To open on mobile:*
Copy `index.html` to your smartphone and open it with any local file viewer or browser app to experience a premium pocket companion while playing!

---

## 📚 เครดิตคู่มืออ้างอิง (Credits & Acknowledgments)
This app is compiled using data and inspired by legendary guides from GameFAQs:
- **Jimeous** (DQM2 Walkthrough, Items, & Skills Data)
- **rogueKlyntar** (DQM2 Ultimate Skill & Breeding Guide)
- **Rena Chan** (Breeding & Location Guide)
- **Ambios** (DQM2 Monster Guide)
- **Solarys** (Monster Stat Growth Tables)
