# vajaa4_interupt
b) PA0
c) PC9 (zelena) , PC8 (modra).
d) HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);
HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);
HAL_Delay(500);

PINOUT:

![image](https://user-images.githubusercontent.com/97598727/205745948-3ea4637b-602d-43ec-b515-b4dcfb13f6b4.png)



Komentar: 

Deluje modra LED lučka, vendar ob pritisku modrega gumba se zelena ne prižge.
