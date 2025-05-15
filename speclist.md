## 使用 Imagination GPU IP 的 RISC-V/信创/有可参考价值 产品



**A-Series A系列：**

| 厂商名称 | 产品型号 | IP型号     | 系列     | GPU频率    | 产品类型   | BVNC Code    | DDK Version  | 来源/备注                                                    |
| -------- | -------- | ---------- | -------- | ---------- | ---------- | ------------ | ------------ | ------------------------------------------------------------ |
| ESWIN    | EIC7700  | AXM-8-256  | Volcanic | 800Mhz     | RISC-V Soc | 30.3.408.101 | 24.2@6643903 | 自购验证                                                     |
| ESWIN    | EIC7702  | AXM-8-256  | Volcanic | 800Mhz     | RISC-V Soc | 30.3.408.101 | 24.2@6643903 | 自购验证（使用EIC7700判断）                                  |
| Sophgo   | SG2380   | AXT-16-512 | Volcanic |            | RISC-V Soc |              |              | https://milkv.io/chips/sg2380                                |
| Phytium  | X100     | AXT-16-512 | Volcanic | 400/600Mhz | 桥片       | 30.3.816.20  | 1.16@6099580 | 自购验证（GPU频率根据文档可得有两种规格，同时还有不带GPU的版本） |

**B-Series B系列：**

| 厂商名称          | 产品型号         | IP型号          | 系列     | GPU频率  | 产品类型   | BVNC Code     | DDK Version  | 来源/备注                                                    |
| ----------------- | ---------------- | --------------- | -------- | -------- | ---------- | ------------- | ------------ | ------------------------------------------------------------ |
| SpacemiT          | K1/M1            | BXE-2-32 MC1    | Rogue    | 614.4Mhz | RISC-V Soc | 36.29.52.182  | 24.2@6603887 | 自购验证                                                     |
| StarFive          | JH7110           | BXE-4-32 MC1    | Rogue    | 594MHz   | RISC-V Soc | 36.50.54.182  | 1.19@6345021 | 自购验证                                                     |
| Texas Instruments | AM68             | BXS-4-64        | Rogue    | 800Mhz   | ARM Soc    | 36.53.104.796 | 24.2@6643903 | 自购验证                                                     |
| XuanTie           | TH1520           | BXM-4-64        | Rogue    |          | RISC-V Soc | 36.52.104.182 | 1.17@6210866 | 自购验证                                                     |
| Allwinner         | A733             | BXM-4-64 MC1    | Rogue    |          | ARM Soc    |               | 24.1         | https://www.notebookcheck-cn.com/A733.951900.0.html          |
| Innosilicon       | Fantasy 1 Type-A | BXT-32-1024     | Volcanic |          | 独立显卡   | 35.4.1632.23  |              | https://www.design-reuse-china.com/news/202202135            |
| Innosilicon       | Fantasy 2        | BXT-32-1024     | Volcanic |          | 独立显卡   | 35.4.1632.23  |              |                                                              |
| Moore Threads     | MTT-S80          | BXT-32-1024 MC8 | Volcanic | 1800 MHz | 独立显卡   | 35.4.1632.23  | 1.19@6345021 | https://vulkan.gpuinfo.org/displayreport.php?id=36623<br />驱动信息推断为原始基础版本，实际被其进行过大量改动，可能和IMGDDK特性已经有所不同 |
| Moore Threads     | MTT-S70          | BXT-32-1024 MC8 | Volcanic | 1600 MHz | 独立显卡   | 35.4.1632.23  | 1.19@6345021 |                                                              |
| Moore Threads     | MTT-S30          | BXT-32-1024 MC2 | Volcanic | 1300 MHz | 独立显卡   | 35.4.1632.23  | 1.19@6345021 |                                                              |
| Moore Threads     | MTT-S10          | BXT-32-1024 MC2 | Volcanic | 1000 MHz | 独立显卡   | 35.4.1632.23  | 1.19@6345021 |                                                              |
| XIANGDIXIAN       | PanGu A0         | BXT-32-1024     | Volcanic |          | 独立显卡   |               |              |                                                              |
| XIANGDIXIAN       | PanGu B0         | BXT-32-1024     | Volcanic |          | 独立显卡   |               |              | 已经有成品上架（ ERUN-130B-4 ERUN-130B-2），但价格有波动<br />336→496 |

**C-Series C系列：**

暂无

**D-Series D系列：**

| 厂商名称    | 产品型号  | IP型号             | 系列     | GPU频率 | 产品类型 | BVNC Code | DDK Version | 来源/备注                                                    |
| ----------- | --------- | ------------------ | -------- | ------- | -------- | --------- | ----------- | ------------------------------------------------------------ |
| Google      | Tensor G5 | DXT-48-1536-0.5RT2 | Volcanic | 1100Mhz | ARM Soc  |           |             | https://www.androidpolice.com/google-pixel-10-tensor-g5-may-not-deliver-performance-boost/<br />同时根据官方网页显示DXT-48-1536型号为DXT-48-1536-0.5RT2<br />https://www.imaginationtech.com/product/img-dxt-48-1536/ |
| Xiaomi      |           | DXT-72-2304        | Volcanic |         | ARM Soc  |           |             | 本处出处来源微博（内容已被删除出处无法考究），另有酷安来源为：CXT-48-1536<br />但根据IMG产品宣传文档推测为DXT系列 |
| XIANGDIXIAN | FuXi A0   | DXD-72-2304        | Volcanic |         | 独立显卡 |           |             | https://www.imaginationtech.com/products/gpu/img-dxd-gpu/    |


> [!TIP]
> 内容均来自公开官方/非官方资料检索或根据新闻稿推测，仅供参考，不做任何可靠性保证<br />列表中无 BVNC Code 的条目均为推测


> [!CAUTION]
>**请部分KOL（例如：微博ID-定*码）再次阅读上述两句话，不要甩一张图就说实锤某些内容博取流量，如果懒不想打字可以截图多截点避免误导他人**


> [!NOTE]
> 相关信息获取方式：<br />
> GPU频率：cat /sys/kernel/debug/pvr/gpu00/debug_dump | grep freq<br />
> BVNC Code 以及 DDK Version：cat /sys/kernel/debug/pvr/version <br />
> 驱动及固件运行状态 GPU占用率等：cat /sys/kernel/debug/pvr/status <br />
