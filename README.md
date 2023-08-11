# advPattern: Physical-World Attacks on Deep Person Re-Identification via Adversarially Transformable Patterns
<img width="454" alt="image" src="https://github.com/AlirezaRahimpour/AdvPatternDeepREID/assets/18356361/9679d5a5-6ffb-48f5-bb4e-b945e92585e7">

Person re-identification (re-ID) is the task of matching person images across camera views, which plays an important role in surveillance and security applications. Inspired by great progress of deep learning, deep re-ID models began to be popular and gained state-of-the-art performance. However, recent works found that deep neural networks (DNNs) are vulnerable to adversarial examples, posing potential threats to DNNs based applications. This phenomenon throws a serious question about whether deep re-ID based systems are vulnerable to adversarial attacks. In this paper, we take the first attempt to implement robust physical-world attacks against deep re-ID. We propose a novel attack algorithm, called advPattern, for generating adversarial patterns on clothes, which learns the variations of image pairs across cameras to pull closer the image features from the same camera, while pushing features from different cameras farther. By wearing our crafted "invisible cloak", an adversary can evade person search, or impersonate a target person to fool deep re-ID models in physical world. We evaluate the effectiveness of our transformable patterns on adversaries' clothes with Market1501 and our established PRCS dataset. The experimental results show that the rank-1 accuracy of re-ID models for matching the adversary decreases from 87.9% to 27.1% under Evading Attack. Furthermore, the adversary can impersonate a target person with 47.1% rank-1 accuracy and 67.9% mAP under Impersonation Attack. The results demonstrate that deep re-ID systems are vulnerable to our physical attacks.

Paper: 
[advPattern: Physical-World Attacks on Deep Person Re-Identification via Adversarially Transformable Patterns](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_advPattern_Physical-World_Attacks_on_Deep_Person_Re-Identification_via_Adversarially_Transformable_ICCV_2019_paper.html)

## Citation
### Our paper has been accepted to appear in **ICCV 2019**. Please **cite** our paper if you're interested in our work!
---
```bibtext
@InProceedings{Wang_2019_ICCV,
author = {Wang, Zhibo and Zheng, Siyan and Song, Mengkai and Wang, Qian and Rahimpour, Alireza and Qi, Hairong},
title = {advPattern: Physical-World Attacks on Deep Person Re-Identification via Adversarially Transformable Patterns},
booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}
```
