<p align="center">
  <img width='850' src='https://github.com/flowstateeng/FlowState-Nodes/blob/main/imgs/FlowState-Custom-Nodes-Banner.png' alt='MNIST Digits'/>
</p>

# FlowState Custom Nodes
The ultimate set of ComfyUI custom nodes to streamline your workflows. Enjoy!

Email info@flowstateengineering.com with questions.
<br/><br/>


# Sponsorship
<div align="center">

** [:heart: Github Sponsor](https://github.com/sponsors/flowstateeng) | [:coin: Ca$hApp](cash.app/$FlowStateEngineering) | [:dollar: Venmo](account.venmo.com/u/flowstateeng) | [:goat: Stripe](donate.stripe.com/9AQ3fm04OfqCgiAcMN) **

</div>

Everything is open and free, but if you like my work and wish to see updates and new features please consider sponsoring my projects.

- [FlowState Unified Sampler](https://github.com/flowstateeng/FlowState-Nodes/blob/main/FlowStateUnifiedSampler.py)
- [FlowState Unified Model Loader](https://github.com/flowstateeng/FlowState-Nodes/blob/main/FlowStateUnifiedModelLoader.py)
- [FlowState LLM Prompt & LLM Output](https://github.com/flowstateeng/FlowState-Nodes/blob/main/FlowStateLLMPrompt.py)
- [FlowState Latent Chooser](https://github.com/flowstateeng/FlowState-Nodes/blob/main/FlowStateLatentChooser.py)
- [FlowState FVD Sampler](https://github.com/flowstateeng/FlowState-Nodes/blob/main/FlowStateLatentChooser.py) (alpha)

Video tutorials can be found on YouTube at [FlowState YouTube Channel](https://www.youtube.com/@flowstateeng)

The only way to keep the code open and free is by sponsoring its development. The more sponsorships, the more time I can dedicate to open source projects for everyone!

Please consider a [Github Sponsorship](https://github.com/sponsors/flowstateeng) or [Patreon Membership](https://www.patreon.com/flowstateeng/membership), or one-time donations through [CashApp](cash.app/$FlowStateEngineering), [Venmo](account.venmo.com/u/flowstateeng) or [Stripe](donate.stripe.com/9AQ3fm04OfqCgiAcMN).



## Status
![Build Status](https://img.shields.io/badge/build-Beta-green.svg)
![License](https://img.shields.io/badge/license-NONE-green.svg)
<br/><br/>


## Installation
[Video Demo](https://youtu.be/5wAHg8OvgbM?si=Uhl5oNx51d1y7XWQ) in my [ComfyUI Playlist](https://youtube.com/playlist?list=PLopF-DMGUFkQqh_FXP03qES4Lq-wY34kO&si=u4ltujwGIX-sZLYG)

Paste this link into your ComfyUI Manager > Install via Git URL: https://github.com/flowstateeng/FlowState-Nodes.git

OR

In your ComfyUI custom nodes folder...
```bash
git clone https://github.com/flowstateeng/FlowState-Nodes.git
```
<br/><br/>


# Current Nodes
## FlowState Unified Sampler
The new kid on the block is the FlowState Unified Sampler. Use this powerful sampler with your Flux AND Stable Diffusion models. Includes support for testing a variety of parameters in your batches. Add parameters and/or prompts to your output images for easy identification. Adjust font size and number of lines to include exactly the text you want. Control your terminal/CMD prompt output. Includes Latent Multiply and VAE Decode functionality, so no need for extra nodes in your workflow.
<p align="center">
  <img width='850' src='https://github.com/flowstateeng/FlowState-Nodes/blob/main/imgs/FS-Unified-Sampler.png' alt='FS Unified Sampler Image'/>
  <img width='850' src='https://github.com/flowstateeng/FlowState-Nodes/blob/main/imgs/FS-Unified-Sampler-Output.png' alt='FS Unified Sampler Image 2'/>
</p><br/><br/>

## FlowState LLM Prompt & LLM Prompt Output
Tighten up your workflow with the FlowState LLM Prompt. Load a .gguf model to generate sophisticated image prompts, or simply flip a switch to use your own. Handles the text encoding for you internally, so you don't need another Text Encode node off to the side. Outputs the original and generated text and conditioning, in case you want to pass it to another node. Also includes the Clip Attention Multiply functionality, thus eliminating another node from your workflow.
<p align="center">
  <img width='850' src='https://github.com/flowstateeng/FlowState-Nodes/blob/main/imgs/FS-LLM.png' alt='FS LLM Image'/>
</p><br/><br/>

## FlowState Unified Model Loader
Simplify your model loading with the FlowState Unified Model Loader. Load your UNET and Checkpoint models in a single node. Including support for Flux NF4! (Flux .gguf support coming soon!) Includes global seed you can use for your entire workflow. No need to have three separate nodes for Stable Diffusion, Flux Dev/Schnell and Flux NF4. Do it all in a single node!
<p align="center">
  <img width='850' src='https://github.com/flowstateeng/FlowState-Nodes/blob/main/imgs/FS-Unified-Model-Loader.png' alt='FS Unified Model Loader Image'/>
</p><br/><br/>

## FlowState Latent Chooser
Expand your latent options and clean up your workflow with FlowState Latent Chooser. Easily select between an empty latent, input image as a latent, and imported image as a latent with a simple switch. Vary the denoise on your sampler to control the amount of style transfer you want from your image latent in your generated images.
<p align="center">
  <img width='850' src='https://github.com/flowstateeng/FlowState-Nodes/blob/main/imgs/FS-Latent-Chooser.png' alt='FS Latent Chooser Image'/>
</p><br/><br/>


## Authors
**Johnathan Chivington:**
* [YouTube](https://youtube.com/@flowstateeng), [Patreon](https://youtube.com/@flowstateeng), [X](https://x.com/FlowStateEng), [GitHub](https://github.com/flowstateeng)
<br/>

## Contributing
Not currently accepting outside contributors, but feel free to use as you wish.
<br/><br/>

## License
There is no license associated with this content.
<br/><br/>
