# Holtwood Forks

上游开源项目的 fork 集合，分为两类：**研读副本**（读源码、加注释、做对照实验）与
**自用 fork**（本地化、日常工具，改动只留在自己的分支）。

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

## 自用与汉化 fork

不用于研读，只为自己跑得舒服；与上面两组学习向副本分开看。

| 仓库 | 上游 | 说明 |
|------|------|------|
| [Termius-Pro-zh_CN](https://github.com/holtwood-forks/Termius-Pro-zh_CN) | ArcSurge/Termius-Pro-zh_CN | Termius 汉化中文包 |
| [DLX](https://github.com/holtwood-forks/DLX) | OwO-Network/DLX | 自建翻译 API 服务 |
| [axonhub](https://github.com/holtwood-forks/axonhub) | looplj/axonhub | 开源 AI Gateway（多模型统一接入） |
| [massCode](https://github.com/holtwood-forks/massCode) | massCodeIO/massCode | 开发者工作区（片段/笔记/HTTP 请求） |
| [Clay](https://github.com/holtwood-forks/Clay) | chaun-yi7/Clay | Typora 主题（仿 Claude 配色） |
| [gpt6-astra-one-shot-games](https://github.com/holtwood-forks/gpt6-astra-one-shot-games) | Ayi1337/gpt6-astra-one-shot-games | GPT-6 Astra One Shot 小游戏合集 |
| [fruit-ninja-dojo](https://github.com/holtwood-forks/fruit-ninja-dojo) | yongqixue99-hue/fruit-ninja-dojo | 原生 Canvas 水果忍者小游戏 |
| [patch-devin](https://github.com/holtwood-forks/patch-devin) | a0yark/patch-devin | Devin CLI 系统提示词补丁工具 |
| [web_search_devin](https://github.com/holtwood-forks/web_search_devin) | mimimaster/windsurf-search-mcp | Devin 服务端 Web 搜索 MCP 服务器 |

## 约定

- 不改写上游历史：不 rebase、不 squash
- 实验改动只放在自己的分支，不推 upstream
- 版权与许可归原作者，各仓库保留原 LICENSE
