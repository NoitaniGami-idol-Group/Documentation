## 搭载 Imagination GPU IP 的 RISC-V 产品开源驱动状态



此处我们引入了德州仪器的AM68（BXS-4-64）作为参照，该型号也是现阶段IMG官方开源驱动主要推进型号，另外AXE-1-16M现在可以进行一些相对良好的图形操作但规模较小故不做对照。

Rogue：

| IP型号                                                       | 使用该GPU的RISC-V Soc型号 | 固件是否放出 | 开源驱动可用性 | 是否有开发进度                                               | 备注                       |
| ------------------------------------------------------------ | ------------------------- | ------------ | -------------- | ------------------------------------------------------------ | -------------------------- |
| [BXE-2-32](https://gitlab.freedesktop.org/imagination/mesa/-/commit/289aae12c0480540c0a896b8308c62bd7c4f2b31) | SpacemiT K1/M1            | 是           |                | https://gitlab.freedesktop.org/imagination/linux-firmware/-/issues/2#note_2643442<br /> |                            |
| [BXE-4-32](https://gitlab.freedesktop.org/imagination/mesa/-/commit/a3e1248cea54ba219c928ecfc0945f9db5805f39) | StarFive JH7110           | 是           |                |                                                              |                            |
| [BXM-4-64](https://gitlab.freedesktop.org/imagination/mesa/-/commit/76609e34471aca4bea8f62bf241b6973089c2084) | XuanTie TH1520            | 是           |                | 1：https://gitlab.freedesktop.org/imagination/linux-firmware/-/issues/2#note_2643442 （其中有部分内容涉及）<br />2：https://lore.kernel.org/all/20241014123314.1231517-1-m.wilczynski@samsung.com/ |                            |
| [BXS-4-64](https://gitlab.freedesktop.org/imagination/mesa/-/commit/e47428718337f4e8e1f71c48b5ed646ad12044bb) |                           | 是           |                | Imagination Technologies 官方开发                            | 仅可进行十分基础的图形操作 |

Volcanic：

| IP型号    | 使用该GPU的RISC-V Soc型号 | 固件是否放出 | 开源驱动可用性 | 是否有开发进度 | 备注 |
| --------- | ------------------------- | ------------ | -------------- | -------------- | ---- |
| AXM-8-256 | ESWIN EIC7700/2           | 否           | 不可用         | 无             |      |






> [!NOTE]
>
> 开源驱动可用性：开源驱动功能实现是否可以达到替换闭源驱动。<br />固件是否放出：固件是开源驱动的前置要素，即使有开源驱动也需要来自IMG官方的固件支持。

相关链接直达：

https://gitlab.freedesktop.org/imagination/linux-firmware

https://gitlab.freedesktop.org/imagination/mesa
