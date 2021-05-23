# Telegram-Bot-PHP
* طريقة تشغيل البوتات باستخدام ميثود getupdates
* الطريقة تعمل على السيرفرات فقط 🙂
# Commands Screen
* تشغيل أي ملف بدون توقف من خلال السكرين 💯
```
screen -S NameScreen Run R
```
<b>Example 🔰 :</b>
```
screen -S Bot php ./bot.php R
```
* السكرينات الموجودة بالسيرفر 👁‍🗨
```
screen -ls
```
* حذف سكرين 🗑
```
screen -X -S NameScreen kill
```
<b>Example 🔰 :</b>
```
screen -X -S 10749.Bot kill
```
<b>ملاحظه:</b><br>
يجب ان يكون الاسم الموجود ضمن قائمة `screen -ls` وليس الذي تم وضعه عند إنشاء السكرين ✔️
# Files Bot Notes
* يجب عليك اتباع التعليمات التالية : <br>
استبدل `exit();` ب `retun false;` <br>
قم بوضع جميع الفنشكنات خارج فنشكن `run()` <br>
لا تقم بعمل <b>ويب هوك للتوكن</b> حتى لا يتوقف 🙂 <br>
قم برفع الملف في مسار `/root` وليس `/var/www/html`
* [يحيى السوري 💕](https://t.me/KKYKKN)
<br>
<a href="https://t.me/Dv_Wolf"><img src="https://img.shields.io/badge/Chat-on%20Telegram-2CA5E0.svg?logo=telegram&style=for-the-badge" alt="Chat on Telegram"/></a>
