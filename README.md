# unit11
mq9
**نام آزمایش:** تشخیص غلظت گاز با استفاده از سنسور MQ9


**هدف آزمایش:** هدف این پروژه، طراحی و پیاده‌سازی سیستمی است که با استفاده از سنسور MQ9 می‌تواند غلظت گازهای مختلف را تشخیص داده و مقادیر آن را بر روی سریال مانیتور نمایش دهد.






**مراحل انجام آزمایش:** 

**تجهیزات مورد نیاز:**
 - Arduino - سنسور MQ9 - LED -  کابل‌های اتصال - بردبورد  منبع تغذیه


**توضیحات بستن پروژه**
اتصال قطعات  سنسور MQ9 به پین A0 برای اندازه‌گیری ولتاژ سنسور متصل می‌شود. 
خروجی دیجیتال سنسور MQ9 به پین 8 (DO) متصل می‌شود. - LED به پین 2 متصل می‌شود.
- تنظیمات اولیه در تابع setup انجام می‌شود. پین‌های مورد نیاز به عنوان ورودی و خروجی تنظیم می‌شوند و ارتباط سریال برای مشاهده مقادیر بر روی سریال مانیتور آغاز می‌شود. - در تابع loop، مقدار ولتاژ سنسور از پین A0 خوانده می‌شود و مقاومت سنسور و نسبت RS به R0 محاسبه می‌شود. - مقادیر محاسبه شده بر روی سریال مانیتور نمایش داده می‌شود. - با استفاده از خروجی دیجیتال سنسور، وضعیت LED کنترل می‌شود.


**نتیجه‌گیری**
 در این پروژه، با استفاده از سنسور MQ9 و Arduino، سیستمی برای تشخیص و اندازه‌گیری غلظت گازهای مختلف طراحی و پیاده‌سازی شد.
 این سیستم قادر است تغییرات ولتاژ سنسور را اندازه‌گیری کند و مقادیر مقاومت سنسور را محاسبه نماید.
 مقادیر محاسبه شده بر روی سریال مانیتور نمایش داده می‌شوند و با استفاده از خروجی دیجیتال سنسور، وضعیت LED کنترل می‌شود. 
این پروژه می‌تواند به عنوان پایه‌ای برای توسعه سیستم‌های پیچیده‌تر تشخیص گاز و ایمنی محیطی مورد استفاده قرار گیرد.



























