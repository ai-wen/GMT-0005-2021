# 《GMT 0005-2021 随机性检测规范》

参考依赖 github.com/Trisia/randomness

# RandomCheckTool.exe 随机数检测工具
支持《GMT 0005-2021 随机性检测规范》的快速 国密随机数检测工具

## 测试环境:
    Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz   2.21 GHz
    耗时：10分钟左右

- [ 1] 单比特频数检测 MonoBitFrequencyTest
- [ 2] 块内频数检测 FrequencyWithinBlockTest
- [ 3] 扑克检测 PokerTest
- [ 4] 重叠子序列检测 OverlappingTemplateMatchingTest
- [ 5] 游程总数检测 RunsTest
- [ 6] 游程分布检测 RunsDistributionTest
- [ 7] 块内最大游程检测 LongestRunOfOnesInABlockTest
- [ 8] 二元推导检测 BinaryDerivativeTest
- [ 9] 自相关检测 AutocorrelationTest
- [10] 矩阵秩检测 MatrixRankTest
- [11] 累加和检测 CumulativeTest
- [12] 近似熵检测 ApproximateEntropyTest
- [13] 线型复杂度检测 LinearComplexityTest
- [14] Maurer通用统计检测 MaurerUniversalTest
- [15] 离散傅里叶检测 DiscreteFourierTransformTest


![测试时常](https://github.com/ai-wen/GMT-0005-2021/blob/main/3.png)
![工具界面](https://github.com/ai-wen/GMT-0005-2021/blob/main/1.png)
![CPU占用](https://github.com/ai-wen/GMT-0005-2021/blob/main/2.png)

# rdgen.exe 随机数生成工具
gen.bat