English:

In this config, i'm using vless-tcp-TLS on port 443 with fallback vmess-httpUpgrade (because i using Chain and CDN config at same time in client side and i forced to use one of HTTPS ports supported by Cloudflare)
You can also use fallback vmess-ws or vless-ws or vless-httpUpgrade, but the changes must be applied on the user configuration side
>[!NOTE]
>You can using one of ports : 443,2053,2083,2087,2096,8443 according to [cloudflare HTTPS ports supported](https://developers.cloudflare.com/fundamentals/reference/network-ports/)


پارسی:

توی این کانفیگ، من از vless-tcp-TLS روی پورت ۴۴۳ با فالبک به vmess-httpUpgrade استفاده کردم (چون من کانفیگ Chain و CDN در سمت کاربر بصورت همزمان استفاده میکنم، مجبور به استفاده از یکی از پورت های HTTPS پشتیبانی شده کلودفلر هستم)
شما میتوانید فالبک vmess-ws یا vless-ws یا vless-httpUpgrade هم استفاده کنید، اما تغییرات در سمت کانفیگ کاربر باید اعمال گردد
>[!NOTE]
>شما میتوانید یکی از پورت های : 443,2053,2083,2087,2096,8443 باتوجه به [پورت های HTTPS پشتیبانی شده کلودفلر](https://developers.cloudflare.com/fundamentals/reference/network-ports/) استفاده کنید
