# Simulacion_IA_NPC
Class taken at Universidad Panamericana

## Proyect Overview
This project focuses on leveraging the power of OpenAI's advanced language model within the Unity game engine to create dynamic and interactive Non-Player Characters (NPCs). The primary objective is to enhance the realism and engagement of NPCs by enabling them to understand and respond to player inputs in a natural and contextually appropriate manner.

![Video_Parcial_Simulacion-ezgif com-video-to-gif-converter](https://github.com/CodeWaffl3/Simulacion_IA_NPC/assets/112717957/7f801731-f524-4168-b782-35011bb285a0)


### How to use

YOU WILL NEED AN API KEY, FOR SECURITY REASONS WE DID NOT PROVIDE OUR API KEY!

The game starts in the Main Menu scene. Here, the player is presented with a simple interface featuring a "Play" button. Clicking this button transitions the player to the main level.
In the main level, players can interact with NPCs using a chat input field. The player types their message, and upon submission, the NPC's response is displayed in a dialogue bubble above the NPC. This setup allows for real-time text-based interaction, making the NPCs feel responsive and engaged with the player's input.


### How to setup your api key for use

#### Setting Up Your OpenAI Account
To use the OpenAI API, you need to have an OpenAI account. Follow these steps to create an account and generate an API key:

- Go to https://openai.com/api and sign up for an account
- Once you have created an account, go to https://beta.openai.com/account/api-keys
- Create a new secret key and save it

#### Saving Your Credentials
To make requests to the OpenAI API, you need to use your API key and organization name (if applicable). To avoid exposing your API key in your Unity project, you can save it in your device's local storage.

To do this, follow these steps:

- Create a folder called .openai in your home directory (e.g. `C:User\UserName\` for Windows or `~\` for Linux or Mac)
- Create a file called `auth.json` in the `.openai` folder
- Add an api_key field and a organization field (if applicable) to the auth.json file and save it
- Here is an example of what your auth.json file should look like:

```json
{
    "api_key": "sk-...W6yi",
    "organization": "org-...L7W"
}
```
