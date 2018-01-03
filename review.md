# review
1. 完整计算机系统由**配套的硬件设备**和**软件系统**构成
2. 浮点加减法，左右规格。右规格：尾数（算术）右移，阶码+1.左：尾数左移，阶码-1.左：为了规格化。右规：防溢出
规格化：小数点后面的那一位是有效位。（正数是1，负数是0)
3. SRAM电位（触发器），DRAM电容（电荷）
4. Cache与CPU传送以**字/字节**为单位，Cache与主存传送以**（数据）**块为单位
5. 提高加法器运算速度：提高进位信号的传播时间，先行进位：低位的进位信号可以直接向高位传播
6. 指令系统满足：完备性，有效性，规整性，兼容性四个要求，并具有数据处理，数据存储，数据传送，程序控制四大类指令
1. 破坏性读出，动态存储，断电后信息丢失
1. 浮点数由符号位S,阶码E，位数M组成，E的值等于指数的真值e加上一个固定的偏移bias组成。
1. 流水线结构冲突，通常采用资源重复和过程细分
1. 通过重新组织代码顺序消除暂停的技术成为指令调度。
1. MTTR平均修复时间 MTTF(mean time to failure)平均无故障时间
1. RAID01 和RAID10的区别是先条带再镜像，还是先镜像再条带