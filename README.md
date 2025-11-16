# ⭐ **Neuromorphic Motion Detection Using Spiking Neural Networks (SNNs)**

*A real-time gesture recognition system built using event-based neuromorphic vision and FPGA-ready SNN models.*

## 📌 **Overview**

This project implements a **neuromorphic gesture-recognition pipeline** using the **DVS128 event-based sensor dataset**. Instead of traditional frame-based vision, the system processes **asynchronous spike events**, enabling faster and low-power motion detection suitable for **edge devices**.

The model uses a **Spiking Neural Network (SNN)** trained in PyTorch and optimized for hardware deployment through ONNX → Verilog conversion.

---

## 🔧 **Key Features**

* Real-time gesture-recognition using **event-based neuromorphic data**
* Complete spike-data preprocessing pipeline (temporal binning + event tensors)
* SNN architecture implemented and trained using **PyTorch**
* Model quantized using **Brevitas** for efficient inference
* Exported to **ONNX → Verilog** for FPGA-based edge deployment
* Achieved **85.94% accuracy** with low-latency inference
* Suitable for **edge devices, low-power systems, and neuromorphic computing research**

---

## 🧠 **Technical Stack**

* **Languages:** Python, Verilog
* **Frameworks:** PyTorch, Brevitas
* **Tools:** ONNX, FPGA toolchain
* **Dataset:** DVS128 Gesture Dataset

---

## 📂 **Repository Structure**

```
├── preprocessing/       # Spike data conversion, temporal binning  
├── models/              # SNN architecture  
├── training/            # Training scripts  
├── quantization/        # Brevitas quantization  
├── onnx_export/         # ONNX conversion code  
├── verilog/             # Synthesized Verilog for FPGA  
└── README.md            # Project documentation  
```

---

## 🎯 **Applications**

* Low-power gesture recognition
* Intelligent embedded interfaces
* Edge AI acceleration
* Event-based neuromorphic systems
* Robotics and HCI

---

## 📈 **Results**

✔ 85.94% test accuracy
✔ Low-latency inference
✔ FPGA-compatible SNN pipeline
✔ Efficient spike-based real-time classification
