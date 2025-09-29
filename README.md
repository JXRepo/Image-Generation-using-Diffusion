# Diffusion-Text-to-Image

This project implements a text-to-image generation pipeline using a state-of-the-art diffusion model in PyTorch.

## Features

• Generates images from textual prompts with strong semantic consistency.

• Uses pretrained models and a custom scheduler for improved convergence.

• Built with PyTorch for training and sampling routines.

## Usage

1. Install dependencies: `pip install -r requirements.txt`

2. Run training: `python train_diffusion.py`

3. Generate images: `python sample_diffusion.py --prompt "your text here"`

## Future Improvements

• Explore larger diffusion models for higher-quality images.

• Fine-tune on domain-specific datasets.

• Optimize scheduler and sampling techniques for faster inference.
