## 使用 Imagination GPU IP 的 RISC-V/信创/有可参考价值 产品



**A-Series A系列：**

| 厂商名称 | 产品型号 | IP型号     | GPU频率 | 产品类型   | BVNC Code    | DDK Version  |
| -------- | -------- | ---------- | ------- | ---------- | ------------ | ------------ |
| ESWIN    | EIC7700  | AXM-8-256  | 800Mhz  | RISC-V Soc | 30.3.408.101 | 24.2@6643903 |
| ESWIN    | EIC7702  | AXM-8-256  | 800Mhz  | RISC-V Soc | 30.3.408.101 | 24.2@6643903 |
| Sophgo   | SG2380   | AXT-16-512 |         | RISC-V Soc |              |              |
| Phytium  | X100     | AXT-16-512 |         | 桥片       | 30.3.816.20  | 1.16@6099580 |

**B-Series B系列：**

| 厂商名称          | 产品型号         | IP型号          | GPU频率 | 产品类型   | BVNC Code     | DDK Version  |
| ----------------- | ---------------- | --------------- | ------- | ---------- | ------------- | ------------ |
| SpacemiT          | K1/M1            | BXE-2-32        | 614Mhz  | RISC-V Soc | 36.29.52.182  | 24.2@6603887 |
| StarFive          | JH7110           | BXE-4-32 MC1    |         | RISC-V Soc | 36.50.54.182  | 1.19         |
| Texas Instruments | AM68             | BXS-4-64        |         | ARM Soc    | 36.53.104.796 | 24.2@6643903 |
| T-Head/XuanTie    | TH1520           | BXM-4-64        |         | RISC-V Soc | 36.52.104.182 | 1.17@6210866 |
| Allwinner         | A733             | BXM-4-64        |         | ARM Soc    |               | 24.1         |
| Innosilicon       | Fantasy 1 Type-A | BXT-32-1024     |         | 独立显卡   |               |              |
| Innosilicon       | Fantasy 2        | BXT-32-1024     |         | 独立显卡   | 35.4.1632.23  |              |
| Moore Threads     | MTT-S Series     | BXT-32-1024 MC2 |         | 独立显卡   |               |              |

**C-Series C系列：**

暂无

**D-Series D系列：**

| 厂商名称                  | 产品型号  | IP型号      | GPU频率 | 产品类型 | BVNC Code | DDK Version |
| ------------------------- | --------- | ----------- | ------- | -------- | --------- | ----------- |
| Google                    | Tensor G5 | DXT-48-1536 | 1100Mhz | ARM Soc  |           |             |
| Xiaomi                    | XuanJie   | DXT-72-2304 |         | ARM Soc  |           |             |
| XIANGDIXIAN（已结束营业） |           | DXD-72-2304 |         | 独立显卡 |           |             |





Tips：内容均来自公开官方/非官方资料检索，仅供参考，不做任何可靠性保证



相关信息获取方式：

GPU频率：使用PVRTune获取

BVNC Code：在 lib/firmware 下观察 rgx.fw.xxxxx 后面的数字，或 查看设备的 Vulkan UUID 将其 ASCII 转字符

DDK Version：查看vulkaninfo，或查看系统 dmesg 启动信息

