# Dynamic Modality-Temporal Adaptation for Video-based Visible–Infrared Person Re-Identification

This is the official repository for **DMTA**, a novel framework designed for **Video-Based Visible-Infrared Person Re-Identification**.


![framework](./img/dmta.png)


---

## 🚀 Getting Started

### 📁 Dataset 

This project supports two benchmark datasets for Video-based Visible-Infrared Person Re-Identification: **VCM** and **BUPT**.

- 📂 [VCM Dataset Download & Processing Instructions](https://github.com/VCM-project233/MITML)

- 📂 [BUPT Dataset Download & Processing Instructions](https://github.com/dyhBUPT/BUPTCampus)




### 🏋️‍♂️ Training

To train DMTA on the **VCM** dataset:

```
python train.py
```

The dataset path is configured in the `data_manager.py` file

To train DMTA on the **BUPT** dataset:

```
python train.py --data_root ../datasets/BUPTCampus/DATA/
```

### :car:Evaluation

To evaluate the model on the **VCM** dataset:

```
python test.py --resume v2t_map_best.pth
```

To evaluate the model on the **BUPT** dataset:

```
python test.py --resume v2t_map_best.pth
```


### 💾 Pretrained Models & Training Logs

We provide pretrained weights and training logs for both datasets:

### 🔹 VCM Dataset

- 📑 [Training Log (VCM)]([Anonymized Repository - Anonymous GitHub](https://anonymous.4open.science/r/VVIReID-DMTA/HITSZ-VCM/VCM_v1_os.txt))

### 🔹 BUPT Dataset

- 📑 [Training Log (BUPT)]([Anonymized Repository - Anonymous GitHub](https://anonymous.4open.science/r/VVIReID-DMTA/BUPTCampus/BUPTCampus_drop_0.2_4_16_lr_0.1_seed_1234_os.txt))

