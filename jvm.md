# JVM体系结构
一、内存管理的划分
1. jvm在内存管理上分为堆、栈两大块，这一部分又可以叫做jre运行时环境,jre运行基于hotspot(native本地环境)，基于jre运行时环境运行的pack200(解压缩包)，native本地环境又包含只读数据段，native本地方法栈，和代码段、数据段。
2. 永久带与元数据区(metaspace)
   永久带是metaspace的前身，
