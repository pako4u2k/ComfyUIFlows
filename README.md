# ComfyUI Workflows 
Example of a ComfyUI Workflow mixing InstantID to preserve identity (my face from the picture), LoRA finetuned models to apply a specific style (Master Chief Halo, IronMan or Goku) and ControlNet to copy specific poses from another image (OpenPose Preprocessor and Model).

Organized the Workflow in Node Groups and with notes for every category for better clarity and at the bottom some opther image outputs of the same workflow with specific LoRA filters and prompts.

## LoRA, InstantID and ControlNet Workflow

![](https://www.wimotics.net/comfyUI/InstantIDLoraControlNet_Flow.png)
## Outputs
<img src="https://www.wimotics.net/comfyUI/ComfyUI_00129_.png" width=20% height=20%>
<img src="https://www.wimotics.net/comfyUI/ComfyUI_00170_.png" width=30% height=30%>
<img src="https://www.wimotics.net/comfyUI/ComfyUI_00109_.png" width=30% height=30%>

## Wan 2.1 Conistent Video Generation Workflow (Fruit Guys)
First generated with Stable Diffusion the start images from Positive andf Negative Prompts and normal KSampler for the three characters (Fruit Guys).
Then animated conistently with Wan 2.1 Models/Nodes Positive/Negative Prompts the characters as described in the following Workflow and on the web site
here you can see the full results: https://www.wimotics.net/FruitGuys
![](https://www.wimotics.net/comfyUI/Wan2.1Workflow.png)
## 3D Pipeline Workflow (Fruit Guys continued...)
An example 3D rendering with ComfyUI 3D Pack and Stable Fast 3D Model Nodes, using teh start image as the Dragon Fruit Ninja Guy generated from the prompt in the previous Stable Diffusion Flow.
![](https://www.wimotics.net/comfyUI/3dPackFast3DWorkflow.png)

Thanks,
Pasquale
