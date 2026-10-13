<div align="center">

# RAX: Scaling Online Exploration for Robot Agents

<b>R</b>obot <b>A</b>gent e<b>X</b>ploration: an open-source platform on which coding agents learn robot tasks by exploring

<br>

[![Project WebPage](https://img.shields.io/badge/Project-webpage-%23fc4d5d)](https://robot-agent-exploration.com) ![Video](https://img.shields.io/badge/Video-coming%20soon-blue) [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<br>

Runhan&nbsp;Huang<sup>1,\*</sup>, Xiangcheng&nbsp;Zhang<sup>1,\*,†</sup>, Haoyu&nbsp;Chen<sup>1,‡</sup>, Yitong&nbsp;Li<sup>2,‡</sup>, Yen-Jen&nbsp;Wang<sup>3,‡</sup>, Bohan&nbsp;Lyu<sup>3,‡</sup>, Haoyu&nbsp;Xiong<sup>4</sup>, Yangzhen&nbsp;Wu<sup>3</sup>, Chuye&nbsp;Hong<sup>3</sup>, Haotian&nbsp;Ye<sup>5</sup>, Yixuan&nbsp;Wang<sup>2</sup>, Travis&nbsp;Manderson<sup>4</sup>, Stefano&nbsp;Ermon<sup>5</sup>, Dawn&nbsp;Song<sup>3</sup>, Pieter&nbsp;Abbeel<sup>3</sup>, Qianqian&nbsp;Wang<sup>1</sup>, Antonio&nbsp;Torralba<sup>4</sup>, Weirui&nbsp;Ye<sup>4</sup>, Yilun&nbsp;Du<sup>1</sup>

<sup>1</sup>Harvard University &nbsp; <sup>2</sup>NVIDIA &nbsp; <sup>3</sup>UC Berkeley &nbsp; <sup>4</sup>MIT &nbsp; <sup>5</sup>Stanford University

<sub><sup>\*</sup>Equal contribution &nbsp; <sup>†</sup>Project lead &nbsp; <sup>‡</sup>Core contributor</sub>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/affiliations_dark.png">
  <img src="assets/affiliations_light.png" alt="Harvard University, NVIDIA, UC Berkeley, MIT and Stanford University" width="520">
</picture>

</div>

<br>

<p align="center">
  <img src="assets/teaser.png" alt="RAX overview: real-robot tasks learned through exploration, exploration scaling in simulation, comparison with the strongest prior models, and the speed-up from agent to code" width="100%">
</p>

## 💡 Overview

RAX is an open-source framework for robot agents built around one principle, **scaling exploration**: a robot agent should improve by gathering its own online experience and optimizing its own programs. A general-purpose coding agent programs the robot directly, with no teleoperation corpus, no hand-engineered action primitives and no value-function guidance. It explores online, finds the decisions that make a task succeed, and compiles them into modular programs that run the full perception, planning and control loop on their own. The language model's weights never change. What the agent learns lives in a persistent workspace of programs, notes and verified skills.

## ✨ Highlights

- 📈 **Exploration scales.** Performance on unseen scenes rises steadily as the exploration budget grows.
- 🦾 **One agent, many embodiments.** Single-arm, bimanual, dexterous, mobile and humanoid robots, across six simulation benchmarks and two real robots (Franka and Rainbow RB-Y1). A new robot joins through its API alone, with no data collection and no policy training.
- 🏆 **State of the art in simulation.** RAX surpasses the strongest prior models by **+37.4** on average.
- ⚡ **From exploration to code.** The agent's discoveries become fully automated programs that solve real-robot tasks two orders of magnitude faster than the agent itself.
- 🔁 **Continual learning on real robots.** Memory-dependent, articulated, high-precision, deformable and long-horizon mobile manipulation tasks are learned through autonomous exploration, and skills verified in earlier sessions compose into longer ones.

## 🔥 News

- **[2026-10]** 🌐 The [project page](https://robot-agent-exploration.com) is live. The code release is in progress; ⭐ star or 👀 watch this repository to be notified.

## 🗺️ Release Plan

- [x] Project page
- [ ] RAX in simulation
- [ ] RAX in the real world

## 📖 Citation

BibTeX coming soon.

## 📄 License

RAX is released under the [MIT License](LICENSE).
