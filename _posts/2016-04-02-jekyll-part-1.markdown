---
layout: post
title:  "آموزش نصب جکیل (قسمت دوم)"
date: 2016-04-02  
categories: jekyll update
image-id: jekyll-1
---
خوب برای شروع نصب جکیل باید پیش نیاز هاش رو نصب کنیم:

1. چون جکیل با زبان روبی نوشته شده باید روبی رو نصب کنیم. نصب روبی خیلی راحت بوسیله لینک زیر ممکن است:

[ruby installer]: http://rubyinstaller.org/downloads/.

فقط در نصب تیک زیر را فراموش نکنید. بقیه نصب به راحتی طی می شود.

2.ruby devkit رو هم باید باید نصب کنیم برای 
مراحل نصب به صورت زیر است:

[ruby devkit installer]: http://rubyinstaller.org/downloads/.

بعد از نصب Ruby نوبت به نصب Ruby DevKit میرسه که از همون آدرس قبلی قابل دسترسی هست. برای نصب ابتدا محتویات فایل zip رو درون یک پوشه (ترجیحا در root یکی از درایورها) که اسمش بدون فاصله و حروف خاص باشه قرار می دیم. بطور مثال C:\RubyDevKit مکان مناسبی برای نصب Ruby DevKit است. پس از قرار دادن فایلها نوبت به اجرای اونها میرسه. کدهای زیر رو برای نصب DevKit توی command prompt ویندوز وارد می کنیم. دقت کنید که باید توی مسیر همین پوشه ایجاد شده باشیم تا بتونیم محتویاتش رو نصب کنیم.


{% highlight ruby %}
C:\RubyDevKit> chcp 1252
C:\RubyDevKit> ruby dk.rb init
C:\RubyDevKit> ruby dk.rb install
{% endhighlight %}

نصب جکیل رو در پست بعدی می گذارم.


مطالب پیشنهادی:

[آموزش جکلیل (قسمت اول)](http://hot-ice.ir/jekyll/edu/2016/04/03/jekyll.html)

[آموزش جکلیل (قسمت دوم)](http://hot-ice.ir/jekyll/update/2016/04/02/jekyll-part-1.html)

[آموزش جکلیل (قسمت سوم)](http://hot-ice.ir/jekyll/edu/2016/04/01/jekyll-part-2.html)

[آموزش جکلیل (قسمت چهارم)](http://hot-ice.ir/jekyll/update/2016/03/28/jekyll-part-3.html)

[آموزش جکلیل (قسمت پنجم)](http://hot-ice.ir/jekyll/edu/2016/03/01/jekyll-part-4.html)


