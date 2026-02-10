<h2 align="center">⚙️ Setup</h2>

<ul>
  <li>Fork this project</li>
  <li>Create a <b>Free Fire guest account</b></li>
  <li>Open <code>app.py</code></li>
  <li>Go to <b>line 596–598</b></li>
  <li>Edit the code and add your <b>guest account UID and password</b></li>
  <li>Save the changes</li>
</ul>

---

<h2 align="center">🚀 Deployment (Render)</h2>

<ul>
  <li>Create a <b>Render account</b></li>
  <li>Connect your <b>GitHub account</b> with Render</li>
  <li>Select the project repository</li>
  <li>Scroll down to the <b>Build & Deploy</b> section</li>
  <li>Add <b>Build Command</b>:</li>
</ul>

```bash
pip install -r requirements.txt
�
Add Start Command:
Copy code
Bash
python app.py
�
Deploy the projectWait a few moments for deployment to completeCopy your deployed project link
�
🔗 Endpoint

Copy code
Text
/join?tc=<team_code>&uid1=<uid>&uid2=<uid2>&emote_id=<emote_id>
�
🧩 Usage

�
Open any browserAdd your team code, UID, and emote code in the URL to start emoteEmote codes reference:
Copy code

https://0xme.github.io/ItemID2/?mode=1&q=Emote+Box%26collectionType%3AEMOTE
�
Enjoy using the project 🚀
