arm_adapter
=====

Small addition to Noah's 20-pin to 10-pin ARM JTAG/SWD adapter to include additional connectors in addition to the 10-pin SMT connector:
* 6-pin through-hole (e.g. Amarok)
* 10-pin through-hole (non-standard APC pinout?)
* 10-pin through-hole Cortex debug connector (same pin-out as 10-pin SMT)
* 20-pin SMT Debug+Cortex ETM connector

pcb render
=====
<!---
![front](https://raw.githubusercontent.com/noahp/arm_20to10/master/front.png). . . . . .  ![back](https://raw.githubusercontent.com/noahp/arm_20to10/master/back.png)
-->

assembly render
=====
<!---
![top](https://raw.githubusercontent.com/noahp/arm_20to10/master/3drender_top.png)
![iso](https://raw.githubusercontent.com/noahp/arm_20to10/master/3drender_iso.png)
-->

assembled unit
=====
<!---
<img src="https://raw.githubusercontent.com/noahp/arm_20to10/master/assembled_picture.jpg" width="480">
-->

parts
=====
10 pin through hole male connector
-----
[digikey](http://www.digikey.com/product-detail/en/20021111-00010T4LF/609-3712-ND/2209072)
[mouser](http://www.mouser.com/ProductDetail/FCI/20021111-00010T4LF/?qs=sGAEpiMZZMs%252bGHln7q6pmwodwKqstCempwNsK2c%2fC6s%3d)
[ebay](http://www.ebay.com/itm/12-pcs-Gold-Plated-1-27mm-2x40-80pin-Breakable-Pin-Header-Male-Double-Row-Strip-/370935487630?pt=LH_DefaultDomain_0&hash=item565d7a5c8e)

[shrouded, digikey](http://www.digikey.com/product-detail/en/3220-10-0100-00/1175-1627-ND/3883661)

20 pin through hole female connector
-----
[digikey](http://www.digikey.com/product-detail/en/SFH11-PBPC-D10-ST-BK/S9197-ND/1990090)
[ebay](http://www.ebay.com/itm/20-Pcs-2x10-Double-Row-20-Pins-PCB-Female-Header-2-54mm-/400316132430?pt=LH_DefaultDomain_0&hash=item5d34b36c4e)
[digkey right angle](http://www.digikey.com/product-detail/en/SFH11-PBPC-D10-RA-BK/S9205-ND/1990098)

3.3v ldo
-----
[mouser- skyworks sot23-5](http://www.mouser.com/ProductDetail/Skyworks-Solutions-Inc/AAT3223IGU-33-T1/?qs=sGAEpiMZZMsGz1a6aV8DcBc9KxeEYlaaHoWA415Wy2k%3d)
[mouser- TI sot23-5](http://www.mouser.com/ProductDetail/Texas-Instruments/LP5907MFX-33-NOPB/?qs=sGAEpiMZZMsGz1a6aV8DcHd1yzolGFo2Xmtn9ZKMxmA%3d)
[digikey- TI sot23-5](http://www.digikey.com/product-detail/en/TLV70233DBVR/296-32415-1-ND/3505572)
[digikey- Micrel sot23-5 300mA](http://www.digikey.com/product-detail/en/MIC5504-3.3YM5%20TR/576-4764-1-ND/4864028)

beefier ldo
----
[mouser- ON](http://www.mouser.com/ProductDetail/ON-Semiconductor/NCP1117LPST33T3G/?qs=sGAEpiMZZMsGz1a6aV8DcG1%252bflTKYVRGzugDxB67PIA%3d)
[mouser- diodes](http://www.mouser.com/ProductDetail/Diodes-Incorporated/AP1117IE33G-13/?qs=sGAEpiMZZMsGz1a6aV8DcCIlKWhD2GibreMCbJvWdNw%3d)

slide switch
-----
[mouser- C&K](http://www.mouser.com/ProductDetail/CK-Components/PCM12SMTR/?qs=sGAEpiMZZMsqIr59i2oRcvc9UQrBbcoBkFYgnQFYwWU%3d)
[digikey- Copal](http://www.digikey.com/product-detail/en/CUS-12TB/563-1102-1-ND/1124231)
[mouser- ALPS](http://www.mouser.com/ProductDetail/ALPS/SSSS810701/?qs=sGAEpiMZZMtHXLepoqNyVe%252bcQMRoBF1BAzyvwoNmgBo%3d)
