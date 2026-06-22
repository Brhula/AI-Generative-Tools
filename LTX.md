### LTX 2.3

Lightricks: https://huggingface.co/Lightricks   
Awesome LTX: https://github.com/wildminder/awesome-ltx2?tab=readme-ov-file   
LTX easy prompts (experimental): https://github.com/seanhan19911990-source/LTX2EasyPrompt-LD   


Kijai : https://huggingface.co/Kijai   


#### WORKFLOWS   

https://huggingface.co/RuneXX/LTX-2.3-Workflows   


#### RESOLUTION   

Width and height must be divisible by 32   

|  Aspect Ratio | Width  | Height  | Quality  |  	VRAM |
|---|---|---|---|---|
| 9:16 (portrait)  | 480  | 864  | Low / fast preview  |  Low |
| 9:16 (portrait)  | 736  |  1280 | 720p — recommended default  | Medium  |
| 9:16 (portrait)  | 1088  |  1920 | 1080p — high quality | High (RTX 5090+)  |
|  16:9 (landscape) | 864  |  480 | Low / fast preview  | Low  |
|  16:9 (landscape) | 1280  |  736 | 720p — recommended  | Medium  |
|  16:9 (landscape) | 1920  |  1088 | 1080p — high quality  | High (RTX 5090+) |
| 1:1 (square)  | 768  | 768  | 	Social media square  | Medium |


#### PROMPTING   

- Use a negative prompt: Add terms like "jump cut, teleport, morph, dissolve, glitch, stutter, duplicate face, warped limbs" to your negative prompt to discourage the model from producing artifacts during the interpolated sections.
