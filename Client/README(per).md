> [!WARNING]
> اگر بر روی اینترنت شما هنوز وایرگارد کار میکنه از کانفیگ Chain استفاده کنید وگرنه از CDN استفاده کنید
> (کانفیگ Chain روی ارائه دهنده های اینترنت : ایرانسل، آسیاتک، زیتل و مبین نت تست شده و کار میکند)

>[!CAUTION]
>برای کانفیگ Chain :
>برای هر دستگاه، کانفیگ وارپ وایرگارد مجزا تهیه کنید، با یک کانفیگ وارپ و دستگاه متفاوت کلادفلر دچار مشکل و اختلال میشه (باعث وصل نشدن یا تجربه سرعت پایین میشه)


>[!NOTE]
>شما از vless بجای vmess، از websocket بجای httpUpgrade میتوانید استفاده کنید اما در سمت سرور هم باید تغییرات را اعمال کنید
>در تجربه من (ایران)، vmess و httpUpgrade کارایی بهتر و امنیت بالاتری دارند


در کانفیگ های CDN، در خروجی های fragment، پارامتر length داریم. کمترین ۷ کاراکتر کمتر از تعداد کاراکتر دامنه و بیشترین باید ۱ کاراکتر کمتر از تعداد کاراکتر دامنه باشد. برای مثال دامنه شما ۴۴ کاراکتر هست (با احتساب زیردامنه و بدون احتساب نقطه ها)، مقدار "length : "37-43 می شود


شما بجای کمترین که ۷ کاراکتر کمتر از تعداد کاراکتر دامنه هست میتونید از اعداد بالاتری استفاده کنید مثل ۷،۸،۹ ... اما بیشترین باید ۱ کاراکتر کمتر از تعداد کاراکتر دامنه باشد
