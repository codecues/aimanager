---
title: Humanitys Last Exam
description: >-
  LLM Benchmarking
author: tharif
date: 2025-01-22 20:55:00 +0800
categories: [AI/ML]
tags: [ai, benchmarking]
pin: false
media_subpath: '/posts/20180809'
---

Curated collection of 2,700 difficult questions across over 100 subjects, spanning everything from the sciences to the humanities. 
The questions in this dataset are crafted to be at the cutting edge of human knowledge, ensuring that only the most capable AI models can tackle them.

![image](https://github.com/user-attachments/assets/7d350e85-d4da-46c6-9122-f075552bbbe8)

DataSet - https://huggingface.co/datasets/cais/hle

Model Comparison Summary
_As of Jan2025/EarlyFeb._

Leading AI models across various critical metrics including intelligence, output speed (tokens per second), latency (seconds), price, and context window.

1.Intelligence
When it comes to intelligence, two models stand out: o3-mini and o1. These models are widely regarded as the highest quality available today. They are followed closely by DeepSeek R1 and o1-mini, which offer impressive performance but with slightly less sophistication in comparison to the leaders. Here’s how the rankings look for intelligence:

Top Models: o3-mini, o1
Followed by: DeepSeek R1, o1-mini
If you need a model with refined output quality and ability to understand complex inputs, o3-mini and o1 should be your top contenders.

2.Output Speed (Tokens/Second)
Output speed is crucial when time is of the essence, especially in real-time applications. Models like DeepSeek R1 Distill Qwen 1.5B and Gemini 1.5 Flash-8B deliver blazing-fast speeds of 375 tokens per second and 276 tokens per second, respectively. These models are ideal for high-demand scenarios where speed is paramount. Next in line are models like Gemini 2.0 Flash-Lite (Preview) and Ministral 3B. Here’s how the models rank in terms of output speed:

Fastest Models: DeepSeek R1 Distill Qwen 1.5B (375 t/s), Gemini 1.5 Flash-8B (276 t/s)
Followed by: Gemini 2.0 Flash-Lite (Preview), Ministral 3B
When considering output speed, DeepSeek R1 Distill Qwen 1.5B and Gemini 1.5 Flash-8B stand out for their exceptional performance.

3.Latency (Seconds)
Latency plays a crucial role when the response time is critical. Models like Gemini 1.5 Flash (Sep) and Gemini 1.5 Pro (May) exhibit the lowest latency, clocking in at just 0.10 seconds and 0.11 seconds, respectively. These models are perfect for applications that require minimal delay, such as interactive chatbots or real-time decision-making systems. Next in line are Gemini 1.5 Pro (Sep) and Gemini 1.5 Flash (May), offering only slightly higher latency.

Lowest Latency: Gemini 1.5 Flash (Sep) (0.10s), Gemini 1.5 Pro (May) (0.11s)
Followed by: Gemini 1.5 Pro (Sep), Gemini 1.5 Flash (May)
For ultra-low latency, the Gemini 1.5 Flash (Sep) and Gemini 1.5 Pro (May) models should be at the top of your list.

4.Price ($ per Million Tokens)
Pricing can make or break the viability of using an AI model, especially for large-scale implementations. The Llama 3.2 1B and Ministral 3B are among the most affordable models, priced at just $0.04 per million tokens. These models provide good value for developers or companies working on a budget. Close behind are DeepSeek R1 Distill Llama 8B and OpenChat 3.5, which offer competitive pricing as well.

Most Affordable Models: Llama 3.2 1B ($0.04), Ministral 3B ($0.04)
Followed by: DeepSeek R1 Distill Llama 8B, OpenChat 3.5
If cost is a primary concern, Llama 3.2 1B and Ministral 3B are solid, budget-friendly options.

5.Context Window
The context window refers to the model's capacity to handle larger chunks of input data. Models with a larger context window are better equipped to handle complex inputs or provide more coherent responses. The MiniMax-Text-01 model leads the pack with a remarkable 4 million tokens context window, followed by Gemini 2.0 Pro Experimental at 2 million tokens. The Gemini 1.5 Pro (Sep) and Gemini 1.5 Pro (May) come in with a respectable 1 million tokens context window.

Largest Context Window: MiniMax-Text-01 (4m), Gemini 2.0 Pro Experimental (2m)
Followed by: Gemini 1.5 Pro (Sep), Gemini 1.5 Pro (May)
