<h1>🏀 NBA Checker CLI</h1>

<p>
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" />
  <img src="https://img.shields.io/badge/Build-Nuitka-orange.svg" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey.svg" />
  <img src="https://img.shields.io/badge/Status-Premium%20Checker-success.svg" />
</p>

<p><b>NBA Account Checker CLI</b> built in pure Python using <code>httpx</code> + <code>Colorama</code>.  
It mimics OpenBullet logic with full keychecks, captures, proxy rotation, drag & drop combo input,  
and rich CLI output with a premium ASCII banner.</p>

<img width="964" height="421" alt="image" src="https://github.com/user-attachments/assets/652b2fd7-c638-4306-bf1d-0cba7c02ca90" />

<h2>✨ Features</h2>
<ul>
  <li>🔥 Shadow Block ASCII Banner + Centered Subtitle</li>
  <li>🔥 Drag & Drop Combo / Proxy File Input</li>
  <li>🔥 Proxy Support: <code>ip:port</code> or <code>ip:port:user:pass</code></li>
  <li>🔥 Live CPM + Retries Counter</li>
  <li>🔥 Full Keycheck & Capture Flow</li>
  <li>🔥 Captures Country, Plan, Auto-Renew, NextBillingDate, DaysLeft, PaymentMethod</li>
  <li>🔥 Expired accounts shown in <b>yellow</b></li>
  <li>🔥 Saves results to timestamped files: <code>Hits_YYYY-MM-DD_HH-MM-SS.txt</code>, <code>Custom_YYYY-MM-DD_HH-MM-SS.txt</code></li>
  <li>🔥 Colorama output with professional CLI look</li>
</ul>

<h2>📸 Example Output</h2>
<pre><code>
askedwaeon@gmail.com:Keontae14$ COUNTRY = US | PLAN = NBA League Pass Premium 
| AUTO_RENEW = YES✅ | NextBillingDate = 2025-09-20 | DaysLeft = 21 
| PaymentMethod = Credit/Debit Card | NBA Checker By 🔥 Telegram: @therealyashvirgaming 🔥
</code></pre>

<img width="1103" height="741" alt="image" src="https://github.com/user-attachments/assets/f207eaa5-61be-41a7-8f62-deacba6df64b" />

<h2>⚙️ Requirements</h2>
<pre><code>pip install -r requirements.txt</code></pre>

<pre><code>
httpx==0.27.0
colorama==0.4.6
</code></pre>

<h2>🚀 Usage</h2>
<pre><code>
# Launch checker
python nba_checker.py

# Or build exe with Nuitka
Builder.bat
</code></pre>

<h2>📂 Build EXE</h2>
<pre><code>
python -m nuitka --onefile --windows-icon-from-ico=icon.ico ^
   --output-filename=NBA_Checker.exe nba_checker.py
</code></pre>

<h2>💡 Credits</h2>
<p>
Made with ❤️ by <b>Yashvir Gaming</b><br>
🔥 Telegram: <a href="https://t.me/therealyashvirgaming">@therealyashvirgaming</a> 🔥
</p>
