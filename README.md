<p align="center">
  <a href="" rel="noopener">
 <img src="http://optimizer.math.sharif.edu/wp-content/uploads/2021/02/optimizer.png" alt="Optimizer logo"></a>
</p>
<h3 align="center">رندُم</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mtefagh/demos/HEAD)
  [![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/mtefagh/demos/blob/master/LICENSE)

</div>

---

<p align="center"> کد مسابقه optimezer 2022 مرحله اول
در این کد با استفاده از K-means و مصور سازی داده ها خوشه بندی انجام شد.
    <br> 
</p>

## 📝 فهرست مطالب
- [صورت‌بندی سوال](#problem_statement)
- [روند اجرا](#getting_started)
- [نحوه استفاده](#usage)
- [وابستگی‌ها](#tech_stack)


## 🧐 صورت‌بندی سوال <a name = "problem_statement"></a>
<div>
\begin{matrix}
min \sum_{i=1,j=1}^{n,m}d(A_{i},C_{j}) \\
 d(A_{i},C_{j})=\sqrt{\sum_{k=1}^{d}(A_{ik}- C_{jk})^{2}}
\end{matrix}
 </div>

## 🏁 روند اجرا <a name = "getting_started"></a>
فایل قرار داده شده باید با jupyet notebook احرا شود.

### پیش‌نیازها
نصب ژوپیتر
<div align="center">
(https://docs.jupyter.org/en/latest/install.html)
</div>

## 🎈 نحوه استفاده <a name="usage"></a>
به عنوان ورودی در خط اول نام فایل به عنوان مقدار متغیر file_name وارد شود. خانه‌های بعدی کد به ترتیب باید اجرا شود.

## ⛏️ وابستگی‌ها <a name = "tech_stack"></a>
#### python
#### numpy
#### sklearn
#### time
#### matplotlib.pyplot
#### mpl_toolkits.mplot3d
#### matplotlib.ticker 
