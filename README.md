<p align="center">
  <a href="" rel="noopener">
 <img src="http://optimizer.math.sharif.edu/wp-content/uploads/2021/02/optimizer.png" alt="Optimizer logo"></a>
</p>
<h3 align="center">Panda</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mtefagh/demos/HEAD)
  [![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/mtefagh/demos/blob/master/LICENSE)

</div>

---

<p align="center"> 
    <br> 
</p>

## 📝 فهرست مطالب
- [صورت‌بندی سوال](#problem_statement)
- [الگوریتم بهینه‌سازی](#idea)
- [محدودیت‌ها](#limitations)
- [ایده‌های گسترش](#future_scope)
- [روند اجرا](#getting_started)
- [نحوه استفاده](#usage)
- [وابستگی‌ها](#tech_stack)
- [نویسندگان](#authors)
- [قدردانی](#acknowledgments)

## 🧐 صورت‌بندی سوال <a name = "problem_statement"></a>

## 💡 الگوریتم بهینه‌سازی <a name = "idea"></a>
از روش کمینه‌سازی نرم یک وزندار با تصادف متغیر استفاده کردیم که آن را می‌توان در فصل هفتم و بخش دوم کتاب

Sparse Optimization Theory and Methods

نیز پیدا کرد. در ابتدا بردار وزن را همه یک قرار می‌دهیم و نرم یک را کمینه می‌کنیم سپس بردار وزن را آپدیت می‌کنیم و دوباره بهینه‌سازی را انجام می‌دهیم. این کار را چند بار تکرار می‌کنیم تا به جوابی با نرم صفر کوچک برسیم
## ⛓️ محدودیت‌ها <a name = "limitations"></a>
روش ما محدودیت خاصی ندارد
## 🚀 ایده‌های گسترش <a name = "future_scope"></a>

## 🏁 روند اجرا <a name = "getting_started"></a>
اگر ریپازیتوری را کلون کنید دیتاهای سه سوال در سه فایل مجزا آمده است و کد برای خواندن  دیتای بخش اول و ذخیره کردن پاسخ آن آورده شده است و با تغییر نام فایل ورودی در اولین خط کد و همچنین در آخر کد (بخش سیو) می‌توان از آن برای سوال‌های دو و سه نیز استفاده کرد 
### پیش‌نیازها

نیاز به نصب کامپایلر جولیا و جوپیتر نوتبوک داریم.
برای نصب کامپایلر جولیا می‌توان از لینک زیر استفاده کرد

https://julialang.org/downloads/

برای نصب ژوپیتر نوتبوک نیز کافیست در کامپایلر نصب شده دو خط کد زیر را بنویسیم

```
Pkg using
Pkg.add(”IJulia”)
```
پکیج‌های آورده شده در بخش وابستگی‌ها را هم می‌توان به سادگی با کد زیر نصب کرد

`Pkg.add("package name")`
### نصب
کد نیاز به نصب ندارد
## 🎈 نحوه استفاده <a name="usage"></a>
همه چیز به طور مرتب در نوتبوک آمده است و فقط کافیست از اول تا اخر سلول‌های آن را به ترتیب اجرا کنیم و اگر بخواهیم مجددا کد را اجرا کنیم لازم نیست همه سلول‌ها از ابتدا اجرا شوند و کافیست سلولی که الگوریتم این بخش را پیاده‌سازی کرده است اجرا شود
## ⛏️ وابستگی‌ها <a name = "tech_stack"></a>
زبان برنامه‌نویسی

[julia](https://julialang.org/)

پکیج‌های استفاده شده 
```
MathOptInterface
GLPK
Random
LinearAlgebra
```
## ✍️ نویسندگان <a name = "authors"></a>
علی فتحی
## 🎉 قدردانی <a name = "acknowledgments"></a>
تشکر از هر کسی که به نحوی در برگزاری این مسابقه سهیم بوده است
