---
layout: default
title: Hands-On Generative AI - Table of Contents
---

## Part I: Leveraging Open Models

### **1. An Introduction to Generative Media**
- Generating Images
- Generating Text
- Generating Sound Clips
- Ethical and Societal Implications
- Where We’ve Been and Where Things Stand
- How Are Generative AI Models Created?
- Summary

### **2. Transformers**
- A Language Model in Action
- Tokenizing Text
- Predicting Probabilities
- Generating Text
- Zero-Shot Generalization
- Few-Shot Generalization
- A Transformer Block
- Transformer Model Genealogy
- Sequence-to-Sequence Tasks
- Encoder-Only Models
- The Power of Pretraining
- Transformers Recap
- Limitations
- Beyond Text
- Project Time: Using LMs to Generate Text
- Summary
- Exercises
- Challenges
- References

### **3. Compressing and Representing Information**
- AutoEncoders
  - Preparing the Data
  - Modeling the Encoder
  - Decoder
  - Training
  - Exploring the Latent Space
  - Visualizing the Latent Space
- Variational AutoEncoders
  - VAE Encoders and Decoders
  - Sampling from the Encoder Distribution
  - Training the VAE
  - VAEs for Generative Modeling
- CLIP
  - Contrastive Loss
  - Using CLIP, Step-by-Step
  - Zero-Shot Image Classification with CLIP
  - Zero-Shot Image-Classification Pipeline
  - CLIP Use Cases
  - Alternatives to CLIP
- Project Time: Semantic Image Search
- Summary
- Exercises
- Challenges
- References

### **4. Diffusion Models**
- The Key Insight: Iterative Refinement
- Training a Diffusion Model
  - The Data
  - Adding Noise
  - The UNet
  - Training
  - Sampling
  - Evaluation
- In Depth: Noise Schedules
  - Why Add Noise?
  - Starting Simple
  - The Math
  - Effect of Input Resolution and Scaling
- In Depth: UNets and Alternatives
  - A Simple UNet
  - Improving the UNet
  - Alternative Architectures
- In Depth: Diffusion Objectives
- Project Time: Train Your Diffusion Model
- Summary
- Exercises
- Challenges
- References

### **5. Stable Diffusion and Conditional Generation**
- Adding Control: Conditional Diffusion Models
  - Preparing the Data
  - Creating a Class-Conditioned Model
  - Training the Model
  - Sampling
  - Improving Efficiency: Latent Diffusion
- Stable Diffusion: Components in Depth
  - The Text Encoder
  - The Variational AutoEncoder
  - The UNet
- Stable Diffusion XL
- FLUX, SD3, and Video
- Classifier-Free Guidance
- Putting It All Together: Annotated Sampling Loop
- Open Data, Open Models
- Challenges and the Sunset of LAION-5B
- Alternatives
- Fair and Commercial Use
- Project Time: Build an Interactive ML Demo with Gradio
- Summary
- Exercises
- Challenge
- References

## Part II: Transfer Learning for Generative Models

### **6. Fine-Tuning Language Models**
- Classifying Text
  - Identify a Dataset
  - Define Which Model Type to Use
  - Select a Good Base Model
  - Preprocess the Dataset
  - Define Evaluation Metrics
  - Train the Model
  - Still Relevant?
- Generating Text
  - Picking the Right Generative Model
  - Training a Generative Model
- Instructions
  - A Quick Introduction to Adapters
  - A Light Introduction to Quantization
  - Putting It All Together
  - A Deeper Dive into Evaluation
- Project Time: Retrieval-Augmented Generation
- Summary
- Exercises
- Challenge
- References

### **7. Fine-Tuning Stable Diffusion**
- Full Stable Diffusion Fine-Tuning
  - Preparing the Dataset
  - Fine-Tuning the Model
  - Inference
- DreamBooth
  - Preparing the Dataset
  - Prior Preservation
  - DreamBoothing the Model
  - Inference
- Training LoRAs
- Giving Stable Diffusion New Capabilities
  - Inpainting
  - Additional Inputs for Special Conditionings
- Project Time: Train an SDXL DreamBooth LoRA by Yourself
- Summary
- Exercises
- Challenge
- References

## Part III: Going Further

### **8. Creative Applications of Text-to-Image Models**
- Image to Image
- Inpainting
- Prompt Weighting and Image Editing
  - Prompt Weighting and Merging
- Editing Diffusion Images with Semantic Guidance
  - Real Image Editing via Inversion
  - Editing with LEDITS++
  - Real Image Editing via Instruction Fine-Tuning
- ControlNet
- Image Prompting and Image Variations
  - Image Variations
  - Image Prompting
- Project Time: Your Creative Canvas
- Summary
- Exercises
- References

### **9. Generating Audio**
- Audio Data
  - Waveforms
  - Spectrograms
- Speech to Text with Transformer-Based Architectures
  - Encoder-Based Techniques
  - Encoder-Decoder Techniques
  - From Model to Pipeline
- Evaluation
- From Text to Speech to Generative Audio
  - Generating Audio with Sequence-to-Sequence Models
- Going Beyond Speech with Bark
- AudioLM and MusicLM
- AudioGen and MusicGen
- Audio Diffusion and Riffusion
- Dance Diffusion
- More on Diffusion Models for Generative Audio
- Evaluating Audio-Generation Systems
- What’s Next?
- Project Time: End-to-End Conversational System
- Summary
- Exercises
- Challenges
- References

### **10. Rapidly Advancing Areas in Generative AI**
- Preference Optimization
- Long Contexts
- Mixture of Experts
- Optimizations and Quantizations
- Data
- One Model to Rule Them All
- Computer Vision
- 3D Computer Vision
- Video Generation
- Multimodality
- Community

## Appendices

### **A. Open Source Tools**
- The Hugging Face Stack
- Data
- Wrappers
- Local Inference
- Deployment Tools

### **B. LLM Memory Requirements**
- Inference Memory Requirements
- Training Memory Requirements
- Further Reading

### **C. End-to-End Retrieval-Augmented Generation**
- Processing the Data
- Embedding the Documents
- Retrieval
- Generation
- Production-Level RAG
