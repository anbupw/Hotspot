# :warning: For Educational Purposes Only :exclamation:

Disclaimer :
1. For educational purposes only.
2. Don't use them for illegal activities.
3. You are the only responsible for your actions :exclamation:

:see_no_evil: :hear_no_evil: :speak_no_evil:

-------------------------------------------------------------------------


#### UNTUK BYPASS HOTSPOT KAT LAPTOP UNTUK GUNA DATA SELAIN DARI HOTSPOT DI HANDPHONE 

1. buka hotspot di phone
2. di laptop/pc, connect kepada hotspot
3. di laptop, buka cmd, run as administrator 
4. type "netsh int ipv4 set glob defaultcurhoplimit=65" di cmd tu
5. tekan enter dan akan keluar ok
6. dah bypass


-------------------------------------------------------------------------


#### INFORMATION


Using hotspot data from your mobile phone on your laptop/computer

1. netsh int ipv4 set glob defaultcurhoplimit=65
2. netsh int ipv6 set glob defaultcurhoplimit=65


Use your laptop as a Wi-Fi repeater:

1. netsh int ipv4 set glob defaultcurhoplimit=64
2. netsh int ipv6 set glob defaultcurhoplimit=64


Set it to default:

1. netsh int ipv4 set glob defaultcurhoplimit=128
2. netsh int ipv6 set glob defaultcurhoplimit=128


Default TTL and Hop Limit values vary between different operating systems, here are the defaults for a few:

1. Linux kernel 2.4 (circa 2001): 255 for TCP, UDP and ICMP
2. Linux kernel 4.10 (2015): 64 for TCP, UDP and ICMP
3. Windows XP (2001): 128 for TCP, UDP and ICMP
4. Windows 10 (2015): 128 for TCP, UDP and ICMP
5. Windows Server 2008: 128 for TCP, UDP and ICMP
6. Windows Server 2019 (2018): 128 for TCP, UDP and ICMP
7. MacOS (2001): 64 for TCP, UDP and ICMP


*defaultcurhoplimit - Default HopLimit of packets sent*

**************************************************************************

#### REFERENCE

1. [Change TTL in Windows 10](https://social.technet.microsoft.com/Forums/en-US/08f61f15-68ac-4bde-880a-1e2b1a038ccf/change-ttl-in-windiws-10?forum=win10itpronetworking "Microsoft: TechNet")
2. [netsh interface ipv4 set global command](http://www.colorconsole.de/cmd/en/Windows_7/netsh/interface/ipv4/set/global.htm "Color Console")
3. [IP Time to Live (TTL) and Hop Limit Basics](https://packetpushers.net/ip-time-to-live-and-hop-limit-basics/ "Packet Pushers")
4. [2019: Bypass Verizon Hotspot Throttle (NO ROOT)](https://www.reddit.com/r/Android/comments/cmxp66/2019_bypass_verizon_hotspot_throttle_no_root/ "Reddit")
5. [How to make the cmd line executable](https://stackoverflow.com/questions/42826625/how-to-make-the-cmd-line-executable "Stackpverflow")
6. [How to change the default TTL of TCP/IP packets?](https://askubuntu.com/questions/667096/how-to-change-the-default-ttl-of-tcp-ip-packets "askubuntu")
7. https://www.allegro.cc/forums/thread/614960
8. https://www.reddit.com/r/Android/comments/x77ji/undetectable_tethering_using_android_phone/
9. https://searchnetworking.techtarget.com/definition/time-to-live
10. https://subinsb.com/default-device-ttl-values/
11. https://web.archive.org/web/20150206054041/http://www.binbert.com/blog/2009/12/default-time-to-live-ttl-values/
12. https://android.stackexchange.com/questions/47819/how-can-phone-companies-detect-tethering-incl-wifi-hotspot
13. https://itstillworks.com/remove-sassexe-8693324.html
14. http://noahdavids.org/self_published/TTL_values.html
15. https://forum.xda-developers.com/android/help/tethering-ttl-t3824958

#### YOUTUBE REFERENCE

1. [Tutorial Hotspot/tethering UNLIMITED Umobile/Digi untuk iphone sahaja.](https://youtu.be/WuD31ZkDiPc "Youtube")
