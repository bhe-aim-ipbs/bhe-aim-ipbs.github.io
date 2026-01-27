---
---

# bhe-aim-ipbs's Website

Welcome to bhe-aim-ipbs website! Relying on The Key Laboratory of Brain Health Intelligent Evaluation and Intervention of the Ministry of Education, our lab is dedicated to solving the problem of intelligent perception of body sounds and contributing to the advancement of the discipline and society. We welcome people from all areas to visit our website to know more about our research achievements, team members and other contents. We look forward to working with you to explore the mysteries of science!

{% include section.html %}


## Research Directions
The Intelligent Perception of Body Sound Group focuses on three complementary research directions that jointly address data scarcity, deployment efficiency, and collaborative intelligence in real-world audio perception systems:
### 1. Few-Shot and Low-Resource Learning
This direction aims to address the fundamental challenge of limited labeled data in body sound perception tasks, particularly in personalized, rare-event, or domain-specific scenarios. We investigate few-shot learning, meta-learning, and representation transfer techniques to enable intelligent agents to rapidly adapt to new users, environments, and sound categories with minimal supervision. By enhancing generalization under data-scarce conditions, this line of research provides a robust learning foundation for scalable and personalized audio perception systems.

### 2. Lightweight and Efficient Model Design
This direction focuses on developing lightweight, computation-efficient audio perception models suitable for deployment on resource-constrained platforms such as wearable devices, mobile agents, and embedded systems. We explore model compression, knowledge distillation, efficient neural architectures, and hardware-aware optimization to balance recognition accuracy with latency, memory footprint, and energy consumption. The goal is to enable real-time, on-device audio perception that supports continuous interaction and long-term operation of intelligent agents.

### 3. Federated and Privacy-Preserving Learning
This research direction investigates federated learning frameworks for collaborative audio perception across distributed agents while preserving user privacy and data security. We study communication-efficient aggregation, heterogeneous data modeling, and personalized federated optimization to enable collective learning from decentralized and non-IID audio data. By allowing intelligent agents to improve their perception capabilities without centralized data collection, this direction supports scalable, privacy-aware, and ethically responsible audio intelligence systems.

## Highlights

{% capture text %}

Our new paper entitled “Computer audition for healthcare: A survey on speech analysis” has been accepted and published online by the AI Open  (IF-2024: 14.8).

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/AI-open-1.jpg"
  link="research"
  title="Our Research"
  text=text
%}




{% capture text %}

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}

