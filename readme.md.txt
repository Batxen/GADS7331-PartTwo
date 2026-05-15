GADS7331 - Part Two
README.md

Overview:
The purpose of this GADS7331 - Part Two is to explore the implementation of Large Language Models (LLMs) within a video game project, and the extents to which its use cases are useful. For this project the LLM is used to give dialogue to the player in regards to their quest and to justify why it is the player is doing this.    

Installation Instructions:
In order for this project to run some external technologies will be required in order for the LLM to run successfully. 
Some of these technologies will only apply to the Unity Project File.
These technologies are:
1.) The Ollama Windows Application
2.) The Git (not GitHub) Windows Application
3.) A GitHub project called 'Neocortex-Unity-SDK-Main'
4.) A GitHub project called 'Neocortex-Ollama-Support-Master'
5.) The Unity Windows Application
Note: The GitHub Projects do not need to be installed directly from GitHub. Keep the tabs for the GitHub projects open as there will be a link for each that allows us to directly install the projects into Unity.  
1.) While within the Unity Project select Window -> Package Management -> Package Manager
2.) Click on the plus icon in the top left of Package Manager -> Select "Install Package for Git URL" -> Paste this link (https://github.com/neocortex-link/neocortex-unity-sdk.git) into the input field that will appear. Wait for that to finish it's installation.
3.) Click on the plus icon in the top left of Package Manager -> Select "Install Package for Git URL" -> Paste this link (https://github.com/neocortex-link/neocortex-ollama-support.git) into the input field that will appear. Wait for that to finish it's installation.
4.) Return to the Main Unity Project Page -> Select Tools -> Neocortex -> Ollama Support (You will need to have installed Ollama prior and have it open during this process).
5.) Select 'Select Model' -> Select 'Llama 3.2: 3B' 

Dependencies:
Ollama (Recommended to keep open in the background at all times and signed in)
Neocortex-Unity-SDK-Main (Will be needed for the Unity project)
Neocortex-Ollama-Support-Master (Will be needed for the Unity project)
Llama 3.2 3B (while other local models are available it is recommended you use this model due to the small scale of the project and the technical demands of this model being lower than it's peers)
An internet connection
The Git application open

Credits:
Altundas, S. 2025. "neocortex-ollama-support". [Online]. Available at: https://github.com/neocortex-link/neocortex-ollama-support (Accessed 15th May 2026).
Altundas, S. 2026. "neocortex-unity-sdk". [Online]. Available at: https://github.com/neocortex-link/neocortex-unity-sdk (Accessed 15th May 2026).

AI Tools Used:
Cursor - Assistance in code generation and the logging of the refinements-changes.md file.
Ollama - Serves as the base for the rest of the LLM.
Llama 3.2 with 3B parameters - Allows for the generation of dialogue for the quest.