# FINAL PROJECT TITLE HERE

## Project Description

Please describe your Startup Campus final project here. You may should your <b>model architecture</b> in JPEG or GIF.

## Contributor

| Full Name   | Affiliation              | Email                         | LinkedIn                                                    | Role        |
| ----------- | ------------------------ | ----------------------------- | ----------------------------------------------------------- | ----------- |
| Yoshua P Sr | Startup Campus, AI Track | josuasiringoringo06@gmail.com |                                                             | Team Lead   |
| Ivan        | Startup Campus, AI Track | ivanputram007@gmail.com       | https://www.linkedin.com/in/ivan-putra-m-24a267237          | Team Member |
| Tiara       | Startup Campus, AI Track | tiaraputrim822@gmail.com      | https://www.linkedin.com/in/tiara-putri-maharani-bb24a0292/ | Team Member |
| Nabila      | Startup Campus, AI Track | nabilaskmngr@gmail.com        | https://www.linkedin.com/in/nabila-sukmanegara-39bb34277/   | Team Member |
| Usama       | Startup Campus, AI Track | posowandhy1@gmail.com         | https://www.linkedin.com/in/usama-997656268                 | Team Member |
| Fikri       | Startup Campus, AI Track | fikriarifviando.if@gmail.com  | https://www.linkedin.com/in/fikri-arifviando                | Team Member |

## Setup

### Prerequisite Packages (Dependencies)

- pandas==2.1.0
- pytorch=2.0.0
- numpy=1.26.2

### Environment

|     |                                  |
| --- | -------------------------------- |
| CPU | Example: AMD RYZEN 7 4800 SERIES |
| GPU | Example: Nvidia GTX 1650 TI      |
| ROM | Example: 1 TB SSD                |
| RAM | Example: 8 GB                    |
| OS  | Example: Windws 11 Home          |

## Dataset

Describe your dataset information here. Provide a screenshot for some of your dataset samples (for example, if you're using CIFAR10 dataset, then show an image for each class).

- Link: https://drive.google.com/file/d/1lRqU_iY8GQqgEJlB81RtMhdHMr71XqvZ/view?usp=sharing

## Results

### Model Performance

Describe all results found in your final project experiments, including hyperparameters tuning and architecture modification performances. Put it into table format. Please show pictures (of model accuracy, loss, etc.) for more clarity.

#### 1. Metrics

Inform your model validation performances, as follows:

- For classification tasks, use **Precision and Recall**.
- For object detection tasks, use **Precision and Recall**. Additionaly, you may also use **Intersection over Union (IoU)**.
- For image retrieval tasks, use **Precision and Recall**.
- For optical character recognition (OCR) tasks, use **Word Error Rate (WER) and Character Error Rate (CER)**.
- For adversarial-based generative tasks, use **Peak Signal-to-Noise Ratio (PNSR)**. Additionally, for specific GAN tasks,
  - For single-image super resolution (SISR) tasks, use **Structural Similarity Index Measure (SSIM)**.
  - For conditional image-to-image translation tasks (e.g., Pix2Pix), use **Inception Score**.

Feel free to adjust the columns in the table below.

| model   | epoch | learning_rate | batch_size | optimizer | val_loss | val_precision | val_recall | ... |
| ------- | ----- | ------------- | ---------- | --------- | -------- | ------------- | ---------- | --- |
| Yolo V5 | 300   | 0.01          | 32         | SGD       | 0.035    | 0.967         | 0.946      | ... |
| RCNN    | 300   | 0.0001        | 16         | ADAM      | 0.17     | 0.76          | 0.83       | ... |
| ...     | ...   | ...           | ...        | ...       | ...      | ...           | ...        | ... |

#### 2. Ablation Study

Any improvements or modifications of your base model, should be summarized in this table. Feel free to adjust the columns in the table below.

| model   | layer_A            | layer_B           | layer_C             | layer_D           | top1_acc | top5_acc |
| ------- | ------------------ | ----------------- | ------------------- | ----------------- | -------- | -------- |
| Yolo V5 | Conv,[64, 6, 2, 2] | Conv, [128, 3, 2] | BottleneckCSP,[128] | Conv, [256, 3, 2] | 0.83     | 0.965    |
| ...     | ...                | ...               | ...                 | ...               | ...      | ...      |

#### 3. Training/Validation Curve

Insert an image regarding your training and evaluation performances (especially their losses). The aim is to assess whether your model is fit, overfit, or underfit.

-link: https://drive.google.com/drive/folders/1aItorDOHrXFd5Wy3ZgabdTMBN7kNho0A?usp=sharing

### Testing

Show some implementations (demos) of this model. Show **at least 10 images** of how your model performs on the testing data.
https://drive.google.com/drive/folders/1tVFF0gLDK4-JTmoWfQzNNMVx12GQcYmS

### Deployment (Optional)

- Tidak melakukan deployment

## Supporting Documents

### Presentation Deck

- Link: https://www.canva.com/design/DAF1FYSORGI/kFE-PctrEK-2WOYGOQWBig/edit?utm_content=DAF1FYSORGI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

### Business Model Canvas

Provide a screenshot of your Business Model Canvas (BMC). Give some explanations, if necessary. https://drive.google.com/drive/folders/1_sKOUqERhjqELpjp_T2IcLXDyyVPw5pJ 

### Short Video

Provide a link to your short video, that should includes the project background and how it works.

- Link: https://drive.google.com/drive/folders/1ypf7tAeUSgd8U3K_UDvrw-XpFhVXvhKE?usp=sharing

## References

Provide all links that support this final project, i.e., papers, GitHub repositories, websites, etc.

- Link: https://youtu.be/LB9SklRNDUA?si=z8FNJkqoU0yJQR8l

## Additional Comments

Provide your team's additional comments or final remarks for this project. For example,

1. Projek ini masih dalam tahap pengembangan development
2. ...
3. ...

## How to Cite

If you find this project useful, we'd grateful if you cite this repository:

```
@article{
    https://www.researchgate.net/publication/363918401_A_lightweight_modified_YOLOX_network_using_coordinate_attention_mechanism_for_PCB_surface_defect_detection
}
```

## License

For academic and non-commercial use only.

## Acknowledgement

This project entitled <b>"Solder Defect Identification on The Printed Circuit Board using Faster RCNN and Yolo V5"</b> is supported and funded by Startup Campus Indonesia and Indonesian Ministry of Education and Culture through the "**Kampus Merdeka: Magang dan Studi Independen Bersertifikasi (MSIB)**" program.
