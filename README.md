## KoIn_Benchmark_Dataset - Korean Influencer

### New Benchmarks for Asian Facial Recognition Tasks: Face Classification with Large Foundation Models
* This repository provides Korean Influencer(KoIN) Dataset and PyTorch implementations for Image Classification models.
* This work is presented at arXiv

### Authors
[Jinwoo Seo](), [Soora Choi](), [Eungyeom Ha](https://github.com/poori-nuna), [범준 킴](), [Dongbin Na](https://github.com/ndb796)

### Abstract
> The face classification system is an important tool for recognizing personal identity properly.
This paper introduces a new Large-Scale Korean Influencer Dataset named KoIn.
Our presented dataset contains many real-world photos of Korean celebrities in various environments that might contain stage lighting, backup dancers, and background objects.
These various images can be useful for training classification models classifying K-influencers.
Most of the images in our proposed dataset have been collected from social network services (SNS) such as Instagram.
Our dataset, KoIn, contains over 100,000 K-influencer photos from over 100 Korean celebrity classes.
Moreover, our dataset provides additional \textit{hard case} samples such as images including human faces with masks and hats.
We note that the hard case samples are instrumental in evaluating the robustness of the classification systems.
We have extensively conducted several experiments utilizing various classification models to validate the effectiveness of our proposed dataset.
Specifically, we demonstrate that recent state-of-the-art (SOTA) foundation architectures show decent classification performance when trained on our proposed dataset.
In this paper, we also analyze the robustness performance against hard case samples of large-scale foundation models when we fine-tune the foundation models on the normal cases of the proposed dataset, KoIn.
Our presented dataset and codes will be publicly available for academic purposes after the paper is accepted.

### Datasets
* The dataset is divided into three distinct groups based on the difficulty of image classification, the <b>Normal cases</b>, the <b>Hard cases</b>, and the <b>Group cases</b>.

    <img src="resources/KI.png" width="90%">

* This repository provides (1) Normal case training dataset, (2) Hard case training dataset, (3) Normal case test dataset, (4) Hard case test dataset, (5) Normal case test dataset, (6) Hard case test dataset.

    <pre><b>Dataset/</b>
        <b>normal_cases/</b>
            train/
            test/
        <b>hard_cases/</b>
            train/
            test/</pre>

* The normal case training dataset contains 100,000 images.
* The normal case test dataset contains 5,000 images.
* The hard case test dataset contains 1,000 images.
* The group case test dataset contains 500 images.
  
### Source Codes

### Demonstration
* The example images from the hard case test dataset and the corresponding inference results based on the training dataset.

  <img src="resources/KI2.png" width="90%">

* The detection performance of trained models.

  <img src="resources/KI_model.png" width="90%">
  
### Citation
