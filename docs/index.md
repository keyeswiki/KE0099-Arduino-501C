Arduino电子迷基础元件包套件501C

![](media/b39ef7179d7fed5202e83a2a975599cc.jpg)

# 1、说明

这个套件包含我们玩单片机时使用到的几个常用元件，如不同阻值的电阻、不同颜色的LED灯、按键、电位器等。元件包中还包括电源模块，该模块输出DC 3.3V或DC 5V。套件适用于各种单片机和树莓派。我们还会根据这些元件，提供一些基于Arduino开发板的一些学习课程，如LED闪烁实验、按键控灯实验、电位器控灯等，让你对这些电子元件和Arduino开发板有个初步的了解。

# 2、清单


|编码|名称|描述|数量|图片|
|-|-|-|-|-|
|1|LED|F5-红发红-短|3|![](media/1eba37a568de56317c9b9a59738e76ee.png)|
|2|LED|F5-黄发黄-短|3|![](media/c871ecd95ce2be359e1ac2babcfcfaeb.png)|
|3|LED|F5-绿发绿-短|3|![](media/fb6f7a17d1cd0704124dd36063ef06bd.png)|
|4|LED|F5-白发红-短|3|![](media/a94e9e64e20d8c938f70e899e794fc34.jpg)|
|5|电阻|碳膜色环 1/4W 5% 100R 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|6|电阻|碳膜色环 1/4W 5% 1K 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|7|电阻|碳膜色环 1/4W 5% 4.7K 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|8|电阻|碳膜色环 1/4W 5% 10K 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|9|电阻|碳膜色环 1/4W 5% 47K 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|10|电阻|碳膜色环 1/4W 5% 100K 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|11|电阻|碳膜色环 1/4W 5% 1M 编带|30|![](media/f6a8649da4e79abb2f1d15479f073bb5.jpg)|
|12|可调电位器|3386 MU 103（三针直排）|2|![](media/6d6025bc96667b6f44070355f2041f13.jpg)|
|13|按键帽|A24 白帽(12*12*7.3)圆|2|![](media/7f94aded9f45d50e15c2e6281a1bebe3.jpg)|
|14|按键帽|A24 红帽(12*12*7.3)圆|2|![](media/f4522a2209f122d0b094cb5e4755b211.jpg)|
|15|按键帽|A24 蓝帽(12*12*7.3)圆|2|![](media/4be4ce2e80aa9f06e7f02d37c7c5a42a.jpg)|
|16|轻触按键|12*12*7.3MM 插件|6|![](media/4be4ce2e80aa9f06e7f02d37c7c5a42a.jpg)|
|17|模块|面包板专用电源模块 2路5V/3.3V ARDUINO 红色|1|![](media/043582aed0c8ce9aec273d5814320cfa.jpg)|
|18|排针|1*40P 黑色 2.54 针长3.0等边|1|![](media/c1a95d6334a4e20388ddb5a75683c495.png)|
|19|面包线|面包板连接线65根|1|![](media/a741fbc4b471318a5e3ef45f3871c07c.png)|
|20|面包板跳线|140根 14种长度|1|![](media/5f74816773d99c81d1624db265efb6b7.png)|
|21|面包板|830孔 ZY-102（ 未包装）|1|![](media/48648e8442ff9d9c8f57ac99c46fdd04.jpg)|
|22|电阻卡|100*70MM|1|![](media/2e0238b84585943d531ae10d88551d7c.jpg)|


# 3、Arduino IDE和驱动的安装

当我们拿到开发板时，首先我们要安装Arduino IDE和驱动，相关文件我们可以在官网上找到，以下链接是包含各种系统、各种版本的Arduino IDE和驱动任你选择。

<https://www.arduino.cc/en/Main/OldSoftwareReleases#1.5.x>

下面我们介绍下Arduino-1.5.6 版本IDE在Windows系统的安装方法。

下载下来的文件是一个arduino-1.5.6-r2-windows.zip的压缩文件夹，解压出来到硬盘。

双击Arduino-1.5.6 .exe文件

![](media/f5f98943a74471640eefe95e3cccd0ee.png)

然后

![](media/44384a228758644aca47e983417e0079.png)

然后

![](media/704e73c99bcc5eed53d0ab210107b5e1.png)

等待安装完成.点击close，安装完成。

![](media/742a2a6ad75dbc8f8d55cc25c2dc61ca.png)

1.5.6版本安装后的样子。

![](media/4baf5095962e49c1f3ebeb6c2da823f0.png)

接下来是开发板驱动的安装，这次我们安装的是Keyes UNO R3
开发板的驱动，Keyes 2560 R3
开发板安装驱动方法和这个类似，驱动文件可以用同一个文件。

不同的系统，安装驱动的方法也有一些细小的区别，下面我们介绍在WIN 7系统安装驱动的方法。

第一次Keyes UNO R3
开发板连接电脑时，点击计算机--属性--设备管理器，显示如下图。

![](media/ef888e8d5fad0b30e4da671933f8842c.png)

点击 Unknown device 安装驱动，如下图。

![](media/231c0059b83eb424215dbc17edb21afb.png)

进入下图，选择

![](media/1b36a09374634af82cf432f86cb8843f.png)

找到Arduino安装位置的drivers文件夹

![](media/19f226835eac31a0ed12516dcefcfc53.png)

点击“Next”，今天下图选择，开始安装驱动

![](media/501a7a03b5656b8ad60d5e077c58fa51.png)![](media/b9b5f051f1a2b6afdc68eb3b7b2f1c7d.png)

安装驱动完成，出现下图点击Close。

这样驱动就装好了。点击计算机--属性--设备管理器，我们可看见如下图。

![](media/af9806622ecf816c62f7597448a3cc5f.png)

# 4、Arduino IDE的使用方法

Keyes UNO R3
开发板的USB驱动安装成功之后，我们可以在Windows设备管理器中找到相应的串口。

下面示范第一个程序的烧写，串口监视器中显示“Hello World！”。

测试代码为：

int val;

int ledpin=13;

void setup()

{

Serial.begin(9600);

pinMode(ledpin,OUTPUT);

}

void loop()

{

val=Serial.read();

if(val=='R')

{

digitalWrite(ledpin,HIGH);

delay(500);

digitalWrite(ledpin,LOW);

delay(500);

Serial.println("Hello World!");

}

}

我们打开Arduino 的软件，编写一段程序让Keyes UNO R3
开发板接受到我们发的指令就显示“Hello World！”字符串；我们再借用一下Keyes UNO R3 开发板上的 D13
的指示灯，让Keyes UNO R3
开发板接受到指令时指示灯闪烁一下，再显示“Hello World！”。

打开Arduino 的软件，设置板，如下。

![](media/43d9c16b238cfa52845c3a1b553cc630.png)

设置COM端口，如下

![](media/025e24eacb26620c8831c8a3571412f6.png)

点击![](media/eb385c638a1aa0b63971a8871b1bb907.png)编译程序，检查程序是否错误；点击![](media/027da150683195e85b2f0dcdd879e0c1.png)上传程序；Keyes UNO R3 开发板设置OK后右下脚显示如下图，和设备管理器中显示一致。

![](media/add2f4f32678fe555861ae1763488afd.png)

上传成功，输入R，点击发送，Keyes UNO R3 开发板上的 D13
的指示灯闪烁一次，串口监视器中显示 Hello World! 如下图

![](media/fa8f2de13c41710b9dbbfde0833eca74.png)

那么恭喜你，你的第一个程序已经成功了！！！

# 5、实验课程

## 实验一 LED 闪烁实验

实验说明

LED 闪烁实验是比较基础的实验之一，上一个“ Hello World！”实验里已经利用到了Arduino 自带的LED，这次我们利用其他I/O
口和外接直插LED 灯来完成这个实验。

实验器材

开发板\*1

USB线\*1

LED\*1

100Ω 电阻\*1

面包板\*1

面包板连接线若干

接线图

![](media/48b940463b28d7084387604ef440b197.jpeg)

测试代码

int led = 2; //定义数字口2

void setup()

{

  pinMode(led, OUTPUT);     //设置led为输出

}

void loop()

{

  digitalWrite(led, HIGH);   //开启led

  delay(1000); //延迟1秒

  digitalWrite(led, LOW);    //关闭led

  delay(1000);//延迟1秒

}

测试结果

下载完程序就可以看到我们的IO口外接小灯在闪烁了，这样我们的实验现象为LED不停闪烁，间隔大约为1秒。

## 实验二 呼吸灯实验

实验说明

上一课程中我们只是控制LED的亮和灭，那么我们可以怎么控制LED的亮度呢？本课程中我们把LED接到PWM口中，然后通过改变PWM数值，调节LED亮度，使LED逐渐变亮，和逐渐变暗，从而达到呼吸灯的效果。

实验器材

开发板\*1

USB线\*1

LED\*1

100Ω 电阻\*1

面包板\*1

面包板连接线若干

接线图

![](media/aca03c9deeb7b7c3b71138a6aeb5478a.jpeg)

测试代码

int ledPin = 3; // 定义数字口3

void setup()

{

pinMode(ledPin, OUTPUT);// 将ledPin设置为输出

}

void loop()

{

for (int a=0; a\<=255;a++)// 设置使LED逐渐变亮

{

analogWrite(ledPin,a); //
开启led,调节亮度，范围是0-255，在255时led最亮

delay(10); // 延迟0.01S

}

for (int a=255; a\>=0;a--) // 设置使LED逐渐变暗

{

analogWrite(ledPin,a); //
开启led,调节亮度，范围是0-255，在255时led最亮

delay(10); // 延迟0.01秒

}

delay(1000);// 延迟1秒

}

测试结果

下载完程序就可以看到我们的IO口外接小灯显示出呼吸灯的效果，小灯先逐渐变亮，后逐渐变暗，循环交替。

## 实验三 广告灯实验

实验说明

在生活中我们经常会看到一些由各种颜色的led灯组成的广告牌，广告牌上各个位置上癿led灯不断的变话,形成各种效果。本节实验就是利用led灯编程模拟广告灯效果。

实验器材

开发板\*1

USB线\*1

LED\*5

100Ω 电阻\*5

面包板\*1

面包板连接线若干

接线图

![](media/c90ef8d2a9ebd506632b03ce5993656f.jpeg)

测试代码

int BASE = 2 ; //第一个 LED 接的 I/O 口

int NUM = 5; //LED 的总数

void setup()

{

for (int i = BASE; i \< BASE + NUM; i ++)

{

pinMode(i, OUTPUT); //设定数字I/O口为输出

}

}

void loop()

{

for (int i = BASE; i \< BASE + NUM; i ++)

{

digitalWrite(i, HIGH); //设定数字I/O口输出为"高"，即逐渐开灯

delay(200); //延迟

}

for (int i = BASE; i \< BASE + NUM; i ++)

{

digitalWrite(i, LOW); //设定数字I/O口输出为"低"，即逐渐关灯

delay(200); //延迟

}

}

测试结果

下载完程序就可以看到我们的IO口外接小灯先逐渐变亮，然后逐渐变暗，循环交替。

## 实验四 交通灯实验 

实验说明

前面我们已经完成了单个小灯的控制实验，接下来我们就来做一个稍微复杂一点的交通灯实验，其实聪明的朋友们可以看出来这个实验就是将上面单个小灯的实验扩展成3
个颜色的小灯，就可以实现我们模拟交通灯的实验了。

实验器材

红色LED\*1

黄色LED\*1

绿色LED\*1

100Ω电阻\*3

面包板\*1

面包板连接线若干

接线图

![](media/c2b85cc9b9ade450960ae2eafd15dcc8.jpeg)

测试代码

int redled =10; //定义数字10 接口

int yellowled =7; //定义数字7 接口

int greenled =4; //定义数字4 接口

void setup()

{

pinMode(redled, OUTPUT);//定义红色小灯接口为输出接口

pinMode(yellowled, OUTPUT); //定义黄色小灯接口为输出接口

pinMode(greenled, OUTPUT); //定义绿色小灯接口为输出接口

}

void loop()

{

digitalWrite(greenled, HIGH);////点亮 绿灯

delay(5000);//延时5秒

digitalWrite(greenled, LOW); //熄灭 绿灯

for(int i=0;i\<3;i++)//闪烁交替三次，黄灯闪烁效果

{

delay(500);//延时0.5 秒

digitalWrite(yellowled, HIGH);//点亮 黄灯

delay(500);//延时0.5 秒

digitalWrite(yellowled, LOW);//熄灭 黄灯

}

delay(500);//延时0.5 秒

digitalWrite(redled, HIGH);//点亮 红灯

delay(5000);//延时5 秒

digitalWrite(redled, LOW);//熄灭 红灯

}

测试结果

按照接线图接好线，上传完程序，上电后，我们就可以看到我们自己设计控制的交通灯了。实验效果为绿灯亮5秒，绿灯熄灭，黄灯循环闪烁3次，红灯亮5秒，依次循环。

## 实验五 按键控制LED实验

实验说明

I/O 口的意思即为INPUT 接口和OUTPUT
接口，到目前为止我们设计的小灯实验都还只是应用到Arduino 的I/O
口的输出功能，这个实验我们来尝试一下使用Arduino的I/O
口的输入功能即为读取外接设备的输出值，我们用一个按键和一个LED
小灯完成一个输入输出结合使用的实验，让大家能简单了解I/O 的作用。

实验器材

开发板 \*1

USB线\*1

LED\*1

轻触按键\*1

100Ω 电阻\*1

10KΩ 电阻\*1

面包板\*1

面包板连接线若干

接线图

![](media/0f125bf1f28ad6a6aadb71d26d510975.jpeg)

测试代码

int ledPin = 11; //定义数字口11

int inputPin = 3; //定义数字口3

void setup()

{

pinMode(ledPin, OUTPUT); //将ledPin设置为输出

pinMode(inputPin, INPUT); //将inputPin设置为输入

}

void loop()

{

int val = digitalRead(inputPin);

//设置数字变量val，读取到数字口3的数值，并赋值给 val

if (val == LOW) //当val为低电平时，LED变暗

{

digitalWrite(ledPin, LOW); // LED变暗

}

else

{

digitalWrite(ledPin, HIGH); // LED亮起

}

}

测试结果

下载完程序，上电后，当按键按下时小灯亮起，否则小灯不亮。

## 实验六 抢答器实验

实验说明

完成上面的实验以后相信已经有很多朋友可以独立完成这个实验了，我们可以将上面的按键控制小灯的实验扩展成4个按键对应3
个小灯，占用7个数字I/O
接口。本实验中我们利用4个按键控制3个LED灯，从而达到抢答器的效果。

实验器材

开发板\*1

USB线\*1

RGB灯\*1

轻触按键\*4

10KΩ 电阻\*4

100Ω 电阻\*3

面包板\*1

面包板连接线若干

杜邦线若干

接线图

![](media/9ee5e51dbd39e787f05dfcb842b9a188.jpeg)

测试代码

int redled=9;

int yellowled=10;

int greenled=11;

int redpin=5;

int yellowpin=4;

int greenpin=3;

int restpin=2;

int red;

int yellow;

int green;

void setup()

{

pinMode(redled,OUTPUT);

pinMode(yellowled,OUTPUT);

pinMode(greenled,OUTPUT);

pinMode(redpin,INPUT);

pinMode(yellowpin,INPUT);

pinMode(greenpin,INPUT);

}

void loop()

{

red=digitalRead(redpin);

yellow=digitalRead(yellowpin);

green=digitalRead(greenpin);

if(red==LOW)RED_YES();

if(yellow==LOW)YELLOW_YES();

if(green==LOW)GREEN_YES();

}

void RED_YES()

{

while(digitalRead(restpin)==1)

{

digitalWrite(redled, HIGH);

digitalWrite(yellowled, LOW);

digitalWrite(greenled, LOW);

}

clear_led();

}

void YELLOW_YES()

{

while(digitalRead(restpin)==1)

{

digitalWrite(redled, LOW);

digitalWrite(yellowled, HIGH);

digitalWrite(greenled, LOW);

}

clear_led();

}

void GREEN_YES()

{

while(digitalRead(restpin)==1)

{

digitalWrite(redled, LOW);

digitalWrite(yellowled, LOW);

digitalWrite(greenled, HIGH);

}

clear_led();

}

void clear_led()

{

digitalWrite(redled, LOW);

digitalWrite(yellowled, LOW);

digitalWrite(greenled, LOW);

}

测试结果

按照接线图接线，上传完程序，上电后，一个简单的抢答器就做好了，我们根据亮起不同的LED灯，判断谁抢答成功。在复位后，三个LED灯关闭。

## 实验七 电位器调控灯光亮度实验

实验说明

在第二课程中我们直接通过PWM口控制灯的亮度，从而达到呼吸灯的效果。在这课程中我们通过一个电位器，利用电位器调节PWM值，从而控制灯的亮度。

实验器材

开发板\*1

USB线\*1

LED\*1

220Ω 电阻\*1

可调电位器\*1

面包板\*1

面包板连接线若干

接线图

![](media/0da158c100d6ad0a97f1fe19dc983093.jpeg)

测试代码

int ledpin=11;//定义数字接口11（PWM 输出）

void setup()

{

pinMode(ledpin,OUTPUT);//定义数字接口11 为输出

Serial.begin(9600);//设置波特率为9600

}

void loop()

{

int val=analogRead(0);//读取模拟口A0口的值

val = map(val, 0, 1023, 0, 255);//从0-1023映射到0-255

Serial.println(val);//显示val 变量

analogWrite(ledpin,val);// 打开LED 并设置亮度

delay(100);//延时0.1 秒

}

测试结果

下载完程序后。我们可以通过旋转可调电位器控制小灯的亮度，打开串口监视器，设置波特率为9600，就可看到调节LED亮度的PWM值。

# 6、 相关资料链接

<https://pan.baidu.com/s/1qfxCklOiClO1ygwcNi1-oA>

提取码：w2dz




