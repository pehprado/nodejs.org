---
layout: security.hbs
title: امنیت
---

# امنیت

### گزارش باگ در Node.js

تمامی مشکل‌های امنیتی در Node.js جدی گرفته می‌شوند و باید از طریق [HackerOne](https://hackerone.com/nodejs) یا رایانامه [security@nodejs.org](mailto:security@nodejs.org) گزارش داده شوند. این گزارش به زیر مجموعه‌ای از تیم هسته Node.js که مسئول رفع کردن مشکلات امنیتی هستند تحویل داده خواهد شد.


گزارش شما حداکثر تا ۲۴ ساعت تصدیق خوهد شد و حداکثر تا ۴۸ ساعت پاسخ دقیقی به گزارش خود دریافت خواهید کرد که نشان خواهد داد کام های بعدی در رسیدگی به درخواست شما چیست.
 
 پس از پاسخ اولیه به گزارش شما، تیم امنیتی تلاش خواهد کرد تا شما را از پیشرفت کار در جهت یک اعلامیه کامل  و تعمیر مطلع سازد و ممکن است از شما در رابطه با اطلاعات تکمیلی یا راهنمایی در حیطه مسئله گزارش شده سوال پرسیده شود. این به‌روزرسانی حداقل هر پنج روز یک بار ارسال خواهد شد. اما در عمل امکان بیشتری وجود دارد که هر ۲۴ تا ۴۸ ساعت یک بار ارسال شوند.

 
###  برنامه جایزه پیدا کردن باگ در Node.js
 
پروژه Node.js در یک برنامه رسمی جایزه برای باگ شرکت می‌کند که برای فعالان امنیتی و  افشاهای عمومی است.

این برنامه از طریق پلتفرم HackerOne مدیریت می‌شود به آدرس  [https://hackerone.com/nodejs](https://hackerone.com/nodejs) برای اطلاعات بیشتر.

## گزارش باگ در ماژول‌های سوم شخص

گزارش‌های  باگ در ماژول‌های سوم شخص باید به نگاه دارندگان آن ها اعلام شود و همجنین باید از طریق [تیم اکو سیستم Node](https://hackerone.com/nodejs-ecosystem) رایانامه  [security-ecosystem@nodejs.org](mailto:security-ecosystem@nodejs.org)  اعلام شود.
 

اطلاعات بیشتر در رابطه با این فرایند را می‌توانید در  [مخزن گروه کاری امینت ](https://github.com/nodejs/security-wg/blob/master/processes/third_party_vuln_process.md).
پیدا کنید.

از شما بابت بهتر کردن امنیت Node.js و اکوسیستم آن متشکریم. 
از تلاش‌ها  و فاش‌سازی مسئولانه شما بسیار استقبال میکنیم و متوجه آن خواهیم بود.


## سیاست افشاگری

- گزارش امنیتی دریافت و سپس به یک رسیدگی کننده اصلی محول خواهد شد. این شخص مختصات تعمیر را مشخص و منتشر خواهد کرد.
مشکل تایید شده و فهرست تمامی نسخه‌های تاثیر دیده مشخص می‌شود. کد برای پیدا کردن اشکالات مشابه بازرسی خواهد شد.
تعمیرها برای تمام انتشارهایی که هنوز نگه‌داری می‌شوند آماده خواهد شد.
این اقدامات بر روی مخازن اصلی اعمال نخواهد شد و تا انتشار اعلامیه به صورت داخلی نگه‌داری خواهند شد. 

- تاریخ منع پیشنهادی برای این آسیب‌پذیری انتخاب و یک CVE (Common Vulnerabilities and Exposures  CVE®) برای این آسیب‌پذیری درخواست خواهد شد. 

- در تاریخ منع، به فهرست رایانامه امنیتی Node.js یک رونویس از اعلامیه ارسال خواهد شد. 
تغییرات به مخزن عمومی اعمال خواهند شد و ساخت های جدید در nodejs.org مستقر خواهند شد. 
ظرف مدت ۶ ساعت از اطلاع‌رسانی به فهرست رایانامه، یک رونویس از مشاوره بر روی بلاگ Node.js منتشر خواهد شد.


- به طور معمول تاریخ منع ۷۲ ساعت پس از ثبت CVE تنظیم خواهد شد. با این حال، این ممکن است به نسبت به شدت اشکال یا سختی تعمیر، متفاوت باشد.


- این فرایند ممکن است کمی زمان ببرد، مخصوصاً زمانی که هماهنگی با نگهدارندگان پروژه‌های دیگر نیاز است.
تلاش خواهد شد تا باگ‌ها در سریع‌ترین حالت ممکن رسیدگی شوند. با این حال مهم است که ما فرایند انتشار بالا را تا پیدا کردن یک راه مشخص برای رفع مشکل دنبال کنیم.

##   دریافت به‌روزرسانی‌های امنیتی


اعلان‌های امنیتی به روش‌های زیر توزیع خواهند شد.

- [گروه گوگل https://groups.google.com/group/nodejs-sec](https://groups.google.com/group/nodejs-sec)
- [بلاگ https://nodejs.org/en/blog](https://nodejs.org/en/blog)

##   نظرات بر روی این سیاست

اگر شما در رابطه با بهبود این فرایند پیشنهادی دارید برای بحث در رابطه با آن لطفاً یک [pull request](https://github.com/nodejs/nodejs.org) بفرستید یا  [یک   issue ایجاد کنید](https://github.com/nodejs/security-wg/issues/new).