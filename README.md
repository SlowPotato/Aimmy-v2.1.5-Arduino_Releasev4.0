# Aimmy-v2.1.5-Arduino_Releasev4.0 (Razer mouse recommended)

Hardware links:

Leonardo R3 Atmega32u4
https://www.aliexpress.us/item/3256808603244408.html?spm=a2g0o.productlist.main.15.239e5b33IvuwDL&algo_pvid=ab1549e9-f30c-4d80-82e4-10fa69ab0adc&algo_exp_id=ab1549e9-f30c-4d80-82e4-10fa69ab0adc-14&pdp_ext_f=%7B%22order%22%3A%2257%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%216.46%211.66%21%21%2145.71%2111.72%21%402101e80317638596985842992eafc9%2112000046669953843%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A50bda464%3Bm03_new_user%3A-29895%3BpisId%3A5000000187461913&curPageLogUid=H74AmT90Z8TF&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008789559160%7C_p_origin_prod%3A

USB HOST 2.0
https://www.aliexpress.us/item/3256808561161776.html?spm=a2g0o.productlist.main.23.f1c92YtB2YtBad&algo_pvid=bf2c68b8-0271-4e89-9cf3-859ae81fb7bf&algo_exp_id=bf2c68b8-0271-4e89-9cf3-859ae81fb7bf-20&pdp_ext_f=%7B%22order%22%3A%2210%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis!USD!6.65!2.65!!!6.65!2.65!%402101c59117638593277557866e588f!12000046500694356!sea!US!0!ABX!1!0!n_tag%3A-29910%3Bd%3A50bda464%3Bm03_new_user%3A-29895%3BpisId%3A5000000187461913&curPageLogUid=worKoeAHEl2U&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008747476528%7C_p_origin_prod%3A


<img width="359" height="242" alt="Boards Setup" src="https://github.com/user-attachments/assets/e8e3c285-cd22-45d0-9870-069185f7511f" />

![Visual](https://github.com/user-attachments/assets/3ed96842-58d4-4eee-a451-3fbc1d08ee62)

Check your HOST SHIELD Board for pre-soldering, if no solder is in the areas shown below then you will need to buy a soldering iron and solder to bridge the connections.

<img width="384" height="366" alt="Needs Solder" src="https://github.com/user-attachments/assets/bb96dbb0-bffa-4e53-a0b5-b7d71e468526" />


Do the following below if you have a "non" pre-soldered board.
--

Here is a tutorial video on how to solder and bridge the connection points.

https://github.com/user-attachments/assets/15feee58-98ea-4044-81b7-81a0560c071d

Connection points as shown after soldering.

<img width="464" height="327" alt="Solder points" src="https://github.com/user-attachments/assets/9581888c-fb79-43a3-ae7d-1fa8fb3a06b1" />

Now you're ready to program the board. Plug micro usb cable to power the Leonardo R3 and proceed with the video guide below.

---
Guide
---
If using a HOST SHIELD select "Y" when prompted if you don't have one just select "N". HOST SHIELD is "recommended" for games on STEAM, EA, Battlenet etc... since the newest patch 10/15/25 blocks 2nd mouse inputs such as Leonardo R3 alone without a HOST SHIELD, DDxoft, Mouse Events, Razer Drivers, LG Hub Drivers. [If using without HOST SHIELD this will still work on other games that block out most external mouse inputs]

https://github.com/user-attachments/assets/5d933af0-6dc1-425c-90f5-f920b4b94c04

---
DOWNLOAD:
---
Found here: https://drive.google.com/file/d/1AFlfR-jMat8cHeF-BKt679vFSWuXHfWs/view?usp=sharing

If any reason you cant access my GDrive message me in discord @ MentalEngineer#4729, if you're already on the known discord then just DM me.

WIN11 USERs getting "wmic" error
-
Do the following command in Powershell as Admin
command: Add-WindowsCapability -online -name WMIC

Then re-run .bat as Admin.

If still fails run this command: dism /online /add-capability /capabilityname:WMIC~~~~

KNOWN UNSUPPORTED MOUSES:
--
Logitech G300s, Logitech Hero 502, Logitech G102
