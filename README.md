# ai-social-good-project


Problem: The problem is that Hazardous waste is difficult to identify quickly in workplaces such as recycling centers, hospitals, and waste disposal facilities. Workers depend on manual inspection to know what dangerous material it is. The process can be slow and might cause human error. Improper disposal of hazardous wastes may cause pollution of the environment. In order to keep up with the amount of waste, it is necessary to have a fast way of detecting hazardous materials.

AI Capability: This prototype uses the Google Gemini multimodal AI model combined with computer vision techques to analyze hazardous waste images. The AI can interpret visual information from an image and would generate responses with default language prompts, which the AI needs time to learn more about until it's ready. It fits because the AI can identify hazardous items, categorize waste types, and perform safety analysis to evaluate the environmental risk.  Gemini AI analyzes the hazardous waste material. It is necessary to run the input image and the command by the user simultaneously through the AI.


Workflow: The workflow begins by uploading an image into Google Colab using the files.upload() function. The uploaded image is displayed using the Pillow library so the user can verify the image before analysis. Of course, if it's a real thing the camera would identify without uploading an image, which would be faster. The system use four preset waste prompt object detection, hazard classification, safety analysis, and recommended action.
<img width="1104" height="798" alt="image" src="https://github.com/user-attachments/assets/537cf249-f3cd-4d99-869d-36d8b01c58f1" />

This then would analyze the image sends both an image and the hazardous waste question to Gemini AI. This would generate a response based on what it can detect in the image. 
<img width="1708" height="691" alt="image" src="https://github.com/user-attachments/assets/9e1153ce-dd46-452b-9bc9-842a0608b4ff" />

In the prototype, In the prototype, I made it so that you can ask a question about the picture to know more about it in real time
<img width="1595" height="436" alt="image" src="https://github.com/user-attachments/assets/5e4ee110-72bb-4d8a-8e5d-f353934a7b3e" />





