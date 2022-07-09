# آراسته: تبدیل نوشته‌های فارسی به هنر اسکی

مشابه ابزار figlet ولی برای نوشته‌های فارسی و عربی

**توجه** : ابزار آراسته تحت توسعه است.

در حال حاضر می‌توانید با دستور زیر، با استفاده از قلمی که تنظیم شده است یک واژه، جمله یا چند سطر نوشته را بنویسید.  

```bash
python3 araste.py 'آراسته'
```

نمونه‌ای از خروجی برنامه (این برنامه تحت توسعه است و ممکن است خروجی شما با این متفاوت باشد.):

```
......................................██████..........
........████................██........██..............
..████......................██..........██............
..████....██....██..██..██..██....██....██............
....██████████████████████..██....██....██............
..................................██..................
................................██....................

```

## نصب و استفاده

1. این مخزن را با کمک ابزار git بارگیری کنید.

```bash
git clone 'https://github.com/ekm507/araste.git'
```


2. از برنامهٔ آراسته استفاده کنید! برای استفاده نیاز به پایتون نسخهٔ ۳ دارید. این برنامه وابستگی به بستهٔ خاصی ندارد و با بسته های پیش‌فرض پایتون کار می‌کند.

``` bash
./araste.py 'متن شما'
```


## برای انجام

- [x] طراحی یک قلم فارسی اسکی
- [x] پشتیبانی از قالب flf مشابه figlet
- [x] طراحی یک قلم دیگر
- [ ] داشتن ۳ قلم
- [x] تبدیل قلم‌ها به فرمت flf  
مشابه راهنمای [این صفحه](https://github.com/Marak/asciimo/issues/3)
- [ ] رفع اشکال‌های قلم flf  
- [ ] کامل کردن برنامهٔ آراسته تا بتواند به‌درستی کار کند. 
- [ ] توسعهٔ یک ابزار خط‌فرمان با امکان نصب
- [ ] انتشار نسخهٔ ۱
- [ ] نوشتن یک README انگلیسی
                             