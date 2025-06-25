# 🗓️ Progress Calendar Tracker

A sleek, dark-themed personal productivity calendar that helps you track your day-to-day progress with visual feedback. Built to be offline, private, and super easy to use.

![Calendar Preview](assets/CalendarPreview.png)

---

### ✨ Key Features

- ✅ **Click-to-strike** any day to mark it as done
- 🖊️ **Add notes or tags** to any date (like “Done”, “Pending”, “Missed”)
- 🔐 **Login system** to secure your personal view
- 🌑 **Dark mode UI** for a clean and eye-friendly look
- 🧠 **No internet needed** – works 100% offline
- 🔁 **Data stays saved** even after you close the tab

---

## 🔒 Login System (Browser-Based)

This project includes a basic login screen to make each user's calendar feel personalized.

- The login system **does not require any server or online database**.
- **Username and Password are stored only in your browser** using `localStorage`.
- On first login, any username and password you enter will be saved locally.
- You'll then be asked to log in again using the same credentials.
- From then on, your login will work automatically **only in that browser**.
- If you open the link in a different browser/device, you'll need to create a new login there.

🧪 **To reset or test fresh:**
- Open the site in **Incognito Mode**, or
- Run `localStorage.clear()` in DevTools Console to clear saved data.

This setup is great for **personal tracking** without any backend or authentication system.


---

> Designed to help you stay consistent, motivated, and visually track how far you’ve come.

---
