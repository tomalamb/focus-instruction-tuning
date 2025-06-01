# Focus Instruction Tuning (FIT)

> 🚧 **Code coming soon**  
> We are in the process of preparing the codebase for public release. Stay tuned!

Repository for the paper introducing Focus Instruction Tuning (FIT).  

![Focus Instruction Tuning Diagram](static/images/motivation.png)

### Abstract
Despite the success of Instruction Tuning (IT) in training large language models (LLMs), such models often leverage spurious or biased features learnt from their training data and can become misaligned, leading to undesired behaviours. While existing techniques can steer model behaviour at inference-time, they are often post-hoc and do not embed steering as an intrinsic model feature. In this work, we introduce Focus Instruction Tuning (FIT), which trains LLMs to condition their responses by focusing on specific features whilst ignoring others, leading to different behaviours based on what features are specified. Across diverse benchmarks, we demonstrate that FIT: (i) steers behaviour at inference time; (ii) increases robustness by amplifying core task signals and down-weighting spurious cues; (iii) mitigates social bias by suppressing demographic attributes; and (iv) generalises to distribution shifts and previously unseen focus features. FIT therefore offers a lightweight, intrinsic mechanism for building robust, fair, and easily controllable LLMs suitable for real-world deployment.

