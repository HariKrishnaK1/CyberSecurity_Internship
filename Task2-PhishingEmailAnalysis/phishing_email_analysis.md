# 📩 Phishing Email Analysis

### 🧪 Sample Email Breakdown

*From:* support@amaz0n-secure.com  
*Subject:* URGENT: Your Amazon Account Has Been Locked!  

---

### 🔍 Detected Red Flags

| No. | Trait                     | Observation                                                                 | Why It’s Suspicious |
|-----|---------------------------|------------------------------------------------------------------------------|---------------------|
| 1️⃣ | Sender Address            | support@amaz0n-secure.com — uses "amaz0n" with zero instead of "o"         | Spoofed to look like Amazon |
| 2️⃣ | Subject Line              | "URGENT: Your Amazon Account Has Been Locked!"                              | Creates fear/urgency |
| 3️⃣ | Suspicious Link           | Link text looks normal, but points to http://amaz0n-security-check.com     | Fake URL |
| 4️⃣ | Threatening Language      | “Respond within 12 hours or your account will be locked”                     | Tries to panic user |
| 5️⃣ | Grammar/Spelling Errors   | Unnatural tone and robotic phrasing                                         | Not professional |
| 6️⃣ | Generic Greeting          | “Dear Customer” instead of using real name                                  | Not personalized |
| 7️⃣ | Fake Domain               | Domain is long and misleading                                               | Real sites are clean and short |
| 8️⃣ | “Do Not Reply” Ending     | Makes it one-way, to avoid getting caught                                   | Avoids user replying |