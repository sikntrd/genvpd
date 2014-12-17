GenVPD - Generates VPD 2.0 files to use with coreboot for Chromeboxes/books
===========================================================================
This is for people who lost their original or never backed up.<br/><br/>
History<br/>
*genvpd v0.1 - Initial release<br/><br/>
How to use:

1. save script as genvpd
2. chmod +x genvpd
3. ./genvpd <output.file>
4. fill out the form

<table style="width:100%">
<tr><td>ethernet_mac</td><td>00:01:02:03:04:05</td></tr>
<tr><td>mlb_serial_number</td><td>123456789ABCDE</td></tr>
<tr><td>initial_locale</td><td>am,be,bg,br,by,ca,ch,cz,de,dk,ee,es,fi,fr,gb,ge,gr,hr,hu,ie,il,is,it,jp,latam,lt,lv,mn,no,pl,pt,ro,rs,ru,se,si,sk,tr,ua,us</td></tr>
<tr><td>initial_timezone</td><td>https://src.chromium.org/svn/trunk/src/chromeos/settings/timezone_settings.cc</td></tr>
<tr><td>keyboard_layout</td><td>https://src.chromium.org/svn/trunk/src/chromeos/ime/input_methods.txt</td></tr>
<tr><td>model_name</td><td><brand> Acer/Asus/Dell/HP Chromebox</td></tr>
<tr><td>region</td><td>am,be,bg,br,by,ca,ch,cz,de,dk,ee,es,fi,fr,gb,ge,gr,hr,hu,ie,il,is,it,jp,latam,lt,lv,mn,no,pl,pt,ro,rs,ru,se,si,sk,tr,ua,us</td></tr>
<tr><td>serial_number</td><td>see product sticker,serial: 123456789A</td></tr>
<tr><td>sku_number</td><td>see product sticker,product: 1234567-89A</td></tr>
</table>

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
