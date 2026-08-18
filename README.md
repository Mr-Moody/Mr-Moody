<h1 align="center">Thomas Moody</h1>

<p align="center">
  <b>MEng Robotics &amp; AI @ UCL</b> · London<br>
</p>

<p align="center">
  <a href="https://linkedin.com/in/thomas-moody1"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:thomasmoody16@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### Now

**🎵 [CodaJam](https://codajam.com)** — the shared screen for live music. Synced charts for the band, lyrics for everyone else.

Bar-accurate notation and a shared clock across every device in the room, held to sub-10ms drift with NTP-style server timestamps rather than relative beat counts. Three surfaces off one monorepo: Expo/React Native for performers, Next.js for the audience display, and a persistent Node WebSocket server doing the sync. Tiered content resolution falls back gracefully from full Guitar Pro tab → chord sheet → timestamped lyrics, so a session never dead-ends on a missing chart.

`Next.js` `Expo` `TypeScript` `Supabase` `Railway` `Upstash` `alphaTab` `Cloudflare`

**🐈 Biorobotics Research @ UCL REBL** — EPSRC-funded work on whisker-based airflow sensing, asking what cheetah whisker density buys you over a domestic cat's. Carbon fibre whiskers on magnetic roots and a TPU flexure plate, nine MLX90393 magnetometers muxed through a PCA9548, Ridge regression and 1D-CNN models trained on wind tunnel episodes to resolve air speed and direction.

---

### Selected work

<table>
<tr><td width="50%" valign="top">

**[SmolVLA-Testing](https://github.com/Mr-Moody/SmolVLA-Testing)**<br>
Unified pipeline for collecting, labelling, converting and training robot demonstration data across SmolVLA, Pi0, Pi0.5 and ACT. Extended with Qwen3-VL offline phase annotation.<br>
<sub>`Python` `PyTorch` `VLA`</sub>

</td><td width="50%" valign="top">

**[NeMo-Ray](https://github.com/Harrishayy/NeMo-Ray)** 🏆<br>
Winner, NVIDIA Hack for Impact. RF propagation modelling for the UK Emergency Services Network using Sionna RT and Nemotron.<br>
<sub>`Sionna RT` `Nemotron` `Python`</sub>

</td></tr>
<tr><td width="50%" valign="top">

**MarshGazers — Autonomous Rover** 🏆<br>
Best Critical Design Review, UKSEDS Olympus Rover Trials (Advanced Stream). Multi-package ROS2 stack on Jetson Orin Nano with micro-ROS on custom STM32 hardware.<br>
<sub>`ROS2 Humble` `Nav2` `SLAM` `Gazebo`</sub>

</td><td width="50%" valign="top">

**[uncookd](https://github.com/Harrishayy/uncookd)** 🏆<br>
1st place, AgentVerse Hackathon — hosted by UCL, AWS, Anthropic, Cisco and EF.<br>
<sub>`TypeScript` `Agents`</sub>

</td></tr>
</table>

<details>
<summary><b>More detail on the rover →</b></summary>

<br>

- Architected a multi-package ROS2 Humble + micro-ROS stack supporting both physical and fully simulated launch.
- Fused RPLidar A1 and Intel RealSense D455 through `rtabmap` to build a 3D map, then marked coordinates for autonomous point-to-point navigation.
- SmacPlanner2D for global routing, MPPI local controller for collision avoidance.
- Tuned costmaps to catch rocks and 30° slopes without falsely marking sand dunes as obstacles — the hard part.
- Modelled the Airbus Mars yard in Blender for the Gazebo terrain.

</details>

<details>
<summary><b>Control systems &amp; hardware →</b></summary>

<br>

**Inverse Pendulum Balancing Robot** — Stabilised a free-flowing inverted pendulum on a four-motor cart. Kalman filter state estimation from pendulum and motor encoders, LQR and pole placement control with cascaded velocity-tracking PIDs. Designed a custom KiCad PCB to convert 5V differential encoder signals to 3.3V single-ended so the Arduino Giga R1 could read them safely.

**Extend Robotics** — Built a VLA policy training pipeline end to end (teleoperation → cleaning → annotation → training → deployment) onto a Franka Emika Panda 7, fine-tuning SmolVLA, ACT and Pi0 for high-precision electrical plug insertion. Integrated safety tooling including a deadman's switch and bounded operating envelope.

**MathWorks Minidrone Competition** — State-flow control for a simulated Parrot Minidrone: image masking and Hough transform for line detection, take-off/follow/land state transitions.

**Smart Green Island Makeathon** — With MathWorks and Krones, automated a 6DoF igus arm across vacuum forming, drying and waxing stations for plant-fibre cup manufacturing.

</details>

---

### Toolkit

**Languages**  Python · C · C++ · C# · TypeScript · JavaScript · MATLAB

**Robotics**  ROS2 Humble · micro-ROS · Nav2 · Gazebo · Isaac Sim/Lab · Webots · Simulink · PID · LQR · MPC · MPPI · Kalman filtering

**ML**  PyTorch · SmolVLA · ACT · Pi0 · OpenCV · scikit-learn · NumPy · Pandas

**Software**  Next.js · React · Expo · Supabase · Railway · Vercel · Upstash · Docker · Git

**Hardware**  KiCad · Fusion 360 · PCB design · STM32 · Arduino · Jetson · 3D printing · soldering

---

<p align="center">
  <sub>MEng Robotics and AI, UCL · Predicted First · Open to 2027 internships and research collaboration</sub>
</p>
