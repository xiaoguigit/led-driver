v1:
�����ں� drivers/char
�޸� drivers/char/Makefile����ӣ�
obj-y += leds_4412.o

���±����ں�

v2:
�� leds_4412.c �ŵ�drivers/leds
�޸� drivers/leds/Makefile:
obj-y += leds_4412.o

���������ں�
make menuconfig

CONFIG_LEDS_CLASS
CONFIG_LEDS_TRIGGERS
CONFIG_LEDS_TRIGGER_TIMER

-> Device Drivers
  -> LED Support
   [*]   LED Class Support    
   [*]   LED Trigger support
   <*>   LED Timer Trigger
   
���±����ں�

