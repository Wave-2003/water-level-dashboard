# SmartWater Telemetry Platform - เทศบาลตำบลน้ำง้ำ อ.พะเยา

ระบบติดตามและแจ้งเตือนระดับน้ำอัจฉริยะแบบเรียลไทม์ พัฒนาร่วมระหว่าง **เทศบาลตำบลน้ำง้ำ** และ **บริษัท โทรคมนาคมแห่งชาติ จำกัด (มหาชน) NT**

---

## 🚀 ลิงก์สำหรับเข้าชมเว็บไซต์ (GitHub Pages)

เมื่ออัปโหลดขึ้น GitHub แล้ว สามารถเข้าชมได้ที่:
`https://<your-github-username>.github.io/<your-repository-name>/`

---

## 📂 โครงสร้างไฟล์ในโปรเจกต์ (Files Structure)

* `index.html`: หน้าหลักทางเข้าสำหรับ GitHub Pages (มาพร้อมปุ่มสลับโหมด Demo และ Radar Live API)
* `smartwater_phayao_live.html`: หน้าสำหรับต่อใช้งานจริงกับเซ็นเซอร์เรดาร์ (Radar Water Level Sensor via API)
* `smartwater_phayao_dashboard.html`: หน้าสำหรับนำเสนอ/สาธิต (Interactive Demo Mode มี Slider ทดสอบ)
* `LOGO/`: โฟลเดอร์เก็บโลโก้ตราเทศบาลตำบลน้ำง้ำ และโลโก้ NT
* `.nojekyll`: ป้องกัน Jekyll ประมวลผลชื่อภาษาไทยบน GitHub Pages

---

## 📌 ขั้นตอนการนำขึ้น GitHub Pages (Step-by-Step Guide)

1. **สร้าง Repository บน GitHub**:
   * ไปที่ [GitHub.com](https://github.com) $\rightarrow$ กด **New Repository**
   * ตั้งชื่อ Repository เช่น `smartwater-phayao` แล้วกด **Create repository**

2. **อัปโหลดไฟล์ขึ้น GitHub**:
   * เปิด Command Prompt / Terminal ในโฟลเดอร์นี้ แล้วรันคำสั่ง:
     ```bash
     git init
     git add .
     git commit -m "Deploy SmartWater Platform to GitHub Pages"
     git branch -M main
     git remote add origin https://github.com/<your-username>/smartwater-phayao.git
     git push -u origin main
     ```

3. **เปิดใช้งาน GitHub Pages**:
   * ไปที่ Repository บนเว็บ GitHub $\rightarrow$ เลือกแท็บ **Settings**
   * ที่เมนูด้านซ้าย เลือก **Pages**
   * ใต้หัวข้อ **Build and deployment** $\rightarrow$ เลือก Source เป็น `Deploy from a branch`
   * เลือก Branch เป็น `main` / `root` แล้วกด **Save**

4. **สำเร็จ!**:
   * รอประมาณ 1-2 นาที GitHub จะสร้าง URL สำหรับเข้าชมเว็บแดชบอร์ดให้ทันที! 🎉
