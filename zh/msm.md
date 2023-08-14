# 多标量乘法

## 算法和方法

- [使用蒙哥马利技巧的椭圆曲线上快速多标量乘法方法](https://link.springer.com/chapter/10.1007/3-540-36400-5_41)
- [更快的批量伪造识别](https://eprint.iacr.org/2012/549) 查看第4节以了解 MSM、桶方法
- [Pippenger 的指数算法 - Bernstein](https://cr.yp.to/papers/pippenger.pdf)
- [高效的多指数算法](https://github.com/wborgeaud/python-pippenger/blob/master/pippenger.pdf)
  - [Python 实现](https://github.com/wborgeaud/python-pippenger)
- [多标量乘法：现状与 Gus Gutoski 的新想法](https://www.youtube.com/watch?v=Bl5mQA7UL2I)
- [改进的快速指数运算 - Bodo Moller](https://www.bmoeller.de/pdf/fastexp-icisc2002.pdf)
- [带预计算的快速指数运算 - Brickell Gordon 等](https://www.dmgordon.org/papers/fast.pdf)
- [Matter labs - 算法](https://github.com/matter-labs/eip1962/blob/master/documentation/Algorithms_for_EIP1962.pdf)
- [Ryah Henry - 论文](https://cacr.uwaterloo.ca/techreports/2010/cacr2010-26.pdf)
- [高效的多指数算法：桶方法 - Bootle](https://jbootle.github.io/Misc/pippenger.pdf)

## 实现
<!-- markdown-link-check-disable -->
- [pipezk](https://www.microsoft.com/en-us/research/publication/pipezk-accelerating-zero-knowledge-proof-with-a-pipelined-architecture/)
- [使用 FPGA 的 MSM - Connor Masterson 论文](https://github.com/connormas/MultiScalarMultiplication/blob/main/ConnorMastersonThesisV2.pdf)
- [PipeMSM](https://eprint.iacr.org/2022/999)
- [EdMSM](https://ia.cr/2022/1400)
- [CycloneMSM](https://eprint.iacr.org/2022/1396)
- [Cuzk](https://eprint.iacr.org/2022/1321)
- [Zprize MSM 实现](https://github.com/z-prize/2022-entries/tree/main/open-division/prize1-msm)
