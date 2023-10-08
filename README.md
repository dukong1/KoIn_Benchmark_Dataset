## Korean_Influencer_Benchmark_Dataset_KoIn

### New Benchmarks for Asian Facial Recognition Tasks: Face Classification with Large Foundation Models
* This repository provides Korean Influencer(KoIN) Dataset and PyTorch implementations for Image Classification models.
* This work is presented at arXiv

### Authors
[Jinwoo Seo](), [Soora Choi](), [Eungyeom Ha](https://github.com/poori-nuna), [범준 킴](), [Dongbin Na](https://github.com/ndb796)

### Abstract
> The face classification system is an important tool for recognizing personal identity properly.
This paper introduces a new Large-Scale Korean Influencer Dataset named \textit{KoIn}.
Our presented dataset contains many real-world photos of Korean celebrities in various environments that might contain stage lighting, backup dancers, and background objects.
These various images can be useful for training classification models classifying K-influencers.
Most of the images in our proposed dataset have been collected from social network services (SNS) such as Instagram.
Our dataset, \textit{KoIn}, contains over 100,000 K-influencer photos from over 100 Korean celebrity classes.
Moreover, our dataset provides additional \textit{hard case} samples such as images including human faces with masks and hats.
We note that the \textit{hard case} samples are greatly useful in evaluating the robustness of the classification systems.
We have extensively conducted several experiments utilizing various classification models to validate the effectiveness of our proposed dataset.
Specifically, we demonstrate that recent state-of-the-art (SOTA) foundation architectures show decent classification performance when trained on our proposed dataset.
In this paper, we also analyze the robustness performance against \textit{hard case} samples of large-scale foundation models when we fine-tune the foundation models on the \textit{normal cases} of the proposed dataset, \textit{KoIn}.
Our presented dataset and codes will be publicly available for academic purposes after the paper is accepted.

### Datasets
* The dataset is divided into two distinct groups based on the difficulty of detection, the <b>Normal cases</b> and the <b>Hard cases</b>.

    <img src="resources/examples_for_each_case.png" width="90%">

* This repository provides (1) normal case training dataset, (2) hard case training dataset, (3) normal case test dataset, (4) hard case test dataset.

    <pre><b>Dataset/</b>
        <b>normal_cases/</b>
            train/
            test/
        <b>hard_cases/</b>
            train/
            test/</pre>

* The normal case training dataset contains 5,198 images.
* The hard case training dataset contains 4,908 images.
* The normal case test dataset contains 270 images.
* The normal case training dataset contains 255 images.

### Source Codes

### Demonstration
* The example images from the hard case test dataset and the corresponding inference results based on the training dataset.

  <img src="resources/hardcases_results_YOLO.png" width="90%">

* The detection performance of trained models.

  <img src="resources/detection_performance.png" width="90%">
  
### Citation
