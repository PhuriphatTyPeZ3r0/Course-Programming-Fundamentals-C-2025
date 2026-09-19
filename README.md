# Programming Fundamentals (การโปรแกรมเบื้องต้น - ภาษา C)

<div align="center">

[![Self-Taught](https://img.shields.io/badge/Learning-Self--Taught-7C3AED?style=for-the-badge&logo=googlescholar&logoColor=white)](https://github.com/PhuriphatTyPeZ3r0)
[![Language: C](https://img.shields.io/badge/Language-C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Obsidian Compatible](https://img.shields.io/badge/Obsidian-Vault%20Ready-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white)](https://obsidian.md/)

**คลังแบบฝึกหัด โค้ดแล็บ และสรุปเนื้อหาการเรียนรู้ภาษา C ด้วยตนเอง**
*บันทึกการเรียนรู้ส่วนบุคคล (Personal Learning Archive) — ไม่ได้สังกัดรายวิชาของสถาบันใด*

</div>

---

## <img src="https://api.iconify.design/material-symbols:list-alt-outline.svg?color=%236366F1" width="20" height="20" align="center" /> สารบัญ (Table of Contents)
- [<img src="https://api.iconify.design/material-symbols:menu-book-outline.svg?color=%230284C7" width="16" height="16" align="center" /> 1. เกี่ยวกับ Repository นี้ (About)](#-1-เกี่ยวกับ-repository-นี้-about)
- [<img src="https://api.iconify.design/material-symbols:folder-open-outline.svg?color=%23F59E0B" width="16" height="16" align="center" /> 2. โครงสร้าง Repository](#-2-โครงสร้าง-repository)
- [<img src="https://api.iconify.design/material-symbols:school-outline.svg?color=%230284C7" width="16" height="16" align="center" /> 3. เนื้อหาที่เรียนรู้ (Topics Covered)](#-3-เนื้อหาที่เรียนรู้-topics-covered)
- [<img src="https://api.iconify.design/material-symbols:terminal-outline.svg?color=%2310B981" width="16" height="16" align="center" /> 4. แบบฝึกหัดและการทดลองภาคปฏิบัติ (Labs & Exercises)](#-4-แบบฝึกหัดและการทดลองภาคปฏิบัติ-labs--exercises)
- [<img src="https://api.iconify.design/material-symbols:trophy-outline.svg?color=%23F59E0B" width="16" height="16" align="center" /> 5. โปรเจกต์ (Projects)](#-5-โปรเจกต์-projects)
- [<img src="https://api.iconify.design/material-symbols:edit-note-outline.svg?color=%238B5CF6" width="16" height="16" align="center" /> 6. สรุปทบทวนเนื้อหา (Reviews)](#-6-สรุปทบทวนเนื้อหา-reviews)
- [<img src="https://api.iconify.design/material-symbols:verified-user-outline.svg?color=%23EF4444" width="16" height="16" align="center" /> 7. หมายเหตุการใช้งาน (Usage Notice)](#-7-หมายเหตุการใช้งาน-usage-notice)
- [<img src="https://api.iconify.design/material-symbols:person-outline.svg?color=%2306B6D4" width="16" height="16" align="center" /> 8. ผู้จัดทำ (Author)](#-8-ผู้จัดทำ-author)

---

## <img src="https://api.iconify.design/material-symbols:menu-book-outline.svg?color=%230284C7" width="22" height="22" align="center" /> 1. เกี่ยวกับ Repository นี้ (About)

- **หัวข้อที่เรียนรู้:** Programming Fundamentals (การโปรแกรมเบื้องต้น)
- **ภาษาโปรแกรมที่ใช้:** C (GCC / Clang C11/C17)
- **รูปแบบการเรียนรู้:** ศึกษาด้วยตนเอง (Self-Study) จากสื่อการเรียนรู้สาธารณะและการฝึกเขียนโค้ดจริง
- **จุดประสงค์:** เก็บบันทึกแบบฝึกหัด โค้ดตัวอย่าง และสรุปเนื้อหาระหว่างการเรียนรู้ภาษา C ด้วยตนเอง

---

## <img src="https://api.iconify.design/material-symbols:folder-open-outline.svg?color=%23F59E0B" width="22" height="22" align="center" /> 2. โครงสร้าง Repository

```text
Course-Programming-Fundamentals-C-2025/
├── 00_Templates/               # Template โน้ตและคู่มือ format (Markdown/Obsidian)
├── 01_Lectures/                # เอกสารและบันทึกประกอบการเรียนรู้
│   ├── 01_Docs/               # เอกสารประกอบ (สรุปย่อ, Handouts)
│   └── 02_Teaching_Slides/    # สไลด์ประกอบการเรียนรู้รายหัวข้อ
├── 02_Labs_Assignments/       # แบบฝึกหัดและโค้ดแล็บภาษา C
│   └── Code/                  # ซอร์สโค้ดภาษา C (.c) ทดสอบตรรกะและการจัดการหน่วยความจำ
├── 03_Projects/                # โปรเจกต์ที่พัฒนาขึ้นระหว่างการเรียนรู้
│   └── README.md
├── 04_Exams_Review/            # สรุปทบทวนเนื้อหาและแบบทดสอบตนเอง
└── README.md                   # เอกสารแนะนำและสารบัญหลัก
```

> **หมายเหตุ:** โครงสร้างนี้รองรับการเปิดอ่านบน GitHub และเปิดเป็น **Obsidian Vault** โดยสมบูรณ์

---

## <img src="https://api.iconify.design/material-symbols:school-outline.svg?color=%230284C7" width="22" height="22" align="center" /> 3. เนื้อหาที่เรียนรู้ (Topics Covered)

| หมวดเนื้อหา | หัวข้อ | รายละเอียดเนื้อหา | สไลด์ / เอกสาร |
| :---: | :--- | :--- | :---: |
| **C Syntax Foundations** | **Structure, Compilation & Preprocessors** | โครงสร้างภาษา C, Preprocessor (`#include`, `#define`), วงจรการคอมไพล์ GCC | [เอกสาร](01_Lectures/) |
| **Data & Memory** | **Data Types, Variables & Memory Model** | ขนาดข้อมูล (Byte Width), รูปแบบเลขฐาน, การจัดสรรหน่วยความจำแบบ Stack | [เอกสาร](01_Lectures/) |
| **Operators** | **Arithmetic, Relational & Bitwise Operations** | ตัวดำเนินการทางคณิตศาสตร์ ตรรกศาสตร์ และ Bitwise Shifting (`<<`, `>>`, `&`, `\|`, `^`) | [เอกสาร](01_Lectures/) |
| **Flow Control** | **Branching & Iteration Algorithms** | การตัดสินใจเงื่อนไข (`if-else`, `switch`), วนซ้ำ (`for`, `while`, `do-while`), Nested Control | [เอกสาร](01_Lectures/) |
| **Functions & Modularization** | **Functions & Parameter Passing** | การแยกฟังก์ชันย่อย, Call-by-value, และการเตรียมพร้อมสู่พอยน์เตอร์ (Pointers) | [เอกสาร](01_Lectures/) |

---

## <img src="https://api.iconify.design/material-symbols:terminal-outline.svg?color=%2310B981" width="22" height="22" align="center" /> 4. แบบฝึกหัดและการทดลองภาคปฏิบัติ (Labs & Exercises)

| ลำดับแบบฝึกหัด | หัวข้อแล็บ (Lab Topic) | สาระสำคัญและเนื้อหาการทดลอง | โฟลเดอร์ซอร์สโค้ด |
| :---: | :--- | :--- | :---: |
| **Lab 01** | Basic Syntax & Standard I/O | การใช้งาน `printf`, `scanf`, Format Specifiers (`%d`, `%f`, `%s`), Escape Characters | [เปิดโค้ด](02_Labs_Assignments/Code/Test.c) |
| **Lab 02** | Flow Control & Conditional Logic | การแก้โจทย์เงื่อนไขซับซ้อน, การตรวจสอบขอบเขตข้อมูล, และการคำนวณสูตรคณิตศาสตร์ | [เปิดโค้ด](02_Labs_Assignments/Code/TestX2.c) |
| **Lab 03** | Repetition & Data Processing | การวนลูปประมวลผลชุดตัวเลข, Nested Loops แสดงผลรูปแบบ Matrix/Patterns | [เปิดโค้ด](02_Labs_Assignments/Code/testX3.c) |

---

## <img src="https://api.iconify.design/material-symbols:trophy-outline.svg?color=%23F59E0B" width="22" height="22" align="center" /> 5. โปรเจกต์ (Projects)

> โปรเจกต์และโปรแกรมประยุกต์ภาษา C ที่พัฒนาขึ้นระหว่างการเรียนรู้ (เก็บอยู่ในโฟลเดอร์ `03_Projects/`)

### ⚡ C Algorithm & Memory-Efficient Console Utility
- **รายละเอียด:** โปรแกรมประยุกต์สำหรับแก้ปัญหาการคำนวณและประมวลผลข้อมูลเชิงตรรกะแบบ High Performance บนคอนโซล
- **เทคโนโลยี:** `C (C11/C17 Standard), GCC Compiler, Make / Clang`
- **ซอร์สโค้ด:** [โฟลเดอร์โปรเจกต์](03_Projects/)

---

## <img src="https://api.iconify.design/material-symbols:edit-note-outline.svg?color=%238B5CF6" width="22" height="22" align="center" /> 6. สรุปทบทวนเนื้อหา (Reviews)

- [x] **สรุปทบทวนช่วงที่ 1:** [บันทึกสรุปไวยากรณ์และลำดับการประมวลผล](04_Exams_Review/)
- [x] **สรุปทบทวนช่วงที่ 2:** [บันทึกสรุป Pointers, Arrays, Strings และฟังก์ชัน](04_Exams_Review/)

---

## <img src="https://api.iconify.design/material-symbols:verified-user-outline.svg?color=%23EF4444" width="22" height="22" align="center" /> 7. หมายเหตุการใช้งาน (Usage Notice)

> [!NOTE]
> คลังนี้จัดทำขึ้นเพื่อเป็น **บันทึกการเรียนรู้ส่วนบุคคล (Personal Learning Archive)** จากการศึกษาด้วยตนเอง และนำเสนอพัฒนาการทางการเขียนโปรแกรม (Portfolio) เท่านั้น
> ไม่ใช่เนื้อหาหรือแบบฝึกหัดที่มาจากรายวิชาของสถาบันการศึกษาใด กรุณาอย่านำไปคัดลอกส่งเป็นงานโดยไม่ได้ทำความเข้าใจด้วยตนเอง

---

## <img src="https://api.iconify.design/material-symbols:person-outline.svg?color=%2306B6D4" width="22" height="22" align="center" /> 8. ผู้จัดทำ (Author)

**Phuriphat Hemakul (PhuriphatTyPeZ3r0)**
- <img src="https://api.iconify.design/material-symbols:code-outline.svg?color=%230284C7" width="16" height="16" align="center" /> ผู้เรียนรู้การเขียนโปรแกรมด้วยตนเอง (Self-Taught Programmer)
- <img src="https://api.iconify.design/simple-icons:github.svg?color=%23181717" width="16" height="16" align="center" /> GitHub: [@PhuriphatTyPeZ3r0](https://github.com/PhuriphatTyPeZ3r0)
- <img src="https://api.iconify.design/material-symbols:language.svg?color=%233B82F6" width="16" height="16" align="center" /> Portfolio: [portfolio-phuriphatizamus-projects.vercel.app](https://portfolio-phuriphatizamus-projects.vercel.app)
