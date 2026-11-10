# mi300x-notes

MI300X 上跑大模型推理的实验笔记。

## 计划

- 在 AMD MI300X（192GB HBM3）上用 ROCm 跑 vLLM，测 Qwen3-70B 推理速度
- 对比 FP16 和 AWQ 量化的显存占用
- 部署 ComfyUI，跑 Flux / Wan 2.2 文生视频

## 环境

- GPU: AMD Instinct MI300X
- 框架：ROCm 7.x + vLLM / SGLang
- 工具：ComfyUI（ROCm 官方镜像）