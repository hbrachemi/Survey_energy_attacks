# Sponge_attacks
A collection of existing papers related to energy-latency attacks

**Table of Contents**
- [Inference Stage Attacks](#Inference-Stage-Attacks)
- [Training Stage Attacks](#Training-Stage-Attacks)

<div align=center><img src="./attack_scenarios.png" width="110%" height="110%" /></div>

---

## Inference-Stage-Attacks

|Attack  | Venue | Target | Application | Attack setting | Papers :page_facing_up:| Code |
| :--- | :---: |:---:|:---:|:---:|:---:|:---:|
| Sponge examples  | [EuroS&P (2021)](https://www.ieee-security.org/TC/EuroSP2021/)  | Transformers + CNNs | CV & NLP | Black & white box | [paper](https://arxiv.org/abs/2006.03463) | [Github](https://github.com/iliaishacked/sponge_examples)|
|Sparsity attacks | [IEEE Transactions on Computer-Aided\ Design of Integrated Circuits and Systems](https://dl.acm.org/journal/tcadics)| CNNs | CV | White box | [paper](https://arxiv.org/abs/2006.08020) |  ✘ |
| ILFO | [CVPR (2020)](https://cvpr2020.thecvf.com/) |Depth-dynamic AdNNs| CV | White box | [paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Haque_ILFO_Adversarial_Attack_on_Adaptive_Neural_Networks_CVPR_2020_paper.html) | ✘ |
|DeepSloth | [ICLR (2021)](https://iclr.cc/Conferences/2021) | Multi-exit CNNs | CV | White box | [paper](https://arxiv.org/abs/2010.02432) | [Github](https://github.com/Sanghyun-Hong/DeepSloth)|
|GradAuto  | [ECCV (2022)](https://eccv2022.ecva.net/) | Depth- and \width-dynamic AdNNs | CV | White box | [paper](https://eprints.lancs.ac.uk/id/eprint/179610/1/Advanced_Adversarial_Attack_on_Dynamic_Neural_Networks.pdf) | [Github](https://github.com/JianhongPan/GradAuto)|
|SpikeAttack| [ACM-DAC (2022) ](https://dl.acm.org/doi/proceedings/10.1145/3489517)|SNNs | CV | White box | [paper](https://dl.acm.org/doi/pdf/10.1145/3489517.3530443) |  ✘ |
|NMTSloth | [ESEC/FSE (2022) ] (https://2022.esec-fse.org/) | Decoder-based NMT \systems | NLP | White box | [paper]([https://arxiv.org/abs/2210.03696v2](https://arxiv.org/abs/2210.03696v1)) | [Github](https://github.com/SeekingDream/FSE22_NMTSloth) |
|LLMEffiChecker | [ACM Transactions on Software\ Engineering and Methodology](https://dl.acm.org/journal/tosem) | LLMs | NLP | Black & white box | [paper](https://arxiv.org/abs/2210.03696) | [Github](https://github.com/Cap-Ning/LLMEffiChecker) |
|NICGSlowDown

## Training-Stage-Attacks
