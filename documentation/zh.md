<!-- ELUCENIA technical documentation · escala-de-ashworth-modificada · zh · no clinical/professional/rights approval -->

# 改良 Ashworth 量表

[条件、来源与许可](https://elucenia.org/zh/tools/escala-de-ashworth-modificada)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 被动运动的阻力（约 1 秒内完成）

`grau`

- `0` — 0 – 肌张力无增加
- `1` — 1 – 轻度增加：出现卡顿后释放，或运动范围末端轻微阻力
- `2` — 2 – 大部分运动范围内阻力明显增加，但患部仍容易移动
- `3` — 3 – 明显增加：被动运动困难
- `4` — 4 – 屈曲或伸展位僵硬
- `1p` — 1+ – 轻度增加：卡顿后在不足半程的运动范围内有轻微阻力

## 方法版本

改良Ashworth/Bohannon–Smith 1987：0/1/1+/2/3/4；特定1+级

## 已记录的公式

患者放松并仰卧时，在约1秒内被动活动该肢段至全范围，选择相应阻力等级。Bohannon和Smith在原Ashworth量表中增加1+级。

## 限制与适用人群

该量表对被动运动时的阻力进行临床分级，与肌力不同。原始可靠性研究检查了颅内损伤患者的肘屈肌。不能将该研究中的表现自动推广到所有关节或神经系统疾病。

## 参考文献

- [Bohannon RW, Smith MB. Interrater reliability of a modified Ashworth scale of muscle spasticity. Phys Ther, 1987.](https://doi.org/10.1093/ptj/67.2.206)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

肌张力无增加


### 2

在不足一半的活动范围内肌张力轻度增加


### 3

肌张力显著增加：被动活动困难

