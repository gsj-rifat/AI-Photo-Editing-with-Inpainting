# AI-Photo-Editing-with-Inpainting
This project demonstrates a modern AI-powered web app that allows users to seamlessly swap out the background of a subject in an image.

## Features

- Automatically detects and masks the subject using point prompts.
- Supports background replacement via text-to-image inpainting.
- Powered by state-of-the-art models: `facebook/sam-vit-base` and `diffusers/stable-diffusion-xl-1.0-inpainting-0.1`.
- Runs efficiently with mixed precision and model offloading.

🛠 Tech Stack
1. Python 
2. HuggingFace Transformers & Diffusers
3. PyTorch
4. NumPy
5. SAM (Segment Anything Model)
6. Stable Diffusion XL Inpainting


✨ Workflow
1. Select points on the subject.

2. Generate a binary mask using SAM.

3. Provide a text prompt for a new background (e.g., "sunset beach").

4. Inpaint and visualize the result.
