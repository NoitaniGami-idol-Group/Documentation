主流GPU测试



AMD：

| 厂商名称 | 产品型号                        | IP型号/微架构 | 频率 | 驱动版本 | fp32-scalar     | fp32-vec4       | fp16-scalar     | fp16-vec4       | fp16-matrix     | fp64-scalar   | fp64-vec4     | int32-scalar  | int32-vec4    | int16-scalar   | int16-vec4     | int64-scalar  | int64-vec4    | int8-dotprod   | int8-matrix    |
| -------- | ------------------------------- | ------------- | ---- | -------- | --------------- | --------------- | --------------- | --------------- | --------------- | ------------- | ------------- | ------------- | ------------- | -------------- | -------------- | ------------- | ------------- | -------------- | -------------- |
| AMD      | AMD Radeon Pro WX 5100 Graphics | GCN 4.0       |      |          | 3272.23 GFLOPS  | 3082.63 GFLOPS  |                 |                 |                 |               |               | 703.87 GIOPS  | 702.09 GIOPS  |                |                |               |               |                |                |
| AMD      | AMD Radeon 550X Series          | GCN 4.0       |      |          | 1542.84 GFLOPS  | 1515.31 GFLOPS  |                 |                 |                 |               |               | 308.55 GIOPS  | 308.52 GIOPS  |                |                |               |               |                |                |
| AMD      | AMD Radeon Pro Vega 20          | GCN 5.1       |      |          | 3265.23 GFLOPS  | 3248.00 GFLOPS  | 6468.45 GFLOPS  | 6485.45 GFLOPS  |                 |               |               | 650.17 GIOPS  | 650.32 GIOPS  | 650.93 GIOPS   | 5788.28 GIOPS  |               |               | 1115.17 GIOPS  |                |
| AMD      | AMD Radeon W7800 Graphics       | RDNA 3        |      |          | 31808.54 GFLOPS | 22111.20 GFLOPS | 30548.27 GFLOPS | 39561.60 GFLOPS | 94644.69 GFLOPS | 819.23 GFLOPS | 814.84 GFLOPS | 5184.98 GIOPS | 5032.47 GIOPS | 26768.47 GIOPS | 40661.69 GIOPS | 1703.22 GIOPS | 1397.05 GIOPS | 85744.04 GIOPS | 91868.69 GIOPS |

Intel：

| 厂商名称 | 产品型号                  | IP型号/微架构 | 频率 | 驱动版本 | fp32-scalar     | fp32-vec4      | fp16-scalar     | fp16-vec4       | fp16-matrix      | fp64-scalar   | fp64-vec4     | int32-scalar  | int32-vec4    | int16-scalar   | int16-vec4     | int64-scalar | int64-vec4   | int8-dotprod   | int8-matrix     |
| -------- | ------------------------- | ------------- | ---- | -------- | --------------- | -------------- | --------------- | --------------- | ---------------- | ------------- | ------------- | ------------- | ------------- | -------------- | -------------- | ------------ | ------------ | -------------- | --------------- |
| Intel    | Intel(R) UHD Graphics 630 | Gen9.5        |      |          | 432.91 GFLOPS   | 436.94 GFLOPS  | 829.50 GFLOPS   | 870.71 GFLOPS   |                  |               |               | 144.49 GIOPS  | 145.86 GIOPS  | 143.77 GIOPS   | 351.43 GIOPS   |              |              | 65.80 GIOPS    |                 |
| Intel    | ARC B580                  | Xe-HPG        |      |          | 12962.29 GFLOPS | 9148.19 GFLOPS | 26529.99 GFLOPS | 20286.76 GFLOPS | 116427.46 GFLOPS | 841.08 GFLOPS | 828.91 GFLOPS | 3481.59 GIOPS | 3237.61 GIOPS | 12615.83 GIOPS | 13657.78 GIOPS | 674.18 GIOPS | 573.90 GIOPS | 49103.28 GIOPS | 232855.67 GIOPS |

NVIDIA:

| 厂商名称 | 产品型号 | IP型号/微架构 | 频率 | 驱动版本 | fp32-scalar | fp32-vec4 | fp16-scalar | fp16-vec4 | fp16-matrix | fp64-scalar | fp64-vec4 | int32-scalar | int32-vec4 | int16-scalar | int16-vec4 | int64-scalar | int64-vec4 | int8-dotprod | int8-matrix |
| -------- | -------- | ------------- | ---- | -------- | ----------- | --------- | ----------- | --------- | ----------- | ----------- | --------- | ------------ | ---------- | ------------ | ---------- | ------------ | ---------- | ------------ | ----------- |
|          |          |               |      |          |             |           |             |           |             |             |           |              |            |              |            |              |            |              |             |
|          |          |               |      |          |             |           |             |           |             |             |           |              |            |              |            |              |            |              |             |

其他：

| 厂商名称 | 产品型号 | IP型号/微架构 | 频率 | 驱动版本          | fp32-scalar  | fp32-vec4    | fp16-scalar  | fp16-vec4     | fp16-matrix | fp64-scalar | fp64-vec4 | int32-scalar | int32-vec4  | int16-scalar | int16-vec4  | int64-scalar | int64-vec4 | int8-dotprod | int8-matrix |
| -------- | -------- | ------------- | ---- | ----------------- | ------------ | ------------ | ------------ | ------------- | ----------- | ----------- | --------- | ------------ | ----------- | ------------ | ----------- | ------------ | ---------- | ------------ | ----------- |
| Rockchip | RK3588   | Mali-G610     |      | PanVK mesa-25.1.6 | 80.06 GFLOPS | 70.73 GFLOPS | 79.17 GFLOPS | 76.92 GFLOPS  |             |             |           | 27.01 GIOPS  | 27.03 GIOPS | 27.02 GIOPS  | 27.03 GIOPS | 3.65 GIOPS   | 3.17 GIOPS |              |             |
| Rockchip | RK3588   | Mali-G610     |      | PanVK mesa-25.3.0 | 85.40 GFLOPS | 71.59 GFLOPS | 85.02 GFLOPS | 150.80 GFLOPS |             |             |           | 27.03 GIOPS  | 27.05 GIOPS | 27.03 GIOPS  | 53.90 GIOPS | 3.65 GIOPS   | 3.26 GIOPS | 429.72 GIOPS |             |
|          |          |               |      |                   |              |              |              |               |             |             |           |              |             |              |             |              |            |              |             |