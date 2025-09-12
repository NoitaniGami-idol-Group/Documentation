# 参考

| 厂商名称 | 产品型号                        | IP型号         | 频率 | 驱动版本           | fp32-scalar     | fp32-vec4      | fp16-scalar     | fp16-vec4      | fp16-matrix      | fp64-scalar    | fp64-vec4    | int32-scalar   | int32-vec4    | int16-scalar    | int16-vec4     | int64-scalar  | int64-vec4   | int8-dotprod    | int8-matrix      | bf16-dotprod | bf16-matrix | fp8-matrix | bf8-matrix |
| -------- | ------------------------------- | -------------- | ---- | ------------------ | --------------- | -------------- | --------------- | -------------- | ----------------- | -------------- | ------------ | -------------- | ------------- | --------------- | -------------- | ------------- | ------------ | ---------------- | ----------------- | ------------ | ----------- | ---------- | ---------- |
| AMD      | AMD Radeon 550X Series          | RADV POLARIS12 |      |                    | 1542.84 GFLOPS  | 1515.31 GFLOPS |                 |                |                   |                |              | 308.55 GIOPS   | 308.52 GIOPS  |                 |                |               |              |                  |                   |              |             |            |            |
| AMD      | AMD Radeon Pro WX 5100 Graphics | RADV POLARIS10 |      |                    | 3272.23 GFLOPS  | 3082.63 GFLOPS |                 |                |                   |                |              | 703.87 GIOPS   | 702.09 GIOPS  |                 |                |               |              |                  |                   |              |             |            |            |
| Rockchip | RK3588                          | Mali-G610      |      | PanVK mesa-25.1.6  | 80.06 GFLOPS    | 70.73 GFLOPS   | 79.17 GFLOPS    | 76.92 GFLOPS   |                   |                |              | 27.01 GIOPS    | 27.03 GIOPS   | 27.02 GIOPS     | 27.03 GIOPS    | 3.65 GIOPS    | 3.17 GIOPS   |                  |                   |              |             |            |            |
| Rockchip | RK3588 | Mali-G610 | | PanVK mesa-25.3.0 | 85.40 GFLOPS | 71.59 GFLOPS | 85.02 GFLOPS | 150.80 GFLOPS | | | | 27.03 GIOPS | 27.05 GIOPS | 27.03 GIOPS | 53.90 GIOPS | 3.65 GIOPS | 3.26 GIOPS | 429.72 GIOPS | | | | | |
| Intel    | ARC B580                        | BMG G21        |      |                    | 12962.29 GFLOPS | 9148.19 GFLOPS | 26529.99 GFLOPS | 20286.76 GFLOPS | 116427.46 GFLOPS  | 841.08 GFLOPS  | 828.91 GFLOPS| 3481.59 GIOPS | 3237.61 GIOPS | 12615.83 GIOPS  | 13657.78 GIOPS | 674.18 GIOPS  | 573.90 GIOPS | 49103.28 GIOPS   | 232855.67 GIOPS   |              |             |            |            |

# Rogue 系列

| 厂商名称          | 产品型号 | IP型号       | 频率     | DDK Version    | fp32-scalar | fp32-vec4   | fp16-scalar | fp16-vec4   | int32-scalar | int32-vec4 | int16-scalar | int16-vec4 |
| ----------------- | -------- | ------------ | -------- | -------------- | ----------- | ----------- | ----------- | ----------- | ------------ | ---------- | ------------ | ---------- |
| SpacemiT          | K1/M1    | BXE-2-32 MC1 | 614.4Mhz | 23.2@6460340   | 0.67 GFLOPS | 0.76 GFLOPS | 1.31 GFLOPS | 0.88 GFLOPS | 7.64 GIOPS   | 0.67 GIOPS | 7.64 GIOPS   | 0.67 GIOPS |
| SpacemiT          | K1/M1    | BXE-2-32 MC1 | 614.4Mhz | 24.2@6603887   | 2.56 GFLOPS | 0.76 GFLOPS | 2.53 GFLOPS | 0.88 GFLOPS | 7.74 GIOPS   | 0.67 GIOPS | 7.78 GIOPS   | 0.67 GIOPS |
| StarFive          | JH7110   | BXE-4-32 MC1 | 594MHz   | 1.17@6210866   | 1.08 GFLOPS | 2.31 GFLOPS | 5.84 GFLOPS | 1.89 GFLOPS | 4.67 GIOPS   | 1.15 GIOPS | 4.67 GIOPS   | 1.15 GIOPS |
| Texas Instruments | AM68     | BXS-4-64 MC1 | 800Mhz   | 23.1@6404501   | 1.18 GFLOPS | 1.36 GFLOPS | 2.34 GFLOPS | 1.48 GFLOPS | 14.25 GIOPS  | 1.19 GIOPS | 14.49 GIOPS  | 1.17 GIOPS |
| Texas Instruments | AM68     | BXS-4-64 MC1 | 800Mhz   | 23.2@6460340   | 1.18 GFLOPS | 1.36 GFLOPS | 2.34 GFLOPS | 1.48 GFLOPS | 14.30 GIOPS  | 1.19 GIOPS | 14.47 GIOPS  | 1.17 GIOPS |
| Texas Instruments | AM68     | BXS-4-64 MC1 | 800Mhz   | 23.3@6512818   | 1.18 GFLOPS | 1.36 GFLOPS | 2.34 GFLOPS | 1.48 GFLOPS | 14.28 GIOPS  | 1.19 GIOPS | 14.44 GIOPS  | 1.17 GIOPS |
| Texas Instruments | AM68     | BXS-4-64 MC1 | 800Mhz   | 24.1@6554834   | 1.18 GFLOPS | 1.36 GFLOPS | 2.35 GFLOPS | 1.48 GFLOPS | 14.54 GIOPS  | 1.18 GIOPS | 14.61 GIOPS  | 1.17 GIOPS |
| Texas Instruments | AM68     | BXS-4-64 MC1 | 800Mhz   | 24.2@6643903   | 4.61 GFLOPS | 1.36 GFLOPS | 4.67 GFLOPS | 1.48 GFLOPS | 14.55 GIOPS  | 1.18 GIOPS | 14.56 GIOPS  | 1.17 GIOPS |
| XuanTie           | TH1520   | BXM-4-64     |          | 1.17@6210866   | 1.54 GFLOPS | 3.09 GFLOPS | 8.58 GFLOPS | 2.54 GFLOPS | 8.68 GIOPS   | 1.54 GIOPS | 8.68 GIOPS   | 1.54 GIOPS |

# Volcanic 系列

| 厂商名称 | 产品型号           | IP型号     | 频率   | DDK Version   | fp32-scalar   | fp32-vec4     | fp16-scalar   | fp16-vec4     | int32-scalar | int32-vec4  | int16-scalar | int16-vec4  | int64-scalar | int64-vec4  | int8-dotprod |
| -------- | ------------------ | ---------- | ------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------ | ----------- | ------------ | ----------- | ------------ | ----------- | ----------- |
| ESWIN    | EIC7700            | AXM-8-256  | 800Mhz | 1.18@6307965  | 182.81 GFLOPS | 101.30 GFLOPS | 182.53 GFLOPS | 91.69 GFLOPS  | 45.33 GIOPS  | 42.26 GIOPS | 45.15 GIOPS  | 42.39 GIOPS |              |             |             |
| ESWIN    | EIC7700            | AXM-8-256  | 800Mhz | 24.2@6643903  | 182.75 GFLOPS | 182.79 GFLOPS | 182.46 GFLOPS | 149.08 GFLOPS | 45.32 GIOPS  | 42.54 GIOPS | 45.15 GIOPS  | 42.50 GIOPS |              |             |             |
| ESWIN    | EIC7702（任意GPU） | AXM-8-256  | 800Mhz | 24.2@6643903  | 182.72 GFLOPS | 182.74 GFLOPS | 182.43 GFLOPS | 149.24 GFLOPS | 45.37 GIOPS  | 42.57 GIOPS | 45.18 GIOPS  | 42.52 GIOPS |              |             |             |
| Phytium  | X100               | AXT-16-512 | 400Mhz | 1.16@6099580 | 203.07 GFLOPS | 103.80 GFLOPS | 187.35 GFLOPS | 156.68 GFLOPS | 45.12 GIOPS | 42.29 GIOPS | 44.95 GIOPS | 42.25 GIOPS | 15.07 GIOPS | 11.26 GIOPS |  |
| Google | Tensor G5 | DXT-48-1536-0.5RT2 MC1 | 396 MHz（Base） | 24.3@6660496 | 1608.84 GFLOPS | 1633.70 GFLOPS | 1795.98 GFLOPS | 2249.23 GFLOPS | 314.78 GIOPS | 314.64 GIOPS | 314.74 GIOPS | 314.78 GIOPS |  |  | 1677.82 GIOPS |


对比测试使用vkpeak （https://github.com/nihui/vkpeak）
