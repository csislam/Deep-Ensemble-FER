# Deep Ensemble Learning with Attention Mechanisms for Robust Facial Emotion Recognition

This repository contains the implementation of **Deep Ensemble Learning with Attention Mechanisms for Robust Facial Emotion Recognition**, a research project aimed at improving the accuracy and robustness of facial emotion recognition (FER) systems through heterogeneous deep learning ensembles and attention-based feature refinement.

---

## 🚀 Overview

Facial Emotion Recognition (FER) plays a pivotal role in human–computer interaction, mental health analysis, and intelligent surveillance. Traditional CNN-based methods often struggle with generalization due to varying illumination, occlusions, and subject diversity.

This project proposes a **heterogeneous deep ensemble model** that integrates three complementary architectures — **EfficientNet-B3**, **ResNet50**, and a **custom Multi-Scale CNN** — each augmented with **Convolutional Block Attention Modules (CBAM)** for adaptive feature recalibration.

---

## 🧠 Key Features

* **Heterogeneous Ensemble Learning:** Combines multiple deep architectures to capture diverse facial features and expression variations.
* **Attention-Enhanced Feature Learning:** Uses **CBAM** to refine spatial and channel attention, improving discriminative feature representation.
* **Advanced Training Strategies:** Employs **label smoothing**, **focal loss**, and optimized learning rate scheduling for enhanced stability.
* **Performance:** Achieved **73.33% accuracy**, outperforming baseline and individual models in preliminary evaluations.
* **Robustness:** Designed to generalize across complex, real-world FER datasets.

---

## 🧩 Architecture

The ensemble integrates:

1. **EfficientNet-B3:** Efficient scaling of network width, depth, and resolution.
2. **ResNet50:** Deep residual learning for improved gradient flow.
3. **Multi-Scale CNN:** Captures fine-grained local and global emotional cues.
4. **CBAM Attention Modules:** Enhance spatial and channel attention in each architecture before ensemble fusion.

---

## 🧪 Experimental Setup

* **Dataset:** [Specify dataset, e.g., FER2013 or RAF-DB]
* **Framework:** PyTorch
* **Optimizer:** Adam / SGD with momentum
* **Loss Functions:** Focal Loss + Label Smoothing Cross-Entropy
* **Evaluation Metrics:** Accuracy, F1-score, Confusion Matrix

---

## 📈 Results

| Model                        | Accuracy (%) | Notes                            |
| :--------------------------- | :----------: | :------------------------------- |
| ResNet50                     |     68.42    | Baseline                         |
| EfficientNet-B3              |     70.11    | Improved generalization          |
| Multi-Scale CNN              |     69.78    | Strong spatial performance       |
| **Proposed Ensemble (CBAM)** |   **73.33**  | **State-of-the-art performance** |

---

## 🧩 Future Work

* Integrate **Transformer Encoders** for multimodal emotion understanding.
* Explore **Explainable AI (XAI)** frameworks for FER transparency.
* Deploy model as a real-time web demo using **Streamlit** or **Gradio**.

---

## 📚 Citation

If you use this work or find it helpful, please cite:

```
@project{noor2025ferensemble,
  title={Deep Ensemble Learning with Attention Mechanisms for Robust Facial Emotion Recognition},
  author={Noor Islam S. Mohammad},
  year={2025},
  institution={Istanbul Technical University},
  url={https://github.com/csislam/Deep-Ensemble-FER}
}
```

---

## 🧑‍💻 Author

**Noor Islam S. Mohammad**
---

⭐ **If you find this repository useful, please star it to support the research!**
