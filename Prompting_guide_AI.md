### USEFUL BASIC PROMPTS   

- `remove watermark`

### "FILE LEVEL" prompts for restoring images

Prompts tipo

```
Task: Restore this photo faithfully. Steps:
1) Reconstruct ONLY the missing/damaged areas so they match the original scene (no reinterpretation).
2) Clean and enhance the file: deblur + denoise, histogram equalization, unsharp mask, white balance correction, color grading, micro-contrast, lens distortion correction.
3) Output must look like modern, professional-quality digital photography: clean, sharp, natural, no artifacts.
4) If the photo is misframed/tilted, correct the framing (straighten/level/recenter) with the minimum necessary adjustment.
5) Do NOT change anything else: no new elements, no removals, no style changes beyond restoration and the listed corrections.
```

Mirar este enlace con toda la info: https://www.reddit.com/r/StableDiffusion/comments/1qhulcx/flux2_klein_distilledcomfyui_use_filelevel/

`FLux Klein` :  en este post hay tips para mejorar el aspecto de la piel con "ReferenceLatent chaining" y CFG a 1.2.
