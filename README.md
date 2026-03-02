# Velfox Tweaks
### Adaptive Performance Scheduler for Android
Velfox Tweaks is a daemon-based adaptive performance module designed to intelligently balance performance, thermal stability, and power efficiency on Android devices.

Unlike static tweak scripts, Velfox runs through a persistent background daemon that dynamically monitors workload conditions and applies contextual system adjustments in real time.

Supported SoC platforms:
- Snapdragon  
- MediaTek  
- Exynos  
- Unisoc  
- Tensor  

---

## Architecture
Velfox operates as a lightweight background daemon responsible for:
- Real-time workload monitoring  
- Context-aware parameter switching  
- Dynamic CPU & GPU scaling control  
- Scheduler and kernel parameter management  
- System resource prioritization  
This adaptive approach ensures stability, sustained performance, and reduced thermal stress compared to traditional static tuning methods.

---

## Core Features
### Universal Kernel Optimization
Adaptive kernel parameter tuning compatible with various Android versions and custom kernels.
### Dynamic CPU & GPU Clock Management
Real-time frequency scaling to improve sustained performance and reduce thermal throttling.
### Custom DVFS Rules
Userspace-controlled Dynamic Voltage and Frequency Scaling for fine-grained thermal and performance regulation.
### I/O Scheduler Optimization
Latency-aware queue tuning for better responsiveness under heavy workloads.
### Governor Optimization
Fine-tuned CPU governor parameters for smoother and more efficient scaling behavior.
### Networking AI Velocity
Adaptive networking stack tuning focused on latency consistency and throughput stability.

---

## Operational Modes
Velfox integrates a context-aware engine capable of automatically switching between three performance profiles:

### Esport Mode
- Sustained clock stability  
- FPS consistency  
- Reduced jitter  
- Gaming-focused performance scaling  
### Balanced Mode
- Optimized for daily usage  
- Responsive scaling behavior  
- Balanced power efficiency  
### Efficiency Mode
- Conservative frequency scaling  
- Optimized idle handling  
- Battery-focused strategy  

---

## Universal Tweaks Included
- Tx & Rx Network Optimization  
- Advanced TCP Stack Tuning  
- Kernel Panic Control Adjustment  
- CRF Optimization  
- Memory Optimization (VM & I/O tuning)  
- Kernel Log Noise Reduction  
- EAS Optimization  
- Scheduler Boost Control  
- Touch Responsiveness Tuning  
- Uclamp Optimization  
- CPU Priority Control  
- Foreground & Background Task Management  
- System & Service Priority Control  

---

## SOC Specific Optimizations
### Snapdragon
- CPU & GPU Frequency Control  
- DDR Frequency Control 
- DVFS Frequency Control
- Adreno Limiter Control  
### MediaTek
- CPU Frequency Control  
- FPSGO Optimization  
- CCI Tuning  
- DDR Boost  
- GED Optimization  
- Limiter Control  
### Exynos
- CPU Frequency Control  
- DRAM Optimization  
- Limiter Control  
### Unisoc
- CPU Frequency Control  
- GPU Optimization  
- Limiter Control  
### Tensor
- CPU Frequency Control  
- GPU Optimization  
- Limiter Control  

---

## Installation Guide
1. Download the Velfox Tweaks module (.zip).
2. Flash using:
   - Magisk  
   - KSU  
   - APatch  
3. Reboot the device to initialize the daemon.
4. Access the WebUI to configure performance profiles.

---

## 📋 Requirements
- Root access  
- Compatible Android kernel interfaces  
- Do **NOT** combine with other performance modules  

---

## ⚠️ Important Notes
- Do not stack multiple performance modules.  
- Avoid using other kernel tweak modules simultaneously.  
- Do not redistribute module files directly.  

---

## 👥 Credits
- Rem01Gaming — Encore Support  
- VelocityFox22 — Module Developer  
- RiProG — Technical Assistance  
- All Testers — Feedback & Validation  
