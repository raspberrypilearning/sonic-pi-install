## تثبيت Sonic Pi على نظام Windows

- في مستعرض ويب، انتقل إلى [sonic-pi.net](https://sonic-pi.net/)

- انقر فوق زر **Windows** الموجود في أسفل الصفحة.

![للتحميل](images/download-buttons.png)

- انقر فوق زر **Windows 10 (64 bit) MSI Installer** اذا كنت تستخدم Windows 10.

![msi](images/msi-installer.png)

- في مجلد التنزيلات Downloads، انقر نقرًا مزدوجًا فوق `msi` ملف.

![نافذة١](images/windows1.png)

- اقبل الشروط والأحكام ثم انقر فوق **Install**.

![نافذة٢](images/windows2.png)

- انقر فوق **Finish** لإكمال التثبيت وتشغيل Sonic Pi.

![نافذة٣](images/windows3.png)


## تثبيت Sonic Pi على نظام macOS

- في مستعرض ويب، انتقل إلى [ sonic-pi.net ](https://sonic-pi.net/)

- انقر فوق زر **macOS** الموجود في أسفل الصفحة.

![للتحميل](images/download-buttons.png)

- انقر فوق زر **Download**.

![للتحميل](images/download.png)

- في مجلد التنزيلات الخاص بك، انقر فوق ملف `.dmg` الذي قمت بتنزيله.

![macOS1](images/macOS1.png)

- اسحب ملف `Sonic Pi.app` في مجلد التطبيقات الخاص بك.

![macOS2](images/macOS2.png)

- افتح مجلد التطبيقات في Finder. اضغط واستمر بالضغط على مفتاح `Ctrl` وانقر على ملف `Sonic Pi.app`، ثم انقر فوق **Open**.

![macOS3](images/macOS3.png)

- انقر فوق **Open** عندما يُطلب منك ذلك.

![macOS4](images/macOS4.png)

## تثبيت Sonic Pi على Raspberry Pi

- اضغط على مفاتيح `Ctrl` ، `Alt` و `T` في نفس الوقت. سيؤدي هذا إلى فتح نافذة الاوامر.

- في النافذة أسطر الأوامر، اكتب:

```bash
sudo apt update && sudo apt install sonic-pi -y
```

