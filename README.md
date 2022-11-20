# About

This started as an actual experiment I decided to make a while ago. The experiment was to check how much a well-trained model could hold its output by slightly changing the input image. I'll call this changes RISPP - Random Incremental Single Pixel Perturbations.

# The code

It's  everything on the `ispp.ipynb` notebook. Run `pip3 install -r requirements.txt` to install needed packages.

You could use your own model and images. Check it out!

# Results

![Screenshot](https://i.imgur.com/bcbdFuh.png)

---

![Screenshot](https://i.imgur.com/xUUDtMu.png)

---

![Screenshot](https://i.imgur.com/X9PUMPh.png)

# Relevant links
This is already a well-documented field, that started around [2015](https://karpathy.github.io/2015/03/30/breaking-convnets) and still growing stronger since then. The research in this field keeps pushing the models to their limits, both for attack or/and defense.
For additional info, check those papers that were also used to fundament this experiment: [Haotian Zhang, XuMa (2022)](https://www.sciencedirect.com/science/article/pii/S016740482200270X?dgcid=rss_sd_all#!), [Hong Wang et al. (2021)](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_AGKD-BML_Defense_Against_Adversarial_Attack_by_Attention_Guided_Knowledge_Distillation_ICCV_2021_paper.pdf), [Atiye Sadat Hashemi &  Saeed Mozaffari (2021)](https://link.springer.com/article/10.1007/s11042-020-10379-6#auth-Atiye_Sadat-Hashemi),[ Kevin Eykholt et al. (2018)](https://arxiv.org/pdf/1707.08945.pd), [Xiaoshuang Shi et al.(2022)](https://www.sciencedirect.com/science/article/pii/S0031320322004046#!), [Jiawei Su et. al (2017)](https://arxiv.org/abs/1710.08864).