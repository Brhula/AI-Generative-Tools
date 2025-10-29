# ComfyUi useful NODES .   

- Manager (basic): https://github.com/ltdrdata/ComfyUI-Manager
- SUPIR: SDXL Up Scale of images and video https://github.com/kijai/ComfyUI-SUPIR
- KJNodes for ComfyUI: for quality of life improvements https://github.com/kijai/ComfyUI-KJNodes
- Inspire Pack: for quality of life improvements https://github.com/ltdrdata/ComfyUI-Inspire-Pack
- Depth Anithing: create depth maps https://github.com/kijai/ComfyUI-DepthAnythingV2
- Frame interpolation: useful to go from 16 to 25 or 30 fps in video https://github.com/Fannovel16/ComfyUI-Frame-Interpolation
- Video Helper suit: helps voith video and audio https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite
- WAN video wrapper: for WAN video workflows https://github.com/kijai/ComfyUI-WanVideoWrapper

# Where to put files in ComfyUi.   

File structure in https://comfyui-wiki.com/en/interface/files

#### <ins>MODELS</ins>   

- Regular models (.ckpt or .safetensors) : `ComfyUI/models/checkpoints`
- GGUF : `ComfyUI/models/unet`
- FP8:

#### <ins>CLIP</ins>     

- Text Encoders (clip) : `ComfyUI/models/clip`


####  <ins>CUSTOM NODES</ins>   

- open CMP/PoweShell on "custom_nodes" folder
- `git clone <repository>`
- go to install directory :  `cd ..\..`
- Install requieriments (if needed) :  `python_embeded\python.exe -m pip install -r ComfyUI\custom_nodes\<repository>\requirements.txt`


####  <ins>INSTALL</ins>   

- Use ComfyUI easy Install as template
- After installing it, add "sage attention" and "nunchaku" add on 
