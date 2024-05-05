<h2 dir="rtl">  نام و نام خانوادگی : محمدمعین محمدی </h2>
<h2 dir="rtl"> موضوع : تفاوت  sql  و  nosql </h2>
<h2 dir="rtl">
اصلی ترین تفاوت بین  Sql  و Nosql  در ساختار داده ، مدل روابط و قابلیت افزایش خطی اون هاست. Sql  برای داده های ساختار یافته و با روابط پیچیده مناسبه ولی  Nosql  برای داده های غیر ساختار یا نیازمند سرعت و قابلیت افزایش خطی مناسبه.
شکل داده ها در  nosql  انعطاف پذیری بیشتری دارند.
سرعت عملیات خواندن و نوشتن در  nosql  بیشتر از  sql  است.
در  sql  داده های جداول مختلف میتونن وقتی بهشون نیاز داریم به راحتی با هم ترکیب شن که در nosql  از این کار جلوگیری میشه.
برای شرایط و زمانی که خواندن زیاده عملکرد  nosql بهتره.
معمولا پایگاه های داده  sql پایدار تر هستند.


تمرین هفته دوم 
موضوع : تفاوت  oracle , mysql, sqlserver

رواقع اس کیو ال سرور امکانات بیشتری نسبت به مای اس کیو ال دارد ولی مای اس کیو ال رایگانه و هزینه ای برای کاربر نداره
.کارکردن با دیتابس اوراکل سخت تر از دیگر دیتابیس هاست اما در اکثر پروژه های بزرگ از این دیتابیس استفاده میشه ، و از نظر مدیریت بانک اطلاعاتی اوراکل بهتر از اس کیو ال سرور است
.زبان های برنامه نویسی اوراکل و مای اس کیو ال با اس کیو ال سرور تفاوت داره و اوراکل و مای اس کیو ال از زبان های سی پلاس پلاس و سی استفاده کردن
 .اس کیو ال سرور نسبت به اوراکل یادگیریش ساده تره ولی اوراکل قابل انعطاف تره
اوراکل روی پلتفرم های مختلف ورژن خاص خودش رو داره و اس کیو ال سرور میشه گفت فقط مختص ویندوزه
اس کیو ال سرور از لحاظ رابط کاربری ساه تر و جذاب تر از بقیه ی دیتابیس هاست و درکل کارکردن باهاش راحت تره.و ابزارهای مدیریت آن بیشتر و بهترن.

تمرین هفته سوم 
موضوع :  caching server - logstash - Data warehouse


.کش سرور : یک سرور شبکه یا سرویس در سروره که صفحه‌های وب و محتوای اینترنت رو تو خودش ذخیره می‌کنه
این کار باعث میشه که در دفعات بعدی مراجعه به یک صفحه، درخواست کاربر براساس اطلاعات ذخیره‌شده تو حافظه پنهان یا همون کش خونده میشه و باعث افزایش سرعت بارگذاری صفحه میشه.
کش سرور دارای یک سری مزایا است که شامل : 
کاهش بار پردازشی سرور اصلی
کاهش مصرف پهنای باند
بهبود عملکرد شبکه
بهبود تجربه کاربری


موضوع دوم : logstash
یک ابزار قدرتمند برای متمرکز سازی و تحلیل لاگ هااست که کمک میکنهیه دید کلی از محیط خودمون داشته باشیم وو خیلی سریع مشکلات سرور هارو تشخیص بدیم
پس خیلی راحت میتونیم روی داده ها کوئری اجرا کنیم.
 استفاده میشه.Elasticsearch یکی از محصولات اصلی الاستیک است که برای جمع‌آوری و پردازش داده‌ها و ارسال آن بهlogstash 
این قابلیت به ما امکان می دهد تا داده هارا از چندین منبع به طور همزمان دریافت کنیم
استفاده می شود هم افزایی قوی با این فناوری ها ارایه می دهدELK يا Elastic Stack اغلب به عنوان يک بخش کليدي از پشتهLogstash 


:data warehouseموضوع سوم
انبار داده است که مجموعه بزرگی از داده های تجاری است که به سازمان ها و کسب و کار ها کمک می کنه  که در تصمیم گیری های خود دقیق تر و هوشمندانه تر عمل کنند
در واقع یک انبار داده شامل عناصر مختلفی از جمله :
یک پایگاه داده رابطه‌ای برای ذخیره و مدیریت داده‌ها
قابلیت‌های تجزیه‌و‌تحلیل آماری، گزارش‌دهی و داده‌کاوی و ... می باشد
انبار های داده این مزیت را ایجا میکنند که به سازمان اجازه دهند حجم مختلفی از داده های مختلف را تجزیه و تحلیل کرده و اطلاعات ارزشمندی از آن استخراج کنند.
انبار داده در صنایع و شرکت های مختلف کاربرد زیادی دارد به خصوص در صنعت بیمه - خرده فروشی  صنعت سلامتی و ...
