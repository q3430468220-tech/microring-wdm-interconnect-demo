# 架构

本期参考 Ayar Labs 公开的微环光 I/O 架构，建立可运行的四波长链路。参照版本固定为 WO2021173732A1（2021 年公开）的架构实施例；不拼接不同代际的商用带宽、波段或能效数字。本期器件参数、接收等效结构、传输负载和误差场景由模型配置定义。


|---|---|---|
| Ayar Labs，TeraPHY Chiplet Optical Input/Output System，WO2021173732A1，2021-09-02 | 网页正文[0033]—[0034]、[0055]—[0062]；94页PDF的第75页Fig.2A/B、第85页Fig.7、第86页Fig.8A已渲染目视核对，对应附图页2/20、12/20、13/20 | 外置多波长供光、Tx/Rx切片、微环与加热调谐、芯片间光连接。Fig.7接收切片描述包括微环探测器；本期“add-drop微环滤波＋独立PD”是功能等效选择，不声称是该商业芯片的内部版图 |
| Ayar Labs，Hot Chips 31公开演示文稿，2019-08-20 | 下载48页PDF并目视核读第20—22页、31页；页码与幻灯片编号一致 | 第20—22页展示片外激光、微环调制与微环探测的WDM组织；第31页展示Ring PD、接收前端、解串与眼图监测。用于交叉核对模块关系，不把其400G接收宏、BER曲线或能效数值当作本期模型结果 |
| Ayar Labs，A 45 nm CMOS-SOI Monolithic Photonics Platform With Bit-Statistics-Based Resonant Microring Thermal Tuning，2016官方资源页 | 只核读网页摘要与作者信息，无固定页码；未获得并逐页核读该论文全文 | 位统计监测、调制眼开度目标与热调谐提供控制思路。本期扫描和反馈算法是自行实现，不把该论文的温控能效或链路性能搬入模型 |
| 前置项目《微环PN调制器设计》第三弹 | 本地性能与核查、技术讲义 | 复用TCMT、电路和单位核查的方法。本期不继续采用前期PN有限元输出数值，因此不把新的频率调谐效率写成前期器件仿真结果 |

原文链接：[专利正文](https://patents.google.com/patent/WO2021173732A1/en)；[专利PDF](https://patentimages.storage.googleapis.com/1a/e6/55/1eb535fea4e138/WO2021173732A1.pdf)；[Hot Chips 2019文稿](https://old.hotchips.org/hc31/HC31_2.9_AyarLabs_20190820_HC_FINAL.pdf)；[Ayar热调谐研究摘要](https://ayarlabs.com/resource/a-45-nm-cmos-soi-monolithic-photonics-platform-with-bit-statistics-based-resonant-microring-thermal-tuning/)。





