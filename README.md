Design of a GenAI UX Layer with Small Language Models for Edge Computing in Smart Agriculture

📘 Overview

This repository contains the code, data, and documentation associated with the study “Design of a GenAI UX Layer with Small Language Models for Edge Computing in Smart Agriculture”, developed by
Juan M. Núñez V., Carlos A. Peláez, Andrés Solano, Juan M. Corchado, and Fernando De la Prieta (University of Salamanca and Universidad Autónoma de Occidente).

The project proposes a GenAI-UX reference framework for integrating Small Language Models (SLMs) into Edge Computing environments, optimizing human–AI interaction through User Experience (UX) design principles and Human-Centered Artificial Intelligence (HCAI) guidelines.

🎯 Objectives

Design an Edge–IoT architecture with a GenAI-UX layer based on lightweight models (TinyLlama, DeepSeek).

Apply UX and HCAI principles to improve accessibility and usability for small and medium-sized agricultural producers.

Validate the impact of UX design on agronomic efficiency, reducing harvest cycles and improving productivity.

State of the Art

A systematic PRISMA-UXAI review (2019–2025) was conducted using academic databases (IEEE Xplore, ACM, SpringerLink, Elsevier).
The analysis identified methodological gaps in integrating UX + GenAI + Edge Computing, highlighting:

| Approach                                | Observed Limitations                         | Contribution of This Study                                                                  |
| --------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Cloud-based LLMs (AgriGPT, Farmer.Chat) | Internet dependency, high energy consumption | Use of **local SLMs** (TinyLlama, DeepSeek) with edge processing                            |
| Traditional IoT systems                 | Complex interfaces, low user adoption        | **GenAI-UX layer** with multimodal (voice/text/audio) interaction accessible to rural users |
| UX studies in IoT                       | Focused only on performance metrics          | Application of **HCAI principles and 37 validated UX guidelines**                           |

Comparison across 30 studies revealed that none implemented or experimentally validated a UX–GenAI–Edge framework in agriculture, confirming the novelty of this research.

User Surveys and Characterization

As part of the requirement identification phase, 12 semi-structured interviews were conducted with coriander farmers (7 men, 5 women, aged 25–61), representing diverse educational levels (technical, undergraduate, and postgraduate).

Main Findings

Identified needs: accessible interfaces for elderly users and low-literacy farmers.

Preferences: automated irrigation and lighting systems, voice notifications, and simplified navigation.

Challenges: trust in AI, interpretability of results, and clarity of recommendations.

These findings led to the definition of UX requirements aligned with six design principles and 37 UX guidelines, grouped into themes of ethics, inclusion, human–AI collaboration, personalization, trust, and accuracy.

🧠 Methodology

The project followed the Design Science Research Methodology (DSRM) with three main phases:

Problem and requirement identification

Farmer interviews and FAO analysis to determine optimal crop parameters.

Design and implementation of the Edge + GenAI-UX architecture

Deployment on Raspberry Pi 5 (8GB) using TinyLlama and DeepSeek.

Experimental and UX validation

A/B/C testing in a controlled coriander cultivation environment.


⚙️ Technical Architecture

Physical Layer: IoT sensors (temperature, humidity, lighting).

Edge Layer: Optimization engine using genetic algorithms + SLM models.

GenAI-UX Layer: Multimodal interaction (voice, text, audio) — accessible and customizable.

The system processes real-time data, optimizing irrigation, lighting, and environmental control through locally executed models, without requiring cloud connectivity.


📊 Key Results

Harvest cycle reduced: from 45 → 32 days.

Productivity increased: +29% to +47%.

Energy consumption and latency reduced compared to traditional IoT systems.

Regression model accuracy: 
𝑅2=0.853
R2=0.853 applied to key agroclimatic variables.

🧪 UX Validation and User Participation

User experience evaluation used meCUE 2.0 and MEEGA+ instruments, demonstrating:

↑38% improvement in perceived control and trust.

↑42% improvement in usability and accessibility.

Reduced cognitive load and better understanding of AI recommendations.

🧰 Technologies Used

Hardware: Raspberry Pi 5 (8GB RAM), DHT22 and BH1750 sensors.

Software: Python, TensorFlow Lite, PyTorch, ONNX Runtime, RAG pipeline.

Models: TinyLlama (1.1B) and DeepSeek-R1 (1.5B).

Optimization: Genetic algorithms + multiple linear regression.

UX Framework: 37 empirically validated guidelines for GenAI in Edge Computing environments.

🧾 License

This project is distributed under the MIT License.
Please cite this work as:

Núñez, J. M., Peláez, C. A., Solano, A., Corchado, J. M., & De la Prieta, F. (2025). Design of a GenAI UX Layer with Small Language Models for Edge Computing in Smart Agriculture. BISITE Research Group, University of Salamanca.

📫 Contact

Lead Author: Juan M. Núñez V. – jmnunez@usal.es

Research Group: BISITE Research Group

University: University of Salamanca
