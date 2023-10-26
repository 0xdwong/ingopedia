# 离散傅里叶变换

## 算法和方法

- [FFT - Vitalik](https://vitalik.ca/general/2019/05/12/fft.html)
- [Reed-Solomon 编码：Vitalik](https://ethresear.ch/t/reed-solomon-erasure-code-recovery-in-n-log-2-n-time-with-ffts/3039)
- [FFT 笔记](https://www.csee.umbc.edu/~phatak/691a/fft-lnotes/fftnotes.pdf)
- [有限域中的快速傅里叶变换 - Pollard](https://www.ams.org/journals/mcom/1971-25-114/S0025-5718-1971-0301966-0/S0025-5718-1971-0301966-0.pdf)
- [数论变换（NTT）：介绍](https://www.nayuki.io/page/number-theoretic-transform-integer-dft)
- [简单地介绍 NTT 1（包括环）](https://cryptographycaffe.sandboxaq.com/posts/ntt-01/)
- [简单地介绍 NTT 2（包括环）](https://cryptographycaffe.sandboxaq.com/posts/ntt-02/)
- [NTT 的高效素数 - Goldilocks](https://cp4space.hatsya.com/2021/09/01/an-efficient-prime-for-number-theoretic-transforms/)
  - [nuFHE 中的 Goldilocks](https://nufhe.readthedocs.io/en/latest/implementation_details.html)
  - [Goldilocks NTT技巧 - Solberg](https://www.ingonyama.com/blog/goldilocks-ntt-trick)
- [椭圆曲线快速傅里叶变换（ECFFT）第一部分：所有有限域上的快速多项式算法：Eli Ben-Sasson等](https://arxiv.org/abs/2107.08473)
  - [Talk - zk study club](https://www.youtube.com/watch?v=kQZvBXLZ8dM)
  - [ECFFT 算法](https://solvable.group/posts/ecfft/)
  - [Rust 实现 - Wboregaud](https://github.com/wborgeaud/ecfft-bn254)
  - [Rust ECFFT BN254 - Wboregeaud](https://solvable.group/posts/ecfft-bn254/)
- [ECFFT-2 Ben-Sasson 等](https://eccc.weizmann.ac.il/report/2022/110/)
- [FFT - Ferror Moreno 论文](https://www.uprm.edu/cise/wp-content/uploads/sites/171/2018/12/ferrermoreno.pdf)
- [Zcash FFT](https://zcash.github.io/halo2/background/polynomials.html)
- [用于多项式乘法的 FFT](https://cse.hkust.edu.hk/mjg_lib/Classes/COMP3711H_Fall16/lectures/FFT_Slides.pdf)
- [快速重心评估教程 - Vitalik](https://hackmd.io/@vbuterin/barycentric_evaluation)
- [重心插值 - Math Oxford](https://people.maths.ox.ac.uk/trefethen/barycentric.pdf)
- [Walsh Hadamard 变换 - Borgeaud](https://solvable.group/posts/walshhadamard-transform/)
- [有限域上的 FFT 介绍](https://t.co/qXTu1Z4OzK)

## 实现

- [论文：BUNTTERFLY：用于数论变换的灵活硬件生成器 - Jason Vranek](https://escholarship.org/content/qt37t8364f/qt37t8364f.pdf)
- [CycloneNTT](https://eprint.iacr.org/2022/1657)
- [NTL：用于 NTT 的库](https://libntl.org)
- [Zprize 2022](https://github.com/z-prize/2022-entries/tree/main/open-division/prize2-ntt)
