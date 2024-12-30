| 厂商名称 | 产品型号 | IP型号   | DDK Version  | fp32-scalar | fp32-vec4 | fp16-scalar | fp16-vec4 | fp16-matrix |      |      |      |      |      |      |
| -------- | -------- | -------- | ------------ | ----------- | --------- | ----------- | --------- | ----------- | ---- | ---- | ---- | ---- | ---- | ---- |
| SpacemiT | K1/M1    | BXE-2-32 | 23.2@6460340 |             |           |             |           |             |      |      |      |      |      |      |

root@k1:~/vkpeak/build# ./vkpeak 0
device       = PowerVR B-Series BXE-2-32

fp32-scalar  = 0.67 GFLOPS
fp32-vec4    = 0.76 GFLOPS

fp16-scalar  = 1.31 GFLOPS
fp16-vec4    = 0.88 GFLOPS
fp16-matrix  = 0.00 GFLOPS

fp64-scalar  = 0.00 GFLOPS
fp64-vec4    = 0.00 GFLOPS

int32-scalar = 7.64 GIOPS
int32-vec4   = 0.67 GIOPS

int16-scalar = 7.64 GIOPS
int16-vec4   = 0.67 GIOPS