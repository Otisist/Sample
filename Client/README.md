[Persian](https://github.com/Otisist/Sample/blob/main/Client/README(per).md)

> [!WARNING]
> If Wireguard is still working on your internet, use Chain config otherwise use CDN
> (Chain config has been tested and works on internet providers: Irancell, Asiatech, Zi-tel and Mobinnet)

>[!CAUTION]
>For chain config :
>For each device you must get different warp wireguard config, cloudflare confused the same warp wireguard configuration on different devices (it causes not connecting or experiencing low speed)

>[!NOTE]
>You can use Vless instead of vmess, use websocket transfer instead of httpUpgrade. but you have to apply these changes on the server as well
In my experience (Iran), vmess and httpUpgrade work better and have a higher security factor

In CDN configs, in fragment outbounds, we have length parameter, min length 7 characters less than the character length of the domain and max must be 1 character less than the character length of the domain. for example your domain has 44 characters, length: "37-43"


You can in min length instead of 7 characters change number to above 7, like 8,9,10 ... But in max length, you must be 1 character less than character length of the domain
