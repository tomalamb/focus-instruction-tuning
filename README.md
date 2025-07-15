# Focus Instruction Tuning (FIT)

Repository of the project website for our ICML25 paper, *Focus On This, Not That! Steering LLMs With Adaptive Feature Specification* [[Website](https://tomalamb.github.io/focus-instruction-tuning/) | [Paper](https://openreview.net/forum?id=rbI5mOUA8Z)]

![Focus Instruction Tuning Diagram](static/images/motivation.png)

### Abstract
Despite the success of Instruction Tuning (IT) in training large language models (LLMs), such models often leverage spurious or biased features learnt from their training data and can become misaligned, leading to undesired behaviours. While existing techniques can steer model behaviour at inference-time, they are often post-hoc and do not embed steering as an intrinsic model feature. In this work, we introduce **Focus Instruction Tuning (FIT)**, which trains LLMs to condition their responses by focusing on specific features whilst ignoring others, leading to different behaviours based on what features are specified. Across diverse benchmarks, we demonstrate that FIT: (i) steers behaviour at inference time; (ii) increases robustness by amplifying core task signals and down-weighting spurious cues; (iii) mitigates social bias by suppressing demographic attributes; and (iv) generalises to distribution shifts and previously unseen focus features. FIT therefore offers a lightweight, intrinsic mechanism for building robust, fair, and easily controllable LLMs suitable for real-world deployment.


### BibTeX

```
@inproceedings{
  lamb2025focus,
  title={Focus On This, Not That! Steering {LLM}s with Adaptive Feature Specification},
  author={Tom A. Lamb and Adam Davies and Alasdair Paren and Philip Torr and Francesco Pinto},
  booktitle={Forty-second International Conference on Machine Learning},
  year={2025},
  url={https://openreview.net/forum?id=rbI5mOUA8Z}
}
```
