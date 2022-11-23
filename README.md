# AI-photopainter for Windows


##  About
AI-photopainter is a tool for generating AI image on Photoshop for Windows.
This app interacts with photoshop and stable-diffusion AI tool to inpaint or outpaint various photos.
This app was written with c# and the AI backend was written python.
The AI generating image process is done by [Stable Diffusion](https://github.com/CompVis/stable-diffusion) and [Automatic1111 Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui).
You can view the outpainting function in below:
https://user-images.githubusercontent.com/99020933/198564805-4e96151b-df74-4a61-995b-9ffef95fa28c.mp4


<br />

## ⚡ Features

* Infinite outpainting on Photoshop
* Inpainting on Photoshop
* Inpainting/outpainting with mask

## ️ Requirements

* Graphics board, NVIDIA GeForce RTX or higher is recomended.
* Windows 7 or later
* Adobe Photoshop
* [Automatic1111 stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
* .NET Framework 4.8 runtime library

<br />

##  Install

1. [Download](https://github.com/AUTOMATIC1111/stable-diffusion-webui) latest version of **`Automatic1111 Stable Diffusion web UI (Automatic1111)`**
2. Install **`Automatic1111`** to the installation folder.
3. Check generate images on **`Automatic1111`**
4. Set command line arguments **`--api`** for **`Automatic1111`** <br />
     Edit **`webui-user.bat`**, **`set COMMANDLINE_ARGS=`** to **`set COMMANDLINE_ARGS=--api`**
###
5. Extract it to installation folder
6. At windows 10/11, right-click executable file, and select menu item **`properties`** to **`unlock`** security warning
###
7. Start **`Automatic1111`**
8. Start **`Adobe Photoshop`**
9. Start **`AI-photopainter.exe`** in the installation folder.

##  Privacy policy

- Do not send privacy information.
- Do not display online ads.
- Do not collect telemetry information.
- If online information is needed, get it from github repositories whenever possible.

*This policy only applies to AI-photopainter, and not to other libraries or software such as **`Adobe Photoshop`** or **`Automatic1111`**

<br />

##  Changelog

- Ver109 <br />
Show progress <br />
Ver109 work for Automatic1111 2022/11/05 02:00 UTC version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/30b1bcc64e67ad50c5d3af3a6fe1bd1e9553f34e

- Ver108 <br />
Support dynamic prompts <br />
Add option enable/disable wildcards and dynamic prompts <br />
Ver108 work for Automatic1111 2022/11/04 10:00 UTC version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/81973091bc07c706d056809d89221bafcd01b38a

- Ver107 <br />
Support wildcards <br />
Add import NovelAI prompt button <br />
Ver107 work for Automatic1111 2022/11/03 21:00 UTC version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/c2465f67db2529d962e311b3a520bd5cd715058b

- Ver106 <br />
Support variation<br />
Add import automatic1111's infotext button<br />
Ver106 work for Automatic1111 2022/11/02 23:00 UTC version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/commit/d98eacea40c7a40227f36dbea9cf92f90489310b

- Ver105 <br />
Support restore faces, tiling, ENSD, clip skip<br />
Set/get photoshop forground/background color <br />
Bug fix json request/response <br />
Ver105 work for Automatic1111 2022/11/01 03:00 UTC version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/5c9b3625fa03f18649e1843b5e9f2df2d4de94f9

- Ver104 <br />
Support latest version of Automatic1111's API <br />
Ver104 work for Automatic1111 2022/10/31 06:00 UTC version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/17a2076f72562b428052ee3fc8c43d19c03ecd1e


- Ver103 <br />
Save last prompt/negative/layername setting for default value <br />
Add setting layer name function <br />
Bug fix image processing exception <br />
Ver103 work for Automatic1111 2022/10/28 version<br />
https://github.com/AUTOMATIC1111/stable-diffusion-webui/tree/9ceef81f77ecce89f0c8f412c4d849210d852e82


- Ver102 <br />
Support text2image. Use generate button with pressing [shift] key <br />
Change log output of generated images to InfoText only <br />


- Ver101 <br />
Bug fix log message out <br />
Bug fix seed input <br />
Bug fix json deserialize <br />


- Ver100 <br />
Initial release

<br />

##  Suggestions and feedback
If you have any idea or suggestion, please add a github issue.

<br />



##  Thanks
AI-photopainter uses a some of tools and libraries. Thank you for these projects!

- [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
- [Automatic1111 Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)


<br />
<br />
<br />

#### Copyright (c) David




