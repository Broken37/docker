# Requirements

* Install [Docker](https://docs.docker.com/engine/install/debian/)
  and [docker-compose](https://docs.docker.com/compose/install/) on your system


# Setup

```
docker-compose up --build
```

# توضیحات

این پروژه برگرفته از مرج ریکوئستیه که من قبلا زدم که تغییراتش رو [اینجا](https://github.com/MahtaFetrat/Time-Series-Analysis-Tool/pull/6/files) می‌تونید مشاهده کنید.

در این پروژه من با داکر کامپوز موارد زیر رو بالا میارم

۱. خود پروژه که با فایل Dockerfile ساخته میشه

۲.دیتابیس (از ایمیج آماده استفاده میشه)

۳. مینیو کلاینت (از ایمیج آماده استفاده میشه)

۴. مینیو سرور (از ایمیج آماده استفاده میشه)

۵. انجنیکس (از ایمیج آماده استفاده میشه)

من با داکر زیاد کار کردم اینجا چون فیلتر شکن ندارم از یه پروژه دیگه اسکرین شات گرفتم که قبلا بیلد شده و کش کرده و پروژه‌ها نیازی به ریکوئست با پستمن ندارن میشه از تو مرورگر بازشون کرد ادمین رو باز کردم.

دستور بیلد کردن و بالا آوردن (جدا هم می‌توان بیلد کرد با کامند ``` docker-compose build```)
![image 1](https://github.com/Broken37/docker/assets/25611438/0603ce67-5d58-4ab7-b102-5743da858b14)

دستور دیدن داکر کانتینر‌هایی که بالا هستند
![image 2](https://github.com/Broken37/docker/assets/25611438/b76c4ed4-f6b6-4987-a7a2-9deb727247e4)

دستور دیدن ایمیج‌های ساخته شده
![image 3](https://github.com/Broken37/docker/assets/25611438/3cceaf5a-82c9-4296-a98c-820129f5c0a3)

و در نهایت ریکوئست زدن به کانتینر
![image 4](https://github.com/Broken37/docker/assets/25611438/56ec909e-e9fc-467e-a0cd-ad7dd6f9c4d5)

فایل‌های استاتیک رو کالکت نکردم برای همین یه مقدار زشت شده ولی اصل مطلب داره کار می‌کنه :)
