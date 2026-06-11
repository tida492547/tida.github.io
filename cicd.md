# ⚙️ CI/CD

> **Continuous Integration / Continuous Delivery** · หัวใจของ DevOps สมัยใหม่

---

## 📖 Definition

### English — Red Hat
> *"CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment."*

### English — Atlassian
> *"Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. Continuous delivery (CD) automatically deploys all code changes to a testing and/or production environment after the build stage."*

### 🇹🇭 Thai — สรุปในสไตล์ของตัวเอง
CI/CD คือกระบวนการ **อัตโนมัติเต็มรูปแบบ** ตั้งแต่นักพัฒนา push code ไปจนถึง code นั้นขึ้น Production — ระบบจะ test, build และ deploy ให้เองโดยไม่ต้องทำมือ ลดความผิดพลาดจากคน และทำให้ส่ง feature ใหม่ได้เร็วและมั่นใจมากขึ้น 🚀

---

## 🔍 Explanation

CI/CD แบ่งออกเป็น 2 ส่วนหลัก

### 🔄 Continuous Integration (CI)
เมื่อนักพัฒนา push code ขึ้น repository ระบบจะทำงานอัตโนมัติตามลำดับ

| ขั้นตอน | การทำงาน |
|---|---|
| 1️⃣ Pull | ดึง code ใหม่มา |
| 2️⃣ Test | รัน Unit Test และ Integration Test |
| 3️⃣ Quality | ตรวจสอบ Code Quality |
| 4️⃣ Build | Build ตัวโปรแกรม |
| 5️⃣ Notify | แจ้งผลทันทีว่าผ่านหรือไม่ |

### 🚀 Continuous Delivery / Deployment (CD)

| รูปแบบ | ความหมาย |
|---|---|
| **Continuous Delivery** | เตรียม release พร้อม Deploy แต่รอการอนุมัติจากคนก่อน |
| **Continuous Deployment** | Deploy ขึ้น Production อัตโนมัติเลย ไม่ต้องรอ |

### 🛠️ เครื่องมือยอดนิยม

`GitHub Actions` · `GitLab CI` · `Jenkins` · `CircleCI` · `Travis CI`

---

## 🤖 GenAI Explanation

> *"CI/CD เปลี่ยนการ deploy จาก 'เหตุการณ์น่ากลัวที่ต้องนัดทำในคืนวันศุกร์' มาเป็น 'กิจกรรมธรรมดาที่เกิดขึ้นได้ทุกวัน' — มันคือวัฒนธรรม DevOps ที่ทำให้ทีมส่งงานได้เร็วและมั่นใจขึ้นจริงๆ"*
>
> — **ChatGPT** (OpenAI)

> *"CI/CD pipeline ที่ดีคือ safety net ของทีมพัฒนา — ทุกครั้งที่ push code ระบบจะช่วยตรวจว่า code ใหม่ไม่ได้ทำลายสิ่งที่เคยทำงานได้ดีอยู่แล้ว ทำให้ developer กล้า refactor และเพิ่ม feature ได้อย่างมั่นใจ"*
>
> — **Gemini** (Google)

---

## 📚 References

1. Red Hat. (2024). [*What is CI/CD?*](https://www.redhat.com/en/topics/devops/what-is-ci-cd)
2. Atlassian. (2024). [*Continuous integration vs. delivery vs. deployment*](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
3. GitHub. (2024). [*GitHub Actions Documentation*](https://docs.github.com/en/actions)

---

