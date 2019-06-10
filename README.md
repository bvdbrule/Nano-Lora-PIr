# Nano-Lora-Pir
PCB: Arduino Nano with Lora RFM95w and PIR sensor AM312 

<picture>
  <img src="https://github.com/bvdbrule/Nano-Lora-PIr/blob/master/Nano-Lora-AM312.jpeg"  alt="Arduino Nano with Lora RFM95W" style="width:auto;">
</picture>

PCB is designed to use in combination with a power connector case <a href="https://www.conrad.nl/p/strapubox-typ-i-stekkerbehuizing-37-x-43-x-735-abs-zwart-1-stuks-522716">Strapubox TYP 522716</a>

<H2>BOM</H2>
<UL>
<LI>1x <a href="https://s.click.aliexpress.com/e/2bAT3EjMB">AC/DC converter 230V to 5V 2W</a>
<LI>1x <a href="https://s.click.aliexpress.com/e/oj4uVwhix">Arduino Nano V3.0</a>  
<LI>1x <a href="https://s.click.aliexpress.com/e/PBDM0cXJl">RFM95W Lora transmitter 868 MHz</a>
<LI>1x <a href="https://s.click.aliexpress.com/e/WBSL7YfS3">74HC4050D Hex non-inverting HIGH-to-LOW level shifter SOP16</a>  
<LI>1x <a href="https://s.click.aliexpress.com/e/6nBLz9hcr">Mini PIR sensor AM312</a>
<LI>1x <a href="https://s.click.aliexpress.com/e/FeFXT5VVZ">Coil antenna 868 MHz</a>  
<LI>1x <a href="https://aisler.net/p/XXJEPJJO">PCB fabricated by Aisler</a>  
</UL>
Note: Solder the spiral/coil/wire antenna directly on the RFM95W ANT pin.

<H2>LMIC Pin Mapping</H2>
const lmic_pinmap lmic_pins = {<br>
.nss = 10,{<br>
.rxtx = LMIC_UNUSED_PIN,{<br>
.rst = LMIC_UNUSED_PIN,{<br>
.dio = {7, 8, 9},{<br>
};{<br>


