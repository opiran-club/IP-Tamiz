# IP-Tamiz
creating your own ip tamiz cloudflare


# ip-tamiz

با دستور زیر اول اسکریپت را داخل سرور خود نصب کنید

``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/OPIran-CluB/IP-Tamiz/main/ip-tamiz.sh && chmod +x ip-tamiz.sh && bash ip-tamiz.sh
```

  گزینه ۴ را انتخاب کرده

 سپس پورت مورد نظر که روی IP که مدنظر هست بنویسید، مثال 443

 سپس IP مورد نظر که باید Port Forwarding انجام شود را وارد کنید، مثال 104.18.54.52

 سپس از شما پرسیده می شود که چه پورتی باید روی سرور شما باز شود، که می‌توانید خالی بزارید 

 سپس IP سرور شما پرسیده می‌شود که اگر خالی بزارید بطور اتوماتیک IP سرور خودتون تشخیص داده می‌شود

 در نهایت از شما تاییدیه کانفیگ نهایی گرفته می‌شود که Enter بزنید

درنهایت Port forwarding مشخص برای شما فعال می‌شود


  با دستور زیر اجرا کنید دوباره اسکریپت
``` bash
bash ip-tamiz.sh
```
