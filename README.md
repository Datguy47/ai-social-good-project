# ai-social-good-project


Problem: The problem is that Hazardous waste is difficult to identify quickly in workplaces such as recycling centers, hospitals, and waste disposal facilities. Workers depend on manual inspection to know what dangerous material it is. The process can be slow and might cause human error. Improper disposal of hazardous wastes may cause pollution of the environment. In order to keep up with the amount of waste, it is necessary to have a fast way of detecting hazardous materials.

AI Capability: This prototype uses the Google Gemini multimodal AI model combined with computer vision techques to analyze hazardous waste images. The AI can interpret visual information from an image and would generate responses with default language prompts, which the AI needs time to learn more about until it's ready. It fits because the AI can identify hazardous items, categorize waste types, and perform safety analysis to evaluate the environmental risk.  Gemini AI analyzes the hazardous waste material. It is necessary to run the input image and the command by the user simultaneously through the AI.


Workflow: The workflow begins by uploading an image into Google Colab using the files.upload() function. The uploaded image is displayed using the Pillow library so the user can verify the image before analysis. Of course, if it's a real thing the camera would identify without uploading an image, which would be faster. The system use four preset waste prompt object detection, hazard classification, safety analysis, and recommended action.
<img width="1104" height="798" alt="image" src="https://github.com/user-attachments/assets/537cf249-f3cd-4d99-869d-36d8b01c58f1" />

This then would analyze the image sends both an image and the hazardous waste question to Gemini AI. This would generate a response based on what it can detect in the image. 
<img width="1708" height="691" alt="image" src="https://github.com/user-attachments/assets/9e1153ce-dd46-452b-9bc9-842a0608b4ff" />

In the prototype, I made it so that you can ask a question about the picture to know more about it in real time
<img width="1595" height="436" alt="image" src="https://github.com/user-attachments/assets/5abf0975-e35c-4f33-b2b8-88d0193f89f0" />

Failure Case: The one failure of this would be that this AI could not detect what type of Hazardous waste it is. The only time it can detect if there is a clear image of a truck with show warning of what waste is inside the truck. There could be times when a truck gets a leak unnoticed, and the truck would be gone, which makes it harder for AI to detect it. There could be times when something in the screenshot would be hidden, which would cause the AI to not know what it's looking at and would probably have to guess.
<img width="1810" height="332" alt="image" src="https://github.com/user-attachments/assets/50b1af96-326a-4b9d-8306-2df1b78e448b" />




Oversight and Tradeoff: People are still needed since the AI system is designed to help workers rather than replace them. This AI detects and confirms if hazards exist before taking action. The main tradeoff is balancing automation with reliability. The AI system improves in monitoring speed and reduces manual inspection workload, and sometimes can still produce false positives or may miss detection. The AI involving camera installation would be expensive. Even when it has these limitations, this project shows how AI in image analysis can improve hazardous waste and protect lives.



