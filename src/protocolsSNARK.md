# SNARK Protocols --- UNDER CONSTRUCTION 

|Protocols|Paper|Implenetation |Resources |
|:---:|---|:---:|:---:|
|Pinocchio - 2013|[ →📝 ](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6547113)|
|TinyRAM - 2013|[ →📝](https://eprint.iacr.org/2013/507.pdf) 
|vnTinyRAM - 2014|[ →📝](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-ben-sasson.pdf)|[Mike Hearn](https://blog.plan99.net/vntinyram-7b9d5b299097) 
|Geppetto - 2015|[ →📝](https://ieeexplore.ieee.org/document/7163030?denied=)|
|Buffet - 2015|[ →📝](https://www.ndss-symposium.org/ndss2015/ndss-2015-programme/efficient-ram-and-control-flow-verifiable-outsourced-computation/)|
|Groth -2016|[ →📝](https://eprint.iacr.org/2016/260.pdf)|ConsenSys-gnark[[1]](https://github.com/ConsenSys/gnark)arkworks-rs[[2]](https://github.com/arkworks-rs/groth16)|Groth16 Malleability - Geometry[[1]](https://geometry.xyz/notebook/groth16-malleability) Proof of forgery[[2]](https://medium.com/ppio/how-to-generate-a-groth16-proof-for-forgery-9f857b0dcafd) Groth16 aggregation proposal[[3]](https://docs.zkproof.org/pages/standards/accepted-workshop4/proposal-aggregation.pdf) Groth - Talk[[4]](https://www.youtube.com/watch?v=OseAdq0CoOY) Deep into bellman library - Star Li[[5]](https://trapdoortech.medium.com/zkp-deep-into-bellman-library-9b1bf52cb1a6) Lookups for groth16?[[6.1]](https://hackmd.io/@Merlin404/SJmtF_k-2) ultragroth[[6.2]](https://hackmd.io/@Merlin404/Hy_O2Gi-h?utm_source=substack&utm_medium=email)|
|Ligero - 2017|[ →📝](https://dl.acm.org/doi/pdf/10.1145/3133956.3134104)|
|ZoKrates - 2018|[ →📝](https://api-depositonce.tu-berlin.de/server/api/core/bitstreams/2b81beb7-5b0f-4048-a56f-104317a82675/content)|[ZoKrates](https://zokrates.github.io/)|Proving hash preimage with Zokrates - Decentriq[[1]](https://blog.decentriq.com/proving-hash-pre-image-zksnarks-zokrates/) Efficient ECC in Zokrates- Decentriq[[2]](https://blog.decentriq.com/efficient-ecc-in-zksnarks-using-zokrates/)
|xjSNARK - 2018|[ →📝](https://akosba.github.io/papers/xjsnark.pdf)|
|Hyrax - 2018|[ →📝](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8418646)|
|Sonic - 2019|[ →📝](https://eprint.iacr.org/2019/099.pdf)| |[Benthams Gaze](https://www.benthamsgaze.org/2019/02/07/introducing-sonic-a-practical-zk-snark-with-a-nearly-trustless-setup/)
|Plonk - 2019|[ →📝](https://eprint.iacr.org/2019/953.pdf)|heliaxdev[[1]](https://github.com/heliaxdev/plonk) kobigurk[[2]](https://github.com/kobigurk/plonk/tree/kobigurk/port_to_zexe) ZK-Garage[[3]](https://github.com/ZK-Garage/plonk) dusk-network[[4]](https://github.com/dusk-network/plonk) Jellyfish (Includes Plookup)[[5]](https://github.com/EspressoSystems/jellyfish)|Plonk high level summary[[1]](https://www.smartcontractresearch.org/t/research-summary-plonk-permutations-over-lagrange-bases-for-oecumenical-noninteractive-arguments-of-knowledge/382) Talk: Ariel Gabizon[[2]](https://www.youtube.com/watch?v=dHo56MhQlHk) Talk: Zac Williamson[[3]](https://www.youtube.com/watch?v=ty-LZf0YCK0) Understanding Plonk - Vitalik[[4]](https://vitalik.ca/general/2019/09/22/plonk.html) From AIRs to RAPs - how PLONK-style arithmetization works[[5]](https://hackmd.io/@aztec-network/plonk-arithmetiization-air#How-does-all-this-relate-to-R1CS) On optimizations of Plonk[[6]](https://www.fluidex.io/en/blog/on-plonk/) Custom gates on plonk -Do whatever[[7]](https://kobi.one/2021/05/20/plonk-custom-gates.html) Plonk Cafe[[8]](https://www.plonk.cafe/top) Plonk: Anatomy of a proof generation: Scroll[[9]](https://scroll.io/blog/proofGeneration#heading-22) Resource: Plonk by hand -1 Metastate[[10.1]](https://research.metastate.dev/plonk-by-hand-part-1/) Resource: Plonk by hand -2 Metastate[[10.2]](https://research.metastate.dev/plonk-by-hand-part-2-the-proof/) Resource: Plonk by hand -3 Metastate[[10.3]](https://research.metastate.dev/plonk-by-hand-part-3-verification/) Resource: Plonk and Plookup Metastate[[10.4]](https://research.metastate.dev/on-plonk-and-plookup/) Turboplonk[[11]](https://docs.zkproof.org/pages/standards/accepted-workshop3/proposal-turbo_plonk.pdf) Custom gates in plonk[[12]](https://www.plonk.cafe/t/details-of-custom-gate/122) Plonk: Thomas Piellard[[13]](https://hackmd.io/@gnark/plonk) ZKP intro to Plonk - Star Li[[14]](https://trapdoortech.medium.com/zkp-plonk-algorithm-introduction-834556a32a) Multi set checks in Plonk and Plookup: Gabizon[[15]](https://hackmd.io/@arielg/ByFgSDA7D) Plonk - Kimchi: Mina Protocol[[16.1]](https://eng-blog.o1labs.org/posts/plonk/) Kimchi[[16.2]](https://minaprotocol.com/blog/kimchi-the-latest-update-to-minas-proof-system)
|Redshift - 2019|[ →📝](https://eprint.iacr.org/2019/1400)|Redhsift Summary[[1]](https://www.smartcontractresearch.org/t/research-summary-redshift-transparent-snarks-from-list-polynominal-commitment-iops/344) Plonk not a monad tutorial [[2]](https://blog.lambdaclass.com/all-you-wanted-to-know-about-plonk/?utm_source=substack&utm_medium=email)|
|Spartan - 2019|[ →📝](https://eprint.iacr.org/2019/550.pdf)|[Microsoft](https://github.com/microsoft/Spartan)
|Halo - 2019|[ →📝](https://eprint.iacr.org/2019/1021.pdf)|
|MIRAGE - 2020|[ →📝](https://eprint.iacr.org/2020/278.pdf)|
|Marlin - 2020|[ →📝](https://eprint.iacr.org/2019/1047.pdf)|[arkworks-rs](https://github.com/arkworks-rs/marlin)
|Fractal -2020|[ →📝](https://eprint.iacr.org/2019/1076)|[scipr-lab/libiop](https://github.com/scipr-lab/libiop)
|Lunar - 2020|[ →📝](https://eprint.iacr.org/2020/1069)|
|SuperSonic - 2020|[ →📝](https://eprint.iacr.org/2019/1229.pdf)|
|Darlin - 2021 |[ →📝](https://arxiv.org/pdf/2107.04315.pdf)|
|Plonkup -2021|[ →📝](https://eprint.iacr.org/2022/086.pdf)|[HorizenOfficial/ginger-lib](https://github.com/HorizenOfficial/ginger-lib)
|SnarkPack -2021|[ →📝](https://research.protocol.ai/publications/snarkpack-practical-snark-aggregation/gailly2021.pdf)|
|FFlonk -2021|[ →📝](https://eprint.iacr.org/2021/1167.pdf)|
|Brakedown - 2021|[ →📝](https://eprint.iacr.org/2021/1043.pdf)|
|Gemini - 2022|[ →📝](https://eprint.iacr.org/2022/420)|
|Hyperplonk - 2022|[ →📝](https://eprint.iacr.org/2022/1355)|[EspressoSystems](https://github.com/EspressoSystems/hyperplonk)
|Testudo: Groth+Spartan - 2023|[ →📝](https://cryptonet.org/blog/testudo-efficient-snarks-with-smaller-setups)|[cryptonetlab](https://github.com/cryptonetlab/Testudo)
