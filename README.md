<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0d1117,50:58a6ff,100:0d1117" width="100%"/>

<img src="https://capsule-render.vercel.app/api?type=transparent&height=150&text=Sarib%20Azim&fontSize=54&fontColor=58a6ff&fontAlignY=40&animation=fadeIn&desc=AI%20Engineer%20and%20Researcher%20%C2%B7%20Computer%20Vision%20%C2%B7%20Model%20Interpretability&descAlignY=74&descSize=15&descColor=8b949e"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=400&size=16&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=600&lines=Building+production+ready+AI+systems;LLMs+%C2%B7+Quantization+%C2%B7+RAG+%C2%B7+Deployment;Speech+%C2%B7+Vision+%C2%B7+NLP+%C2%B7+Time+Series;Taking+models+from+research+to+production)](https://git.io/typing-svg)

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0d1117,50:58a6ff,100:0d1117" width="100%"/>

</div>

<br/>

## Research Projects

<table>
<tr>
<td width="50%" valign="top">

### Quantization Fidelity Study
<a href="https://github.com/SaribAzim/quantization-fidelity-study"><img src="https://img.shields.io/badge/Repository-0d1117?style=flat-square&logo=github&logoColor=58a6ff" alt="Repository"/></a>

Systematic evaluation of neural network quantization methods, investigating the trade-off between model precision, quantization error, and predictive performance.

**Key finding**<br/>
<sub>Quantization fidelity depends on weight rounding, quantization granularity, and calibration data, not just bit-width.</sub>

<img src="https://img.shields.io/badge/PyTorch-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Quantization-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/LLMs-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Model%20Evaluation-161b22?style=flat-square"/>

</td>
<td width="50%" valign="top">

### voiceMonitor · INFERENCE Lab
<a href="https://github.com/Inference-LAB/voiceMonitor"><img src="https://img.shields.io/badge/Repository-0d1117?style=flat-square&logo=github&logoColor=58a6ff" alt="Repository"/></a> <a href="https://inference-lab.org/people/sarib-azim"><img src="https://img.shields.io/badge/Lab%20Note-0d1117?style=flat-square&logo=readthedocs&logoColor=58a6ff" alt="Lab Note"/></a>

Core Engineer on an open source vocal fatigue monitoring library (INFERENCE Lab Engineering Fellowship, Cohort 01). Designed a **vocal load impulse response model** adapted from the Banister sports science framework, with EMA smoothing, acoustic feature extraction (jitter, shimmer, HNR, CPPS), and personal baseline calibration. Shipped to **v1.1.0** with **93%** test coverage and CI.

**Core idea**<br/>
<sub>Vocal fatigue can be modelled like training load: each speaking session adds strain that decays over time, giving a recovery estimate instead of a single snapshot.</sub>

<img src="https://img.shields.io/badge/Python-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Parselmouth%20%2F%20Praat-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Signal%20Processing-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Time%20Series-161b22?style=flat-square"/>

<sub>Published as an Engineering Journal entry on inference-lab.org</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Neural Network Calibration Study
<a href="https://github.com/SaribAzim/Neural-Network-Calibration"><img src="https://img.shields.io/badge/Repository-0d1117?style=flat-square&logo=github&logoColor=58a6ff" alt="Repository"/></a>

Post-hoc calibration analysis of ResNet-50 on CIFAR-10. Measured systematic overconfidence using **ECE** and **MCE**. Applied temperature scaling, a single scalar T, to reduce ECE by **67%** without retraining.

**Key finding**<br/>
<sub>High top-1 accuracy and good calibration are independent properties. Most models only optimise for one.</sub>

<img src="https://img.shields.io/badge/PyTorch-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Calibration-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/ResNet--50-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Temperature%20Scaling-161b22?style=flat-square"/>

<sub>Reference: Guo et al. (2017), ICML</sub>

</td>
<td width="50%" valign="top">

### CNN vs ViT Interpretability Study
<a href="https://github.com/SaribAzim/cnn-vit-interpretability"><img src="https://img.shields.io/badge/Repository-0d1117?style=flat-square&logo=github&logoColor=58a6ff" alt="Repository"/></a>

Comparative saliency analysis across ResNet-50, EfficientNet-B0, and ViT-B/16 on ImageNette. Implemented Grad-CAM for CNNs and Grad-CAM with a patch reshape transform for ViT.

**Key finding**<br/>
<sub>CNNs focus on local discriminative patches. ViT attends globally, even when all three models agree on the correct label.</sub>

<img src="https://img.shields.io/badge/PyTorch-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Grad--CAM-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/ViT-161b22?style=flat-square"/> <img src="https://img.shields.io/badge/Interpretability-161b22?style=flat-square"/>

<sub>Reference: Selvaraju et al. (2017), ICCV</sub>

</td>
</tr>
</table>

<br/>

## Technical Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

<div align="center">

[![Spotify](https://spotify-github-profile.kittinanx.com/api/view?uid=31lztsnzj2e3bndtews7x2texqmu&cover_image=false&theme=default&show_offline=false&background_color=121212&interchange=false&profanity=false&hide_remaster=false)](https://github.com/kittinan/spotify-github-profile)

</div>

<br/>

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sarib%20Azim-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sarib-azim-90aa56295/)
[![GitHub](https://img.shields.io/badge/GitHub-SaribAzim-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SaribAzim)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0d1117,50:58a6ff,100:0d1117" width="100%"/>

</div>
