<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffb347,33:e07b00,66:b34700,100:8b1a00&height=180&section=header&text=Sharven%20Rane&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Medical%20Imaging%20AI%20%7C%20Computer%20Vision%20%7C%20MLOps&descAlignY=52&descSize=16"/>
</div>

<br/>

I build computer vision and deep learning systems and take them from research into production. I am a Data Scientist at **Vetology** in Chicago, where I have shipped 200+ models across classification, detection, and segmentation, trained on A100s over 250,000+ radiographs, and processed more than 12 million images in production.

My focus is medical imaging, self supervised learning, and the model validation and governance that regulated, clinical use demands. I care about the whole path: pretraining and architecture, then validation, monitoring, and efficient inference once a model ships.

```yaml
currently  : Data Scientist @ Vetology, Chicago
focus      : medical imaging AI, model validation and governance, MLOps
background : MS Data Science, Stevens Institute of Technology
interests  : self supervised pretraining, regulated AI, efficient inference
```

<br/>

## Things I work with

<div align="center">

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

<br/>

## Selected work

> Most of the repos below are clean, tested implementations built to be read and run. Where a project would normally lean on a huge pretrained model or external service, it uses a small stand in so the tests stay offline and honest. Nothing here claims a result a run did not produce.

<table>
<tr>
<td width="50%">

**Medical imaging**

[chest-xray-classification](https://github.com/SharvenRane/chest-xray-classification): multi label chest X-ray classifier, real mean AUC 0.832, with a validation report and an FDA style change control plan

[medical-image-segmentation](https://github.com/SharvenRane/medical-image-segmentation): UNet++ and DeepLabV3+ with a Dice plus BCE loss

[tumor-grading](https://github.com/SharvenRane/tumor-grading): a PathMNIST tissue classifier, real validation accuracy near 0.92

[dicom-toolkit](https://github.com/SharvenRane/dicom-toolkit): DICOM windowing, Hounsfield rescaling, and normalization, tested against the pydicom samples

</td>
<td width="50%">

**Validation and governance**

[model-monitoring](https://github.com/SharvenRane/model-monitoring): drift detection with PSI, the KS test, and chi square

[medical-uncertainty-estimation](https://github.com/SharvenRane/medical-uncertainty-estimation): Monte Carlo Dropout and conformal prediction with coverage guarantees

[medical-explainability](https://github.com/SharvenRane/medical-explainability): Grad-CAM, Grad-CAM++, and occlusion sensitivity side by side

[ci-cd-for-ml](https://github.com/SharvenRane/ci-cd-for-ml): a CI pipeline that trains, tests, and gates on a quality bar

</td>
</tr>
<tr>
<td width="50%">

**Self supervised and foundation models**

[ssl-comparison](https://github.com/SharvenRane/ssl-comparison): SimCLR pretraining compared by a shared linear probe

[mae-pretraining](https://github.com/SharvenRane/mae-pretraining): a Masked Autoencoder from scratch

[medical-foundation-model](https://github.com/SharvenRane/medical-foundation-model): a small self supervised encoder pretrained on MedMNIST with linear probing

[ijepa-implementation](https://github.com/SharvenRane/ijepa-implementation): the core I-JEPA masking, predictor, and EMA target mechanics

</td>
<td width="50%">

**From scratch and generative**

[transformer-from-scratch](https://github.com/SharvenRane/transformer-from-scratch): multi head attention and a Transformer encoder built from scratch

[diffusion-model-from-scratch](https://github.com/SharvenRane/diffusion-model-from-scratch): a DDPM with the forward process, a small UNet, and sampling

[autograd-engine](https://github.com/SharvenRane/autograd-engine): a reverse mode automatic differentiation engine

[yolo-benchmark](https://github.com/SharvenRane/yolo-benchmark): IoU, non maximum suppression, and mAP implemented from scratch

</td>
</tr>
</table>

<br/>

## More repos by area

<details>
<summary>Medical and pathology</summary>
<br/>

[cancer-survival-prediction](https://github.com/SharvenRane/cancer-survival-prediction) · [survival-prediction-imaging](https://github.com/SharvenRane/survival-prediction-imaging) · [weakly-supervised-pathology](https://github.com/SharvenRane/weakly-supervised-pathology) · [cell-segmentation](https://github.com/SharvenRane/cell-segmentation) · [pathology-foundation-models](https://github.com/SharvenRane/pathology-foundation-models) · [whole-slide-image-pipeline](https://github.com/SharvenRane/whole-slide-image-pipeline) · [stain-normalization](https://github.com/SharvenRane/stain-normalization) · [medical-image-augmentation](https://github.com/SharvenRane/medical-image-augmentation) · [federated-learning-medical](https://github.com/SharvenRane/federated-learning-medical)

</details>

<details>
<summary>Self supervised, multimodal, and foundation</summary>
<br/>

[contrastive-learning-methods](https://github.com/SharvenRane/contrastive-learning-methods) · [linear-probing-benchmark](https://github.com/SharvenRane/linear-probing-benchmark) · [dinov2-finetuning](https://github.com/SharvenRane/dinov2-finetuning) · [clip-finetuning](https://github.com/SharvenRane/clip-finetuning) · [image-text-retrieval](https://github.com/SharvenRane/image-text-retrieval) · [multimodal-embeddings](https://github.com/SharvenRane/multimodal-embeddings) · [visual-rag](https://github.com/SharvenRane/visual-rag) · [llava-medical-vqa](https://github.com/SharvenRane/llava-medical-vqa) · [vlm-comparison](https://github.com/SharvenRane/vlm-comparison)

</details>

<details>
<summary>Generative models</summary>
<br/>

[diffusion-transformer](https://github.com/SharvenRane/diffusion-transformer) · [diffusion-math-walkthrough](https://github.com/SharvenRane/diffusion-math-walkthrough) · [controlnet-finetuning](https://github.com/SharvenRane/controlnet-finetuning) · [dreambooth-finetuning](https://github.com/SharvenRane/dreambooth-finetuning) · [image-editing-with-diffusion](https://github.com/SharvenRane/image-editing-with-diffusion) · [medical-image-synthesis](https://github.com/SharvenRane/medical-image-synthesis) · [gan-progression](https://github.com/SharvenRane/gan-progression)

</details>

<details>
<summary>Detection, tracking, and video</summary>
<br/>

[open-vocabulary-detection](https://github.com/SharvenRane/open-vocabulary-detection) · [multi-object-tracking](https://github.com/SharvenRane/multi-object-tracking) · [sam2-finetuning](https://github.com/SharvenRane/sam2-finetuning) · [sam2-video-tracking](https://github.com/SharvenRane/sam2-video-tracking) · [action-recognition](https://github.com/SharvenRane/action-recognition) · [temporal-action-localization](https://github.com/SharvenRane/temporal-action-localization) · [video-anomaly-detection](https://github.com/SharvenRane/video-anomaly-detection) · [video-object-tracking](https://github.com/SharvenRane/video-object-tracking)

</details>

<details>
<summary>3D, sensors, and remote sensing</summary>
<br/>

[lidar-object-detection](https://github.com/SharvenRane/lidar-object-detection) · [3d-object-detection](https://github.com/SharvenRane/3d-object-detection) · [3d-scene-reconstruction](https://github.com/SharvenRane/3d-scene-reconstruction) · [depth-estimation](https://github.com/SharvenRane/depth-estimation) · [occupancy-prediction](https://github.com/SharvenRane/occupancy-prediction) · [multi-sensor-fusion](https://github.com/SharvenRane/multi-sensor-fusion) · [optical-flow](https://github.com/SharvenRane/optical-flow) · [pose-estimation-6dof](https://github.com/SharvenRane/pose-estimation-6dof) · [satellite-foundation-model](https://github.com/SharvenRane/satellite-foundation-model)

</details>

<details>
<summary>Efficient models and edge</summary>
<br/>

[model-compression](https://github.com/SharvenRane/model-compression) · [tensorrt-optimization](https://github.com/SharvenRane/tensorrt-optimization) · [onnx-deployment](https://github.com/SharvenRane/onnx-deployment) · [quantization-aware-training](https://github.com/SharvenRane/quantization-aware-training) · [knowledge-distillation](https://github.com/SharvenRane/knowledge-distillation) · [edge-vision-pipeline](https://github.com/SharvenRane/edge-vision-pipeline) · [real-time-segmentation](https://github.com/SharvenRane/real-time-segmentation)

</details>

<details>
<summary>MLOps and infrastructure</summary>
<br/>

[ml-project-template](https://github.com/SharvenRane/ml-project-template) · [distributed-training](https://github.com/SharvenRane/distributed-training) · [triton-inference-server](https://github.com/SharvenRane/triton-inference-server) · [experiment-tracking](https://github.com/SharvenRane/experiment-tracking) · [feature-store](https://github.com/SharvenRane/feature-store) · [data-versioning](https://github.com/SharvenRane/data-versioning)

</details>

<details>
<summary>Agentic</summary>
<br/>

[vision-agent](https://github.com/SharvenRane/vision-agent) · [medical-diagnosis-agent](https://github.com/SharvenRane/medical-diagnosis-agent) · [auto-image-annotator](https://github.com/SharvenRane/auto-image-annotator) · [image-search-engine](https://github.com/SharvenRane/image-search-engine) · [multi-agent-ml-experiments](https://github.com/SharvenRane/multi-agent-ml-experiments)

</details>

<details>
<summary>Fundamentals</summary>
<br/>

[vision-transformer-from-scratch](https://github.com/SharvenRane/vision-transformer-from-scratch) · [backpropagation-from-scratch](https://github.com/SharvenRane/backpropagation-from-scratch) · [positional-encoding-variants](https://github.com/SharvenRane/positional-encoding-variants) · [loss-functions-explained](https://github.com/SharvenRane/loss-functions-explained) · [paper-implementations](https://github.com/SharvenRane/paper-implementations)

</details>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sharven-rane/)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharvenrane7@gmail.com)

<img src="https://komarev.com/ghpvc/?username=SharvenRane&label=Profile%20views&color=0e75b6&style=flat"/>

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffb347,33:e07b00,66:b34700,100:8b1a00&height=100&section=footer"/>
</div>
