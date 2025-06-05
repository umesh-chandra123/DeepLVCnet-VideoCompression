# DeepLVCnet-VideoCompression
B.Tech Major Project on Deep Learning-Based Video Compression
# 🎥 DeepLVCnet: Deep Learning-Based Video Compression Framework

##  Major Project – B.Tech, Electronics & Communication Engineering  
**Title:** *Efficiency Across Data Sets: Insights into Video Compression Techniques*  
**Team Members:** A. Sreeram, B. Umesh Chandra, G. Sai Swetha  
**Guide:** Shilpa Bagade (Assistant Professor, GRIET)

---

##  Project Overview:

This project introduces **DeepLVCnet**, a deep predictive video compression framework built using deep learning techniques.  
It addresses the limitations of traditional codecs (H.264, H.265) by proposing a **mode-selective**, **multi-frame**, and **context-adaptive** compression architecture that significantly improves coding efficiency, decoding speed, and video quality.

---

##  Key Features:

- Multi-scale feature transformation for residual and motion data compression  
- Mode-selective uni- and bi-directional prediction  
- Temporal Context-Adaptive Entropy Modeling  
- Integrated frame interpolation using optical flow estimation  
- CNN-based enhancement network for improved reconstruction quality  

---

##  Methodology:

- **Multiple Reference Framework:** Uses 2–4 reference frames for temporal accuracy  
- **Context-Net:** Learns Gaussian parameters (μ, σ) using spatial-temporal similarity  
- **Mode-Selective Compression:** Supports intra-, uni-, and bi-directional prediction logic  
- **Enhancement Net:** Utilizes Residual Dense Blocks (RDBs) for frame refinement  

---

## Experimental Results :

- Tested on datasets: **HEVC Class B, Class E**, and **Ultra Video Group (UVG)**  
- Compared against traditional codecs (**H.264**, **H.265**)  
- Achieved up to **60% bitrate reduction** with better or equal MS-SSIM quality  
- Outperformed existing deep video compression models in **real-time performance** and **rate-distortion efficiency**

---

##  Technologies Used :

- **Languages/Frameworks:** Python, TensorFlow / PyTorch  
- **Tools:** OpenCV, FFmpeg  
- **Data:** HEVC & UVG test video datasets  
- **Models:** Autoencoders, Residual Dense Networks (RDN), PWC-Net  

---

##  Repository Structure:
DeepLVCnet-VideoCompression/
│
├── README.md ← Project documentation
├── DeepLVCnet_Model/ ← Source code for architecture & training
├── Datasets/ ← Sample test videos / frame sequences
├── Results/ ← Output graphs, BD-rate tables, visual comparisons
├── Paper/ ← Final PDF report 
└── References/ ← Research papers, citations


---

## Conclusion :

DeepLVCnet demonstrates how **deep neural networks** can revolutionize video compression by leveraging spatial-temporal patterns and mode selection.  
This project bridges the gap between traditional video codecs and modern AI-driven systems, paving the way for faster and smarter video compression.

---




