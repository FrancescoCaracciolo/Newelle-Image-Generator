# Newelle-Image-Generator
  <a href="https://github.com/topics/newelle-extension">
    <img width="150" alt="Download on Flathub" src="https://raw.githubusercontent.com/qwersyk/Assets/main/newelle-extension.svg"/>
  </a>
  
Collection of image generation extensions for Newelle and Nyarch Assistant
**Features**:
- 🖼 Let the AI create prompts an generate images for you
- ♻️ Nice loading animation
- 📄 **Prompt templates**: Adapt the prompt given by the AI to a template automatically
- 📑 **Copy option**: Copy the prompt choosen by the AI in a click
- 💾 **Save option**: Save generated images in custom paths

**Available Extensions**:

⚠️ *These extensions are not made to be used at the same time, always disable one*

- [Pollinations](#pollinations) free online [open source image generator](https://github.com/pollinations/pollinations), no api key, **good to try out image generation**, no setup
- [Stable Diffusion WebUI](#stable-diffusion-webui) uses the API of the self-hostable UI by [automatic111](https://github.com/AUTOMATIC1111/stable-diffusion-webui). **Locally run, more advanced, requires some setup**

### Pollinations

- Download and Install [Newelle](https://flathub.org/apps/io.github.qwersyk.Newelle)
- Download the [python file](https://raw.githubusercontent.com/FrancescoCaracciolo/Newelle-Image-Generator/refs/heads/main/polliations.py) in the repository
- Load the extension
Then you can ask the AI to generate an image of something:
<img width="563" height="502" alt="image" src="https://github.com/user-attachments/assets/e981b022-afe8-4bea-b3e8-544fff5feba9" />

### Stable Diffusion WebUI
Follow these steps:
1. Download and install [Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) according to the official documentation. You can also install it on another server, or something else, endpoint change is supported.
2. Start the stable diffusion webui with API enabled, to do that use `./webui.sh --api`
3. Download and Install [Newelle](https://flathub.org/apps/io.github.qwersyk.Newelle) (or Nyarch Assistant)
4. Download the [python file](https://github.com/FrancescoCaracciolo/Newelle-Image-Generator/blob/main/sdwebui.py) in the repository
5. Load the extensions
6. Tune the settings to your preferences

<img width="498" height="664" alt="image" src="https://github.com/user-attachments/assets/60b36523-80cb-45c0-aeb0-d908dcf60829" />

You can also manually specify a JSON with advanced options if you need it.

Then you can ask the AI to generate images:
<img width="578" height="511" alt="image" src="https://github.com/user-attachments/assets/51f85667-1c9d-48c2-9aad-9d7648a05bde" />
