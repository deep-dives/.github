# Holtwood Forks

上游开源项目的研读副本，用于读源码、加注释和做对照实验。

维护者：[holtwood](https://github.com/holtwood)

## 这里放什么

这里没有原创项目。所有仓库都是上游项目的 fork，保留完整提交历史，随时可以和 upstream 对比。

读大型代码库时，光看不够：需要加注释、改一行看行为、跑最小复现。这些改动放在原创仓库里会和上游历史分叉，所以统一放在这里；改坏了直接重 fork。

原创项目在另外两个地方：

- [open-infra-ai](https://github.com/open-infra-ai)：AI Infra 系统实现与性能证据
- [holtwood-projects](https://github.com/holtwood-projects)：完整可运行的工具与教学项目

## LLM 推理与服务

| 仓库 | 上游 |
|------|------|
| [vllm](https://github.com/holtwood-forks/vllm) | vllm-project/vllm |
| [sglang](https://github.com/holtwood-forks/sglang) | sgl-project/sglang |
| [mini-sglang](https://github.com/holtwood-forks/mini-sglang) | sgl-project/mini-sglang |
| [nano-vllm](https://github.com/holtwood-forks/nano-vllm) | GeeeekExplorer/nano-vllm |
| [LightLLM](https://github.com/holtwood-forks/LightLLM) | ModelTC/LightLLM |
| [TensorRT-LLM](https://github.com/holtwood-forks/TensorRT-LLM) | NVIDIA/TensorRT-LLM |
| [LLM-Workshop](https://github.com/holtwood-forks/LLM-Workshop) | tylerelyt/LLM-Workshop |

## 注意力与算子

| 仓库 | 上游 |
|------|------|
| [flash-attention](https://github.com/holtwood-forks/flash-attention) | Dao-AILab/flash-attention |
| [flashinfer](https://github.com/holtwood-forks/flashinfer) | flashinfer-ai/flashinfer |
| [Triton-Puzzles](https://github.com/holtwood-forks/Triton-Puzzles) | gpu-mode/Triton-Puzzles |
| [extension-cpp](https://github.com/holtwood-forks/extension-cpp) | pytorch/extension-cpp |

## 编译器与运行时

| 仓库 | 上游 |
|------|------|
| [triton](https://github.com/holtwood-forks/triton) | triton-lang/triton |
| [tvm](https://github.com/holtwood-forks/tvm) | apache/tvm |
| [ompi](https://github.com/holtwood-forks/ompi) | open-mpi/ompi |

## CUDA 基础与课程

| 仓库 | 上游 |
|------|------|
| [cuda-samples](https://github.com/holtwood-forks/cuda-samples) | NVIDIA/cuda-samples |
| [cuda-course](https://github.com/holtwood-forks/cuda-course) | Infatoshi/cuda-course |
| [SGEMM_CUDA](https://github.com/holtwood-forks/SGEMM_CUDA) | siboehm/SGEMM_CUDA |
| [lectures](https://github.com/holtwood-forks/lectures) | gpu-mode/lectures |
| [dataflowr-notebooks](https://github.com/holtwood-forks/dataflowr-notebooks) | dataflowr/notebooks |
| [minGPT](https://github.com/holtwood-forks/minGPT) | karpathy/minGPT |
| [tutorials](https://github.com/holtwood-forks/tutorials) | triton-inference-server/tutorials |

## 约定

- 不改写上游历史：不 rebase、不 squash
- 实验改动只放在自己的分支，不推 upstream
- 版权与许可归原作者，各仓库保留原 LICENSE
