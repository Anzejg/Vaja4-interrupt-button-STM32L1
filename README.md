# Vaja4-interrupt-button-STM32L1


SLIKA PINOUT:
<img width="959" height="701" alt="image" src="https://github.com/user-attachments/assets/d23ff7d7-f55f-4bd1-8833-d2d64ec960e4" />

POSNETEK DELOVANJA:




ODGOVORI NA VPRAŠANJA:
2)

b) pin PA0

c) zelena LED- PC9

modra LED- PC8

3)
c) HAL_GPIO_TogglePin(GPIOC,GPIO_PIN_8);

d) 138,889 μ sekund torej 0,138 m sekund

e) HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);

f) HAL_Delay(500);

4)
e) Ko pritisnemo na Modro tipko se prižge zelena LED, modra LED še vedno utripa, ko še enkrat pritisnemo na modro tipko se zelena LED ugasne in modra LED še vedno neprekinjeno utripa.

f) NE pritisk na modro tipko ne vpliva na utripanje modre LED. Z modro led se ne zgodi nič ker modra tipka upravlja le zeleno LED modra LED pa utripa neprekinjeno.

KOMENTAR: S pritiskom na modro tipko smo upravljali le zeleno LED med tem ko je modra LED neprekinjeno konstantno utripala ker smo tako zapisali našo funkcijo. Ob pritisku na tipko pa smo lahko opazili tudi kako naš signal skače.
