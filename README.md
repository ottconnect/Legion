# Legion
[CENTER]
[SIZE=5].:: DEV APEX TEAM Legion 7.2.0 build 24015 ::.[/SIZE]

Dev Apex Team is a MMORPG Framework based mostly in C++.

It is derived from MaNGOS, TrinityCore the Massive Network Game Object Server, and is based on the code of that project with extensive changes over time to optimize, improve and cleanup the codebase at the same time as improving the in-game mechanics and functionality.


If you want more details for now join me on my team website [url][/url]

Also a huge thanks to Trinity Core Team for allowing us to use their core for our project :)

Keep watching at Dev Apex Team we aim to please :)


Also please use internet explorer to register on the website.
--------------------------------------------------------------------------------------------------------------------

Also please follow the first post instruction on how to setup the repack.

Thanks everyone for your support.
-------------------------------------------------------------------------------------------------------------------

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zUzEzNldROXRyOGs"][COLOR="#FF0000"]Core Version 7.2.0 1.0.0.1 32bit[/COLOR][/URL] [COLOR="#FF0000"][/COLOR]

-------------------------------------------------------------------------------------------------------------------

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zaXFMeFRzemdwM3c"][COLOR="#FF0000"]Core Version 7.2.0 1.0.0.1 64bit[/COLOR][/URL]  [COLOR="#FF0000"][/COLOR]
----------------------------------------------------------------------------------------------------------------
Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zUGJtU2xQTTNwYW8"][COLOR="#FF0000"]Database 7.2.0-1.0.0.1[/COLOR][/URL]  [COLOR="#FF0000"][/COLOR] and [COLOR="#FF0000"][/COLOR] 
-----------------------------------------------------------------------------------------------------------------

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zZE9aU1hZZmF2bms"][COLOR="#FF0000"] New DBC[/COLOR][/URL]

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zSXdPdUE4ekNUR0U"][COLOR="#FF0000"]New Maps[/COLOR][/URL]

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zOWRrODlHX1hZa00"][COLOR="#FF0000"]New Vmaps[/COLOR][/URL]

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zanRtV0kwSGpONzA"][COLOR="#FF0000"]Connection Patcher 32bit[/COLOR][/URL]

Download: [URL="https://drive.google.com/open?id=0ByMbyQDZai7zNnBsTDM3YjRuMzg"][COLOR="#FF0000"]Connection Patcher 64bits[/COLOR][/URL]

-----------------------------------------------------------------------------------------------------------

0x00000(some other 0)7 error?
Post By Tkrokli

Are you sure you have installed the 2015 vcredist_x86.exe from Microsoft?
(... or the vcredist_arm.exe if you got the ARM CPU in your computer) (Downlooad link will come soon)

If that is taken care of already, you most likely have installed the OpenSSL-Win64 on your computer as part of your Windows OS system files, but not the Win32 version. The 0xc000007b error is almost always caused by a mix-up of 32bit and 64bit software on a 64bit Windows installation (this error never occurs on 32bit (x86) Windows).

Make sure that the DLLs Libeay32, Libmysql and SSLeay32 are 32bit in the repack folder (which they are in the downloads).

Suggestion: install Win32 OpenSSL v1.0.2h or Win32 OpenSSL v1.0.1h
(both of these are the latest and current versions of 32bit OpenSSL).

 If you still get the 0xc000007b error, you probably have a separate 64bit MySQL server installed, or you need to uninstall any OpenSSL software that you have already installed on your computer.
-------------------------------------------------------------------------------------------------------------

PICTURES WILL COME SOON, PLEASE BE PATIENT THIS IS THE FIRST VERSION OF LEGION 7.2.0.
[/CENTER]
