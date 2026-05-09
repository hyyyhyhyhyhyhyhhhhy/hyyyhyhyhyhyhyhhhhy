# Henry Yang 

I'm a grade 9 student interested in investigating how different AI language models work on describing scenes and angle changes in pictures. 

## What I'm Researching

Currently working on how well different language models can understand and preserve spatial relationships when generating descriptions of visual scenes, especially when the viewpoint changes. Using The Scene Describer Hugging Face space, I test models like distilgpt2, SmolLM, and Qwen by giving them the same scene prompt and asking them to describe it from specific camera angles (such as bird’s-eye view or low angle). The goal is to see whether the models can maintain logical relationships—like left/right, above/below, and near/far—while adapting the description to a new perspective. This investigation helps me explore whether language models are simply generating fluent text or if they demonstrate a deeper ability to reason about space and viewpoint.

[Read the paper-in-progress](https://github.com/hyyyhyhyhyhyhyhhhhy/The-Research-Paper-)

## Spaces I've Built

- [Scene Describer 1.0](https://huggingface.co/spaces/hrnry/Camera_angle_model_lab) — Used to compare how different small language models describe the same scene. 
- [Scene Describer 2.0](https://huggingface.co/spaces/hrnry/Scene_describer) — An upgraded version of the previous one. (generates cinematic scene descriptions from any camera angle) 
- [The Image Editor](https://huggingface.co/spaces/hrnry/The_Image_Editor) — Edits and image regarding to text-based prompts, which is an important trasition from text generation to image generation
- [Perspective Evidence Lab](https://huggingface.co/spaces/hrnry/Perspective_evidence_lab) — Test how language models preserve spatial relationships when describing the same scene from different camera viewpoints.

## Hugging Face

Profile: <https://huggingface.co/hrnry>
Collection: <https://huggingface.co/collections/hrnry/henrys-collection>

## Research Journal

[research-journal.md](https://github.com/hyyyhyhyhyhyhyhhhhy/AI-Research-Level-2-Research-Journals-)
— weekly notes on what I've tested, noticed, and changed. 

## What I'm Building Now

- Building Perspective Evidence Lab, a Hugging Face Space for testing viewpoint reasoning in language models
- Comparing how models preserve spatial relationships across camera angles 
- Testing small language models including distilgpt2, SmolLM2, and Qwen2.5-0.5B
- Studying foreground/background changes, occlusion, visibility, scale, and spatial consistency in generated descriptions
- Designing reproducible AI experiments using fixed generation settings and scoring rubrics
- Exploring the limitations of small/free AI systems in handling genuine perspective transformation
- Using Gradio + Hugging Face Transformers to build lightweight CPU-friendly research tools
- Collecting evidence on how prompt structure affects viewpoint-following and spatial reasoning in AI systems


