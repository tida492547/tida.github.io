# Docker

## Keyword
**Docker**

---

## Definition

### English (Source 1 — Docker Official Docs)
> Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly.

### English (Source 2 — IBM)
> Docker is an open source containerization platform. It enables developers to package applications into containers—standardized executable components combining application source code with the operating system (OS) libraries and dependencies required to run that code in any environment.

### Thai (สรุปในสไตล์ของตัวเอง)
Docker คือเครื่องมือที่ทำให้เราแพ็ก "แอปพลิเคชัน + ทุกอย่างที่มันต้องการ" ลงกล่องเดียวที่เรียกว่า **Container** แล้วจะรันที่ไหนก็ได้ ไม่ว่าจะเป็นเครื่องเรา เครื่องเพื่อน หรือ Server บน Cloud ก็ทำงานได้เหมือนกันทุกครั้ง — จบปัญหา "มันรันได้บนเครื่องฉันนะ" ไปตลอดกาล

---

## Explanation (ขยายความ)

Docker ถูกสร้างขึ้นโดยบริษัท Docker Inc. และปล่อยออกมาในปี 2013 หลักการทำงานของมันคือการสร้าง **Container** ซึ่งต่างจาก Virtual Machine (VM) ตรงที่ Container ไม่ต้องจำลอง OS ทั้งระบบ แต่ใช้ OS ของเครื่อง Host ร่วมกัน ทำให้เบาและเร็วกว่ามาก

องค์ประกอบหลักของ Docker:
- **Dockerfile** — ไฟล์คำสั่งสำหรับ Build Image
- **Docker Image** — แม่แบบของ Container (read-only)
- **Docker Container** — Instance ที่รันจริงจาก Image
- **Docker Hub** — Registry กลางสำหรับแชร์ Image

ในการทำ Project จริง Docker ช่วยให้ทีมทุกคน setup environment ได้เหมือนกันในคำสั่งเดียว `docker compose up` และยังเป็นพื้นฐานสำคัญของระบบ CI/CD และ Kubernetes ในระดับ Production อีกด้วย

### คำอธิบายจาก GenAI

> "Docker เปรียบเหมือนกล่องกระดาษแข็งสำหรับซอฟต์แวร์ — คุณแพ็กทุกอย่างที่โปรแกรมต้องการลงในกล่อง แล้วส่งกล่องนั้นไปวางที่ไหนก็ได้ มันจะทำงานเหมือนกันทุกครั้ง ไม่ต้องกังวลว่า environment ปลายทางจะต่างกัน" — *ChatGPT (OpenAI)*

> "Docker ช่วยแก้ปัญหา dependency hell ได้อย่างสิ้นเชิง ด้วยการ isolate แต่ละ service ไว้ใน container ของตัวเอง ทำให้การ deploy และ scale ระบบทำได้ง่ายและน่าเชื่อถือมากขึ้น" — *Gemini (Google)*

---

## References

1. Docker Inc. (2024). *What is Docker?* https://docs.docker.com/get-started/docker-overview/
2. IBM. (2024). *What is Docker?* https://www.ibm.com/topics/docker
3. Docker Inc. (2024). *Docker Documentation* https://docs.docker.com/
