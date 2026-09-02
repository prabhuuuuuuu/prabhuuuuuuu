<h1 align="center">
  <code style="color:#00ff41; font-size:2.2em;">PHYSICAL_AI_UNIT_v2.6.0-rc1</code>
</h1>
<h1 align="center">
  <code style="color:#ff00ff; font-size:1.8em; font-family:monospace;">0x505241424855_50524156</code>
  <br>
  <code style="color:#00ffff; font-size:0.7em;">[ EDGE • AUTONOMY • EMBODIED INTELLIGENCE ]</code>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/FIRMWARE-2.6.0--rc1-00ff41?style=for-the-badge&logo=git&logoColor=00ff41&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/ARCH-x86_64%20%7C%20ARM64-ff00ff?style=for-the-badge&logo=linux&logoColor=ff00ff&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/NODE-VIT_CHENNAI-00ffff?style=for-the-badge&logo=serverfault&logoColor=00ffff&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/STATUS-OPERATIONAL-00ff41?style=for-the-badge&labelColor=0a0a0a" />
</p>

<pre style="background:#0a0a0f; border:1px solid #6C63FF; border-radius:4px; padding:16px; color:#00ff41; font-family:monospace; font-size:0.85em; overflow:auto;">
<code>>>> BOOT SEQUENCE INITIATED
> KERNEL: Linux 6.8.0-rt (PREEMPT_RT)
> CORES: 16 LOGICAL | 8 PHYSICAL @ 4.2GHz
> MEM: 32GiB DDR5-5600 ECC
> NPU: 2x MEMRYX MX3 @ 10 TOPS ea.
> GPU: RTX 4070 12GB | Jetson Orin 64GB (EDGE)
> STORAGE: 2TB NVMe Gen4 + 512GB UFS 4.0
> NET: 2.5GbE + WiFi 7 + 5G NR mmWave
> SENSORS: IMU(9-DOF) | LiDAR(128-ch) | RGB-D | EVENT_CAM
> ACTUATORS: 6-DOF ARM | DIFF_DRIVE BASE | GRIPPER FORCE_CTRL
> RTOS: Zephyr RTOS v3.6 | FreeRTOS SMP
> COMMS: ROS2 Humble | DDS | gRPC | WebRTC | MQTT
> SECURE_BOOT: ENABLED | TPM 2.0 | MEASURED_BOOT
>>> ALL SUBSYSTEMS NOMINAL
>>> NEURAL PIPELINES: LOADED
>>> CONTROL LOOPS: 1kHz REAL-TIME
>>> AUTONOMY STACK: ENGAGED</code>
</pre>

<h2 align="center" style="color:#6C63FF; font-family:monospace; border-top:1px solid #6C63FF; border-bottom:1px solid #6C63FF; padding:8px;">
  ═══ NEURAL REGISTRY ═══
</h2>

<table align="center" style="border-collapse:collapse; font-family:monospace; font-size:0.85em;">
<tr>
  <td style="color:#00ff41; padding:4px 12px;">VISION_CORE</td>
  <td style="color:#00ffff; padding:4px 12px;">YOLOv8x-seg | ViT-L/14 | DETR | Mask2Former | SAM2 | DepthAnything</td>
</tr>
<tr style="background:#111118;">
  <td style="color:#00ff41; padding:4px 12px;">TRACKING_ENGINE</td>
  <td style="color:#00ffff; padding:4px 12px;">StrongSORT++ | BoT-SORT | ByteTrack | OC-SORT | DeepEIoU</td>
</tr>
<tr>
  <td style="color:#00ff41; padding:4px 12px;">GEN_AI</td>
  <td style="color:#00ffff; padding:4px 12px;">SDXL-Turbo | Flux.1 | LLaVA-NeXT | Phi-3-Vision | Gemma-2-27B</td>
</tr>
<tr style="background:#111118;">
  <td style="color:#00ff41; padding:4px 12px;">RL_POLICY</td>
  <td style="color:#00ffff; padding:4px 12px;">PPO | SAC | TD3 | DreamerV3 | RSL-RL | Isaac Lab</td>
</tr>
<tr>
  <td style="color:#00ff41; padding:4px 12px;">EDGE_RUNTIME</td>
  <td style="color:#00ffff; padding:4px 12px;">TensorRT 10 | ONNX Runtime | TFLite | OpenVINO | ExecuTorch | MNN</td>
</tr>
<tr style="background:#111118;">
  <td style="color:#00ff41; padding:4px 12px;">SIM2REAL</td>
  <td style="color:#00ffff; padding:4px 12px;">Isaac Sim | MuJoCo | Genesis | Habitat 3.0 | CARLA | AirSim</td>
</tr>
</table>

<h2 align="center" style="color:#ff00ff; font-family:monospace; border-top:1px solid #ff00ff; border-bottom:1px solid #ff00ff; padding:8px;">
  ═══ INSTRUCTION SET ═══
</h2>

<p align="center" style="font-family:monospace; color:#00ff41; font-size:0.9em; letter-spacing:1px;">
  <code>PYTHON</code> ▸ <code>C++17/20</code> ▸ <code>RUST</code> ▸ <code>CUDA</code> ▸ <code>GLSL</code> ▸ <code>SQL</code> ▸ <code>BASH</code>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,rust,cuda,git,github,docker,linux,raspberrypi,aws,redis,postgres,mongodb,nginx&theme=dark&perline=10" />
</p>

<h2 align="center" style="color:#00ffff; font-family:monospace; border-top:1px solid #00ffff; border-bottom:1px solid #00ffff; padding:8px;">
  ═══ DEPLOYMENT MATRIX ═══
</h2>

<table align="center" style="border-collapse:collapse; font-family:monospace; font-size:0.8em;">
<tr style="color:#6C63FF;">
  <th style="padding:6px 16px; text-align:left;">TARGET</th>
  <th style="padding:6px 16px; text-align:left;">RUNTIME</th>
  <th style="padding:6px 16px; text-align:left;">MODEL_ZOO</th>
  <th style="padding:6px 16px; text-align:left;">LATENCY</th>
</tr>
<tr style="background:#111118; color:#00ffff;">
  <td style="padding:6px 16px;">MEMRYX MX3</td>
  <td style="padding:6px 16px;">MX SDK | ONNX</td>
  <td style="padding:6px 16px;">YOLOv8n | MobileNetV4 | EfficientViT</td>
  <td style="padding:6px 16px; color:#00ff41;"><2ms @ 30FPS</td>
</tr>
<tr style="color:#00ffff;">
  <td style="padding:6px 16px;">JETSON ORIN NX</td>
  <td style="padding:6px 16px;">TensorRT | DeepStream</td>
  <td style="padding:6px 16px;">YOLOv8x | DETR | BEVFormer</td>
  <td style="padding:6px 16px; color:#00ff41;"><15ms @ 60FPS</td>
</tr>
<tr style="background:#111118; color:#00ffff;">
  <td style="padding:6px 16px;">RPI 5 + HAILO-8</td>
  <td style="padding:6px 16px;">HailoRT | TFLite</td>
  <td style="padding:6px 16px;">YOLOv8s | PoseEst | Depth</td>
  <td style="padding:6px 16px; color:#00ff41;"><10ms @ 30FPS</td>
</tr>
<tr style="color:#00ffff;">
  <td style="padding:6px 16px;">STM32H7 / ESP32-S3</td>
  <td style="padding:6px 16px;">STM32Cube.AI | ESP-DL</td>
  <td style="padding:6px 16px;">TinyML | KeywordSpot | AnomalyDet</td>
  <td style="padding:6px 16px; color:#00ff41;"><5ms @ 100Hz</td>
</tr>
</table>

<h2 align="center" style="color:#6C63FF; font-family:monospace; border-top:1px solid #6C63FF; border-bottom:1px solid #6C63FF; padding:8px;">
  ═══ MISSION LOG ═══
</h2>

<table align="center" style="border-collapse:collapse; font-family:monospace; font-size:0.8em;">
<tr style="color:#ff00ff;">
  <th style="padding:6px 12px;">PROJECT</th>
  <th style="padding:6px 12px;">DOMAIN</th>
  <th style="padding:6px 12px;">STACK</th>
  <th style="padding:6px 12px;">STATUS</th>
</tr>
<tr style="background:#111118; color:#00ffff;">
  <td style="padding:6px 12px;"><code>AUTO_NAV_v3</code></td>
  <td style="padding:6px 12px;">End-to-End Driving</td>
  <td style="padding:6px 12px;">BEVFormer + RL Policy + Isaac Sim</td>
  <td style="padding:6px 12px; color:#00ff41;">DEPLOYED</td>
</tr>
<tr style="color:#00ffff;">
  <td style="padding:6px 12px;"><code>MANIPULATOR_GRASP</code></td>
  <td style="padding:6px 12px;">6-DOF Dex Manipulation</td>
  <td style="padding:6px 12px;">Foundation Policy + Force Control</td>
  <td style="padding:6px 12px; color:#ff00ff;">TRAINING</td>
</tr>
<tr style="background:#111118; color:#00ffff;">
  <td style="padding:6px 12px;"><code>SWARM_COORD</code></td>
  <td style="padding:6px 12px;">Multi-Agent RL</td>
  <td style="padding:6px 12px;">MAPPO + CommNet + ROS2</td>
  <td style="padding:6px 12px; color:#00ff41;">SIM_VALIDATED</td>
</tr>
<tr style="color:#00ffff;">
  <td style="padding:6px 12px;"><code>EVENT_VISION_ODOM</code></td>
  <td style="padding:6px 12px;">Neuromorphic SLAM</td>
  <td style="padding:6px 12px;">EV-FlowNet + Spiking NN</td>
  <td style="padding:6px 12px; color:#ff00ff;">R&D</td>
</tr>
</table>

<h2 align="center" style="color:#ff00ff; font-family:monospace; border-top:1px solid #ff00ff; border-bottom:1px solid #ff00ff; padding:8px;">
  ═══ TELEMETRY ═══
</h2>

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=prabhuuuuuuu&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0a0a0f&title_color=00ff41&icon_color=ff00ff&text_color=00ffff&border_color=6C63FF&custom_title=CORE_REGISTERS" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prabhuuuuuuu&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0a0a0f&title_color=00ff41&text_color=00ffff&border_color=6C63FF&custom_title=INSTRUCTION_MIX" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=prabhuuuuuuu&theme=chartreuse-dark&hide_border=true&background=0a0a0f&ring=00ff41&fire=ff00ff&currStreakLabel=00ffff&sideNums=00ffff&sideLabels=00ffff&custom_title=UPTIME_CYCLES" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prabhuuuuuuu&theme=github-dark&hide_border=true&bg_color=0a0a0f&color=00ff41&line=ff00ff&point=00ffff&area=true&area_color=6C63FF&custom_title=EXECUTION_TRACE" />
</p>

<pre style="background:#0a0a0f; border:1px solid #6C63FF; border-radius:4px; padding:16px; color:#00ff41; font-family:monospace; font-size:0.8em; text-align:center;">
<code>██████╗ ███████╗███████╗████████╗ █████╗ ███╗   ██╗
██╔══██╗██╔════╝██╔════╝╚══██╔══╝██╔══██╗████╗  ██║
██████╔╝█████╗  █████╗     ██║   ███████║██╔██╗ ██║
██╔══██╗██╔══╝  ██╔══╝     ██║   ██╔══██║██║╚██╗██║
██║  ██║███████╗███████╗   ██║   ██║  ██║██║ ╚████║
╚═╝  ╚═╝╚══════╝╚══════╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝
              PHYSICAL AI UNIT ONLINE
                    ▓▓▓▓▓▓▓▓▓▓ 100%
              AWAITING TASK VECTOR...
              [CONNECT] [SYNC] [DEPLOY] [EVOLVE]</code>
</pre>

<p align="center">
  <a href="https://pranavprashantshewale.vercel.app"><img src="https://img.shields.io/badge/▸_PORTAL-6C63FF?style=for-the-badge&labelColor=0a0a0a&logo=vercel&logoColor=white" /></a>
  <a href="https://x.com/pra_bhuu"><img src="https://img.shields.io/badge/▸_UPLINK-000000?style=for-the-badge&labelColor=0a0a0a&logo=x&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pranav-shewale/"><img src="https://img.shields.io/badge/▸_NEURAL_LINK-0A66C2?style=for-the-badge&labelColor=0a0a0a&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.instagram.com/pranaaawv/"><img src="https://img.shields.io/badge/▸_VISUAL_FEED-E4405F?style=for-the-badge&labelColor=0a0a0a&logo=instagram&logoColor=white" /></a>
</p>

<p align="center" style="color:#6C63FF; font-family:monospace; font-size:0.75em;">
  <code>> SYNC COMPLETE | LAST_UPDATED: 2026-09-02T00:00:00Z | CHECKSUM: 0xDEADBEEF</code>
</p>
