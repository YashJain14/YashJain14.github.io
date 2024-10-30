---
layout: page
title: SOPPU
description: Scalable One PEFT per User
img: assets/img/soppu.png
importance: 1
category: work
related_publications: false
---

A framework enabling decentralized, personalized AI through efficient compression and serving of individual user adaptations
- Combines client-side compression of personal PEFT adapters using advanced LoRA compression techniques
- Utilizes scalable serving through LoRAX
- Achieves personalization while maintaining model efficiency and scalability

### Awards
- Global Top 50 in Alibaba Global E-commerce Challenge

### Tech Stack
- **Core Technologies:** Large Language Models (LLMs), Transformers, PEFT
- **Infrastructure:** LoRAX serving system
- **Compression:** Advanced LoRA compression techniques
- **Architecture:** Client-side processing + Centralized inference server

## Experimental Results
<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/reconstruction_errors.png" title="image" class="img-fluid rounded z-depth-1" %}
</div>

**Key Achievements:**
- Achieved 1.99x compression ratio (1.7M to 856K parameters)
- Demonstrated 49.7% average memory savings across adapters
- Successfully scaled to thousands of concurrent users
- Maintained adaptation quality while reducing storage requirements
- Proved better preservation of early layer information through layerwise analysis

## Why I made it
- Solve the impracticality of maintaining separate model copies for each user at scale
- Enable efficient personalization without compromising base model access
- Create a scalable solution for handling multiple user adapters efficiently
- Develop a framework that protects user privacy through local processing while maintaining performance