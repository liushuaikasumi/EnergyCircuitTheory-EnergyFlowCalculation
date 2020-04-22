这个repo包含“综合能源系统分析的统一能路理论（三）：潮流计算”中7节点天然气网络和6节点供热网络的数据与源码。



*代码还在整理中……确认之后会push上来的*



**注意**

#1. 第三方package要求：pandas、numpy、scipy、matplotlib

#2. python版本要求：python 3.x

#3. 给出的源码仅对目标算例负责。举例：7节点气网算例中的压气机扬程保持恒定，故未对其进行傅里叶分解；基值修正部分，标准的做法应对计算得到的流量取绝对值再修正（因为基值是非负的），由于算例中给出的正方向恰好为实际正方向，故源码中未取绝对值。如需扩充、修改算例内容，请自行修改代码。

#4. 天然气网络的算例中，RT用声速（340m/s）的平方代替。这是一个常数，具体取值不影响算法本身。

#5. 为便于阅读与测试，给出的代码包含许多不必要的计算，并非最终的release版本，故运行时间会略微长于原文中给出的运行时间。

#6. 想到再加。

 

如有问题，请在issue中提出，不要私信，谢谢。

have fun ~ ^_-