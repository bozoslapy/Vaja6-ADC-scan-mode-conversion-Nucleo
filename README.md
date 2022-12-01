# Vaja6-ADC-scan-mode-conversion-Nucleo

Odgovori na vprašanja --> 

d) Določite in aktivirajte tri analogne vhode za kanale IN1, IN2 in IN3 za zunanje potenciometre kot Single-ended vhod. 
To bodo pini _____PC0_____, ____PC1_____ in ____PC2______. 

Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? __ADC1__.

f) Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo.
Kaj se izpiše poleg pinov? ___ADC_IN1______, _____ADC_IN2____ in ____ADC_IN3____.

h) V oknu Configuration ADC pretvorbe V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4 MHz.
Koliko bo izbrana vrednost parametra? _____4_______.

j) Koliko je privzeta vrednost paramtera Number of Conversion? ___1___ .

k) Čas vzorčenja Sampling Time izberite 92.5 cikla. Koliko je čas vzorčenja v mikro sekundah? _______61,87μs______. 
Enačba --> tvz = (tvz_cik + 12) / ftakta_pretvorbe

l) V zavihku DMA Settings kliknite Add in v nastalem polju »select« izberite možnost ADC1. Dolžina podatka pretvorbe bo 1 Byte, zato ustrezno popravite izbirno polje Data Width: ______byte______ (tako za Peripheral in Memory). Increment Address omogočite le v registru Memory. V izbirnem polju za način delovanja Mode izberite Circular. Kliknite Ok. Sedaj tudi omogočite DMA Continuos Requests v oknu Parameter Setttings.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Slika mikroprocesorja](https://raw.githubusercontent.com/bozoslapy/Vaja6-ADC-scan-mode-conversion-Nucleo/4d47a22c9f71bfa54ba0d698eb1bf62a38a7e26f/Pinout%206.PNG)

![Slika vezja](https://raw.githubusercontent.com/bozoslapy/Vaja6-ADC-scan-mode-conversion-Nucleo/f3d7343fc18bec1e27d7f05dfdf41b15e950c680/IMG-0370.jpg)


