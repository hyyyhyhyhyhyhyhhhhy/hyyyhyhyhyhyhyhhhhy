# Henry Yang 

Investigating how different AI language models work on describing scenes and angle changes in pictures. 

## What I'm Researching

Currently working on how well different language models can understand and preserve spatial relationships when generating descriptions of visual scenes, especially when the viewpoint changes. Using your Scene Describer tool, you test models like distilgpt2, SmolLM, and Qwen by giving them the same scene prompt and asking them to describe it from specific camera angles (such as bird’s-eye view or low angle). The goal is to see whether the models can maintain logical relationships—like left/right, above/below, and near/far—while adapting the description to a new perspective. This investigation helps you explore whether language models are simply generating fluent text or if they demonstrate a deeper ability to reason about space and viewpoint.

[Read the paper-in-progress](https://github.com/hyyyhyhyhyhyhyhhhhy/The-Research-Paper-)

## Spaces I've Built

- [Scene Describer 1.0](https://huggingface.co/spaces/hrnry/Camera_angle_model_lab) — Used to compare how different small language models describe the same scene. 
- [Scene Describer 2.0](https://huggingface.co/spaces/hrnry/Scene_describer) — An upgraded version of the previous one. (generates cinematic scene descriptions from any camera angle) 
- [The Image Editor](https://huggingface.co/spaces/hrnry/The_Image_Editor) — Edits and image regarding to text-based prompts, which is an important trasition from text generation to image generation.

## Hugging Face

Profile: <https://huggingface.co/hrnry>
Collection: <https://huggingface.co/collections/hrnry/henrys-collection>

## Research Journal

[research-journal.md](https://github.com/hyyyhyhyhyhyhyhhhhy/AI-Research-Level-2-Research-Journals-)
— weekly notes on what I've tested, noticed, and changed. 

## What I'm Building Now

- Compare models on same prompts
- Check spatial accuracy (left/right, depth)
- Test viewpoint-following ability
- Compare prompt styles
- Add stronger models (SmolLM, Qwen)
- Improve prompt instructions
- Add more viewpoints
- Log results automatically


