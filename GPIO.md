# cc2541-tricks


```c
void InitGPIO(void)
{
  P1DIR |= 0x01; //P1.0定义为输出口
  P1SEL &= ~0x01;	//P1.0定义为一般GPIO
}
```