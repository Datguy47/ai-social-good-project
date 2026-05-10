# ai-social-good-project


Problem: The problem is that Hazardous waste is difficult to identify quickly in workplaces such as recycling centers, hospitals, and waste disposal facilities. Workers depend on manual inspection to know what dangerous material it is. The process can be slow and might cause human error. Improper disposal of hazardous wastes may cause pollution of the environment. In order to keep up with the amount of waste, it is necessary to have a fast way of detecting hazardous materials.

AI Capability: This prototype use google gemini multimodel AI model combined with computer vision techques to analyze hazardous waste images. The AI can interpret visual information from an image and would generate responses with default language prompts. which the AI needs time to learn more until it's ready. It fits because the AI can identify hazardous items, categorize waste types, and perform safety analysis to evaluate the environmental risk.  Gemini AI analyzes the hazardous waste material, it is necessary to run the input image and the command by the user simultaneously through the AI.


Workflow: The workflow begins by uploading an image into Google Colab using the files.upload() function. The uploaded image is displayed using the Pillow library so the user can verify the image before analysis. Of course, if it's a real thing the camera would identify without uploading an image, which would be faster. This then would analyze the image sends both an image and the hazardous waste question to Gemini AI. This would generate a response based on what it can detect in the image. In the prototype, I made it so that you can ask a question about the picture to know more about it in real time
<img width="1104" height="798" alt="image" src="https://github.com/user-attachments/assets/537cf249-f3cd-4d99-869d-36d8b01c58f1" />
