**Language / 语言:** [English](README.md) · [简体中文](README.zh.md)

# IO-AI.tech · 艾欧智能

**Bringing robots everywhere, for everyone.**  
**让机器人走进千行百业、服务每一个人。**

[官网](https://io-ai.tech) · [LinkedIn](https://www.linkedin.com/company/io-ai-tech/) · [YouTube](https://www.youtube.com/@IO-AITech) · [Hugging Face](https://huggingface.co/io-intelligence) · [联系](mailto:io@io-ai.tech)

---

艾欧智能（IO-AI Tech）成立于 2023 年，聚焦**真实世界机器人与具身智能数据基础设施**。基于自研软硬件一体化平台，我们提供可扩展、高质量、可定制的训练数据能力，覆盖遥操作采集、标注、可视化到可训练格式导出，支撑 Physical AI 的研发与落地。

**总部：** 中国深圳 · **办公室：** 大阪、新加坡、悉尼、旧金山湾区

---

## 产品

商业产品文档见官网：

| 产品 | 说明 | 文档 |
|------|------|------|
| **TeleXperience** | 通用机器人遥操作平台，支持人形、机械臂、灵巧手 | [中文](https://io-ai.tech/zh/telexperience/) · [English](https://io-ai.tech/en/telexperience/) |
| **SenseXperience** | 真实世界人体数据采集 — 第一视角、UMI、全身动捕 | [中文](https://io-ai.tech/zh/sensexperience/) · [English](https://io-ai.tech/en/sensexperience/) |
| **EmbodiFlow** | 具身智能数据平台 — 采集、标注、质检、LeRobot 导出 | [中文](https://io-ai.tech/zh/embodiflow/) · [English](https://io-ai.tech/en/embodiflow/) |

---

## 重点开源项目

建议从以下仓库开始：

### [rosview](https://github.com/ioai-tech/rosview) · [在线体验 →](https://rosview.com)

面向具身智能数据的**浏览器原生**可视化工具。支持 **MCAP**、**ROS 1 bag**、**ROS 2 db3**、**HDF5**、**BVH** — 可直接访问 [rosview.com](https://rosview.com)，或通过 npm 包 [`@ioai/rosview`](https://www.npmjs.com/package/@ioai/rosview) 嵌入应用。

### [ioenv_cli](https://github.com/ioai-tech/ioenv_cli)

基于 Docker 的机器人开发环境 CLI（GPU + X11）。[安装教程 →](https://io-ai.tech/iocreed/zh/docs/locomotion_00/)

### [data_example](https://github.com/ioai-tech/data_example)

使用 Python 加载与可视化 IO-AI 数据集的示例代码。

### [io_dev_tools_ros2](https://github.com/ioai-tech/io_dev_tools_ros2)

面向 IO-AI 具身数据工作流的 ROS 2 开发工具。

### [io_msgs](https://github.com/ioai-tech/io_msgs) / [io_msgs2](https://github.com/ioai-tech/io_msgs2)

IO-AI 技术栈使用的 ROS 1 / ROS 2 消息定义。

### 生态库

| 仓库 | 说明 |
|------|------|
| [wasm-hdf5](https://github.com/ioai-tech/wasm-hdf5) | WebAssembly HDF5 读取（ROSView 浏览器端依赖） |
| [wasm-zstd](https://github.com/ioai-tech/wasm-zstd) | Vite 友好的 zstd WebAssembly 适配 *(fork)* |
| [jointstate2tf](https://github.com/ioai-tech/jointstate2tf) | 从 URDF 将 JointState 转为 TF（TypeScript） |
| [io_eai_simulation](https://github.com/ioai-tech/io_eai_simulation) | 低成本、高保真具身智能仿真环境 |
| [pytorch_rt1_with_trainer_and_tester](https://github.com/ioai-tech/pytorch_rt1_with_trainer_and_tester) | RT-1 PyTorch 复现及训练流程 *(fork)* |

---

## 全部仓库

<details open>
<summary><strong>数据与可视化</strong></summary>

| 仓库 | 说明 |
|------|------|
| [rosview](https://github.com/ioai-tech/rosview) | 具身智能数据浏览器可视化 |
| [data_example](https://github.com/ioai-tech/data_example) | IO-AI 数据集加载与可视化（Python） |
| [IO-DATA-VISUALIZATION](https://github.com/ioai-tech/IO-DATA-VISUALIZATION) | IO-AI 数据 C++ 可视化工具 |
| [IO-ULTRA-EMBODIMENT-DATASET-DOC](https://github.com/ioai-tech/IO-ULTRA-EMBODIMENT-DATASET-DOC) | IO Ultra 具身数据集文档 |
| [wasm-hdf5](https://github.com/ioai-tech/wasm-hdf5) | WebAssembly HDF5 读取库 |
| [wasm-zstd](https://github.com/ioai-tech/wasm-zstd) | zstd WebAssembly 适配 *(fork)* |

</details>

<details>
<summary><strong>ROS 与机器人中间件</strong></summary>

| 仓库 | 说明 |
|------|------|
| [io_msgs](https://github.com/ioai-tech/io_msgs) | ROS 1 消息定义 |
| [io_msgs2](https://github.com/ioai-tech/io_msgs2) | ROS 2 消息定义 |
| [io_dev_tools_ros2](https://github.com/ioai-tech/io_dev_tools_ros2) | ROS 2 开发工具 |
| [ros_babel_fish](https://github.com/ioai-tech/ros_babel_fish) | ROS 2 运行时消息内省 *(fork)* |
| [audio_common](https://github.com/ioai-tech/audio_common) | ROS 音频通用库 *(fork)* |
| [respeaker_ros](https://github.com/ioai-tech/respeaker_ros) | Respeaker 麦克风阵列 ROS 包 *(fork)* |
| [TeleXperience_robot_ros1_ws](https://github.com/ioai-tech/TeleXperience_robot_ros1_ws) | TeleXperience ROS 1 工作空间 |
| [jointstate2tf](https://github.com/ioai-tech/jointstate2tf) | JointState 转 TF（TypeScript） |

</details>

<details>
<summary><strong>动捕与遥操作</strong></summary>

| 仓库 | 说明 |
|------|------|
| [io_mocap_visualization](https://github.com/ioai-tech/io_mocap_visualization) | IO-Mocap ROS 2 可视化 |
| [io_mocap_visualization_ros1](https://github.com/ioai-tech/io_mocap_visualization_ros1) | IO-Mocap ROS 1 可视化 |
| [io_ee_pose_process](https://github.com/ioai-tech/io_ee_pose_process) | 末端执行器位姿处理工具 |

</details>

<details>
<summary><strong>仿真与训练</strong></summary>

| 仓库 | 说明 |
|------|------|
| [io_eai_simulation](https://github.com/ioai-tech/io_eai_simulation) | 具身智能仿真环境 |
| [ioenv_cli](https://github.com/ioai-tech/ioenv_cli) | Docker 机器人开发环境 CLI |
| [train_openpi](https://github.com/ioai-tech/train_openpi) | OpenPI 训练脚本与配置 |
| [lerobot](https://github.com/ioai-tech/lerobot) | LeRobot 端到端机器人学习 *(fork)* |
| [pytorch_rt1_with_trainer_and_tester](https://github.com/ioai-tech/pytorch_rt1_with_trainer_and_tester) | RT-1 PyTorch 训练流程 *(fork)* |
| [IO-ACT](https://github.com/ioai-tech/IO-ACT) | 具身智能 action-chunking 策略工具 |
| [rlds_dataset_builder](https://github.com/ioai-tech/rlds_dataset_builder) | RLDS 数据集构建示例 *(fork)* |

</details>

<details>
<summary><strong>人形与控制栈</strong></summary>

| 仓库 | 说明 |
|------|------|
| [humanoid_controller](https://github.com/ioai-tech/humanoid_controller) | 人形机器人底层控制 |
| [robot_description](https://github.com/ioai-tech/robot_description) | URDF 与机器人描述资产 |
| [robot_sdk](https://github.com/ioai-tech/robot_sdk) | 机器人硬件集成 SDK |
| [robot_hardware_interface](https://github.com/ioai-tech/robot_hardware_interface) | 硬件抽象层 |
| [onnx_policy](https://github.com/ioai-tech/onnx_policy) | ONNX 策略部署 |
| [io_gripper_sdk](https://github.com/ioai-tech/io_gripper_sdk) | IO 夹爪 SDK |
| [OpenLoong_descriptions](https://github.com/ioai-tech/OpenLoong_descriptions) | 青龙（OpenLoong）机器人描述模型 |

</details>

<details>
<summary><strong>基础设施</strong></summary>

| 仓库 | 说明 |
|------|------|
| [docker-images](https://github.com/ioai-tech/docker-images) | LeRobot 与 OpenPI 用 Docker 镜像 |

</details>

<details>
<summary><strong>嵌入式与硬件</strong></summary>

| 仓库 | 说明 |
|------|------|
| [iomove-hub-bootloader](https://github.com/ioai-tech/iomove-hub-bootloader) | IO-Move Hub 引导加载程序 |
| [iomove-edge-bootloader](https://github.com/ioai-tech/iomove-edge-bootloader) | IO-Move Edge 引导加载程序 |
| [iap-master-app](https://github.com/ioai-tech/iap-master-app) | 在应用编程（IAP）主控程序 |

</details>

<details>
<summary><strong>其他</strong></summary>

| 仓库 | 说明 |
|------|------|
| [algo_test](https://github.com/ioai-tech/algo_test) | 算法实验沙箱 |
| [ioai-tech.github.io](https://github.com/ioai-tech/ioai-tech.github.io) | 历史 GitHub Pages 脚手架（未启用） |

</details>

[查看全部仓库 →](https://github.com/orgs/ioai-tech/repositories)

---

## 参与贡献

- **问题与功能建议：** 在对应仓库提交 Issue
- **贡献代码：** 见 [CONTRIBUTING.md](../CONTRIBUTING.md) 及各仓库指南（如 [rosview](https://github.com/ioai-tech/rosview/blob/main/CONTRIBUTING.md)）
- **安全披露：** 见 [SECURITY.md](../SECURITY.md) — 漏洞请邮件 [io@io-ai.tech](mailto:io@io-ai.tech)
- **加入我们：** [io-ai.tech/careers](https://io-ai.tech/zh/careers/)
- **商务合作：** [io@io-ai.tech](mailto:io@io-ai.tech)

---

<sub>各仓库采用独立许可证。标注 *(fork)* 的仓库跟踪上游项目。</sub>

<sub>最后更新：2026 年 5 月</sub>
