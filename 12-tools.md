حتماً. این بخش از پرتکرارترین سؤالات آزمون شرکت، CEH، eJPT، PNPT، OSCP و مصاحبه‌های تست نفوذ است. پاسخ‌ها را به صورت کوتاه، مفهومی و قابل حفظ کردن نوشته‌ام.
________________________________________
ابزارهای امنیت و تست نفوذ
۱. Burp Suite
تعریف:
ابزار تست نفوذ وب برای رهگیری، تحلیل و تغییر درخواست‌های HTTP/HTTPS.
کاربرد:
•	Proxy
•	Repeater
•	Intruder
•	Scanner (نسخه Professional)
•	Decoder
________________________________________
۲. Nmap
تعریف:
ابزار اسکن شبکه و شناسایی Hostها، Portها و سرویس‌ها.
کاربرد:
•	Port Scan
•	Service Detection
•	OS Detection
•	NSE Script
________________________________________
۳. Nessus
تعریف:
اسکنر آسیب‌پذیری تجاری.
کاربرد:
•	شناسایی CVE
•	بررسی Patch
•	گزارش آسیب‌پذیری
________________________________________
۴. OpenVAS (Greenbone)
تعریف:
اسکنر آسیب‌پذیری متن‌باز.
کاربرد:
•	Vulnerability Scan
•	CVE Detection
________________________________________
۵. Nikto
تعریف:
اسکنر امنیتی وب‌سرور.
کاربرد:
•	Headerهای ناامن
•	فایل‌های حساس
•	تنظیمات اشتباه
•	نسخه‌های آسیب‌پذیر
________________________________________
۶. Gobuster
تعریف:
ابزار کشف Directory، File، DNS و Virtual Host.
کاربرد:
•	Directory Bruteforce
•	DNS Enumeration
________________________________________
۷. ffuf
Fuzz Faster U Fool
تعریف:
ابزار Fuzzing برای کشف مسیرها، پارامترها و Virtual Host.
ویژگی:
سریع‌تر از Gobuster.
________________________________________
۸. sqlmap
تعریف:
ابزار خودکار کشف و بهره‌برداری از آسیب‌پذیری SQL Injection.
کاربرد:
•	تشخیص SQLi
•	استخراج Database
•	Dump اطلاعات
________________________________________
۹. Metasploit
تعریف:
فریمورک تست نفوذ برای بهره‌برداری از آسیب‌پذیری‌ها.
کاربرد:
•	Exploit
•	Payload
•	Meterpreter
•	Post Exploitation
________________________________________
۱۰. Wireshark
تعریف:
ابزار تحلیل Packetهای شبکه.
کاربرد:
•	Packet Capture
•	تحلیل پروتکل‌ها
•	عیب‌یابی شبکه
________________________________________
۱۱. tcpdump
تعریف:
ابزار خط فرمان برای Capture بسته‌های شبکه.
کاربرد:
•	Packet Capture
•	Troubleshooting
________________________________________
۱۲. Hydra
تعریف:
ابزار Brute Force برای سرویس‌های مختلف.
پروتکل‌ها:
•	SSH
•	FTP
•	RDP
•	HTTP
•	SMB
________________________________________
۱۳. John the Ripper
تعریف:
ابزار Crack کردن Hash رمز عبور.
کاربرد:
•	Dictionary Attack
•	Wordlist Attack
________________________________________
۱۴. Hashcat
تعریف:
ابزار قدرتمند Crack کردن Hash با استفاده از GPU یا CPU.
ویژگی:
بسیار سریع‌تر از John.
________________________________________
۱۵. CrackMapExec (CME)
تعریف:
ابزار ارزیابی امنیت شبکه‌های Windows/Active Directory.
کاربرد:
•	SMB
•	WinRM
•	LDAP
•	اجرای دستورات
•	بررسی Credentialها
________________________________________
جدول حفظی آزمون
ابزار	کاربرد
Burp Suite	تست نفوذ وب
Nmap	اسکن شبکه
Nessus	اسکن آسیب‌پذیری
OpenVAS	اسکن آسیب‌پذیری متن‌باز
Nikto	اسکن وب‌سرور
Gobuster	کشف Directory
ffuf	Fuzzing
sqlmap	SQL Injection
Metasploit	بهره‌برداری از آسیب‌پذیری
Wireshark	تحلیل Packet
tcpdump	Capture Packet
Hydra	Brute Force
John	Crack Hash
Hashcat	Crack Hash با GPU
CrackMapExec	ارزیابی امنیت Active Directory
________________________________________
⭐ سوالات پرتکرار آزمون شرکت
Burp Suite چه کاری انجام می‌دهد؟
تست نفوذ برنامه‌های تحت وب.
________________________________________
Nmap چیست؟
ابزار اسکن Host، Port، Service و سیستم‌عامل.
________________________________________
تفاوت Nessus و OpenVAS
Nessus
•	تجاری
•	دقت بالا
•	به‌روزرسانی سریع
OpenVAS
•	متن‌باز
•	رایگان
________________________________________
Nikto چه کاری انجام می‌دهد؟
اسکن امنیتی وب‌سرور و یافتن تنظیمات اشتباه و آسیب‌پذیری‌های شناخته‌شده.
________________________________________
تفاوت Gobuster و ffuf
Gobuster
•	کشف Directory
•	ساده و سریع
ffuf
•	Fuzzing
•	سریع‌تر
•	قابلیت‌های بیشتر
________________________________________
sqlmap برای چیست؟
شناسایی و بهره‌برداری خودکار از SQL Injection.
________________________________________
Metasploit چیست؟
فریمورک اجرای Exploit و Post Exploitation.
________________________________________
Wireshark چه کاری انجام می‌دهد؟
تحلیل Packetهای شبکه به‌صورت گرافیکی.
________________________________________
tcpdump چیست؟
Capture بسته‌های شبکه از طریق خط فرمان.
________________________________________
تفاوت Wireshark و tcpdump
Wireshark
•	محیط گرافیکی
•	تحلیل کامل Packetها
tcpdump
•	خط فرمان
•	Capture سریع Packetها
________________________________________
Hydra برای چیست؟
Brute Force روی سرویس‌های مختلف مانند SSH، FTP، RDP و HTTP.
________________________________________
تفاوت John و Hashcat
John
•	Crack Hash
•	مناسب Wordlist و Dictionary Attack
Hashcat
•	Crack Hash با GPU
•	بسیار سریع‌تر
________________________________________
CrackMapExec چیست؟
ابزار ارزیابی امنیت شبکه‌های ویندوز و Active Directory.
________________________________________
⭐ ابزارها بر اساس مرحله تست نفوذ
مرحله	ابزار
Information Gathering	Nmap
Directory Discovery	Gobuster، ffuf
Vulnerability Scan	Nessus، OpenVAS، Nikto
Web Pentest	Burp Suite، sqlmap
Exploitation	Metasploit
Packet Analysis	Wireshark، tcpdump
Password Attack	Hydra، John، Hashcat
Active Directory	CrackMapExec
________________________________________
⭐ ابزارها را با کاربردشان حفظ کنید
ابزار	کاربرد اصلی
Burp Suite	تست نفوذ وب
Nmap	اسکن شبکه
Nessus	اسکن آسیب‌پذیری
OpenVAS	اسکن آسیب‌پذیری رایگان
Nikto	اسکن وب‌سرور
Gobuster	کشف مسیرها
ffuf	Fuzzing
sqlmap	SQL Injection
Metasploit	Exploit
Wireshark	تحلیل ترافیک
tcpdump	Capture ترافیک
Hydra	Brute Force
John	Crack Hash
Hashcat	Crack Hash با GPU
CrackMapExec	تست امنیت Active Directory
________________________________________
🎯 نکات طلایی برای آزمون
•	Burp Suite = ابزار اصلی تست نفوذ وب.
•	Nmap = شناسایی پورت‌ها، سرویس‌ها و سیستم‌عامل.
•	Nessus = اسکنر آسیب‌پذیری تجاری؛ OpenVAS = نسخه متن‌باز.
•	Nikto = اسکن امنیتی وب‌سرور.
•	Gobuster و ffuf = کشف مسیرها و فایل‌های مخفی (ffuf برای Fuzzing انعطاف‌پذیرتر است).
•	sqlmap = خودکارسازی شناسایی و بررسی SQL Injection.
•	Metasploit = فریمورک اجرای Exploit و فعالیت‌های پس از بهره‌برداری.
•	Wireshark = تحلیل گرافیکی بسته‌های شبکه؛ tcpdump = Capture از طریق خط فرمان.
•	Hydra = بررسی مقاومت سرویس‌ها در برابر حملات حدس رمز (Brute Force) در تست‌های مجاز.
•	John و Hashcat = تحلیل و بازیابی Hashها؛ Hashcat معمولاً از GPU پشتیبانی کرده و سرعت بالاتری دارد.
•	CrackMapExec = ارزیابی امنیت محیط‌های Windows و Active Directory و اعتبارسنجی تنظیمات و دسترسی‌ها.
این ابزارها از پرتکرارترین مباحث آزمون‌های شرکت و مصاحبه‌های تست نفوذ و امنیت هستند و دانستن کاربرد و تفاوت آن‌ها معمولاً امتیاز بالایی دارد.

