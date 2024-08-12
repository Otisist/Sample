If Wireguard is still working on your internet, use Chain config otherwise use CDN
(Chain config has been tested and works on internet providers: Irancell, Asiatech, Zi-tel and Mobinnet)

Important note for chain config :
For each device you must get different warp wireguard config, cloudflare confused the same warp wireguard configuration on different devices (it causes not connecting or experiencing low speed)

You can use Vless instead of vmess, use websocket transfer instead of httpUpgrade. but you have to apply these changes on the server as well
In my experience (Iran), vmess and httpUpgrade work better and have a higher security factor


اگر بر روی اینترنت شما هنوز وایرگارد کار میکنه از کانفیگ Chain استفاده کنید وگرنه از CDN استفاده کنید
(کانفیگ Chain روی ارائه دهنده های اینترنت : ایرانسل، آسیاتک، زیتل و مبین نت تست شده و کار میکند)

نکته مهم برای کانفیگ Chain :
برای هر دستگاه، کانفیگ وارپ وایرگارد مجزا تهیه کنید، با یک کانفیگ وارپ و دستگاه متفاوت کلادفلر دچار مشکل و اختلال میشه (باعث وصل نشدن یا تجربه سرعت پایین میشه)


شما از vless بجای vmess، از websocket بجای httpUpgrade میتوانید استفاده کنید اما در سمت سرور هم باید تغییرات را اعمال کنید
در تجربه من (ایران)، vmess و httpUpgrade کارایی بهتر و امنیت بالاتری دارند
