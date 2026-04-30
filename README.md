🚀 Free Fire Ban Check API

A simple and fast API to check Free Fire player details and ban status using UID.

---

🌐 Live Usage

/bancheck?uid=YOUR_UID

Example:

https://your-app.onrender.com/bancheck?uid=123456789

---

📦 Features

- ✅ Fetch player nickname
- 🌍 Get player region
- 🔒 Check ban status
- ⚡ Fast response
- 🌐 Easy to use (GET API)

---

📥 Installation (Local / Termux)

git clone https://github.com/yourusername/ff-ban-check-api.git
cd ff-ban-check-api
pip install -r requirements.txt
python main.py

---

⚙️ Usage

Open in browser:

http://localhost:10000/bancheck?uid=123456789

---

🧪 Sample Response

{
  "uid": "123456789",
  "nickname": "PRO_PLAYER",
  "region": "IND",
  "ban_status": "Not banned"
}

---

❌ Error Response

{
  "error": "ID NOT FOUND"
}

---

🚀 Deployment (Render)

Start Command:

gunicorn main:app

---

📄 Requirements

flask
requests
gunicorn

---

🧠 Notes

- This API uses external endpoints, so uptime depends on them
- Avoid too many requests (rate limits may apply)
- Works on Termux, VPS, Render, Railway, etc.

---

👨‍💻 Developer

Pankaj Sah
TikTok : nepali_ktwo
InstaGram : pankaj_sah07

---

⭐ Support

If you like this project, give it a ⭐ on GitHub!
