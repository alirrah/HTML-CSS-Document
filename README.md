<div dir=”rtl”>

# HTML & CSS

## فهرست

* [مقدمه](#مقدمه)
* [ابزار مورد نیاز](#ابزار-مورد-نیاز)
* [لینک دانلود](#لینک-دانلود)
* [نحوه ساخت فایل html](#نحوه-ساخت-فایل-html)
* [نحوه ساخت فایل html در VS Code](#نحوه-ساخت-فایل-html-در-VS-Code)
* [شروع HTML](#شروع-html)
* [ساختار استاندار فایل HTML](#ساختار-استاندار-فایل-HTML)
* [فرم اصلی فایل HTML](#فرم-اصلی-فایل-HTML)
* [تگ p](#تگ-p)
* [نحوه تغییر عنوان صفحه](#نحوه-تغییر-عنوان-صفحه)
* [محیط های کدنویسی وب](#محیط-های-کدنویسی-وب)
* [تگ های heading](#تگ-های-heading)
* [تگ های brو hr](#تگ-های-brو-hr)
* [کامنت گذاری](#کامنت-گذاری)
* [تگ های bو i](#تگ-های-bو-i)
* [برخی از تگ های معناگرا](#برخی-از-تگ-های-معناگرا)
* [تگ های supو sub](#تگ-های-supو-sub)
* [لینک](#لینک)
* [عکس](#عکس)
* [لیست ها](#لیست-ها)
* [جدول](#جدول)
* [تفاوت تگ های inline و block](#تفاوت-تگ-های-inline-و-block)
* [فرم](#فرم)
* [فیلم](#فیلم)
* [صدا](#صدا)

## مقدمه

:beginner:HTML

(Hyper Text Markup Language)

(زبان نشانه گذاری ابرمتن)

ساختار و اسکلت بندی:bone: صفحه‌ی وب است.

آخرین نسخه HTML5 ،HTML است.

زبان HTML زبان برنامه نویسی نیست، بلکه زبان نشانه گذاری و تگ گذاری است.<br><br>

:beginner:CSS

(Cascading Style Sheets)

(برگه های سبک آبشاری)

آخرین نسخه CSS3 ،CSS است.

زبان CSS زبان برنامه نویسی نیست بلکه مکمل فوق‌العاده:boom: برای HTML است.

## ابزار مورد نیاز

1. مرورگر (Firefox, chrome, opera,…)
2. محیط کدنویسی (Visual Studio Code, php storm,…)

## لینک دانلود

[مرورگر Firefox](https://www.mozilla.org/en-US/firefox/download/thanks/)

[محیط کدنویسی VS Code](https://code.visualstudio.com/download)

<details>

<summary>
نحوه فهمیدن اینکه ویندوزمان چند بیتی است
</summary>

1. به my computer می رویم.
2. روی بخش خالی صفحه راست کلیک کرده و روی گزینه properties کلیک می کنیم.
3. مقدار system type نشان می دهد سیستم:computer: شما چند بیتی است.

</details>

## نحوه ساخت فایل html
1. به محل و جایی:file_folder: که می خواهیم سند:pencil: را قرار دهیم می رویم.
2. راست کلیک و new و در نتیجه Text Document کلیک:computer_mouse: کنیم.
3. و سپس تغییر اسم و پسوند می دهیم (NAME.html, NAME.htm).
4. روی yes:white_check_mark: کلیک می کنیم.

:pushpin:بهتر است از پسوند .html استفاده کنیم.

<details>

<summary>
نمایش پسوند فایل ها
</summary>

1. بالا صفحه سربرگ view می رویم.
2. روی option کلیک می کنیم یا توی start سرچ می کنید folder option.
3. به سربرگ view رفته و تیک:ballot_box_with_check: Hide extensions for known file types بر می داریم.

</details>

<details>

<summary>
تغییر مرورگر پیش فرض
</summary>

1. کلیک راست روی برنامه و open with را می زنیم.
2. و روی choose another app کلیک:computer_mouse: می کنیم.
3. مرورگر مورد نطر را انتخاب کرده و تیک always use this app to open .html files بزنید و روی ok:ok_hand: کلیک کنید.

</details>

* نوشتن کد های html تو محیط کدنویسی است.
* نمایش نتیجه در مرورگر می باشد.

## نحوه ساخت فایل html در VS Code

1. محیط VS Code را باز می کنیم.
2. روی file، open folder:open_file_folder: می زنیم و به محلی که می خواهیم می رویم و select folder می زینم.
3. از sidebar  به explore  می رویم و روی new file کلیک کنیم (از طریق دکمه بالا یا راست کلیک روی sidebar).
4. و سپس تغییر اسم و پسوند:page_with_curl: می دهیم (NAME.html, NAME.htm).

## شروع HTML

در HTML با تگ های کار می کنیم.


- <><br>
تگ باز<br>
Opening tag<br>
- </><br>
تگ بسته<br>
Closing tag

:pushpin:بین <> Element name قرار می گیرد.

:pushpin:در بین تگ باز و بسته محتوا یا content قرار می گیرد.

:pushpin:بعضی از تگ ها تگ باز و بسته دارند، بعضی ها ندارند.

:pushpin:تگ ها می توانند تو در تو استفاده شوند.

## ساختار استاندار فایل HTML

```html
<html>
    <head>	
    </head>	
    <body>	
    </body>	
</html>
```

:pushpin:تگ های داخل تگ head مربوط به تنظیمات صفحه هستند.
:pushpin: تگ های داخل تگ body به کاربر نمایش داده می شوند.

<details>

<summary>
تغییر اندازه فونت در VS Code
</summary>

1. به File Preferences Setting می رویم.
2. از قسمت font size مقدار تغییر می دهیم.

</details>

<details>

<summary>
راحت تر نوشتن تگ های در VS Code
</summary>

در VS Code با نوشتن اسم تگ و فشار دادن دکمه tab تبدیل به تگ مورد نظر می شود.

```
html + press tab button => <html></html>
```

</details>

## فرم اصلی فایل HTML

به مرورگر باید بگید دارید از چی استفاده می کنید پس در خط اول می نویسیم

```html
<!DOCTYPE html>
```

:pushpin:دقت کنید که تگ فوق تگ بسته ندارد.

پس ساختار اصلی به فرم زیر می شود

```html
<!DOCTYPE html>
<html>
    <head>	
    </head>	
    <body>	
    </body>	
</html>
```
## تگ p

paragraph => p

:round_pushpin:برای نوشتن پاراگراف از تگ فوق استفاده می کنیم.

:round_pushpin: تگ p تگی است که کاربر می بیند، پس داخل تگ body نوشته می شود.

```html
<p></p>
```

:mega:برای نوشتن متن طولانی حتما از تگ p استفاده کنید، همین طوری داخل سند ننویسید. شاید ظاهری فرق نکند ولی از نظر موتور جستجو خیلی فرق می دارد.

:mega:در محیط کد زنی هر چه قدر داخل تگ enter p و space اضافه بزنیم هیچ تغییری در ظاهر نمی بینید.

## نحوه تغییر عنوان صفحه

داخل تگ head می رویم و عبارت زیر رو می نویسیم:arrow_down:

```html
<title>عنوان صفحه</title>
```

که بدین فرم در می آید

```html
<!DOCTYPE html>
<html>
	<head>
		<title>TITLE</title>	
	</head>
	<body>
	</body>	
</html>
```

## محیط های کدنویسی وب

- Text Editor<br>
:diamond_shape_with_a_dot_inside:Notepad, sublime, VS Code, nano,...

- IDE<br>
:diamond_shape_with_a_dot_inside:Php storm, web storm,...

:pushpin:با notepad هم می شود برای کار استفاده کرد ولی خیلی ساده است (و شایدم حوصله سر بر).

## تگ های heading

تگ های heading برای کاربر نمایش داده می شوند، پس داخل تگ body نوشته می شود .

که برای نوشتن عناوین از این تگ استفاده می شود.

تگ های h1, h2, h3, h4, h5, h6 را داریم که به ترتیب کوچک می شوند. (h1 بزرگتر از همه و h6 کوچکتر از همه است.)

```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
```

:small_red_triangle_down:مثال

```
h1: بررسی گوشی
	h2: مشخصات
		h3: دوربین
		h3: بدنه
```

این عنوان بندی برای موتور جستجو مهم است، به طوری که بیشترین اهمیت:100: به تگ h1 و کمتری اهمیت به h6 داده می شود.

<details>

<summary>
حذف منوی اسکرول افقی در VS Code
</summary>

1. به سربرگ view می رویم.
2. تیک toggle word wrap را می زنیم.

</details>

:pushpin:برای باز کردن یک فولدر داخل VS Code می توان آن را بگیریم و داخل محیط VS Code رها کنیم.

:pushpin:با کلیک روی دکمه های sidebar در  VS Code مخفی یا نمایش داده می شود.

## تگ های brو hr

برای رفتن به خط بعدی از تگ br استفاده می کنیم.

برای کشیدن خط افقی در صفحه از تگ hr استفاده می کنیم.

:pushpin:تگ brو hr تگ بسته ندارد.

```html
<br>
<hr>
```

:new_moon_with_face:نمایش فایل html بدون فایل CSS در مرورگر های مختلف ممکن است فرق کند و آنم به خاطر استایل های پیش فرض مرورگر هاست که به تگ های می دهند.

## کامنت گذاری

کامنت ها همه جا کاربرد دارند وهمه جا هستند و هیچ تغییری در ظاهر ایجاد نمی کنند، صرفا برنامه نویس آن ها را می بینند.

```html
<!-- TEXT -->
```

دلیل کامنت گذاری
- کامنت های برای مرور و توسعه بعدی توسط خودتات یا بقیه کاربرد دارند. (یادداشت و note)
- برای اینکه بخشی از کد رو نمایش ندهیم.

:pushpin:برای نمایش ندادن کد می توانیم آن را پاک کنیم ولی خیلی از جاها ممکن است دوباره به کد پاک شده نیاز پیدا کنیم، برای همین بهتر است بخش مدنظرمان را کامنت کنیم.

<details>

<summary>
کامنت گذاری سریع در VS Code
</summary>

هرجایی که خواستیم (اگه متنی می خواهید کامنت کنید، آن را انتخاب یا select کنید) ctrl را با / می زنید تا به کامنت تبدیل شود.

</details>

## تگ های bو i

:exclamation:از تگ b برای بولد و ضخیم کردن متن استفاده می کنیم.

:exclamation:از تگ i برای ایتالیک و مورب کردن متن استفاده می شود.

```html
<b></b>
<i></i>
```

تگ های فرمت دهی(مثل تگ bو i) رو می توان داخل تگ p یا به تنهایی استفاده کرد.

:pushpin:برای اینکه وسط متن راحت تگ بزارید متن موردنظر را cut کنید، بعدش تگ موردنظر باز و بسته کرده و متن رو داخل تگ جدید pate کنید.

اگر دو تا تگ پشت سرهم باز می شوند، مهم نیست کدام اول باز شود و کدام دوم ولی مهم است آن که که اول باز شده، آخر بسته شود و آن که دیرتر باز شده، زودتر بسته شود.

```html
درست
<b><i></i></b>

غلط
<b><i></b></i>
```

## برخی از تگ های معناگرا

:paperclip:تگ strong متن را بولد و ضخیم می کند و تگ معناگرا است.

:paperclip:تگ em متن را ایتالیک و مورب می کند و تگ معناگرا است.

:paperclip:تگ mark متن را هایلایت می کند و یک تگ معنادار است که به معنی این است که توجه کنید.

:paperclip:تگ del یک خط می کشد روی متن که معنادار بوده و به معنی این است که حذف شده و دیگر اعتبار ندارد.

:paperclip:تگ ins یک خط زیر متن می کشد که معنادار بوده و به این معنی است که این متن به تازگی اضافه شده است.

:paperclip:تگ blockquote یک تگ معناگرا است که برای نقل قول کردن استفاده می شود و از cite ،attribute برای قرار دادن لینک نقل قول استفاده می کنیم.

:paperclip:تگ q یک تگ معناگرا است که برای نقل قول استفاده می شود و در مرورگر داخل "" نمایش داده می شود.

:paperclip:تگ abbr برا اینکه بگویم کلمه مخفف یه کلمه دیگه است و از title ،attribute برای گفتن کلمه کامل آن استفاده می کنیم.

:paperclip:تگ address برای آدرس دادن (مکان، تلفن:phone:، ایمیل:e-mail:، نام و ...) استفاده می شود.


```html
<strong></strong>
<em></em>
<mark></mark>
<del></del>
<ins></ins>
```

تگ معناگرا (semantic elements or tags) به موتور جستجو:mag: و مرورگر پیام می دهد که این متن مهم است و توجه کنید.

## تگ های supو sub

:fleur_de_lis:تگ sup برای بالا بردن متن (حالت توان) استفاده می شود.

:fleur_de_lis:تگ sub برای پایین آوردن متن (حالت اندیس) استفاده می شود.

```html
<sup></sup>
<sub></sub>
```
## لینک

لینک ها در HTML ما را از یک صفحه:page_facing_up: به صفحه:page_facing_up: دیگر می برند.

از تگ a برای ساخت لینک:paperclip: استفاده می کنیم.

برای کامل کردن لینک در داخل تگ باز a بعد از حرف a فاصله می زنیم و می نویسیم href=”ADRESS” که به آن attribute گفته می شود.(ADDRESS مسیری است که در نظر داریم که باید جایگزین شود.)

:paperclip:اگر آدرسی را نمی دانید به جاش # قرار دهید.

```html
<a href=”https://google.com”>Click Me</a>
```

برای باز کردن لینک در صفحه جدید در attribute ها target=”_blank” قرار می دهیم که مقدار پیش فرض آن _self است.

```html
<a href=”https://google.com” target=”_black”></a>
```

برای راهنما و گذاشتن یک متن که با نگه داشتن:point_up_2: روی لینک نمایش داده شود، باید در attribute های تگ a مقدار title=”TEXT” قرار دهیم.(TEXT متن مدنظر شما است که باید جایگزین شود.)

```html
<a href=”https://google.com” title=”hello”></a>
```

برای رفتن به صفحه بعدی در لوکال و سیستم:computer: شخصی خودمان از طریق لینک کافی است در href آدرس فایل:file_folder: را بهش بدهیم.

```html
<a href=”test.html”></a>
```

<details>

<summary>
نحوه مسیردهی
</summary>

برای رفتن یه فولدر یا پوشه:open_file_folder: جلو برای آدرس دهی فایل در لینک (مثلا اسم فایل mehdi) به صورت زیر عمل می کنیم.

:arrow_forward:href=”mehdi/test.html”

برای رفتن یه فولدر یا پوشه:open_file_folder: عقب برای آدرس دهی فایل در لینک به صورت زیر عمل می کنیم.

:arrow_forward:href=”../test.html”

از دو مورد فوق می توان باهم استفاده کرد.

:arrow_forward:href=”../mehdi/test.html”

</details>

با استفاده از لینک ها می توان به قسمت های مختلف همان صفحه نیز رفت، برای این کار کافی است به قسمتی که باید برود به تگش id:id: بدهیم و در قسمت href لینک "#اسم ای دی" را قرار دهیم.

```html
<a href=”#part7”>Go to Seven</a>
<p id=”part7”></p>
```

ساخت لینک برای ایمیل:e-mail: زدن

```html
<a href=”mailto:EMAILADDRESS></a>
```

(در کد بالا به جای EMAILADDRESS آدرس ایمیل مدنظر باید قرار بگیرید و جاگرین شود.)

ساخت لینک:link: به شماره تلفن:telephone_receiver:

```html
<a href=”tel:PHONENUMBER”></a>
```

(در کد بالا به جای PHONENUMBER شماره تلفن مدنظر باید قرار بگیرید و جاگرین شود.)

## عکس

برای قرار دادن عکس:city_sunset: در فایل html از تگ img استفاده می کنیم و از attribute، src برای مشخص کردن مسیر عکس اسنفاده می کنیم.

```html
<img src=”ali.png”>
```

بعضی مواقع به دلیل سرعت نت یا پاک شدن عکس از روی سرور عکس نمایش داده نمی شود. برای همین از attribute، alt استفاده می کنیم تا در صورت عدم نمایش، آن متن نمایش داده شود.

```html
<img src=”ali.png” alt=”can not show”>
```

حتما alt ،attribute استفاده کنید چون کاربر موضوع بفهمد و در عین حال برای موتور جستجو:mag: بسیار مهم است.

<details>

<summary>
گرفتن لینک:link: عکس از اینترنت
</summary>

روی عکس در مرورگرتان کلیک:computer_mouse: راست کرده و copy image location یا copy image link کلیک می کنیم.

حالا اگر آدرس عکسی که از نت گرفتید را در src قرار بدید، برای شما عکس در صفحه تان اگر به نت وصل باشید نمایش داده می شود.

:boom:بهتر است عکس ها را دانلود کرده و از لوکال خودتان آدرس دهی کنید.

</details>

برای مشخص کردن انداره عکس از width ،attribute برای عرض و height برای ارتفاع استفاده می کنیم.

واحد پیش فرض برای اندازه گیری:straight_ruler: پیکسل است.

اگر از یکی از width ،attribute یا height استفاده کنیم، عکس به یک نسبت بزرگ یا کوچک می شود.

:pushpin:لینک دادن به عکس

```html
<a href=”ADDRESS” target=”NEW_PAGE_OR_NOT”><img src=”ADDRESS” alt=”TEXT”></a>
```

## لیست ها

در HTML دو نوع لیست داریم

1. Unordered list
2. Ordered list

برای لیست نامرتب یا Unordered list از تگ ul استفاده می کنیم که برای هر آیتم از لیست از تگ li استفاده می شود.

```html
<ul>
    <li></li>
</ul>
```

برای تغییر شکلک ها در لیست ها از CSS استفاده می کنیم.

برای لیست مرتب یا ordered list از تگ ol استفاده می کنیم که برای آیتم ها از تگ li استفاده می کنیم.

```html
<ol>
    <li></li>
</ol>
```

برای تغییر عدد و شکلک پشت آیتم ها از type ،attribute در تگ ol استفاده می کنیم که شامل 1, a, A, i, I می شود و مقدار پیش فرض آن 1 است.

```html
<ol type="i">
    <li></li>
</ol>
```

از لیست ها می توان به صورت تو در تو نیز استفاده کرد.

```html
<ul>
    <li>Hello</li>
    <li>
        <ol>
            <li>ali</li>
            <li>reza</li>
        </ol>
    </li>
    <li>bye</li>
    <li>ali
        <ul>
            <li>ali</li>
            <li>reza</li>
        </ul>
    </li>
</ul>
```

:pushpin:حتما فاصله و تو رفتگی ها داخل کدنویسی رعایت کنید.

<details>

<summary>
مرتب سازی خودکار کد ها در VS Code
</summary>

یکی از دو راه زیر را انجام دهید

- از روی صفحه کیبورد:keyboard: ctrl + shift + p را برنید و بعد بنویسید format document
- از روی صفحه کیبورد:keyboard: alt + shift + f را بزنید.

</details>

در HTML لیست توضیحی هم داریم ولی کاربردی نیست.

```html
<dl>
	<dt>Book</dt>
	<dd>Something we read</dd>
	<dt>TV</dt>
	<dd>Something we watch</dd>
</dl>
```

:bell:سعی کنید خودتان به سوالاتتان برسید و جواب بدید و هیچ کاری آسان نیست، پس اگر به مشکل می خورید تسلیم نشوید.

## جدول

از تگ table برای کشیدن جدول استفاده می کنیم.

از تگ tr برای ساخت سطر و برای ساخت سلول از تگ td استفاده می کنیم.

برای ساخت header از تگ th استفاده می کنیم.

```html
<table>
	<tr>
		<th>Name></th>
		<th>Job</th>
	</tr>
	<tr>
		<td>Alireza</td>
		<td>programmer</td>
	</tr>
</table>
```

برای یکی کردن چند تا سلول که در یک ستون قرار دارد، در تگ td از rowspan=”NUMBER” ،attribute استفاده می کنیم و NUMBER تعداد سطر یکسان است.

```html
<table>
    <tr>
        <th>Month</th>
        <th>Savings</th>
        <th>Savings for holiday!</th>
    </tr>
    <tr>
        <td>January</td>
        <td>$100</td>
        <td rowspan="2">$50</td>
    </tr>
</table>
```

برای یکی کردن چند تا سلول که در یک سطر قرار دارد، در تگ td از colspan=”NUMBER” ،attribute استفاده می کنیم و NUMBER تعداد ستون یکسان است.

```html
<table>
    <tr>
        <th>Month</th>
        <th>Savings</th>
    </tr>
    <tr>
        <td colspan="2">Sum: $180</td>
    </tr>
</table>
```

از تگ table به تازگی در ساخت صفحات وب استفاده نمی شود.

از تگ caption بعد از تگ باز table برای توضیح دادن و عنوان جدول استفاده می کنیم.  

```html
<table>
    <caption>Monthly savings</caption>
    <tr>
        <th>Month</th>
        <th>Savings</th>
    </tr>
    <tr>
        <td>January</td>
        <td>$100</td>
    </tr>
</table>
```

## تفاوت تگ های inline و block

به تگ هایی که کل یک سطر را آشغال می کنند تگ های block گفته می شود. مثل تگ p

به تگ هایی که کل یک سطر را اشغال نمی کنند تگ های inline گفته می شود مثل تگ b 

تگ div برای دسته بندی بود و تگ block است.

تگ span برای دسته بندی بود و تگ inline است.

## فرم

تگ form برای ساخت فرم استفاده می شود.

از تگ input برای گرفتن ورودی استفاده می شود که از type ،attribute برای تعیین نوع آن استفاده می کنیم که یک تگ inline است.

برای ساخت دکمه submit از کد زیر استفاده می کنیم.

```html
<input type=”submit” value=”TEXTOFBUTTON”>
```

(به جای TEXTOFBUTTON متنی که می خواهیم داخل دکمه نمایش داده شود را جایگزین می کنیم.)

به متن هایی که قبل از input قرار می دهیم label می گویند.

برای نوشتن label به طوری به که با کلیک روی متن input مدنظر انتخاب شود به صورت زیر عمل می کنیم

1. یک تگ label باز و بسته کرده و در بین آن متن دلخواه مان را می نویسیم.
2. از for ،attribute برای اسم دادن به label استفاده می کنیم.
3. به تگ input متناظر همان اسمی که به for دادیم را به عنوان id قرار می دهیم.

```html
<label for=”TEXT”>name: </label>
<input type=”text” id=”TEXT”>
```

از action ،attribute در تگ فرم برای فرستادن اطلاعات بعد از زدن دکمه submit استفاده می کنیم که نیاز به زبان برنامه نویسی مثل php, python, … است.

دیگر attribute تگ method ،form است که دو مقدار GET و POST می گیرد.

اگه مقدار target ،attribute در تگ form را مساوی _blank باشد، submit کد در صفحه جدید اتفاق می افتد.

فرم ها در حالت پیشفرض حالت autocomplete دارند یعنی متن های قبلی را برای کامل کردن متن به ما پیشنهاد می دهند که برای برداشتن در تگ form مقدار autocomplete ،attribute را مساوی off قرار می دهیم. همین اتفاق را با قرار داخل تگ input هم می توان رغم زد.

```html
<form action="/action_page.php" method="post" autocomplete="off">
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <input type="submit" value="Submit">
</form>
```

مقدار مختلف type ،attribute

1. text: متن
2. password: رمز (کلمات معلوم نیست)
3. submit: دکمه تایید و ارسال اطلاعات فرم
4. reset: دکمه برای خالی کردن اطلاعات فرم
5. email: برای گرفتن ایمیل (مثل متن است با این تفاوت که برای ایمیل نامعتبر خطا می دهد)
6. number: فقط مقدار عددی می پذیرد
7. url: برای ورودی گرفتن آدرس کامل
8. color: برای گرفتن رنگ از کاربر
9. file: برای آپلود فایل و گرفتن فایل از کاربر
10. hidden: برای گرفتن و فرستادن اطلاعات که لازم نیست کاربر بداند مثل id کاربر

اگر مقدار type مساوی submit یا reset باشد با استفاده از value ،attribute می توان متن داخل دکمه را تغییر داد.

وقتی type=”number” باشد دو تا attribute دیگر هم می توانیم استفاده کنیم که min و max است که بازه عدد ورودی را مشخص می کند.

```html
<input type="text">
<input type="password">
<input type="submit" value="TEXT">
<input type="reset" value="TEXT">
<input type="email">
<input type="number" min="NUMBER" max="NUMBER">
<input type="url">
<input type="color">
<input type="file">
<input type="hidden">
```

(به جایی TEXT متنی می خواهید و به جای NUMBER عددی که مدنظرتان هست را قرار می دهید و جایگزین می کنید.)

از value ،attribute برای قراردهی اولیه فیلد ها استفاده می کنیم.

```html
<input type="text" vlue="TEXT">
```

(به جای TEXT متن مدنظرتان را جایگزین می کنید.)

اگه به تگ input readonly ،attribute بدهیم دیگه قابل تغییر نیست و فقط قابل کپی کردن است.

```html
<input type="text" readonly>
```

اگه به input disable ،attribute بدهیم غیرفعال می شود و قابل کپی کردن نیست.

```html
<input type="text" disable>
```

از size ،attribute برای مشخص کردن تعداد کاراکتر ورودی کاربر استفاده می کنیم.

```html
<input type="text" size="NUMBER">
```

(به جای NUMBER عدد مدنظرتان را جایگزین می کنید.)

از maxlength ،attribute برای مشخص کردن حداکثر تعداد کاراکتر ورودی کاربر استفاده می کنیم.

```html
<input type="text" maxlenght="NUMBER">
```

(به جای NUMBER عدد مدنظرتان را جایگزین می کنید.)

از placeholder ،attribute برای نوشتن متن راهنمایی استفاده می کنیم.

```html
<input type="text" placeholder="TEXT">
```

(به جای TEXT متن مدنظرتان را جایگزین می کنید.)

اگه به input required ،attribute بدهیم پر شدنش لازم می شود و در هنگام submit نمی تواند خالی باشد.

```html
<input type="text" required>
```

اگه به input autofocus ،attribute بدهیم وقتی صفحه بالا می آید به صورت پیش فرض انتخاب شده است.

```html
<input type="text" autofocus>
```

از radio button وقتی استفاده می کنیم از چند تا حالت فقط حق انتخاب یک مورد را داریم. مثل جنسیت، سن و...

برای داشتن radio button از input با type=”radio” استفاده می کنیم. برای اینکه radio button هایی که در یک گروه هستند باهم باشند باید name ،attribute یکسانی داشته باشند.

```html
<input type="radio" id="html" name="fav_language" value="HTML">
<label for="html">HTML</label><br>
<input type="radio" id="css" name="fav_language" value="CSS">
<label for="css">CSS</label><br>
<input type="radio" id="javascript" name="fav_language" value="JavaScript">
<label for="javascript">JavaScript</label>
```

از checkboxes وقتی که امکان انتخاب چند مورد وجود داشته باشد استفاده می کنیم. مثل لیست خرید، علاقه مندی ها و...

برای داشتن checkboxes از input با type=”checkbox” استفاده می کنیم. برای اینکه checkbox هایی که در یک گروه هستند باهم باشند باید name ،attribute یکسانی داشته باشند.

```html
<input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
<label for="vehicle1"> I have a bike</label><br>
<input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
<label for="vehicle2"> I have a car</label><br>
<input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
```

برای داشتن select option از تگ select استفاده می کنیم. 

بهتر است برای تگ attributes ،select های name و id را کامل کنیم.

برای قرار دادن لیستی از آیتم ها در تگ select از تگ option استفاده می کنیم.

یادتون نره برای تگ option value ،attribute را پر کنید.

```html
<select name="cars" id="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="opel">Opel</option>
    <option value="audi">Audi</option>
</select>
```

مقدار پیش فرض select option اولین option است ولی اگه به یکی از option ها selected ،attribute را بدهیم به عنوان مقدار پیش فرض select option قرار می گیرد.

```html
<select name="cars" id="cars">
    <option value="volvo">Volvo</option>
    <option value="saab" selected>Saab</option>
</select>
```

اگر بخواهیم مقدار پیش فرض نداشته باشه یک option با متن "--انتخاب کنید--" اول از همه اضافه می کنیم.

```html
<select name="cars" id="cars">
    <option value="not_select">--انتخاب کنید--</option>
</select>
```

اگر به تگ select، attribute multiple بدهیم امکان انتخاب چند تایی داریم که به جاش بهتر است از checkbox ها استفاده کنیم.

```html
<select name="cars" id="cars" multiple>
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="opel">Opel</option>
    <option value="audi">Audi</option>
</select>
```

از تگ textarea برای محیط متنی که قابلیت تغییر سایز دارد استفاده می کنیم. که attributes cols تعداد ستون و عرض را و attributes rows تعداد ردیف و ارتفاع را نشان می دهد.

دارای attribute placeholder نیز هست.

```html
<textarea id="TEXT" name="TEXT" rows="NUMBER" cols="NUMBER" placeholder="TEXT"></textarea>
```

(به جایی TEXT متنی می خواهید و به جای NUMBER عددی که مدنظرتان هست را قرار می دهید و جایگزین می کنید.)

از تگ button برای دکمه استفاده می کنیم که از نوع block است. که هم بیرون و هم داخل تگ form قابل استفاده است.

```html
<button type="button" onclick="alert('Hello world!')">Click Me!</button>
```

از تگ fieldset استفاده می کنیم تا یه تقسیم بندی داخل فرم داشته باشیم.

برای عنوان دادن به filedset از تگ legend در خط بعدی تگ باز filedset استفاده می کنیم.

```html
<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>
```

## فیلم

فرمت های فیلمی که توسط html5 پشتیبانی می شوند شامل mp4, WebM, Ogg است.

از تگ video برای اضافه کردن فیلم استفاده می کنیم.

```html
<video controls>
	<source src=”PATH” type=”video/VIDEO_TYPE”>
</video>
```

(به جای PATH مسیر فیلم مدنظر و به جای VIDEO_TYPE فرمت فیلم را قرار دهید و جایگرین کنید.)

اگر داخل تگ video متنی بنویسیم در صورتی که فایل پشتیانی نشود و برای کاربر نمایش داده نشود این متن نمایش داده می شود.

برای تغییر اندازه ابعاد فیلم داخل تگ video از width ،attribute و height استفاده می کنیم.

## صدا

فرمت های صدایی که توسط html5 پشتیبانی می شوند شامل mp3, wav, ogg است.

از تگ audio برای اضافه کردن صدا استفاده می کنیم.

```html
<audio controls>
	<source src=”PATH” type=”audio/AUDIO_TYPE”>
</audio>
```

(به جای PATH مسیر صدا مدنظر و به جای AUDIO_TYPE فرمت صدا را قرار دهید و جایگرین کنید.)

اگر داخل تگ audio متنی بنویسیم در صورتی که فایل پشتیانی نشود و برای کاربر نمایش داده نشود این متن نمایش داده می شود.


</div>