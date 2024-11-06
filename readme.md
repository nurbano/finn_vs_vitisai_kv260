##  Comparison of Vitis-AI and FINN for implementing convolutional neural networks on FPGA (KV260)

### Abstract
Convolutional neural networks (CNNs) are essential for image classification and detection, and their implementation in embedded systems is becoming increasingly attractive due to their compact size and low power consumption. Field-Programmable Gate Arrays (FPGAs) have emerged as a promising option, thanks to their low latency and high energy efficiency.

Vitis AI and FINN are two development environments that automate the implementation of CNNs on FPGAs. Vitis AI uses a deep learning processing unit (DPU) and memory accelerators, while FINN is based on a streaming architecture and fine-tunes parallelization. Both environments implement parameter quantization techniques to reduce memory usage.

This work extends previous comparisons by evaluating both environments by implementing four models with different numbers of layers on the Xilinx Kria KV260 FPGA platform. The complete process from training to evaluation on FPGA, including quantization and hardware implementation, is described in detail.

The results show that FINN provides lower latency, higher throughput, and better energy efficiency than Vitis AI. However, Vitis AI stands out for its simplicity in model training and ease of implementation on FPGA. The main finding of this study is that as the complexity of the models increases (with more layers in the neural networks), the differences in terms of performance and energy efficiency between FINN and Vitis AI are significantly reduced.