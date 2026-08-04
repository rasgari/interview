حتماً. این پاسخ‌ها برای آزمون شرکت، مصاحبه DevSecOps، امنیت، Docker و Kubernetes مناسب هستند. پاسخ‌ها کوتاه، دقیق، مفهومی و قابل حفظ کردن هستند.
________________________________________
DevSecOps
۱. DevSecOps چیست؟
تعریف:
ادغام امنیت (Security) با توسعه (Development) و عملیات (Operations) در تمام مراحل چرخه توسعه نرم‌افزار.
هدف:
شناسایی و رفع آسیب‌پذیری‌ها از ابتدای توسعه تا استقرار.
________________________________________
۲. CI/CD چیست؟
CI (Continuous Integration)
ادغام مداوم کدها و اجرای خودکار Build و Test.
CD (Continuous Delivery / Deployment)
تحویل یا استقرار خودکار نرم‌افزار پس از موفقیت تست‌ها.
________________________________________
۳. Jenkins
تعریف:
ابزار متن‌باز CI/CD برای خودکارسازی Build، Test و Deploy.
کاربرد:
اجرای Pipeline و اتوماسیون فرایند توسعه.
________________________________________
۴. GitLab CI
تعریف:
سیستم CI/CD داخلی GitLab برای اجرای Pipeline از طریق فایل .gitlab-ci.yml.
کاربرد:
Build، Test، Scan و Deploy.
________________________________________
۵. GitHub Actions
تعریف:
سیستم CI/CD داخلی GitHub برای اجرای Workflow با فایل‌های YAML.
کاربرد:
اتوماسیون Build، Test، Security Scan و Deploy.
________________________________________
۶. Docker
تعریف:
پلتفرم کانتینرسازی که برنامه و وابستگی‌های آن را در یک Container اجرا می‌کند.
مزایا:
•	سبک
•	قابل حمل
•	اجرای یکسان در همه محیط‌ها
________________________________________
۷. Kubernetes (K8s)
تعریف:
سامانه Orchestration برای مدیریت، مقیاس‌پذیری و استقرار کانتینرها.
وظایف:
•	مدیریت Container
•	Auto Scaling
•	Self-Healing
•	Load Balancing
________________________________________
۸. Trivy
تعریف:
ابزار متن‌باز برای اسکن آسیب‌پذیری و Secret در Imageهای Docker، فایل‌سیستم و Kubernetes.
کاربرد:
شناسایی CVEها و اطلاعات حساس.
________________________________________
۹. SonarQube
تعریف:
ابزار تحلیل کیفیت و امنیت کد منبع.
کاربرد:
•	یافتن Bug
•	Code Smell
•	Vulnerability
•	Technical Debt
________________________________________
۱۰. Dependency Check
تعریف:
ابزار بررسی کتابخانه‌ها و وابستگی‌های پروژه برای شناسایی آسیب‌پذیری‌های شناخته‌شده (CVE).
________________________________________
۱۱. SAST
Static Application Security Testing
تعریف:
تحلیل امنیتی کد منبع بدون اجرای برنامه.
زمان اجرا:
قبل از Build یا در زمان توسعه.
________________________________________
۱۲. DAST
Dynamic Application Security Testing
تعریف:
تحلیل امنیتی برنامه در حال اجرا از بیرون و بدون دسترسی به کد.
زمان اجرا:
بعد از Deploy.
________________________________________
۱۳. SCA
Software Composition Analysis
تعریف:
بررسی کتابخانه‌ها و وابستگی‌های پروژه برای یافتن آسیب‌پذیری و مشکلات مجوز (License).
________________________________________
۱۴. Secret Scanning
تعریف:
شناسایی اطلاعات حساس ذخیره‌شده در کد یا Repository.
نمونه Secretها:
•	API Key
•	Password
•	Token
•	Private Key
•	AWS Access Key
________________________________________
جدول حفظی آزمون
مورد	تعریف کوتاه
DevSecOps	ادغام امنیت با DevOps
CI/CD	خودکارسازی Build، Test و Deploy
Jenkins	ابزار CI/CD
GitLab CI	CI/CD داخلی GitLab
GitHub Actions	CI/CD داخلی GitHub
Docker	اجرای برنامه داخل Container
Kubernetes	مدیریت کانتینرها
Trivy	اسکن آسیب‌پذیری Container
SonarQube	تحلیل کیفیت و امنیت کد
Dependency Check	بررسی آسیب‌پذیری وابستگی‌ها
SAST	تحلیل امنیتی کد منبع
DAST	تحلیل امنیتی برنامه در حال اجرا
SCA	بررسی وابستگی‌ها و کتابخانه‌ها
Secret Scanning	شناسایی رمزها و کلیدهای حساس
________________________________________
⭐ سوالات پرتکرار آزمون شرکت
تفاوت CI و CD
CI
•	ادغام مداوم کد
•	Build
•	Test
CD
•	تحویل یا استقرار خودکار نرم‌افزار
________________________________________
تفاوت Docker و Kubernetes
Docker
•	ساخت و اجرای Container
Kubernetes
•	مدیریت و Orchestration کانتینرها
________________________________________
تفاوت SAST و DAST
SAST
•	تحلیل کد منبع
•	بدون اجرای برنامه
•	White Box
•	قبل از Deploy
DAST
•	تحلیل برنامه در حال اجرا
•	بدون دسترسی به کد
•	Black Box
•	بعد از Deploy
________________________________________
تفاوت SCA و SAST
SAST
•	بررسی امنیت کد نوشته‌شده توسط توسعه‌دهنده.
SCA
•	بررسی کتابخانه‌ها، پکیج‌ها و وابستگی‌های پروژه.
________________________________________
تفاوت Trivy و SonarQube
Trivy
•	اسکن آسیب‌پذیری Image، Container، Kubernetes و Secretها.
SonarQube
•	تحلیل کیفیت و امنیت کد منبع.
________________________________________
Secret Scanning چه چیزی پیدا می‌کند؟
•	Password
•	API Key
•	Token
•	Private Key
•	AWS Secret
•	GitHub Token
________________________________________
⭐ چرخه DevSecOps (پرتکرار در آزمون)
Developer
      │
      ▼
Git Push
      │
      ▼
CI/CD Pipeline
      │
      ├── Build
      ├── Unit Test
      ├── SAST (SonarQube)
      ├── SCA (Dependency Check)
      ├── Build Docker Image
      ├── Trivy Scan
      ├── Secret Scanning
      ├── Deploy
      └── DAST
________________________________________
⭐ ابزارها را با کاربردشان حفظ کنید
ابزار	کاربرد
Jenkins	اجرای Pipeline
GitLab CI	Pipeline در GitLab
GitHub Actions	Workflow در GitHub
Docker	ساخت و اجرای Container
Kubernetes	مدیریت Containerها
SonarQube	تحلیل کد (SAST)
Trivy	اسکن Image و Container
Dependency Check	بررسی CVE وابستگی‌ها
SAST	امنیت کد
DAST	امنیت برنامه اجراشده
SCA	امنیت کتابخانه‌ها
Secret Scanning	یافتن اطلاعات محرمانه
این سؤالات از رایج‌ترین مباحث DevSecOps در آزمون‌های شرکت و مصاحبه‌های فنی هستند و معمولاً به‌صورت مفهومی یا مقایسه‌ای مطرح می‌شوند.

