# VLM-Classroom-Classification Web Page:
https://dinahejji.github.io/VLM-Classroom-Classification/

# Project Abstract:
This project introduces a multimodal AI system designed to understand and respond to real classroom scenes by combining vision, language, and behavioral cues. At its core, a fine-tuned Vision-Language Model (VLM) analyzes classroom images and transcripts to classify the type of activity—such as normal lecture, flipped learning, lab session, or exam—and to detect the academic topic being discussed.

In parallel, a behavior recognition module based on LSTM processes keypoints extracted from pose estimation to track student engagement over time. This allows the system to identify behaviors like writing, using a mobile phone, or disengagement.

Both the VLM's scene understanding and the LSTM's behavioral insights are fused into a unified prompt sent to a Large Language Model (LLM), which then generates intelligent, context-aware robot actions. The result is a fully integrated pipeline for classroom observation and autonomous human-robot interaction.

This end-to-end pipeline enables scalable, context-aware observation of real-world educational environments and supports intelligent classroom agents capable of proactive, multimodal assistance.
