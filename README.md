# f103rc.msb.gpio.key

实现按键控制LED灯逻辑。KEY0控制LED0状态，KEY1控制LED1状态。KEY_UP同时控制LED0和LED1状态。  
按下对应按键，将控制其对应的LED状态反转，即原来亮就变为灭，原来灭就变为亮。

LED0接在PA8引脚上，LED1接在PD2引脚上。KEY0接在PC1引脚上，KEY1接在PC13引脚上，KEY_UP接在PC13引脚上。
