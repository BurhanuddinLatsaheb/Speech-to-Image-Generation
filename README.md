# 🔊🔊Speech to Image 📷 Generation
Realtime Audio to Image Generation

This is an end to end pipeline for Multilingual Speech to Image Generation
## The Models Used are: 

### 1) Whisper Model : 
Whisper is an automatic speech recognition (ASR) system trained on 680,000 hours of multilingual and multitask supervised data collected from the web

![image](https://user-images.githubusercontent.com/95982431/229340460-354e39f2-9570-4b28-a518-89c59c6ff96d.png)

![image](https://user-images.githubusercontent.com/95982431/229340470-4c1698e2-639d-4871-bd66-9f2e92cbdb29.png)

| Size  | Parameters |
| ------------- | ------------- |
| Tiny  | 39 M  |
| Base  |  74 M |
| Small |  244 M |
| Medium | 769 M |
| Large | 1550 M | 
| Large V2 | 1650 M |


### 2) Stable Diffusion Model:
Stable Diffusion is a latent text-to-image diffusion model. Trained on LAION-5B dataset
#### 2.1) Stable Diffusion V1

Uses <b>OpenAI's CLIP</b> as Text encoder 
No Negative Prompts
![image](https://user-images.githubusercontent.com/95982431/229340383-9e57b323-0b23-462a-97c4-f8b531c88350.png)

#### 2.2) Stable Diffusion V2

Uses <b>OpenCLIP</b> as Text Encoder
Negative Prompts are included
![image](https://user-images.githubusercontent.com/95982431/229340373-a22f4b96-529e-44e0-bd59-64bbf8655bc1.png)


# Flowchart of the workflow
![Untitled (1)](https://user-images.githubusercontent.com/95982431/229341234-7a217878-98fa-4ee9-b90d-66fd0acb137f.jpg)

