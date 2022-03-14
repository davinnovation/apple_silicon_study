# apple_silicon_study

## Basics
- Apple Silicon Software Development : https://developer.apple.com/documentation/apple-silicon
- AArch64 Architecture/Instruction Set : https://developer.arm.com/documentation/ddi0487/latest, https://developer.arm.com/documentation/102374/latest/

## Accelerating : https://developer.apple.com/documentation/accelerate

### BNNS : https://developer.apple.com/documentation/accelerate/bnns
- CPU based Neural Network acceleartor

### Metal
- Metal : https://developer.apple.com/documentation/metal
- Metal Performance Shaders : https://developer.apple.com/documentation/metalperformanceshaders
- Metal Performance Shaders Graph : https://developer.apple.com/documentation/metalperformanceshadersgraph
- MetalKit : https://developer.apple.com/documentation/metalkit

## Neural Engine (Not Opened)
- Core ML use neural engine partially : https://developer.apple.com/documentation/coreml
- Looks CNN optimized chip : https://github.com/geohot/tinygrad/tree/master/accel/ane

## Helpful Tools
- Reverse Engineering Tool : https://github.com/rizinorg/cutter
- Silicon ARMv8.5-A assembly programming : https://github.com/below/HelloSilicon
- Accelerate ML with Metal Performance Shaders : https://developer.apple.com/videos/play/wwdc2021/10152/
- MPSCNN based un-official neural network toolkit : https://github.com/hollance/Forge
- Apple Silicon Guide : https://github.com/mikeroyal/Apple-Silicon-Guide
- Roblox Metal usage story : https://blog.roblox.com/ko/2020/07/metal%EA%B3%BC-%ED%95%A8%EA%BB%98%ED%95%9C-3%EB%85%84/
- C based Neural Network : https://github.com/pjreddie/darknet
- Apple silicon system architecture : https://developer.apple.com/videos/play/wwdc2020/10686/
- book of 64-Bit ARM Assembly Language : https://www.amazon.com/Programming-64-Bit-ARM-Assembly-Language/dp/1484258800
- Triggering Apple Neural Engine from C++ : https://www.youtube.com/watch?v=JAyw7OAcXDE
- Apple Neural Engine & Metal Performacne Shader backend : tinygrad : https://github.com/geohot/tinygrad
- Anaylsis of Apple Neural Network : https://github.com/hollance/neural-engine
- breakdown AI Chips : https://geohot.github.io/blog/jekyll/update/2021/06/13/a-breakdown-of-ai-chip-companies.html
- M1 CPU study : https://ieeexplore.ieee.org/abstract/document/9696024
- M1 System report : https://www.systemplus.fr/wp-content/uploads/2020/12/SP20608-Apple-M1-System-on-Chip-Sample.pdf
- M1 Overview : https://gts3.org/blog/apple-m1/apple-m1-overview.pdf
- M1 Explainer : https://twitter.com/handleym99/status/1437537535018684417
- M1 Benchmark : https://www.anandtech.com/show/17024/apple-m1-max-performance-review/5
- Tensorflow benchmark : https://github.com/tlkh/tf-metal-experiments

## Good to know
- What is CoreML? : https://developer.apple.com/documentation/coreml
  ![image](https://user-images.githubusercontent.com/3917185/157598219-66ca0da4-34f1-4576-83ba-02a8c0b8b834.png)
  - Wrapper of BNNS (CPU) and MPS (GPU)

- TensorFlow-metal is based on MPS/MPSGraph : https://developer.apple.com/forums/thread/693944
