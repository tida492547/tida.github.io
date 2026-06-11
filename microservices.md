# 🧩 Microservices

> **Software Architecture Style** · แนวคิดที่ใช้ใน Netflix, Amazon, Uber และอีกมากมาย

---

## 📖 Definition

### English — AWS
> *"Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams."*

### English — Martin Fowler
> *"The microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process and communicating with lightweight mechanisms, often an HTTP resource API."*

### 🇹🇭 Thai — สรุปในสไตล์ของตัวเอง
Microservices คือแนวคิดในการออกแบบ Software ที่ตัดแอปพลิเคชันขนาดใหญ่ออกเป็น **Service เล็กๆ อิสระหลายตัว** แต่ละตัวทำหน้าที่เฉพาะอย่าง สื่อสารกันผ่าน API — เหมือนร้าน Food Court 🍱 ที่แต่ละร้านทำเมนูตัวเองเชี่ยวชาญ ดีกว่าให้คนๆ เดียวทำทุกอย่าง

---

## 🔍 Explanation

สถาปัตยกรรม Microservices เกิดขึ้นเพื่อแก้ปัญหาของ **Monolithic Architecture** ที่เมื่อระบบใหญ่ขึ้น การแก้ไขส่วนเล็กๆ หนึ่งจุดอาจกระทบทั้งระบบ

### ✅ ข้อดีของ Microservices

| ข้อดี | รายละเอียด |
|---|---|
| **Independent Deployment** | Deploy แต่ละ Service แยกกันได้ |
| **Technology Flexibility** | แต่ละ Service ใช้ภาษาหรือ Database ต่างกันได้ |
| **Scalability** | Scale เฉพาะ Service ที่โหลดหนักได้ |
| **Fault Isolation** | Service หนึ่งพังไม่ทำให้ทั้งระบบล่ม |

### 🌍 ตัวอย่างจริง
> **Netflix** แยกระบบออกเป็น Microservices มากกว่า **700 Service** เพื่อรองรับผู้ใช้หลายร้อยล้านคนทั่วโลก

### ⚠️ ข้อควรระวัง
Microservices มาพร้อมความซับซ้อนของ Network, Distributed System และการ Monitor ที่มากขึ้น **ไม่เหมาะกับ Project เล็ก** ที่ยังไม่จำเป็น

---

## 🤖 GenAI Explanation

> *"Microservices เปรียบเหมือน LEGO — แต่ละชิ้นทำงานได้อิสระ และเมื่อประกอบกันจะได้ระบบที่ยืดหยุ่น ขยายได้ง่าย แต่ต้องการการออกแบบที่ดีตั้งแต่ต้น ไม่งั้นจะกลายเป็น 'Distributed Monolith' ที่แย่กว่าเดิม"*
>
> — **ChatGPT** (OpenAI)

> *"แนวคิด Microservices ทำให้ทีม Engineering สามารถพัฒนาและ deploy แต่ละส่วนของระบบได้อย่างอิสระ ลดการ block กันระหว่างทีม และทำให้ cycle การพัฒนาเร็วขึ้นอย่างเห็นได้ชัด"*
>
> — **Claude** (Anthropic)

---

## 📚 References

1. Amazon Web Services. (2024). [*What are Microservices?*](https://aws.amazon.com/microservices/)
2. Fowler, M. & Lewis, J. (2014). [*Microservices*](https://martinfowler.com/articles/microservices.html)
3. Microsoft. (2024). [*Microservices architecture style*](https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)

---

*🔗 กลับไปหน้าหลัก → [Profile](https://username.github.io)*
