# Contribution Guide

Dear students of the "Mathematical Software" and "Programming with R" courses, class project submissions for this semester are only accepted via the **Pull Request (PR)** process in this repository. This procedure is designed to accurately simulate the standard workflow used in real-world software projects and technical teams.

---

## 🛠 Step-by-Step Submission Workflow

### 1. Fork the Repository
First, click the **Fork** button at the top of this page to create a copy of this repository in your own GitHub account. All subsequent steps must be performed on the forked repository in your account.

---

### 2. Create a Dedicated Branch
Never apply your changes directly to the `main` branch. You must create a new branch for each assignment.

* **💻 Professional Method (CLI - Terminal):**
  Clone the repository and create a new branch:
  ```bash
  git clone [https://github.com/YOUR-USERNAME/R-Mathematical-Software-Lab.git](https://github.com/YOUR-USERNAME/R-Mathematical-Software-Lab.git)
  cd R-Mathematical-Software-Lab
  git checkout -b submission/project1
  ```

* **🌐 Alternative Method (GitHub Web UI):**
  On the main page of your forked repository, click on the button that says `main` (top left of the file structure). In the search box, type `submission/project1` and then click on **Create branch: submission/project1**.

---

### 3. Create Your Folder and Add Submissions
You must create a folder named **exactly as your Student ID** inside the `submissions/` directory and place your files *only* there.

* **💻 Professional Method (CLI - Terminal):**
  Create the folder and copy your code and report files into it:
  ```bash
  mkdir submissions/40212345
  # Place your files in this directory
  git add submissions/40212345/
  git commit -m "Add project 1 submission for 40212345"
  git push origin submission/project1
  ```

* **🌐 Alternative Method (GitHub Web UI):**
  1. Ensure you are on the newly created branch (`submission/project1`).
  2. Navigate to the `submissions` folder.
  3. Click **Add file** and then **Create new file**.
  4. In the file name box, type: `YourStudentID/project1_numeric.R` (typing the forward slash `/` will automatically create your dedicated folder).
  5. Paste your code or use the **Upload files** option for your reports.
  6. Click the green **Commit changes** button at the bottom of the page.

---

### 4. Open a Pull Request (PR)
After pushing or committing your files, return to the main page of your repository on GitHub.
1. The **Compare & pull request** button will appear automatically; click on it.
2. You **must** follow this format for the **PR Title**:
   `Full Name - Student ID - Project Name - Course Name`
   *(Example: Ali Ahmadi - 40212345 - Project 1 - Programming with R)*
3. Click **Create pull request**.

---

## ⚠️ Important Rules and PR Rejection Criteria

**Plagiarism & Academic Misconduct:**
All PRs are reviewed in parallel, and submitted codes are cross-compared. If any abnormal similarities in code logic or report text are detected, the project grade for both parties will be recorded as zero.

**Modifying Public Files & Breaking Structure:**
Any tampering with the repository's core files, such as altering the prompts in the `assignments/` folder or placing submission files outside your dedicated Student ID folder, will result in the automatic closure of your request without review.

**Code Execution & Reproducibility:**
Your submitted codes must follow structural principles and run without errors on a clean environment, without requiring the installation of third-party packages (unless explicitly stated in the prompt). Codes containing broken local/absolute paths will not be reviewed.




# راهنمای ارسال پروژه‌ها (Contribution Guide)

دانشجویان گرامی درس‌های «نرم‌افزارهای ریاضی» و «برنامه‌نویسی با نرم‌افزار R»، تحویل پروژه‌های کلاسی در این ترم صرفاً از طریق فرآیند **Pull Request (PR)** در این مخزن پذیرفته می‌شود. این رویه برای شبیه‌سازی دقیق جریان کاری استاندارد در پروژه‌های نرم‌افزاری و تیم‌های فنی طراحی شده است.

---

## 🛠 مراحل گام‌به‌گام تحویل پروژه 

### ۱. فورک کردن مخزن (Fork)
در قدم اول، در بالای همین صفحه روی دکمه **Fork** کلیک کنید تا یک کپی از این مخزن در اکانت گیت‌هاب شما ایجاد شود. تمام مراحل بعدی باید روی مخزنِ فورک‌شده در اکانت خودتان انجام شود.

---

### ۲. ساخت شاخه اختصاصی (Branch)
هیچ‌گاه تغییرات خود را مستقیماً روی شاخه اصلی (`main`) اعمال نکنید. برای هر تمرین باید یک شاخه جدید بسازید.

* **💻 روش حرفه‌ای (خط فرمان - ترمینال):**
  مخزن را کلون کرده و شاخه جدید بسازید:
  ```bash
  git clone [https://github.com/YOUR-USERNAME/R-Mathematical-Software-Lab.git](https://github.com/YOUR-USERNAME/R-Mathematical-Software-Lab.git)
  cd R-Mathematical-Software-Lab
  git checkout -b submission/project1
  ```

* **🌐 روش جایگزین (وب‌سایت گیت‌هاب):**
  در صفحه اصلی مخزن فورک‌شده خود، روی دکمه‌ای که نوشته `main` (بالا سمت چپ ساختار فایل‌ها) کلیک کنید. در کادر جستجو تایپ کنید: `submission/project1` و سپس روی گزینه **Create branch: submission/project1** کلیک کنید.

---

### ۳. ساخت پوشه اختصاصی و افزودن پاسخ‌ها
شما باید یک پوشه **دقیقاً هم‌نام با شماره دانشجویی** خود در مسیر `submissions/` بسازید و فایل‌های خود را فقط آنجا قرار دهید.

* **💻 روش حرفه‌ای (خط فرمان - ترمینال):**
  پوشه را بسازید و فایل‌های کد و گزارش خود را داخل آن کپی کنید:
  ```bash
  mkdir submissions/40212345
  # فایل‌های خود را در این پوشه قرار دهید
  git add submissions/40212345/
  git commit -m "Add project 1 submission for 40212345"
  git push origin submission/project1
  ```

* **🌐 روش جایگزین (وب‌سایت گیت‌هاب):**
  1. مطمئن شوید در شاخه جدیدی که ساختید (`submission/project1`) هستید.
  2. وارد پوشه `submissions` شوید.
  3. روی دکمه **Add file** و سپس **Create new file** کلیک کنید.
  4. در کادر نام فایل بنویسید: `شماره‌دانشجویی/project1_numeric.R` (با زدن اسلش / پوشه اختصاصی شما ساخته می‌شود).
  5. کد خود را پیست کنید یا از گزینه **Upload files** برای آپلود گزارش‌ها استفاده کنید.
  6. در پایین صفحه، روی دکمه سبز رنگ **Commit changes** کلیک کنید.

---

### ۴. ثبت درخواست ادغام (Pull Request)
پس از پوش (Push) یا کامیت کردن فایل‌ها، به صفحه اصلی مخزن خود در گیت‌هاب برگردید.
1. دکمه **Compare & pull request** به طور خودکار نمایش داده می‌شود؛ روی آن کلیک کنید.
2. رعایت فرمت زیر برای **عنوان PR** اجباری است:
   `نام و نام خانوادگی - شماره دانشجویی - نام پروژه - نام درس`
   *(مثال: علی احمدی - 40212345 - پروژه ۱ - برنامه‌نویسی با نرم‌افزار R)*
3. روی **Create pull request** کلیک کنید.

---

## ⚠️ قوانین مهم و معیارهای رد شدن PR

**تخلف علمی (Plagiarism):**
تمام PRها به صورت موازی بررسی و کدهای ارسالی با یکدیگر مقایسه می‌شوند. در صورت مشاهده شباهت غیرعادی در منطق کدها یا متن گزارش‌ها، نمره پروژه برای هر دو طرف صفر لحاظ خواهد شد.

**تغییر در فایل‌های عمومی و ساختارشِکَنی:**
هرگونه دستکاری در فایل‌های اصلی مخزن نظیر تغییر صورت‌مسئله‌ها در پوشه `assignments/` یا قرار دادن فایل پاسخ خارج از پوشه اختصاصیِ شماره دانشجویی، منجر به بسته شدن خودکار درخواست شما بدون بررسی می‌گردد.

**اجرای صحیح کدها:**
کدهای ارسالی شما باید منطبق بر اصول ساختاری بوده و بدون نیاز به نصب پکیج‌های متفرقه روی یک محیط خام بدون خطا اجرا شوند. کدهایی که دارای مسیرهای محلی (Relative/Absolute Paths) شکسته باشند بررسی نخواهند شد.
</div>
