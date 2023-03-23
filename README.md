<div dir=”rtl”>

# HTML & CSS

## فهرست

* [مقدمه](#مقدمه)
* [ابزار مورد نیاز](#ابزار-مورد-نیاز)
* [لینک دانلود](#لینک-دانلود)
* [نحوه ساخت فایل html](#نحوه-ساخت-فایل-html)
* [نحوه ساخت فایل .html در vs code](#نحوه-ساخت-فایل-html-در-vs-code)
* [شروع HTML](#شروع-html)
* [ساختار استاندار فایل HTML](#ساختار-استاندار-فایل-HTML)
* [فرم اصلی فایل HTML](#فرم-اصلی-فایل-HTML)
* [تگ p](#تگ-p)
* [نحوه تغییر عنوان صفحه](#نحوه-تغییر-عنوان-صفحه)
* [محیط های کدنویسی وب](#محیط-های-کدنویسی-وب)
* [تگ های heading](#تگ-های-heading)
* [تگ های brو hr](#تگ-های-brو-hr)

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

## نحوه ساخت فایل .html در vs code

1. محیط vs code را باز می کنیم.
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
:diamond_shape_with_a_dot_inside:Notepad, sublime, vs code, nano,...

- IDE<br>
:diamond_shape_with_a_dot_inside:Php storm, web storm,...

:pushpin:با notepad هم می شود برای کار استفاده کرد ولی خیلی ساده است (و شایدم حوصله سر بر).

## تگ های heading

تگ های heading برای کاربر نمایش داده می شوند، پس داخل تگ body نوشته می شود .

که برای نوشتن عناوین از این تگ استفاده می شود.

تگ های h1, h2, h3, h4, h5, h6 را داریم که به ترتیب کوچک می شوند. (h1 بزرگتر از همه و h6 کوچکتر از همه است.)

```
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

:pushpin: تگ brو hr تگ بسته ندارد.

```
<br>
<hr>
```

:new_moon_with_face:نمایش فایل html بدون فایل CSS در مرورگر های مختلف ممکن است فرق کند و آنم به خاطر استایل های پیش فرض مرورگر هاست که به تگ های می دهند.

</div>