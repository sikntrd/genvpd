GenVPD - Generates VPD 2.0 files for Chromeboxes/books to use with coreboot
===========================================================================
This is for people who lost their original or never backed up.


History
*genvpd v0.1 - Initial release

How to use:

Run genvpd <outputfile>
eg: genvpd vpd.bin

ethernet_mac      : 00:01:02:03:04:05<br/>
mlb_serial_number : 123456789ABCDE<br/>
initial_locale    : pick yours:<br/> am,be,bg,br,by,ca,ch,cz,de,dk,ee,es,fi,fr,gb,ge,gr,hr,hu,ie,il,is,it,jp,latam,lt,lv,mn,no,pl,pt,ro,rs,ru,se,si,sk,tr,ua,us<br/>
initial_timezone  : see https://src.chromium.org/svn/trunk/src/chromeos/settings/timezone_settings.cc<br/>
keyboard_layout   : see https://src.chromium.org/svn/trunk/src/chromeos/ime/input_methods.txt<br/>
model_name        : <brand> Chromebox<br/>
region            : pick yours: am,be,bg,br,by,ca,ch,cz,de,dk,ee,es,fi,fr,gb,ge,gr,hr,hu,ie,il,is,it,jp,latam,lt,lv,mn,no,pl,pt,ro,rs,ru,se,si,sk,tr,ua,us<br/>
serial_number     : see product sticker,serial ) 123456789A<br/>
sku_number        : see product sticker,product) 1234567-89A<br/>

This is valid for HP, but can be used with Acer,Asus and Dell variants<br/>
If you noticed any differences or find any faults, leave me a message at sikntrd@grr.la<br/>

You could also help me with supplying information:<br/>
*Length of all the above variables so i can build in some checks.<br/>
*MAC Addresses:<br/>
Acer: xx:xx:xx:xx:xx:xx<br/>
Asus: xx:xx:xx:xx:xx:xx<br/>
Dell: xx:xx:xx:xx:xx:xx<br/>
HP  : 8C:DC:D4:xx:xx:xx<br/>

With my information i was able to build a 100% genuine vpd.bin file. (verified with my backup)<br/>
