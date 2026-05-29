**Language / 语言:** [English](README.md) · [简体中文](README.zh.md)

# IO-AI.tech

**Bringing robots everywhere, for everyone.**

[Website](https://io-ai.tech) · [LinkedIn](https://www.linkedin.com/company/io-ai-tech/) · [YouTube](https://www.youtube.com/@IO-AITech) · [Hugging Face](https://huggingface.co/io-intelligence) · [Contact](mailto:io@io-ai.tech)

---

IO-AI Tech develops data infrastructure for real-world robotics and embodied AI applications.

Founded in 2023, we build integrated hardware and software for scalable, high-quality training data — from teleoperation capture to annotation, visualization, and model-ready exports.

**Headquarters:** Shenzhen, China · **Offices:** Osaka, Singapore, Sydney, San Francisco Bay Area

---

## Products

Our commercial platforms power end-to-end embodied AI workflows. Documentation lives on our website:

| Product | Description | Docs |
|---------|-------------|------|
| **TeleXperience** | General robot teleoperation platform for humanoids, arms, and dexterous hands | [English](https://io-ai.tech/en/telexperience/) · [中文](https://io-ai.tech/zh/telexperience/) |
| **SenseXperience** | Real-world human data capture — egocentric, UMI, full-body mocap | [English](https://io-ai.tech/en/sensexperience/) · [中文](https://io-ai.tech/zh/sensexperience/) |
| **EmbodiFlow** | Embodied AI data platform — collection, annotation, QA, LeRobot export | [English](https://io-ai.tech/en/embodiflow/) · [中文](https://io-ai.tech/zh/embodiflow/) |

---

## Featured open source

Community projects we actively maintain and recommend starting with:

### [rosview](https://github.com/ioai-tech/rosview) · [Live demo →](https://rosview.com)

Browser-native visualization for embodied intelligence data. Supports **MCAP**, **ROS 1 bag**, **ROS 2 db3**, **HDF5**, and **BVH** — available as [rosview.com](https://rosview.com) or the [`@ioai/rosview`](https://www.npmjs.com/package/@ioai/rosview) npm package.

### [ioenv_cli](https://github.com/ioai-tech/ioenv_cli)

Minimal CLI to run prebuilt Docker images for robotics development (GPU + X11). [Setup guide →](https://io-ai.tech/iocreed/en/docs/locomotion_00/)

### [data_example](https://github.com/ioai-tech/data_example)

Python examples to load and visualize IO-AI datasets.

### [io_dev_tools_ros2](https://github.com/ioai-tech/io_dev_tools_ros2)

ROS 2 developer tooling for IO-AI embodied data workflows.

### [io_msgs](https://github.com/ioai-tech/io_msgs) / [io_msgs2](https://github.com/ioai-tech/io_msgs2)

ROS 1 and ROS 2 message definitions used across IO-AI stacks.

### Ecosystem libraries

| Repository | Description |
|------------|-------------|
| [wasm-hdf5](https://github.com/ioai-tech/wasm-hdf5) | WebAssembly HDF5 reader (powers ROSView in the browser) |
| [wasm-zstd](https://github.com/ioai-tech/wasm-zstd) | Vite-friendly zstd WebAssembly adapter *(fork)* |
| [jointstate2tf](https://github.com/ioai-tech/jointstate2tf) | JointState → TF from URDF (TypeScript, Node/Browser) |
| [io_eai_simulation](https://github.com/ioai-tech/io_eai_simulation) | Low-cost, high-fidelity embodied AI simulation environment |
| [pytorch_rt1_with_trainer_and_tester](https://github.com/ioai-tech/pytorch_rt1_with_trainer_and_tester) | RT-1 PyTorch reimplementation with training pipeline *(fork)* |

---

## All repositories

<details open>
<summary><strong>Data &amp; visualization</strong></summary>

| Repository | Description |
|------------|-------------|
| [rosview](https://github.com/ioai-tech/rosview) | Browser-native embodied AI data visualization |
| [data_example](https://github.com/ioai-tech/data_example) | Load and visualize IO-AI datasets (Python) |
| [IO-DATA-VISUALIZATION](https://github.com/ioai-tech/IO-DATA-VISUALIZATION) | C++ visualization utilities for IO-AI data |
| [IO-ULTRA-EMBODIMENT-DATASET-DOC](https://github.com/ioai-tech/IO-ULTRA-EMBODIMENT-DATASET-DOC) | IO Ultra Embodiment Dataset documentation |
| [wasm-hdf5](https://github.com/ioai-tech/wasm-hdf5) | WebAssembly HDF5 reader |
| [wasm-zstd](https://github.com/ioai-tech/wasm-zstd) | zstd WebAssembly adapter *(fork)* |

</details>

<details>
<summary><strong>ROS &amp; robotics middleware</strong></summary>

| Repository | Description |
|------------|-------------|
| [io_msgs](https://github.com/ioai-tech/io_msgs) | ROS 1 message definitions |
| [io_msgs2](https://github.com/ioai-tech/io_msgs2) | ROS 2 message definitions |
| [io_dev_tools_ros2](https://github.com/ioai-tech/io_dev_tools_ros2) | ROS 2 developer tooling |
| [ros_babel_fish](https://github.com/ioai-tech/ros_babel_fish) | ROS 2 runtime message introspection *(fork)* |
| [audio_common](https://github.com/ioai-tech/audio_common) | Audio utilities for ROS *(fork)* |
| [respeaker_ros](https://github.com/ioai-tech/respeaker_ros) | Respeaker mic array ROS package *(fork)* |
| [TeleXperience_robot_ros1_ws](https://github.com/ioai-tech/TeleXperience_robot_ros1_ws) | TeleXperience ROS 1 workspace |
| [jointstate2tf](https://github.com/ioai-tech/jointstate2tf) | JointState to TF from URDF (TypeScript) |

</details>

<details>
<summary><strong>Mocap &amp; teleoperation</strong></summary>

| Repository | Description |
|------------|-------------|
| [io_mocap_visualization](https://github.com/ioai-tech/io_mocap_visualization) | IO-Mocap visualization for ROS 2 |
| [io_mocap_visualization_ros1](https://github.com/ioai-tech/io_mocap_visualization_ros1) | IO-Mocap visualization for ROS 1 |
| [io_ee_pose_process](https://github.com/ioai-tech/io_ee_pose_process) | End-effector pose processing utilities |

</details>

<details>
<summary><strong>Simulation &amp; training</strong></summary>

| Repository | Description |
|------------|-------------|
| [io_eai_simulation](https://github.com/ioai-tech/io_eai_simulation) | Embodied AI simulation environment |
| [ioenv_cli](https://github.com/ioai-tech/ioenv_cli) | Docker-based robotics dev environments |
| [train_openpi](https://github.com/ioai-tech/train_openpi) | OpenPI training scripts and configs |
| [lerobot](https://github.com/ioai-tech/lerobot) | LeRobot end-to-end robot learning *(fork)* |
| [pytorch_rt1_with_trainer_and_tester](https://github.com/ioai-tech/pytorch_rt1_with_trainer_and_tester) | RT-1 PyTorch training pipeline *(fork)* |
| [IO-ACT](https://github.com/ioai-tech/IO-ACT) | Action-chunking policy tooling for embodied AI |
| [rlds_dataset_builder](https://github.com/ioai-tech/rlds_dataset_builder) | RLDS dataset builder example *(fork)* |

</details>

<details>
<summary><strong>Humanoid &amp; control stack</strong></summary>

| Repository | Description |
|------------|-------------|
| [humanoid_controller](https://github.com/ioai-tech/humanoid_controller) | Humanoid low-level control |
| [robot_description](https://github.com/ioai-tech/robot_description) | URDF and robot description assets |
| [robot_sdk](https://github.com/ioai-tech/robot_sdk) | Robot hardware integration SDK |
| [robot_hardware_interface](https://github.com/ioai-tech/robot_hardware_interface) | Hardware abstraction layer |
| [onnx_policy](https://github.com/ioai-tech/onnx_policy) | ONNX policy deployment for control |
| [io_gripper_sdk](https://github.com/ioai-tech/io_gripper_sdk) | IO gripper SDK |
| [OpenLoong_descriptions](https://github.com/ioai-tech/OpenLoong_descriptions) | OpenLoong robot description models |

</details>

<details>
<summary><strong>Infrastructure</strong></summary>

| Repository | Description |
|------------|-------------|
| [docker-images](https://github.com/ioai-tech/docker-images) | Docker images for LeRobot and OpenPI |

</details>

<details>
<summary><strong>Embedded &amp; hardware</strong></summary>

| Repository | Description |
|------------|-------------|
| [iomove-hub-bootloader](https://github.com/ioai-tech/iomove-hub-bootloader) | IO-Move hub bootloader firmware |
| [iomove-edge-bootloader](https://github.com/ioai-tech/iomove-edge-bootloader) | IO-Move edge bootloader firmware |
| [iap-master-app](https://github.com/ioai-tech/iap-master-app) | In-application programming master app |

</details>

<details>
<summary><strong>Other</strong></summary>

| Repository | Description |
|------------|-------------|
| [algo_test](https://github.com/ioai-tech/algo_test) | Algorithm experiment sandbox |
| [ioai-tech.github.io](https://github.com/ioai-tech/ioai-tech.github.io) | Legacy GitHub Pages scaffold (inactive) |

</details>

[View all repositories →](https://github.com/orgs/ioai-tech/repositories)

---

## Get involved

- **Bug reports & features:** open an issue in the relevant repository
- **Contributing:** see [CONTRIBUTING.md](../CONTRIBUTING.md) and per-repo guides (e.g. [rosview](https://github.com/ioai-tech/rosview/blob/main/CONTRIBUTING.md))
- **Security:** see [SECURITY.md](../SECURITY.md) — please email [io@io-ai.tech](mailto:io@io-ai.tech) for vulnerabilities
- **Careers:** [io-ai.tech/careers](https://io-ai.tech/en/careers/)
- **Business & partnerships:** [io@io-ai.tech](mailto:io@io-ai.tech)

---

<sub>Each repository is licensed independently. Forks are marked above and track their upstream projects.</sub>

<sub>Last updated: May 2026</sub>
