# b4x20221012
B4X實驗: Java串口通信/標準串行端口-JSerialComm,包裝jSerialComm-2.9.0.jar成一個程式庫B4X LIB, RxTx 和（已棄用）Java Communications API 的替代品(B4J/JavaObject/inline Java)

B4X實驗: Java串口通信/標準串行端口-JSerialComm,包裝jSerialComm-2.9.0.jar成一個程式庫B4X LIB, RxTx 和（已棄用）Java Communications API 的替代品(B4J/JavaObject/inline Java)
參考資料:
官網
https://fazecast.github.io/jSerialComm/
API DOC
https://fazecast.github.io/jSerialComm/javadoc/com/fazecast/jSerialComm/package-summary.html
JSerialComm範例解說
https://www.xanthium.in/cross-platform-serial-port-programming-tutorial-java-jdk-arduino-embedded-system-tutorial

0.B4X內建的jSerial.????

1.第一次嘗試 完整包裝一個外部jar庫,成為B4X的程式庫 javaobject
jSerialComm-2.9.0.jar

2.此庫可用於旨在在以下平台上使用的任何 Java 項目：

Windows 7 及更高版本（32 位、64 位和 ARM）
Mac OS X Tiger (10.4) 及更高版本（32/64 位 Intel 和 Apple Silicon）
所有 Linux 發行版（32/64 位 x86、ARM 和 PowerPC）
Solaris 10 及更高版本（32/64 位 x86 和 SPARC）
FreeBSD（32/64 位 x86 和 ARM64）
OpenBSD（32/64 位 x86）
ARM/Intel/AMD Mobile Linux 衍生產品（例如 RaspberryPi、Beaglebone 等）
Android 4.1 (Jelly Bean) 及更高版本


3.程式演示


4.包裝的技巧 /使用的LIB等

a.先用inline Java 把想要包的,在那邊實現函數,由B4X那邊呼叫看,是否有問題  ....第一個按鈕

b.在main那邊寫.使用javaobject相關函數 實現....第二個按鈕

c.熟練之後,改成B4J class module , ....第三個按鈕

5.還有一些功能??等之後再說吧!!!



