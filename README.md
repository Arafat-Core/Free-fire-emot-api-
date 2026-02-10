# 🎮 FF Emote Automator

> **Automate your Free Fire team interactions and emotes with ease.**

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python)
![Render](https://img.shields.io/badge/Deploy-Render-black?style=for-the-badge&logo=render)
![Status](https://img.shields.io/badge/Status-Active-green?style=for-the-badge)

---

## ⚙️ **Phase 1: Configuration**

Before deploying, you need to configure the bot with a **Guest Account**.

1.  **Fork this Repository** to your own GitHub account.
2.  Create a fresh **Free Fire Guest Account**.
3.  Open `app.py` in your code editor.
4.  Navigate to **Line 596 – 598**.
5.  Input your credentials:
    ```python
    # Example (Replace with actual data)
    uid = "YOUR_GUEST_UID"
    password = "YOUR_GUEST_PASSWORD"
    ```
6.  **Save** your changes.

---

## 🚀 **Phase 2: Deployment (Render)**

Get your bot live on the web in just a few clicks.

1.  Create an account on **[Render](https://render.com/)**.
2.  Connect your **GitHub** account and select this repository.
3.  Scroll to the **Build & Deploy** section and input the following:

| Setting | Command |
| :--- | :--- |
| **Build Command** | `pip install -r requirements.txt` |
| **Start Command** | `python app.py` |

4.  Click **Deploy** and wait for the process to finish.
5.  **Copy your URL** (e.g., `https://your-project.onrender.com`).

---

## 🔗 **Phase 3: Usage & API**

Control your bot simply by visiting a specific URL in your browser.

### **The Endpoint**

```http
/join?tc=<TEAM_CODE>&uid1=<USER_UID>&uid2=<USER_UID>&emote_id=<EMOTE_ID>
