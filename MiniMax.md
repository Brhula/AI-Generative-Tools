## MiniMax H3 Video Generation   

### Notas generales sobre la generación    

- Micro expresiones faciales: https://www.reddit.com/r/StableDiffusion/comments/1wap0rb/pushing_ai_emotions_is_possible_through/   
- On Line prompt builder: https://minimaxh3.studio/guide/minimax-h3/prompt-builder#choose-mode
  

#### CALIDAD de la GENERACIONES

- Use 1344×768 at 16:9, res_multistep, the simple scheduler, 20-25 denoising steps, guidance 1, video shift 12, and audio shift 3. This is the dependable open-weight quality baseline.

- Para calidad : olvidarse de los modelos "turbo", subir los pasos (scheduler Steps ~ 50).   
- Las generaciones cambian si cambia la resolución o los "steps".    
