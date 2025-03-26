## 搭载 Imagination GPU IP 的 RISC-V 产品开源驱动状态



此处我们引入了德州仪器的AM68（BXS-4-64）作为参照，该型号也是现阶段IMG官方开源驱动主要推进型号。

Rogue：

| IP型号                                                       | 使用该GPU的RISC-V Soc型号 | 固件是否放出 | 开源驱动可用性 | 备注                                           |
| ------------------------------------------------------------ | ------------------------- | ------------ | -------------- | ---------------------------------------------- |
| [BXE-2-32](https://gitlab.freedesktop.org/imagination/mesa/-/commit/289aae12c0480540c0a896b8308c62bd7c4f2b31) | SpacemiT K1/M1            | 是           |                |                                                |
| [BXE-4-32](https://gitlab.freedesktop.org/imagination/mesa/-/commit/a3e1248cea54ba219c928ecfc0945f9db5805f39) | StarFive JH7110           | 是           |                |                                                |
| [BXM-4-64](https://gitlab.freedesktop.org/imagination/mesa/-/commit/76609e34471aca4bea8f62bf241b6973089c2084) | XuanTie TH1520            | 是           |                |                                                |
| [BXS-4-64](https://gitlab.freedesktop.org/imagination/mesa/-/commit/e47428718337f4e8e1f71c48b5ed646ad12044bb) |                           | 是           |                | 仅可进行十分基础的图形操作，不具备桌面系统可用 |

Volcanic：

| IP型号    | 使用该GPU的RISC-V Soc型号 | 固件是否放出 | 开源驱动可用性 | 备注 |
| --------- | ------------------------- | ------------ | -------------- | ---- |
| AXM-8-256 | ESWIN EIC7700/2           | 否           |                |      |






> [!NOTE]
>
> 开源驱动可用性：开源驱动功能实现是否可以达到替换闭源驱动。<br />固件是否放出：固件是开源驱动的前置要素，即使有开源驱动也需要来自IMG官方的固件支持。
