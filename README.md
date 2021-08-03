# Huawei 5g cpe pro 2 port forwarding

I have googled around for how to open ports on the new 5g modems such as the **Huawei 5g cpe pro 2** and found dead ends everywhere, even on the main company website, however, I found the below method which worked with me and now I have _NAT TYPE: OPEN_

> I live in Saudi Arabia, have a 5g subscription from STC, not sure if this will work for you

بحثت في الإنترنت عن طريقة فتح بورتات في مودم الفايف جي لكن مالقيت طريقة حتى بموقع الشركة نفسه

## Steps in English

- Login your router admin page through the link [http://192.168.8.1/](http://192.168.8.1/), the password is located under your modem
  [image](!https://www.github.com/xxxxxxxxxxxxxx)
- Go to *Advanced*
- Go to *Router / DHCP*
- Make sure your device (PC/Console) has static IP by assigning it an ip under *IP and MAC Address Binding List*
  [image](!https://www.github.com/xxxxxxxxxxxxxx)
- Go to *Security / Firewall*
- Disable Firewall
  [image](!https://www.github.com/xxxxxxxxxxxxxx)

- Go to *Security / Virtual Server*
- In this screen, open the ports you want and direct it to the IP address you assigned to your device
  [image](!https://www.github.com/xxxxxxxxxxxxxx)

- Go to *Security / DMZ Settings*
  [image](!https://www.github.com/xxxxxxxxxxxxxx)

- Enable it and point it to your device
- Go to *Security / UPnP Settings*
- Enable it
  [image](!https://www.github.com/xxxxxxxxxxxxxx)
- That's it, congratulations on your NAT TYPE OPEN



<span dir="rtl" align="right">

## الخطوات بالعربي

</span>



## Say thanks if this helped
- [Twitter](https://www.twitter.com/BuFai7an)








### Keywords
How to open ports on CPE Pro 2 كيف تفتح بورتات/منافذ في مودم الفايف جي
Call of Duty
Modern Warfare
Black Ops
Grand Theft Auto
GTA
كود
كول اوف ديوتي
بلاك اوبس
موديرن وار فير
قراند ذيفت اوتو
زين
موبايلي
إس تي سي
STC
Zain
Mobily
5G
فايف جي
NAT
OPEN
MODERATE