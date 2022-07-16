[English Version](./README_EN.md)

<div align="center">
  <h1> آراسته </h1>
  <h2> تبدیل نوشته‌های فارسی به هنر اسکی </h2>

![image](https://user-images.githubusercontent.com/85228025/178108748-21a4bae4-8e2e-46e1-966d-b98cbd56187f.png)

</div>


مشابه ابزار figlet ولی برای نوشته‌های فارسی و عربی


در حال حاضر می‌توانید با دستور زیر، با استفاده از قلمی که تنظیم شده است یک واژه، جمله یا چند سطر نوشته را بنویسید.  

```bash
$ araste ‌نوشته
```
یا اگر قلمی مدنظر دارید :
```bash
$ araste 'نوشته‌ی شما' -f 'اسم یا مسیر قلم'
```

برای دیدن فهرستی از قلم‌های نصب‌شده:

```bash
$ araste --list
```

درحال‌حاضر چند قلم برای این طراحی شده است که می‌توانید با اسم‌های زیر از آن‌ها استفاده کنید:
```
aipara
aipara_mini
zivar
```

برای راهنما :
```bash
$ araste -h
```

هم‌چنین می‌توانید ورودی را از طریق stdin به برنامه بدهید. برای مثال:

```bash
$ echo 'آراسته' | araste
```

یک نمونه از خروجی برنامه با قلم پیش‌فرض آیپارا :
```
                                      ██████
        ████                ██        ██
  ████                      ██          ██
  ████    ██    ██  ██  ██  ██    ██    ██
    ██████████████████████  ██    ██    ██
                                  ██
                                ██
```
## نصب و استفاده

1. برای نصب برنامه تنها اجرای این دستور نیاز است.

````bash
bash <(curl -s https://raw.githubusercontent.com/ekm507/araste/main/installer/install.sh)
````
یا در شل هایی مانند fish :
````bash
curl -s https://raw.githubusercontent.com/ekm507/araste/main/installer/install.sh | bash
````


2. از برنامهٔ آراسته استفاده کنید! برای استفاده نیاز به پایتون نسخهٔ ۳ دارید. این برنامه وابستگی به بستهٔ خاصی ندارد و با بسته های پیش‌فرض پایتون کار می‌کند.

## نصب قلم‌های بیشتر
برای نصب فونت‌ها می‌توانید از araste-get استفاده کنید.
````bash
araste-get FontName
````

## حذف برنامه
برای پاک کردن برنامه از روی سیستم، کافیست فایل‌های آن را پاک کنید.

اگر آراسته را برای کل سیستم نصب کرده‌اید:

```bash
sudo rm -rf /usr/share/araste
sudo rm /usr/bin/araste
sudo rm /usr/bin/araste-get
```

اگر آراسته را تنها برای کاربر خودتان نصب کرده‌اید:

```bash
rm -rf ~/.local/share/araste
rm ~/.local/bin/araste
rm ~/.local/bin/araste-get
```

## برای انجام
برای انجام کار جدید فایل [TODOS.md](https://github.com/ekm507/araste/blob/main/TODOS.md) را مشاهده کنید
