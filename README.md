# Processsor relevant article collection

处理器相关文集

<br />

# Content

- [关于各种处理器的高性能计算与嵌入式系统相关资料](#article_collection)
- [RISC-V 相关资料](#risk-v_relavant_articles)
- [ARM 处理器相关资料](#arm_relavant_articles)
- [Intel 处理器相关资料](#intel_relevant_articles)
- [各个处理器架构ISA编程指南](#all_kinds_of_processor_isa_ref_manuals)
- [How does an operating system allocate physical memory and map it to the memory page?](#how_does_os_alloc_phys_mem_and_map)
  - [Memory Allocation and Paging Process](#mem_alloc_and_paging_process)
  - [Simplified Example](#how_does_os_alloc_phys_mem_and_map_simplified_example)
- [在 RTL 设计中“RTN”缩写是什么意思](#rtn_in_rtl_design)
- [在 RTL 设计中“gated”是什么意思](#gated_in_rtl_design)
- [在 RTL 设计中“credit”是什么意思](#credit_in_rtl_design)
- [在 RTL 设计中“outstanding”是什么意思](#outstanding_in_rtl_design)
  - [“outstanding”与“pending”有何区别吗？](#diff_from_outstanding_and_pending)

<br />

<a name="article_collection" id="article_collection"></a>
# 关于各种处理器的高性能计算与嵌入式系统相关资料

- [nvdla](https://github.com/nvdla/)
- [AERIS-10: Open Source Pulse Linear Frequency Modulated Phased Array Radar](https://github.com/NawfalMotii79/PLFM_RADAR)
- [数字芯片是怎样设计出来的？](https://www.toutiao.com/article/7169008826468188679/)
- [为什么单颗裸芯被称为die?](https://www.toutiao.com/article/7327482006542484020/)
- [一文读懂APU/BPU/CPU/DPU/EPU/FPU/GPU等处理器](http://www.eefocus.com/mcu-dsp/391017)
- [首个跨 NVIDIA, AMD, Intel, Apple 的 16 代微架构 GPU ISA 研究，硬件不变原语系统性分析与通用 ISA 构想](https://mp.weixin.qq.com/s?__biz=MjM5NDczOTA4NQ==&mid=2447902613&idx=1&sn=e73f53c29947b54a31b61c7f6f84660d)
- [学习笔记丨《图解系统》](https://www.toutiao.com/article/7279780057982206479/)
- [技术上比 ARM 处理器更优雅，却换了七个主人：MIPS 处理器四十年荒诞兴衰录](https://www.toutiao.com/article/7652233988165272106/)
- [48年前的传奇代码重现！微软开源6955行比尔·盖茨联合开发的BASIC解释器，首日狂揽1.5k Star](https://mp.weixin.qq.com/s?__biz=MzA5ODUxOTA5Mg==&mid=2652605541&idx=1&sn=664e8c06fbdef92c1b10c52a8dd6b5d2)
- [多核 CPU 和多个 CPU 有何区别？](https://www.toutiao.com/a6700442139270054408/)
- [CPU、GPU、FPGA、ASIC芯片的对比](https://www.toutiao.com/i6658175328411714061/)
- [移动 SoC 内部组成 (三)：从卷积、SIMD 到 DSP（processing/processor）（上）](https://mp.weixin.qq.com/s?__biz=Mzk2NDQzNzkyOA==&mid=2247484443&idx=1&sn=7dff7799d76e3f482522f1bed93e7483)
- [Camera ISP图像处理揭密（阶段二：IFE）](https://mp.weixin.qq.com/s?__biz=MzUyMzkzNzQwMQ==&mid=2247484230&idx=1&sn=a83ee3e124ca43179f324ce771e5d400)
- [收藏：AI芯片基础知识（2025）](https://mp.weixin.qq.com/s/YoJHG8j9N_xDV3JT7fqFYQ)
- [一颗新芯片，颠覆CPU和GPU](https://www.toutiao.com/article/7431581160754446863/)
- [AI实验室：CPU、GPU、TPU 和 NPU的发展历程和区别](https://zhuanlan.zhihu.com/p/670414115)（其中有对“**脉动**”的介绍：“脉动阵列,有时候也叫做脉动架构, 英文名 ***Systolic Array***”）
- [智图事 | 90%的人都混淆的NPU与GPU！一篇看懂核心差异。拒绝浅层解读，看完直呼通透！](https://mp.weixin.qq.com/s?__biz=MzU3OTYzODUyMQ==&mid=2247484354&idx=1&sn=015f763d91c53a3646f8b895b7749e0a)
- [DSA AI芯片，相对于GPGPU，究竟有多大的能效优势？主要是从哪些方面提高了能效？](https://zhuanlan.zhihu.com/p/457265026)
- [An in-depth look at Google’s first Tensor Processing Unit (TPU)](https://cloud.google.com/blog/products/ai-machine-learning/an-in-depth-look-at-googles-first-tensor-processing-unit-tpu)
- [探索高通骁龙处理器中的Hexagon NPU架构](https://www.toutiao.com/article/7293000269498434089/)
- [NPU开发指南-加速器架构的设计空间探索](https://www.cnblogs.com/wujianming-110117/p/17698409.html)
- [初创芯片企业篇：Tenstorrent的产品与技术](https://mp.weixin.qq.com/s?__biz=MzI0MTQ3NTM0OA==&mid=2247489645&idx=2&sn=534971e4c77d91ede5191f5ec7f63a4b)
- [Tenstorrent Wormhole Analysis – A Scale Out Architecture for Machine Learning That Could Put Nvidia On Their Back Foot](https://semianalysis.com/2021/06/25/tenstorrent-wormhole-analysis-a-scale/)
- [Memory on Tenstorrent](https://clehaxze.tw/gemlog/2025/03-17-memory-on-tenstorrent.gmi)
- [未来芯片或将走向神经拟态计算](https://www.toutiao.com/article/7429655519792480808/)
- [非冯诺依曼新架构：IBM100万忆阻器大规模神经网络加速AI](https://www.toutiao.com/i6576794835460555267)
- [较混合TP-EP策略加速1.4倍！北大联合达摩院提出MoE并行优化框架：基于3D 近内存加速器](https://mp.weixin.qq.com/s?__biz=MjM5ODExNDA2MA==&mid=2449994513&idx=1&sn=02b0796f96095ab59b3017095bfa0383)
- [RISC之父向AI芯片泼冷水：AI推理不需要更强的GPU，需要另一种硬件](https://mp.weixin.qq.com/s?__biz=MzA3NTIyODUzNA==&mid=2649792028&idx=1&sn=0aef833cdb316e0f0a1d335189ef540f)
- [深度解读苹果M1芯片](https://mp.weixin.qq.com/s?__biz=Mzg2NDgzNTQ4MA==&mid=2247656339&idx=2&sn=efa51ff660ccfc909a085c7df423eba5)
- [Apple M1 Max功耗分析与探讨](https://mp.weixin.qq.com/s?__biz=MzUyMTg4NzUwMA==&mid=2247483675&idx=1&sn=5861ba23437b81e97a05863276c72a05)
- [Apple M5处理器P-Core微架构解密](https://mp.weixin.qq.com/s?__biz=MzU3Nzg4NDY4OQ==&mid=2247483809&idx=1&sn=d3311373704b252c6ddcb191ebd7f03f)
- [将Linux移植到M1 Mac真的太难了](https://csdnnews.blog.csdn.net/article/details/115364836)
- [The Qualcomm Snapdragon X Architecture Deep Dive: Getting To Know Oryon and Adreno X1](https://www.anandtech.com/show/21445/qualcomm-snapdragon-x-architecture-deep-dive)
- [Open-source, multi-ISA binary-translation.](https://binary-translation-alliance.org/)
- [一篇详解ARM Cortex-A9处理器相关介绍](https://www.toutiao.com/article/7098955814320587300/)
- [X86，你了解多少？](https://www.toutiao.com/i6946365448938127904/)
- [x86-TSO memory model](https://mp.weixin.qq.com/s?__biz=MzU3Nzg4NDY4OQ==&mid=2247484548&idx=1&sn=abb9b660e9dcc743d0d2773fed9bed17)
- > **TSO（Total Store Order）** 是 x86 架构的内存顺序模型，核心特点是保证所有处理器的写操作（store）在全局内存中按程序顺序可见，但允许读操作（load）与写操作之间乱序执行。 <br/> x86 通过 Store Buffer 和 MESI 协议协同工作：Store 操作先写入 Store Buffer（异步完成），最终按顺序刷新到内存；跨核通信时，MESI 协议确保写操作对所有核最终可见且顺序一致。 <br/> 同核环境下，Store Forwarding 机制让后续 Load 能直接从StoreBuffer读取数据，实现"看起来有序"的效果。TSO 通过强全局 Store 顺序和跨核延迟可见性，兼顾了性能优化与多核内存一致性。
- > **WMO** 就是 **Weak Memory Ordering**，弱内存模型。
- [深入理解MCU启动原理](https://www.toutiao.com/article/7282659068987113999/)
- [一则轶事：对更快的系统调用陷阱的追求](https://www.toutiao.com/i7056937402165674507/)
- [Google深度揭秘TPU：一文看懂原理，以及为何碾压GPU](https://www.toutiao.com/i6419483969682670081/)
- [性能之殇：从冯·诺依曼瓶颈谈起](https://zhuanlan.zhihu.com/p/52721155)
- [面试官问：高并发下，你都怎么选择最优的线程数？](https://www.toutiao.com/a6829183334719947277/)
- [Memory Footprints](https://www.pcmag.com/encyclopedia/term/memory-footprint)
- [彻底搞懂 IO 底层原理](https://www.toutiao.com/i6901537900752585228/)
- [经典重温：AMD 323页PPT介绍IOMMU](https://mp.weixin.qq.com/s?__biz=Mzg5NTAwNDY1Mw==&mid=2247486831&idx=1&sn=76f815ec1c80c5f398c7df4339e06e41)
- [IOMMU功能测试软件设计及实现 (二)](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484389&idx=1&sn=53e3372b92a05f9b075e59faaefb08e0)
- [CPU 伪共享是如何发生的？又该如何避免？](https://www.toutiao.com/article/7268439651449405986/)
- [CPU怎么保证内存访问冲突？一致性？](https://www.toutiao.com/a6748042646326870541/)
- [访问任意数组元素的性能相同？抛开Cache谈性能就是耍流氓](https://www.toutiao.com/a6821051726448034315/)
- [阿里P8说要搞懂volatile 关键字，就靠这 26 张图](https://www.toutiao.com/i6898303659269145102/)
- [linux下C++多线程并发之原子操作与无锁编程](https://www.toutiao.com/i6839967822085358092/)
- [如何利用CAS技术实现无锁队列](https://www.toutiao.com/i6939798423780508174/)
- [并发原理系列二：浅论Lock 与X86 Cache 一致性](https://www.toutiao.com/a6815374276636443148/)
- [解密Linux内核神器：内存屏障的秘密功效与应用方法](https://www.toutiao.com/article/7249661344411173428/)
- [cache coherence和memory consistency](https://mp.weixin.qq.com/s?__biz=MzU3NDA1NDY0Ng==&mid=2247484035&idx=1&sn=2d29cd26f4cf52b97cccb6cf53033341)
- [计算机体系结构15｜Cache Coherence 与 Memory Consistency](https://mp.weixin.qq.com/s?__biz=MzYzOTAyMzU3OA==&mid=2247490954&idx=1&sn=c4b2ebb442db4c1e68e053b1c407c18a)
- [计算机的Cache和Memory访问时Write-back，Write-through及write allocate的区别](https://www.cnblogs.com/guojingdeyuan/p/7626983.html)
- [Understanding write-through, write-around and write-back caching (with Python)](https://shahriar.svbtle.com/Understanding-writethrough-writearound-and-writeback-caching-with-python)
- [深入理解cache对写好代码至关重要](https://www.bilibili.com/read/cv24462455/)
- [cache中的invalidate和clean](https://zhuanlan.zhihu.com/p/515450647)
- [Cache替换策略之tree-PLRU](https://zhuanlan.zhihu.com/p/516582856)
- [TLB: Translation-lookaside buffer](http://www.biscuitos.cn/blog/TLB/)
- [内存是怎么映射到物理地址空间的？内存是连续分布的吗？](https://www.toutiao.com/a6699406470699549195/)
- [彻底搞懂虚拟内存，虚拟地址，虚拟地址空间](https://www.toutiao.com/article/6952760982372385317/)
- [虚拟地址翻译物理地址的流程终于搞懂了~](https://mp.weixin.qq.com/s/Sn6VzXIxmPWlbHu5k2tvaQ)
- [从内核小白到大神——图形驱动基础](https://zhuanlan.zhihu.com/p/555899819)
- [内存系列学习（一）：万字长文带你搞定MMU&TLB&TWU](https://zhuanlan.zhihu.com/p/650956048)
- [malloc 背后的虚拟内存 和 malloc实现原理](https://www.toutiao.com/article/7249649334319448628/)
- [ARMv8 内存系统学习笔记](https://www.toutiao.com/article/7275141440156582452/)
- [从硬件到软件：ARM SMMU全栈技术解析](https://mp.weixin.qq.com/s?__biz=Mzg4NDQ0OTI4Ng==&mid=2247493841&idx=1&sn=1ccee7294601ba644f03145ba4e5a14a)
- [AMD/Intel/Nvidia加速推进Resizable BAR落地 游戏性能提升5-10%](https://www.toutiao.com/i6928553413164663309/)
- [圖解RAM結構與原理，系統記憶體的Channel、Chip與Bank](https://www.techbang.com/posts/18381-from-the-channel-to-address-computer-main-memory-structures-to-understand?fbclid=IwAR0yj1dCTZmi0FpYLDV6BfwEj11iVtLMtIHq1bdep7CtH9V6YzFhliU6tK4)
- [Content-addressable memory (**CAM**)](https://en.wikipedia.org/wiki/Content-addressable_memory)
- [1.3：从芯片说起~自己动手做RAM](https://www.toutiao.com/i7049233754413400579/)
- [1.4：从芯片说起~自己动手做ALU](https://www.toutiao.com/i7050281617067147806/)
- [1.5：从芯片说起~自己设计指令](https://www.toutiao.com/i7051383108465181215/)
- [1.6：从芯片说起~完成你的第一个芯片](https://www.toutiao.com/i7051454906619937294/)
- [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/)
- [现代存储非常快，但是API很糟糕](https://www.toutiao.com/i6899573862590054926/)
- [剖析内存中的程序之秘](https://www.toutiao.com/i6513516605794681347/)
- [NVMe探索](https://www.toutiao.com/a6869199858436145668/)
- [DirectStorage is coming to PC](https://devblogs.microsoft.com/directx/directstorage-is-coming-to-pc/)
- [极致优化 SSD 并行读调度](https://www.toutiao.com/article/7278486952729444918/)
- [Microsoft NUMA Support](https://docs.microsoft.com/en-us/windows/win32/procthread/numa-support)
- [memory: NUMA firmware (bios)的设置及初始化流程](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247485032&idx=1&sn=1675813ad147074c5a4353a22c715ebe)
- [AMD Rome – is it for real? Architecture and initial HPC performance](https://www.dell.com/support/article/zh-cn/sln319015/amd-rome-is-it-for-real-architecture-and-initial-hpc-performance)
- [线程模型Reactor/Proactor的区别](https://www.toutiao.com/i6902028903288717835/)
- [GPFS并行文件系统原理解析](https://www.toutiao.com/i6902319855127609867/)
- [【计算机体系结构连载 08】计算单元为什么还在等：D-Cache、D-TLB 和内存带宽谁在断粮？](https://mp.weixin.qq.com/s?__biz=MzYzOTAyMzU3OA==&mid=2247490238&idx=1&sn=7d5195c18524f18d104b529c0602d119)
- [最全总结！嵌入式系统知识和接口技术](https://www.toutiao.com/i6751313894649643533/)
- [嵌入式开发中那些需要了解的硬件](https://www.toutiao.com/i6729372412858597902/)
- [别再用那些来路不明的驱动了——有人用四年把 171 个芯片驱动做成了同一个标准](https://mp.weixin.qq.com/s?__biz=MzYzNDE5NTAxMA==&mid=2247485713&idx=1&sn=94eb962698f3d8018ff902cfd9d54c3c)（Github：[libdriver](https://github.com/libdriver)）
- [Arm Cortex-M低功耗模式基础](https://www.toutiao.com/a6690433824859357709)
- [干货分享之ESXi CPU调度机制和原理](https://www.toutiao.com/article/7245537321754378786/)
- [CPU硬件辅助虚拟化技术](https://www.toutiao.com/i6768263764224508428/)
- [QEMU KVM学习笔记](https://github.com/yifengyou/learn-kvm)
- [英特尔漏洞门原理解析，保护模式是如何失效的？](https://www.toutiao.com/i6509335383929520648/)
- [走进栈溢出](https://blog.csdn.net/weixin_41185953/article/details/104855669)
- [初探ROP](https://blog.csdn.net/weixin_41185953/article/details/104901494)
- [再探ROP(上)](https://blog.csdn.net/weixin_41185953/article/details/105364797)
- [初探利用angr进行漏洞挖掘（上）](https://www.toutiao.com/a6800737709552828942/)
- [成功率95%以上，Arm TIKTAG推测执行攻击曝光：影响Linux/Chrome](https://www.toutiao.com/article/7381726763715510794/)
- [一个基于汇编的中心重定向框架](https://mp.weixin.qq.com/s?__biz=MzA5NzMwODI0MA==&mid=2647766644&idx=1&sn=134c8defba961c7573595bf7b2161bc6)
- [干货！嵌入式系统“四个地址”，划重点！](https://haokan.baidu.com/v?pd=wisenatural&vid=15776113190438521718)
- [内存地址总线架构及工作原理](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484130&idx=1&sn=8a22aea36033498021b97ef7742cda1c)
- [掌握SPI和I2C总线协议心得，调试起来果然方便多了......](https://www.toutiao.com/a6762391966253613582/)
- [一文读懂STM32芯片总线系统结构](https://www.toutiao.com/article/7254553014319448611/)
- [AMBA_AXI总线详解](https://www.toutiao.com/i7048938792522105380/)
- [ARM ACE 和 ACE-LITE 的含义](https://www.cnblogs.com/linhaostudy/p/18513214)
- [一文读懂GPU 通信之PCIe](https://mp.weixin.qq.com/s?__biz=MzkwOTU5ODU3MQ==&mid=2247484481&idx=1&sn=cc5fdc95152804142ad3d84a5f217e2c)
- [GPU服务器中的PCIe与NUMA性能优化](https://mp.weixin.qq.com/s?__biz=Mzk2NDEyMTM1Mg==&mid=2247488336&idx=1&sn=5e9d17bf69fb300563958414fdc097d5)
- [FPGA漫谈PCI-E：TLP包](https://mp.weixin.qq.com/s?__biz=Mzg2MDgxMTE1Nw==&mid=2247487523&idx=1&sn=3807a50f0579229957419e17ba372021)
- [\[PCIe-DMA\]PCIe DMA机制详解](https://zhuanlan.zhihu.com/p/1943755619849966386)
- [PCIe 错误处理机制及其软件实现 (一)](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484436&idx=1&sn=37dfa9cf6c3fa137c31168c853b6d992)
- [CXL: 内存一致性及软件流程](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484787&idx=1&sn=0572446aa4d6770f50179090e36e658b)
- [PCIe: 多socket/RC下无NTB基于pcie switch组网系统设计 (一)](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484813&idx=1&sn=8b595ddff48472a651b19d90cd86c53a)（RC：Root Complex（RC，根复合体））
- [PCIe atomic 原子操作的优势](https://mp.weixin.qq.com/s?__biz=MzkxNDUxNjI5MQ==&mid=2247486735&idx=1&sn=f804399a4accdcfce8f4275ed2e12d71)
- [基于统一协议GPU芯片高速互联Infinity Fabric的研究 (二)](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484055&idx=1&sn=da20de93261778f582d9299a7fa7b10b)
- [基于NoC的多处理器系统； NoC的基本结构和原理；Router；网络接口；流量控制机制；高速缓存一致性；Network on chip 片上网络； Multi-Processor System](https://www.ewbang.com/community/article/details/998026070.html)
- [NPU 越堆越多，为什么先堵住的是 NoC？](https://mp.weixin.qq.com/s?__biz=Mzg2NTA1NzgxOQ==&mid=2247485747&idx=1&sn=1ec3681f2461dbc087a69a41cb9e50b9)
- [GPMC并口如何实现“小数据-低时延，大数据-高带宽”](https://www.toutiao.com/article/7284641738500178495/)
- [正确理解 Thunderbolt 3 带宽与协议拓扑](https://www.toutiao.com/a6819563018888675854/)
- [Multiplexer \(MUX\)](https://en.wikichip.org/wiki/multiplexer)
- [MUX多路选择器（Multiplexer）](https://zhuanlan.zhihu.com/p/639316069)
- [多路分配器（解复用器）Demultiplexer 的类型分析](https://blog.csdn.net/qq_41657005/article/details/119743210)
- [锁存器Latch和触发器Flip-flop的区别](https://blog.csdn.net/edward_zcl/article/details/89248916)
- [基于忆阻器的存算一体单芯片算力可能高达1POPs](https://www.leiphone.com/news/202008/SHclogrCqLGhkaWb.html)
- [寄存器 SRAM DRAM存储单元区别](https://blog.csdn.net/qq_45683435/article/details/103179091)
- [寄存器，SRAM, DRAM, 熔丝OTP，EPROM，EEPROM简介](https://zhuanlan.zhihu.com/p/463610694)
- [浅析FPGA中的RAM、ROM、CAM、SRAM、DRAM、FLASH](https://zhuanlan.zhihu.com/p/563184725)
- [SRAM，还没死](https://www.toutiao.com/article/7475926315825103399/)
- [一文读懂DDR内存基础知识](https://mp.weixin.qq.com/s?__biz=MzIwNTUxNDgwNg==&mid=2247491063&idx=1&sn=ef190fc63e99ca9895a287a67a70833a)
- [GDDR7大战：谁将成为下一代显卡霸主？](https://www.toutiao.com/article/7379192064849822243/)
- [Xilinx BRAM IP介绍](https://blog.csdn.net/qq_40268672/article/details/124510822)
- [DRAMsim3](https://github.com/umd-memsys/DRAMsim3)（本仓库的 **docs** 目录中有附带的相关文档）
- [AMD 把 HBM 换成了 LPDDR5X，这不是降级，是撤退](https://www.toutiao.com/article/7658565468696904207/)
- [AI时代炙手可热的香饽饽，科技巨头都在抢的 **HBM** 到底是什么？](https://www.toutiao.com/article/7272308855969792531/)
- [NVHBM 登场：把内存控制器搬进显存堆，解锁 AI 硬件新玩法](https://mp.weixin.qq.com/s?__biz=MjM5NTE3Nzk4MQ==&mid=2651251324&idx=1&sn=7cda4c6a416a1247fc4e775369b21203)
- [3D RAM主流/Roadmap方案以及AI部署存储选型策论](https://mp.weixin.qq.com/s?__biz=Mzg2MDE3Nzg0OQ==&mid=2247484637&idx=1&sn=aef191416d7492b3ebecf3ebb87e2428)
- [3D动画揭秘CPU是如何工作的](https://www.toutiao.com/video/7258212224236421647/)
- [3D动画揭秘电脑内存的详细工作原理](https://www.toutiao.com/video/7260069050078724643/)
- [三维动画讲解，芯片是如何制造的，几百亿个晶体管是怎么安装的](https://www.toutiao.com/video/7370252335542764069/)
- [从一辆小车开始你的机器人爱好之旅（上）](https://www.toutiao.com/a6818401220323967500/)
- [ESP32 Xtensa\(HIFI4/HIFI5\) 处理器架构总结](https://blog.csdn.net/tugouxp/article/details/113816681)
- [Intel微处理器Uncore架构简介](https://mp.weixin.qq.com/s?__biz=MzU4MDgyNTAyMw==&mid=2247486682&idx=1&sn=08ebf6afba89b77a821c4cee53a4d382)
- [英特尔®以太网控制器E810介绍：面向5G核心网络](https://www.toutiao.com/a6870508665388925444/)
- [TLS 加速技术：Intel QuickAssist Technology（QAT）解决方案](https://www.toutiao.com/article/7234332484958306872/)
- [光学卷积处理芯片---自动驾驶高性能运算平台的福音？](https://www.toutiao.com/article/7249153468223635979/)
- [PCB 盘中孔是什么？PCB盘中孔工艺流程总结，图文结合，轻松搞定](https://www.toutiao.com/article/7259672991431475768/)
- [花30元，做了个可编程电流表，精度高，功能全！解析一下电路原理](https://www.toutiao.com/article/7278599994838401595/)
- [漫画版电路，电路板都生动了起来](https://www.toutiao.com/article/7291477143354196538/)
- [20种运放典型电路大全，总有一个用得上！](https://www.toutiao.com/article/7287172900066132537/)
- [20个电路能懂5个以上，足以证明你在电子行业混过！](https://www.toutiao.com/w/1781317639211017/)
- [边沿检测电路分析](https://www.toutiao.com/w/1780953700443136/)
- [电路中的GND，它的本质是什么？](https://www.toutiao.com/article/7303840126365729306/)
- [SystemC Tutorial](http://www.asic-world.com/systemc/tutorial.html)
- [基于IP核的FPGA设计方法是什么？](https://www.toutiao.com/article/7288630114198405693/)
- [用Verilog实现流水移位寄存器，请尽量不要使用“阻塞赋值”](https://www.toutiao.com/a6746164678080086531/)
- [Verilog学习笔记HDLBits——Multiplexers](https://blog.csdn.net/bigRr/article/details/125820169)
- [FPGA学习-边沿检测技术，通过边沿采样技术实现上升沿捕获](https://www.toutiao.com/article/7287039457591804471/)
- [扇出型封装结构可靠性试验方法及验证](https://www.toutiao.com/article/7284401507255042600/)
- [芯片验证需要围绕DUT做什么？](https://www.jianshu.com/p/a1b3a471e485)
- [FPGA开发设计中常用XILINX IP CORE的使用与仿真](https://www.toutiao.com/article/7284069288716108307/)
- [模拟IC设计原理图：逻辑电路是如何通过MOS管实现的](https://www.toutiao.com/article/7295652874917528098/)

<br />

<a name="risk-v_relavant_articles" id="risk-v_relavant_articles"></a>
# RISC-V 相关资料

- [RISC-V并不完美？](https://www.toutiao.com/i6903448502840459779/)
- [浅谈RISC-V指令集的基本指令格式和立即数操作](https://www.toutiao.com/i6731643373674824204/?group_id=6731643373674824204)
- [浅谈RISC-V指令集（二）- 整数计算指令](https://www.toutiao.com/i6734682667268178435/)
- [RISC-V中的条件分支指令详解](https://www.toutiao.com/a6736736394133111304/)
- [RISC-V Assembly Programmer's Manual](https://github.com/riscv/riscv-asm-manual/blob/master/riscv-asm.md)（**GOT**: [Global Offset Table](https://en.wikipedia.org/wiki/Global_Offset_Table)）
- [我们一起学RISC-V](https://www.toutiao.com/a6904432642612167172/)
- [我们一起学RISC-V——01-了解处理器和寄存器](https://www.toutiao.com/a6904491425560281604/)
- [我们一起学RISC-V——02-深入了解机器模式下的CSR](https://www.toutiao.com/a6905393723081867780/)
- [我们一起学RISC-V——03-特权指令，Reset和NMI](https://www.toutiao.com/a6905768922071564804/)
- [RISC-V Open Source Supervisor Binary Interface \(OpenSBI\)](https://github.com/riscv-software-src/opensbi)
- [中国芯片产业的一次底层突围，AI芯片创企勇挑RISC-V标准制定大梁](https://mp.weixin.qq.com/s?__biz=MjM5NTM4MTUyMg==&mid=2447909291&idx=1&sn=f613d97cd86a81342dce1605bcb3a1ee)
- [RISC-V Matrix Project](https://github.com/riscv-stc/riscv-matrix-project)

<br />

<a name="arm_relavant_articles" id="arm_relavant_articles"></a>
# ARM 处理器相关资料

- [ARMv8 - ARM](https://en.wikichip.org/wiki/arm/armv8)
- [arm/armv8.1](https://en.wikichip.org/wiki/arm/armv8.1)
- [Memory tagging extension (MTE, MemTag, ARMv8.5-MemTag)](https://en.wikichip.org/wiki/arm/mte)
- [Bringing Armv8.2 Instructions to Android Runtime](https://community.arm.com/developer/tools-software/oss-platforms/b/android-blog/posts/bringing-armv8-2-instructions-to-android-runtime)
- [ARM ISA Intrinsics](https://developer.arm.com/architectures/instruction-sets/intrinsics/)
- [Introduction to SVE](https://developer.arm.com/documentation/102476/0100)
- [Introducing the Scalable Matrix Extension for the Armv9-A Architecture](https://community.arm.com/arm-community-blogs/b/architectures-and-processors-blog/posts/scalable-matrix-extension-armv9-a-architecture)
- [The Scalable Matrix Extension (SME), for Armv9-A -- Arm Architecture Reference Manual Supplement](https://developer.arm.com/documentation/ddi0616/latest/)
- [A64 -- SME Instructions](https://developer.arm.com/documentation/ddi0602/2023-12/SME-Instructions?lang=en)
- [干货：ARM架构代码移植实战分享](https://toutiao.io/posts/ay0cuht/preview)  请使用 **`crc32cb`**、**`crc32ch`**、**`crc32cw`**、**`crc32cx`** 取代x86的 **CRC32** 系列汇编指令，替换方法如表所示，并在编译时添加编译参数 **`-mcpu=generic+crc`**
- [Emulating x86 AES Intrinsics on ARMv8-A](https://blog.michaelbrase.com/2018/05/08/emulating-x86-aes-intrinsics-on-armv8-a/)
- [ARM MTE简介（Memory Tagging Extension）](https://www.toutiao.com/article/7120105520144482820/)
- [ARM’s Scalable Vector Extensions: A Critical Look at SVE2 For Integer Workloads](https://gist.github.com/zingaburga/805669eb891c820bd220418ee3f0d6bd)
- Query SVE Vector Length: [From Arm NEON to SVE](https://learn.arm.com/learning-paths/servers-and-cloud-computing/sve/sve_basics/)
- A good implementation for instruction Cache flush operation from [Dolphin](https://github.com/dolphin-emu/dolphin), contributed by the Mono project. See **`FlushIcache`** and **`FlushIcacheSection`** in [**Arm64Emitter.cpp**](https://github.com/dolphin-emu/dolphin/blob/098e2b3628fbb240ffd6c8124ee8cd729a522798/Source/Core/Common/Arm64Emitter.cpp)

<br />

<a name="intel_relevant_articles" id="intel_relevant_articles"></a>
# Intel 处理器相关资料

- [What is Intel Thread Director?](https://techedged.com/intel-thread-director/)
- [Code Sample: Intel® Deep Learning Boost New Deep Learning Instruction bfloat16 - Intrinsic Functions](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-deep-learning-boost-new-instruction-bfloat16.html)
- [Tuning Guide for Deep Learning with Intel® AVX512 and Intel® Deep Learning Boost on 3rd Generation Intel® Xeon® Scalable Processors](https://www.intel.com/content/www/us/en/developer/articles/guide/deep-learning-with-avx512-and-dl-boost.html)
- [x86指令编码简述(机器码)](https://blog.csdn.net/xiao__1bai/article/details/126584837)（关于 **ModR/M** 可详细参考 vol2 文档，关于 **67H**、**66H** 这些前缀的详细情况，可搜索 vol1 文档。**ModR/M** 的组合顺序从高位到低位依次为：**Mod**，**REG =**，**R/M**；而 **SIB Byte** 的组合顺序从高位到低位依次为：**SS**，**Index**，**Base =**。此外，这里的 **REG =** 表示不包含在寻址操作数中的源/目的寄存器。）
- [X86 CPU的EFLAGS寄存器各个标识位](https://blog.csdn.net/jiary5201314/article/details/8487981)
- [Intel ADX](https://wikimili.com/en/Intel_ADX)
- [Introducing Intel® Advanced Performance Extensions (Intel® APX)](https://www.intel.com/content/www/us/en/developer/articles/technical/advanced-performance-extensions-apx.html)

<br />

<a name="all_kinds_of_processor_isa_ref_manuals" id="all_kinds_of_processor_isa_ref_manuals"></a>
# 各个处理器架构ISA编程指南

- [Intel® 64 and IA-32 Architectures Software Developer Manuals](https://software.intel.com/en-us/articles/intel-sdm)
- [Intel® Threading Building Blocks Developer Guide](https://software.intel.com/en-us/tbb-user-guide)
- [Intel® oneAPI Toolkits](https://software.intel.com/content/www/us/en/develop/tools/oneapi.html)
- [AMD Developer Guides, Manuals & ISA Documents](https://developer.amd.com/resources/developer-guides-manuals/)
- [Intel BMI1](https://www.chessprogramming.org/BMI1)
- [MIPS Open™ Architecture](https://www.mipsopen.com/components-category/mips-open-architecture/)
- [Arm CPU Architecture](https://developer.arm.com/architectures/cpu-architecture)
- [RISC-V Specifications](https://riscv.org/specifications/)
- [Qualcomm® Kryo™ CPU](https://developer.qualcomm.com/sites/default/files/docs/adreno-gpu/snapdragon-game-toolkit/learn_guides.html)
- [Qualcomm® Hexagon™ DSP](https://developer.qualcomm.com/sites/default/files/docs/adreno-gpu/snapdragon-game-toolkit/learn_guides.html)
- [Broadcom BCM7218X](https://www.broadcom.com/products/broadband/set-top-box/bcm7218x)
- [Broadcom BCM49428](https://www.broadcom.com/products/wireless/wireless-lan-infrastructure/bcm49428)
- [arm KEIL 8051 Instruction Set Manual](http://www.keil.com/support/man/docs/is51/)
- [C8051F Series](https://www.silabs.com/support/resources.ct-data-sheets.ct-manuals.page=3)
- [HiFi 2 Audio Engine Instruction Set Architecture Reference Manua](https://wenku.baidu.com/view/3a9e44c3d5bbfd0a7956735c.html)
- [Cadence HiFi 3 DSP User Manual Page](https://www.manualslib.com/manual/1484529/Cadence-Hifi-3-Dsp.html)

<br />

<a name="how_does_os_alloc_phys_mem_and_map" id="how_does_os_alloc_phys_mem_and_map"></a>
# How does an operating system allocate physical memory and map it to the memory page?

An operating system (OS) allocates physical memory and maps it to memory pages using a process called "paging." Here's a simplified explanation of how it works:

<br />

<a name="mem_alloc_and_paging_process" id="mem_alloc_and_paging_process"></a>
## Memory Allocation and Paging Process

1. **Virtual Memory**: 
   - Each process running on an OS is given its own virtual memory space. This is an abstraction that makes it appear as if each process has access to a large, continuous block of memory, independent of other processes.

2. **Page Tables**: 
   - The OS maintains page tables for each process. A page table is a data structure used to map virtual addresses to physical addresses. It contains entries that translate virtual page numbers to physical frame numbers.

3. **Page Size**: 
   - Memory is divided into fixed-size blocks called pages (commonly 4KB each). Correspondingly, physical memory is divided into page frames, which are blocks of the same size as the pages.

4. **Page Allocation**: 
   - When a process needs memory, the OS allocates a certain number of pages. The OS then maps these virtual pages to physical page frames in RAM using the page table.

5. **Page Fault Handling**: 
   - If a process tries to access a page that is not currently mapped to a physical frame (a "page fault"), the OS will handle this by either allocating a new physical frame or bringing the required page from disk (swap space) into physical memory.

6. **Physical Memory Management**: 
   - The OS keeps track of free and used physical memory using data structures like free lists or bitmaps. When a page frame is no longer needed, it is marked as free and can be allocated to other processes.

7. **TLB (Translation Lookaside Buffer)**: 
   - To speed up the translation of virtual addresses to physical addresses, modern CPUs use a special cache called the TLB. The TLB stores recent page table entries to reduce the number of memory accesses needed for address translation.

<br />

<a name="how_does_os_alloc_phys_mem_and_map_simplified_example" id="how_does_os_alloc_phys_mem_and_map_simplified_example"></a>
## Simplified Example

Imagine the OS has a process that needs 12KB of memory. With a page size of 4KB, this would require three pages. The OS allocates three physical page frames from RAM and updates the page table of the process to map the virtual pages to these physical frames. When the process accesses memory, the virtual addresses are translated to physical addresses using the page table entries.

<br />

<a name="rtn_in_rtl_design" id="rtn_in_rtl_design"></a>
# 在 RTL 设计中“RTN”缩写是什么意思

在这篇文章的语境中，**RTN 是 “Return” 的缩写**，表示 **BIF 事务接口的返回/响应通道**。

所以：

> **BIF Transaction Interface (CMD, WRITE, RTN)**

可以理解为 BIF 事务接口包含三类事务或通道：

- **CMD**：Command，命令/请求类事务；
- **WRITE**：写事务；
- **RTN**：Return，返回通道，用于把读请求的结果或响应数据从 BIF 返回给 CDM。

结合文档内容可以印证这一点：

- 在 **BIF Transaction Interface** 表中，`MH_LOAD` 用于读取 Control Stream、Predicate、Indirect Workgroup、Stack State、Context State 等数据；
- 这些 `MH_LOAD` 读取操作的结果，需要通过 **RTN** 返回给 CDM；
- 文档后面也提到 “any locally held **BIF return data** (fetched control stream data) is flushed”，这里的 BIF return data 就是指通过 RTN 通道返回的预取控制流数据。

因此，这里的 **RTN = Return，即 BIF 的读返回/响应通道**。

<br />

<a name="gated_in_rtl_design" id="gated_in_rtl_design"></a>
# 在 RTL 设计中“gated”是什么意思

在 RTL 设计中，**gated 的意思是“被门控 / 被使能 / 受条件控制”**。  
`A is gated by B` 通常表示：**A 是否发生、是否有效，取决于 B；只有 B 有效时，A 才被允许执行或传递。**

你给的例子：

> Link-Stack memory push is gated by splitter link_stack_update_valid

意思是：

> Link-Stack memory 的 push 操作由 splitter 输出的 `link_stack_update_valid` 信号门控。  
> 只有当 `link_stack_update_valid = 1` 时，才会执行 push；  
> 如果 `link_stack_update_valid = 0`，push 被禁止 / 屏蔽，不会写入 Link-Stack memory。

---

### 常见 RTL 写法

可能对应这样的逻辑：

```verilog
// push 使能 = 请求 与 valid 相与
assign link_stack_push_en = link_stack_push_req & link_stack_update_valid;

always @(posedge clk) begin
    if (link_stack_push_en) begin
        mem[ptr] <= push_data;
        ptr      <= ptr + 1;
    end
end
```

或者更直接地写成：

```verilog
always @(posedge clk) begin
    if (link_stack_update_valid) begin
        // push 到 Link-Stack memory
        mem[ptr] <= push_data;
        ptr      <= ptr + 1;
    end
end
```

这里的 `link_stack_update_valid` 就像一道“门”：  
- 它为 1，门打开，push 可以通过；  
- 它为 0，门关闭，push 被挡住。

---

### 和 clock gating 的区别

虽然 “gated” 有时也指 **clock gating（时钟门控）**，例如：

> The clock is gated by an enable signal.

但在你这句话里，`memory push is gated by ... valid` 更常见的是**控制路径/数据路径上的条件使能**，不是直接把时钟关掉。它表示“这个操作要不要做，取决于 valid 信号”。

---

### 总结

- **gated = 被门控、被使能、受条件限制**。
- `push is gated by link_stack_update_valid`  
  = 只有 `link_stack_update_valid` 有效时，push 才会发生。
- 在 RTL 中通常体现为 `if (valid)`、`enable & request` 或 `valid & push` 这类逻辑。

<br />

<a name="credit_in_rtl_design" id="credit_in_rtl_design"></a>
# 在 RTL 设计中“credit”是什么意思

在 RTL 设计中，**credit 通常表示“信用额度 / 令牌 / 可用配额”**，用于**流控（flow control）**。  
它的核心思想是：

> 发送端必须拥有 credit 才能发送数据；  
> 每发送一笔数据，就消耗一个 credit；  
> 接收端处理完数据、释放出缓冲空间后，再把 credit 返还给发送端。

所以 credit 本质上是在描述：**接收端还能再接收多少数据，或者发送端还被允许再发多少数据。**

---

## 1. 典型工作方式

假设接收端有一个深度为 4 的 FIFO：

- 初始时，接收端告诉发送端：我有 4 个 credit。
- 发送端每发一个数据，自己的 credit 计数减 1。
- 当 credit 减到 0 时，发送端必须停止发送。
- 接收端每从 FIFO 中取走一个数据，就返还 1 个 credit。
- 发送端收到返还的 credit 后，计数加 1，于是可以继续发送。

这样就能保证发送端不会把接收端 FIFO 写溢出，同时也不需要在每个周期都用 `ready` 信号做即时反压。

---

## 2. 常见信号命名

在 RTL 中你可能会看到：

```verilog
tx_credit        // 发送端当前可用 credit 数
credit_return    // 接收端返还 credit 的脉冲
credit_update    // credit 更新
credit_count     // credit 计数器
credit_limit     // credit 上限
```

例如：

```verilog
// 发送端 credit 计数
always @(posedge clk or negedge rst_n) begin
    if (!rst_n)
        credit_count <= INIT_CREDIT;
    else if (credit_return)
        credit_count <= credit_count + 1'b1;
    else if (send_valid && send_ready)
        credit_count <= credit_count - 1'b1;
end

// 有 credit 才能发送
assign send_ready = (credit_count != 0);
```

这里 `send_ready` 不是接收端直接给的，而是发送端根据自己剩余的 credit 判断出来的。

---

## 3. 和 valid/ready 握手的区别

| 特性 | valid/ready | credit |
|------|-------------|--------|
| 反压方式 | 每周期即时反压 | 预授权额度 |
| 延迟敏感 | 对组合路径和往返延迟敏感 | 适合长延迟链路 |
| 接收端信息 | 用 ready 表示当前能否接收 | 用 credit 表示还能接收多少 |
| 典型场景 | 短距离、同时钟域、简单流水 | NoC、PCIe、DMA、跨时钟域、长链路 |
| 溢出保护 | 靠 ready 实时控制 | 靠 credit 数量控制 |

credit 机制特别适合**往返延迟很大**的场景。因为如果每发一个数据都要等接收端 `ready` 绕回来，带宽会很低；而 credit 相当于提前把“接收额度”发给发送端，发送端可以连续发送多个数据，不必每拍等待。

---

## 4. 常见应用场景

- **NoC / 片上网络**：virtual channel credit，表示下游 VC 还有多少缓冲空间。
- **PCIe**：接收端广告 header/data credit，发送端跟踪 credit，防止接收端缓冲溢出。
- **DMA / 内存控制器**：用 credit 控制读返回数据或写数据的上限。
- **AXI / 总线桥**：某些实现用 credit 做 outstanding transaction 管理。
- **跨时钟域 FIFO**：用 credit 返还代替每拍同步 ready。

---

## 5. 需要注意的点

1. **credit 不能下溢**：如果 credit 为 0，就不能再减。
2. **credit 不能丢失或重复返还**：否则会导致发送端误判，可能溢出或带宽浪费。
3. **初始 credit 要正确**：通常等于接收端缓冲深度，或双方约定的最大 outstanding 数。
4. **返还时机要明确**：是数据被写入接收端就返还，还是被读出后才返还？这决定了 credit 的实际含义。
5. **跨时钟域要同步**：credit 返还信号跨时钟域时，通常要做同步和边沿检测。

---

## 6. 一句话总结

在 RTL 设计中，**credit = 发送许可证 / 接收端剩余缓冲额度**。  
发送端有 credit 才能发，发一个扣一个；接收端腾出空间后返还 credit。  
它是一种比 `valid/ready` 更适合长延迟链路的流控机制。

<br />

<a name="outstanding_in_rtl_design" id="outstanding_in_rtl_design"></a>
# 在 RTL 设计中“outstanding”是什么意思

在 RTL 设计中，**outstanding** 一般指：

> **已经发出、但还没有收到响应或还没有完成的事务数量。**

也就是“**未完成事务**”或“**悬而未决的请求**”。

---

## 1. 典型含义

比如一个 master 向内存发读请求：

- 发出读地址 `AR`；
- 数据 `R` 还没回来；
- 这个读事务就是 **outstanding**。

发出多个请求后，可能有多个事务同时处于“已发出、未返回”的状态，这些就是 **outstanding transactions**。

系统允许同时存在的最大未完成事务数，通常叫：

- `MAX_OUTSTANDING`
- `outstanding depth`
- `outstanding limit`
- `outstanding capability`

---

## 2. 常见信号/术语

```verilog
outstanding_cnt        // 当前未完成事务计数
outstanding_limit      // 最大允许未完成数
outstanding_full       // 已达到上限
outstanding_transaction
max_outstanding
```

典型逻辑：

```verilog
// 发出请求 +1，收到响应 -1
always @(posedge clk or negedge rst_n) begin
    if (!rst_n)
        outstanding_cnt <= 0;
    else if (req_sent && !rsp_recv)
        outstanding_cnt <= outstanding_cnt + 1'b1;
    else if (!req_sent && rsp_recv)
        outstanding_cnt <= outstanding_cnt - 1'b1;
end

// 达到上限就不能再发
assign can_send = (outstanding_cnt < MAX_OUTSTANDING);
```

---

## 3. 常见场景

- **AXI**：读地址 `AR` 发出后，读数据 `R` 未返回前，该读事务是 outstanding；写地址 `AW`、写数据 `W` 发出后，写响应 `B` 未返回前，该写事务也是 outstanding。
- **NoC / 片上网络**：多个请求包已发出，响应包还没回来。
- **PCIe**：多个非报告事务同时未完成。
- **DMA / 内存控制器**：多个读请求已发往内存，数据还没回来。
- **Cache / MMU**：多个 miss 请求已发出，填充数据还没返回。

---

## 4. 和 credit 的关系

两者经常一起出现，但含义不同：

| 概念 | 含义 |
|------|------|
| **outstanding** | 实际已经发出、但还没完成的事务数 |
| **credit** | 允许发送的“额度/令牌”，是一种流控手段 |

通常：

- 一个 credit 可以对应一个 outstanding 槽位；
- 发送一个请求消耗一个 credit；
- 收到响应后返还 credit；
- `outstanding_cnt` 不能超过 `MAX_OUTSTANDING`，否则会溢出接收端缓冲或导致响应无法匹配。

所以可以理解为：

> **credit 是“许可证”，outstanding 是“已经用掉但还没归还的许可证数量”。**

---

## 5. 为什么需要 outstanding

主要是为了**隐藏延迟、提高吞吐**。

如果每发一个请求都必须等响应回来才能发下一个，带宽会非常低。  
允许一定数量的 outstanding，就可以连续发多个请求，让它们在流水线中并行处理。

但 outstanding 不能无限大，通常受限于：

- 接收端缓冲深度；
- 事务 ID / tag 位宽；
- 重排序资源；
- 响应匹配逻辑；
- 总线协议规定。

---

## 6. 一句话总结

在 RTL 设计中，**outstanding = 已发出但尚未完成的事务数**。  
它衡量“有多少请求还在路上”，常用于 AXI、NoC、PCIe、DMA 等总线或存储接口，和 credit 配合实现流控与延迟隐藏。

<br />

<a name="diff_from_outstanding_and_pending" id="diff_from_outstanding_and_pending"></a>
## “outstanding”与“pending”有何区别吗？

在 RTL 设计中，**outstanding** 和 **pending** 经常被混用，但严格来说有细微区别：

> **outstanding**：已经发出、但还没收到响应/还没完成的事务。  
> **pending**：尚未完成、待处理的事务或事件，范围更广，可能还没发出。

---

## 1. 核心区别

| 维度 | outstanding | pending |
|------|-------------|---------|
| 强调点 | 已发出、在途、等待响应 | 未决、待处理、尚未完成 |
| 是否已发出 | 通常已经发出 | 不一定，可能还在排队、等待资源 |
| 典型协议 | AXI、NoC、PCIe、DMA 等请求-响应接口 | 中断、队列、状态机、缓存 miss 等 |
| 是否计数 | 通常有 outstanding 计数和上限 | 可能只是状态位，也可能有队列深度 |
| 是否需 ID/tag | 通常需要，用于匹配响应 | 不一定，取决于具体场景 |
| 范围 | 较具体 | 较宽泛 |

简单说：

> **outstanding 通常是 pending 的一个子集。**  
> 一个事务可以既是 pending 又是 outstanding；但 pending 不一定 outstanding。

---

## 2. 举例说明

### AXI 总线

- Master 发出读地址 `AR`，但读数据 `R` 还没回来 → 这个读事务是 **outstanding**。
- 如果读请求还在内部队列里，还没发到 AXI 总线上 → 它是 **pending**，但还不是 outstanding。
- 所以：`pending` 可以表示“待发送”，`outstanding` 表示“已发送、待返回”。

### Cache / MMU

- 检测到 cache miss，分配了 MSHR，但请求还没发出去 → **pending miss**。
- 请求已经发到内存，等待数据填充 → **outstanding miss**。
- 两者都可能同时存在，但阶段不同。

### 中断控制器

- 中断已触发，但 CPU 还没处理 → **pending interrupt**。
- 一般不会说 “outstanding interrupt”，因为中断不是请求-响应事务。

### 流水线 / 状态机

- 一个操作等待某个条件满足才能继续 → **pending**。
- 如果它已经作为请求发出，等待对方返回 → **outstanding**。

---

## 3. 信号命名上的区别

常见 RTL 信号：

```verilog
outstanding_cnt        // 当前在途未完成事务数
outstanding_limit      // 最大允许在途数
outstanding_full       // 在途数达到上限

pending_req            // 有待处理的请求
pending_cnt            // 待处理事务数
pending_flag           // 待处理状态标志
```

- `outstanding_cnt` 一般只增不减地跟踪“已发未回”。
- `pending_cnt` 可能跟踪“尚未完成”的所有事务，包括还没发出的。

---

## 4. 总结

- **outstanding**：已发出、未返回，强调“在途”和“未完成响应”，常用于总线、NoC、DMA 等请求-响应协议。
- **pending**：未决、待处理，强调“尚未完成”，范围更广，可能还没发出，也可能已发出未返回。
- 两者有时可以互换，但设计文档中若同时出现，通常：
  - `pending` = 待处理；
  - `outstanding` = 已发出、等待响应。

一句话：

> **pending 是“还没搞定”，outstanding 是“已经发出去了，但还没回来”。**

