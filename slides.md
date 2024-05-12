---
# try also 'default' to start simple
# theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
layout: center
fonts:
  sans: 'Anjoman Max'
  local: Anjoman Max

---

<h1 class='text-green-500'>بلاکچین و بیت‌کوین</h1>
<p>بررسی نحوه کارکرد بلاکچین و چگونگی استفاده از آن در بیت‌کوین و نکات فنی و امنیتی</p>
<!-- <div class='absolute bg-green-500/20 h-[250px] w-[250px] blur-[90px] top-42 -z-10'></div> -->
---
transition: fade-out
class: text-right
---

<h1 class='text-green-500 text-right font-light'>بلاکچین چیست</h1>
<p class='text-sm'>بلاک‌چین یک دیتابیس دیجیتال توزیع شده و غیرمتمرکز است که تراکنش‌ها را به صورت رمزنگاری شده و غیرقابل تغییر در زنجیره‌ای از بلوک‌ها در یک شبکه نظیر به نظیر ثبت می‌کند. <span >هر بلوک شامل هش رمزنگاری شده بلوک قبلی</span>، برچسب زمانی و داده‌های تراکنش است که یک رکورد قابل ردیابی و مقاوم در برابر دستکاری را تشکیل می‌دهد. بلوک‌های جدید از طریق یک مکانیزم اجماع مانند اثبات کار یا اثبات سهام به زنجیره اضافه می‌شوند تا اعتبار و تمامیت تراکنش‌ها را بدون نیاز به مرجع متمرکز تضمین کنند.</p>

<div v-mark.box.green="6" class='flex justify-center items-center mt-12'>
<svg v-click xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="140" height="140" fill="currentColor" viewBox="0 0 256 256"><path d="M223.68,66.15,135.68,18h0a15.88,15.88,0,0,0-15.36,0l-88,48.17a16,16,0,0,0-8.32,14v95.64a16,16,0,0,0,8.32,14l88,48.17a15.88,15.88,0,0,0,15.36,0l88-48.17a16,16,0,0,0,8.32-14V80.18A16,16,0,0,0,223.68,66.15ZM128,32h0l80.34,44L128,120,47.66,76ZM40,90l80,43.78v85.79L40,175.82Zm96,129.57V133.82L216,90v85.78Z"></path></svg>
<svg v-click xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="140" height="140" fill="currentColor" viewBox="0 0 256 256"><path d="M223.68,66.15,135.68,18h0a15.88,15.88,0,0,0-15.36,0l-88,48.17a16,16,0,0,0-8.32,14v95.64a16,16,0,0,0,8.32,14l88,48.17a15.88,15.88,0,0,0,15.36,0l88-48.17a16,16,0,0,0,8.32-14V80.18A16,16,0,0,0,223.68,66.15ZM128,32h0l80.34,44L128,120,47.66,76ZM40,90l80,43.78v85.79L40,175.82Zm96,129.57V133.82L216,90v85.78Z"></path></svg>
<svg v-click xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="140" height="140" fill="currentColor" viewBox="0 0 256 256"><path d="M223.68,66.15,135.68,18h0a15.88,15.88,0,0,0-15.36,0l-88,48.17a16,16,0,0,0-8.32,14v95.64a16,16,0,0,0,8.32,14l88,48.17a15.88,15.88,0,0,0,15.36,0l88-48.17a16,16,0,0,0,8.32-14V80.18A16,16,0,0,0,223.68,66.15ZM128,32h0l80.34,44L128,120,47.66,76ZM40,90l80,43.78v85.79L40,175.82Zm96,129.57V133.82L216,90v85.78Z"></path></svg>
<svg v-click xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="140" height="140" fill="currentColor" viewBox="0 0 256 256"><path d="M223.68,66.15,135.68,18h0a15.88,15.88,0,0,0-15.36,0l-88,48.17a16,16,0,0,0-8.32,14v95.64a16,16,0,0,0,8.32,14l88,48.17a15.88,15.88,0,0,0,15.36,0l88-48.17a16,16,0,0,0,8.32-14V80.18A16,16,0,0,0,223.68,66.15ZM128,32h0l80.34,44L128,120,47.66,76ZM40,90l80,43.78v85.79L40,175.82Zm96,129.57V133.82L216,90v85.78Z"></path></svg>
<svg v-click xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="140" height="140" fill="currentColor" viewBox="0 0 256 256"><path d="M223.68,66.15,135.68,18h0a15.88,15.88,0,0,0-15.36,0l-88,48.17a16,16,0,0,0-8.32,14v95.64a16,16,0,0,0,8.32,14l88,48.17a15.88,15.88,0,0,0,15.36,0l88-48.17a16,16,0,0,0,8.32-14V80.18A16,16,0,0,0,223.68,66.15ZM128,32h0l80.34,44L128,120,47.66,76ZM40,90l80,43.78v85.79L40,175.82Zm96,129.57V133.82L216,90v85.78Z"></path></svg>
</div>

---
transition: slide-up
level: 2
class: text-right
---

<h1 class='text-green-500'>شبکه غیر متمرکز</h1>
<p class='text-sm'>بلاک‌چین یک سیستم توزیع شده و غیرمتمرکز است که در آن سرورها و ذخیره‌سازی داده‌ها در سراسر شبکه‌ای از گره‌های نظیرِ به نظیر (پی‌تو‌پی) پراکنده شده است. این گره‌ها به دو دسته کلی تقسیم می‌شوند: گره‌های کامل (فول‌نود) و ماینرها. گره‌های کامل کپی کاملی از تمام بلاک‌چین را نگه می‌دارند و همه تراکنش‌ها را دریافت، تأیید و انتشار می‌کنند. آنها قوانین شبکه را اعمال می‌کنند و برای حفظ امنیت و یکپارچگی بلاک‌چین ضروری هستند. از طرف دیگر، ماینرها مسئول پردازش تراکنش‌ها، حل مسائل ریاضی پیچیده (پروف‌آف‌ورک) و ایجاد بلوک‌های جدید هستند. آنها با دریافت پاداش از شبکه برای کار خود تشویق می‌شوند. فرایند استخراج و گره‌های کامل به طور مشترک باعث غیرمتمرکز بودن بلاک‌چین می‌شوند، زیرا هیچ نهاد مرکزی وجود ندارد که بر روی شبکه کنترل داشته باشد.</p>

<div class='w-full flex justify-center items-center'>
    <v-switch class='w-full flex flex-col justify-center items-center'>
      <template #1 class='w-[100vw]'>
        <div v-mark.box.green="6" class='grid cols-10 mt-9 w-[100%] '>
          <svg v-for="item of Array.from({length: 67})" xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="20" height="20" fill="currentColor" viewBox="0 0 256 256"><path d="M88,72a8,8,0,0,1,8-8h64a8,8,0,0,1,0,16H96A8,8,0,0,1,88,72Zm8,40h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16ZM208,40V216a16,16,0,0,1-16,16H64a16,16,0,0,1-16-16V40A16,16,0,0,1,64,24H192A16,16,0,0,1,208,40Zm-16,0H64V216H192ZM128,168a12,12,0,1,0,12,12A12,12,0,0,0,128,168Z"></path></svg>
          <svg v-for="item of Array.from({length: 33})" xmlns="http://www.w3.org/2000/svg" class='text-red-500' width="20" height="20" fill="currentColor" viewBox="0 0 256 256"><path d="M88,72a8,8,0,0,1,8-8h64a8,8,0,0,1,0,16H96A8,8,0,0,1,88,72Zm8,40h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16ZM208,40V216a16,16,0,0,1-16,16H64a16,16,0,0,1-16-16V40A16,16,0,0,1,64,24H192A16,16,0,0,1,208,40Zm-16,0H64V216H192ZM128,168a12,12,0,1,0,12,12A12,12,0,0,0,128,168Z"></path></svg>
        </div>
      </template>
      <template #2 class='w-full flex justify-center items-center'>
        <div v-mark.box.green="6" class='grid cols-10 mt-9 w-[100%]'>
          <svg v-for="item of Array.from({length: 50})" xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="20" height="20" fill="currentColor" viewBox="0 0 256 256"><path d="M88,72a8,8,0,0,1,8-8h64a8,8,0,0,1,0,16H96A8,8,0,0,1,88,72Zm8,40h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16ZM208,40V216a16,16,0,0,1-16,16H64a16,16,0,0,1-16-16V40A16,16,0,0,1,64,24H192A16,16,0,0,1,208,40Zm-16,0H64V216H192ZM128,168a12,12,0,1,0,12,12A12,12,0,0,0,128,168Z"></path></svg>
          <svg v-for="item of Array.from({length: 50})" xmlns="http://www.w3.org/2000/svg" class='text-red-500' width="20" height="20" fill="currentColor" viewBox="0 0 256 256"><path d="M88,72a8,8,0,0,1,8-8h64a8,8,0,0,1,0,16H96A8,8,0,0,1,88,72Zm8,40h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16ZM208,40V216a16,16,0,0,1-16,16H64a16,16,0,0,1-16-16V40A16,16,0,0,1,64,24H192A16,16,0,0,1,208,40Zm-16,0H64V216H192ZM128,168a12,12,0,1,0,12,12A12,12,0,0,0,128,168Z"></path></svg>
        </div>
      </template>
      <template #3 class='w-full flex justify-center items-center'>
        <div v-mark.box.green="6" class='grid cols-10 mt-9 w-[100%]'>
          <svg v-for="item of Array.from({length: 51})" xmlns="http://www.w3.org/2000/svg" class='text-green-500' width="20" height="20" fill="currentColor" viewBox="0 0 256 256"><path d="M88,72a8,8,0,0,1,8-8h64a8,8,0,0,1,0,16H96A8,8,0,0,1,88,72Zm8,40h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16ZM208,40V216a16,16,0,0,1-16,16H64a16,16,0,0,1-16-16V40A16,16,0,0,1,64,24H192A16,16,0,0,1,208,40Zm-16,0H64V216H192ZM128,168a12,12,0,1,0,12,12A12,12,0,0,0,128,168Z"></path></svg>
          <svg v-for="item of Array.from({length: 49})" xmlns="http://www.w3.org/2000/svg" class='text-red-500' width="20" height="20" fill="currentColor" viewBox="0 0 256 256"><path d="M88,72a8,8,0,0,1,8-8h64a8,8,0,0,1,0,16H96A8,8,0,0,1,88,72Zm8,40h64a8,8,0,0,0,0-16H96a8,8,0,0,0,0,16ZM208,40V216a16,16,0,0,1-16,16H64a16,16,0,0,1-16-16V40A16,16,0,0,1,64,24H192A16,16,0,0,1,208,40Zm-16,0H64V216H192ZM128,168a12,12,0,1,0,12,12A12,12,0,0,0,128,168Z"></path></svg>
        </div>
      </template>
    </v-switch>
</div>
---
layout: two-cols
layoutClass: gap-16
class: text-right flex flex-col justify-center
---

<h1 class='text-green-500'>ماینینگ</h1>
<p class='text-sm'>در شبکه بیت‌کوین، ماینرها نقش حیاتی در تایید تراکنش‌ها و ایجاد بلوک‌های جدید دارند. فرآیند استخراج (ماینینگ) شامل حل یک معمای ریاضی پیچیده به نام "پروف‌آف‌ورک" است که برای افزودن بلوک جدید به زنجیره بلوکی لازم است. ماینر اولی که این معما را حل کند، می‌تواند تراکنش‌های جدید را در یک بلوک جمع کند و آن را به شبکه ارسال کند.
تعداد کل بیت‌کوین‌هایی که می‌توانند استخراج شوند، محدود و از قبل تعیین شده است - حداکثر ۲۱ میلیون واحد. تا کنون حدود ۱۹ میلیون واحد استخراج شده است. پاداش ماینرها برای هر بلوک جدید که به زنجیره اضافه می‌کنند، مقداری بیت‌کوین جدید به همراه کارمزدهای تراکنش است. با گذشت زمان و نزدیک شدن به عدد ۲۱ میلیون، پاداش استخراج کاهش می‌یابد.
ماینرها نقش مهمی در حفظ امنیت و غیرمتمرکز بودن شبکه بیت‌کوین دارند. آنها با اختصاص منابع محاسباتی برای حل معماهای پروف‌آف‌ورک و تایید تراکنش‌ها، به روزرسانی و نگهداری شبکه کمک می‌کنند. همچنین از تراکنش‌های غیرمجاز و دستکاری داده‌ها جلوگیری می‌کنند. این فرآیند غیرمتمرکز باعث می‌شود که کنترل شبکه در دست یک نهاد مرکزی نباشد.</p>

::right::
<img src='https://bisonapp.com/wp-content/uploads/2020/02/bitcoin-mining-1024x576.jpg' />

---
layout: center
class: text-right
---

<h1 class='text-green-500'>امنیت بلاکچین</h1>
<p class='text-sm'>:امنیت بیت‌کوین و سایر ارزهای رمزنگاری شده بر چند اصل کلیدی استوار است</p>
<p v-click dir='rtl' class='text-sm'>
رمزنگاری قوی: استفاده از الگوریتم‌های رمزنگاری پیشرفته مانند SHA-256 و الگوریتم‌های کلید عمومی/خصوصی برای امنیت کیف‌پول‌ها و تراکنش‌ها. کلیدهای خصوصی برای دسترسی به ارزها لازم هستند.
</p>
<p v-click dir='rtl' class='text-sm'>
شبکه غیرمتمرکز: بیت‌کوین بر روی یک شبکه نظیر به نظیر توزیع شده اجرا می‌شود که توسط هزاران گره و ماینر در سراسر جهان حفظ می‌شود. عدم وجود یک نقطه شکست مرکزی باعث افزایش امنیت می‌شود.
</p>
<p v-click dir='rtl' class='text-sm'>
پروف‌آف‌ورک: مکانیزم اجماع پروف‌آف‌ورک که برای افزودن بلوک‌های جدید لازم است، مانع از حملات سایبری و دستکاری شبکه می‌شود زیرا هکرها برای کنترل شبکه نیازمند انجام محاسبات عظیم هستند.
</p>
<p v-click dir='rtl' class='text-sm'>
تاریخچه عمومی تراکنش‌ها: تمام تراکنش‌ها در بلاک‌چین بیت‌کوین برای همیشه ثبت می‌شوند و قابل مشاهده است. این شفافیت امکان تقلب یا جعل را از بین می‌برد.
</p>
<p v-click dir='rtl' class='text-sm'>
اجماع جامعه: با وجود معماری منبع باز، هر تغییری در پروتکل بیت‌کوین باید توسط اکثریت گره‌ها و ماینرها پذیرفته شود. این روند اجماع جامعه را تضمین می‌کند.
</p>