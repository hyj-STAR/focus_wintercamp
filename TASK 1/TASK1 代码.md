# TASK1 代码

```BLINK
void setup() {
  // put your setup code here, to run once:
pinMode(led_pin,OUTPUT);//设立引脚为输出模式
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(led_pin,HIGH);//点亮LED
  delay(1000);//delay 1000ms
  digitalWrite(led_pin,LOW);
  delay(1000);

}
```

