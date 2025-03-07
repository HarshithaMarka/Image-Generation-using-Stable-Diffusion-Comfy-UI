
# Image Generation Using Stable Diffusion & ComfyUI



# Installation

Clone ComfyUI Repository
```bash
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI

```
Create and Activate Virtual Environment

```bash
# Create virtual environment
python -m venv venv

# On Windows
venv\Scripts\activate

# On Linux/Mac
source venv/bin/activate

```
Install Dependencies
```bash
pip install -r requirements.txt

#If you encounter issues with missing libraries (like torch, numpy, etc.), you can install them manually

```
Download Stable Diffusion Model
```bash
https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors

#You can download other models from:
#Hugging Face
#CivitAI
```
Place the Stable Diffusion model file (.safetensors or .ckpt)
```bash
ComfyUI/
├── models/
│   └── checkpoints/
│       └── model.ckpt  (the downloaded Stable Diffusion .ckpt file or .safetensors file)
```

```bash

```
    
## Run ComfyUI

Once everything is set up, run the following command inside the ComfyUI folder:

```bash
python main.py

```


This will start ComfyUI, and you can access it in your browser at: 

```bash
http://127.0.0.1:5000

```

```bash
Enter a text prompt into the input field.
Press "Generate" to produce the image based on your prompt.

```


## Running Tests

Run the Prompt

```bash
 Floating City Above the Clouds
```


## Output

![Output](https://github.com/HarshithaMarka/Image-Generation-using-Stable-Diffusion-Comfy-UI/blob/main/Floating%20City%20Above%20the%20Clouds.jpg)


## Test 2

Run the Prompt

```bash
 ai avatar in virtual reality

```


## Output 2

![Output](https://github.com/HarshithaMarka/Image-Generation-using-Stable-Diffusion-Comfy-UI/blob/main/AI%20Avatar%20in%20Virtual%20Reality.jpg)



## Optimizations

1️⃣ Use Low VRAM Optimization

2️⃣ Optimize Batch Processing

3️⃣ Reduce Model Size with VAEs

4️⃣ Enable CUDA Graphs for Speedup

5️⃣ Use Efficient Samplers

6️⃣ Optimize for CPU Users


## Demo Video

[🎥 Watch the demo](https://github.com/HarshithaMarka/Image-Generation-using-Stable-Diffusion-Comfy-UI/blob/main/Demo.mp4))




