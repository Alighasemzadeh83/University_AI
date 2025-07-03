# University_AI

This repository contains my AI practices, projects done with my teammates **Ali Najar** and **Mohammad Amin Abbasfar**.  
It includes implementations of deep learning models for computer vision as well as reinforcement learning algorithms.

---

## 📚 Projects

### 🖼️ 1. UNet for Semantic Segmentation

- **Objective:** Implemented UNet architecture from scratch for semantic segmentation, focusing on encoder and decoder blocks.

- **Dataset:**  
  - Self-driving car dataset used for road/lane segmentation.  
  - Download from Kaggle:  
    ```bash
    kaggle datasets download -d mojtabanafez/self-driving-car-dataset-ai-course
    unzip self-driving-car-dataset-ai-course.zip
    ```

- **Highlights:**  
  - Custom implementation of UNet encoder and decoder blocks.  
  - Used binary cross-entropy and IoU metrics for evaluation.

---

### 🎮 2. Advantage Actor-Critic (A2C) on CartPole

- **Objective:** Implemented the A2C (Advantage Actor-Critic) algorithm from scratch.

- **Environment:**  
  - OpenAI Gym `CartPole-v1` environment.

- **Highlights:**  
  - Separate policy (actor) and value (critic) networks.  
  - Trained with parallel environment sampling and discounted returns.  
  - Demonstrated stable balancing on the CartPole environment.

---

