# ComfyUI Workflows

Put API-format workflow JSON files here. Each should have a descriptive filename.

## Recommended Models

For cute/comfy coloring book pages:

| Model | Size | Best For |
|-------|------|----------|
| Flux Dev fp8 | ~12 GB | Best quality, versatile |
| SDXL Base 1.0 | ~6.5 GB | Fast, line art style |
| SD 1.5 | ~4 GB | Lightweight, lora compatible |

## Useful Loras

- `Coloring_book_-_LineArt.safetensors` — line art style (CivitAI #195794)
- `coloringBook_coloringBook.ckpt` — SD 2.1 model trained on coloring books

## Workflow Types Needed

- [ ] Txt2img — basic prompt to coloring page
- [ ] Img2img — reference photo to line art
- [ ] Upscale — increase resolution for KDP print
- [ ] Batch — generate multiple pages at once