# IDSN: A one-stage interpretable and differentiable STFT domain adaptation network for traction motor of high-speed trains cross-machine diagnosis

The ~~pytorch implementation~~ of the paper [IDSN: A one-stage interpretable and differentiable STFT domain adaptation network for traction motor of high-speed trains cross-machine diagnosis](https://doi.org/10.1016/j.ymssp.2023.110846)

Link: https://authors.elsevier.com/c/1hyKp39~t0ffSz  (**50 days' free access**)

# Updating!

[Sorry]The code will be published after the second and third extension papers are accepted!





## Brief introduction  
A surge of transfer fault diagnosis techniques has been proposed to guarantee the safe operation of traction motor systems. However, existing efforts highly depend on the availability of fault data in source domain, which is rare in practice due to the regular maintenance. Fortunately, self-customized testbeds provide an opportunity to easily obtain fault data, assuming that the simulated data can be utilized to monitor the real-world traction motor systems via the cross-machine diagnosis method. Besides, current deep learning-based cross-machine fault diagnosis methods suffer from the poor physical interpretability and the troublesome hype-parameter selection. To tackle aforementioned issues, a one-stage Interpretable and Differentiable STFT cross-machine dual-driven adaptation Network (IDSN) is proposed. In IDSN, a new paradigm termed interpretable differentiable STFT layer is devised, where a derivable coefficient is introduced to adjust pivotal parameters of STFT such as window length by the gradient descent. Prominently, it is a plug-and-play module, which can be embedded into the arbitrary typical network without conflict. Besides, a novel adaptive trade-off coefficient is developed to tackle the weight matching of the domain discrepancy metric. Finally, to ensure the reliability and effectiveness of cross-machine diagnosis, a concise yet valid smoothed joint maximum mean discrepancy is proposed, which simultaneously promotes intra-class compactness and inter-class separability. The results of experiments confirm that the proposed IDSN outperforms the state of the art.

## Highlights

- An interpretable cross-machine network embedded differentiable STFT is proposed.
- The differentiable STFT introduces a derivable coefficient to update window length.
- IDSN absorbs the data-driven expressivity and the knowledge-driven interpretability.
- A trade-off coefficient and smoothing joint maximum mean discrepancy are proposed.
- Experiments validate IDSN, indicating differentiable STFT is compatible with DAN.


## Paper
IDSN: A one-stage interpretable and differentiable STFT domain adaptation network for traction motor of high-speed trains cross-machine diagnosis 

Chao He<sup>a,b</sup>, **Hongmei Shi<sup>a,b,*</sup>** and Jianbo Li<sup>a,b</sup>

<sup>a</sup>School of Mechanical, Electronic and Control Engineering, Beijing Jiaotong University, Beijing 100044, China 

<sup>b</sup>Collaborative Innovation Center of Railway Traffic Safety, Beijing 100044, China 

[Mechanical Systems and Signal Processing](https://www.sciencedirect.com/journal/mechanical-systems-and-signal-processing)



## Citation

```html
@article{HE2023110846,
title = {IDSN: A one-stage interpretable and differentiable STFT domain adaptation network for traction motor of high-speed trains cross-machine diagnosis},
journal = {Mechanical Systems and Signal Processing},
volume = {205},
pages = {110846},
year = {2023},
doi = {https://doi.org/10.1016/j.ymssp.2023.110846},
author = {Chao He and Hongmei Shi and Jianbo Li},
} 
```


C. He, H. Shi, J. Li, IDSN: A one-stage interpretable and differentiable STFT domain adaptation network for traction motor of high-speed trains cross-machine diagnosis, Mechanical Systems and Signal Processing 205 (2023) 110846, https://doi.org/10.1016/j.ymssp.2023.110846.



## Ackowledgements
The authors are grateful for the National Natural Science Foundation of China (No.52272429).



## Contact

- **Chao He**
- **chaohe#bjtu.edu.cn (please replace # by @)**

​      
