# ComfyUI_AI_Recolor
Examples below are accompanied by a [tutorial in my YouTube video](https://youtu.be/_UCGs6f1tow).

This ComfyUI nodes setup lets you change the color style of graphic design based on text prompts using Stable Diffusion custom models. This is similar to the generative recolor function proposed by Adobe. The difference is that you get bitmap images with  both color and style variations here instead of vectors. I think that this mechanism, especially with finely tuned Stable Diffusion models, gives a better result and allows you to get really trendy color schemes, taking into account not only the overall composition, but also the features of the objects in the design.

You can utilize it for your custom setups. Simply save and then drag and drop the image into your [ComfyUI interface window](https://github.com/comfyanonymous/ComfyUI) with ControlNet Canny with preprocessor and T2I-adapter Style modules active to load the nodes, load design you want to modify as 1152 x 648 PNG or images from "Samples to Experiment with" below, modify some prompts, press "Queue Prompt," and wait for the AI generation to complete. Stable Diffusion model used in this demonstration is [Lyriel](https://civitai.com/models/22922/lyriel?modelVersionId=72396).

Video tutorial on how to use ComfyUI, a powerful and modular Stable Diffusion GUI and backend, is [here](https://youtu.be/Ij8k6mBgL3o).

![ComfyUI_00090_](https://github.com/atdigit/ComfyUI_AI_Recolor/assets/105158639/86fed4be-6f20-4f90-ba86-e92063600aad)
![Clip_47](https://github.com/atdigit/ComfyUI_AI_Recolor/assets/105158639/1ff85190-b4c4-4405-8874-c51baacb6b3e)
![ComfyUI_00002_ (1)](https://github.com/atdigit/ComfyUI_AI_Recolor/assets/105158639/2beecbef-0b00-42eb-898e-26729dc0b3d4)
![Clip](https://github.com/atdigit/ComfyUI_AI_Recolor/assets/105158639/87aae144-03d1-460f-bda7-9972eb3ea109)
↑ Node setups (Save picture with crystals to your PC and then drag and drop the image into you ComfyUI interface)

![Time_Crystal_002@4x-100_3](https://github.com/atdigit/ComfyUI_AI_Recolor/assets/105158639/ef838614-38b6-4f26-b38b-4b0902f2ad78)
![ComfyUI_00041_](https://github.com/atdigit/ComfyUI_AI_Recolor/assets/105158639/7ae9a653-b339-4f12-be51-9cfc763ebd89)
↑ Samples to Experiment with (Save to your PC and drag them to "Style It" and "Shape It" Load image nodes in setup above)
