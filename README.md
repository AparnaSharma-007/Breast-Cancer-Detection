# Breast Cancer Classification using Deep Learning

This project focuses on classifying breast cancer as **benign** or **malignant** using mammography and tabular datasets. We trained three separate models on the BCDR, RSNA, and MIAS datasets, incorporating advanced techniques such as Wiener filtering, data augmentation, custom CNN architectures, DCGANs, and ensemble learning.

## 📊 Datasets Used
- **BCDR-D01 & BCDR-F03** (Breast Cancer Digital Repository)
- **MIAS** (Mammographic Image Analysis Society dataset)
- **RSNA Breast Cancer Detection Dataset**
- **Wisconsin Breast Cancer Dataset** (for tabular comparison)

## 🧠 Model Architecture & Techniques
- **Wiener Filtering** for noise reduction  
- **Data Augmentation** for better generalization  
- **Custom CNN Architectures** for image-based learning  
- **DCGAN (Deep Convolutional GAN)** for synthetic data generation  
- **Ensemble Models** combining CNN, RNN, and HCNN architectures  
- **Optimization Techniques**: PSO (Particle Swarm Optimization) used in select models for hyperparameter tuning

## ✅ Results
- Achieved **98% accuracy** in breast cancer classification across multiple datasets
- Demonstrated strong generalization and cross-dataset robustness

## 📈 Comparison with Previous Studies
We compared our results with prior research and baseline methods published in recent breast cancer detection studies. Our hybrid models achieved:
- Higher **accuracy**
- Improved **F1-scores**
- Better **cross-dataset performance**

This shows the effectiveness of combining preprocessing (Wiener filter), advanced data augmentation (DCGAN), and ensemble deep learning techniques.



