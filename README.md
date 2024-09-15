# stickit
We developed a project that allows users to input an image and a prompt, which are then processed to generate a 3D sticker. The entire coding was done in Python, where we used OpenCV for processing the input image and models from Hugging Face to handle the prompt-based transformations. To make the tool more accessible, we built an interface using Gradio, allowing users to easily upload their images and prompts. Initially, we experimented with Stable Diffusion models, but the results were not up to our expectations in terms of quality. We then tried using the SDXL model, which gave better results but required too much space and processing power for our local setup on VS Code. Due to these hardware limitations, we moved the project to Google Colab, where we could access more resources. However, even with Colab, we faced some performance issues, particularly with memory and processing speed. To work around this, we decided to use Pix2Pix to convert the processed images into 3D stickers, which provided a more efficient and manageable solution for generating the final 3D output.
Requirements
Python 3.8+
OpenCV
Hugging Face Transformers
Gradio
Pix2Pix
Google Colab (for large-scale processing)
![Screenshot 2024-09-12 142212](https://github.com/user-attachments/assets/62010482-03c6-4ff7-9763-98bf5eb40176)
![Screenshot 2024-09-15 201539](https://github.com/user-attachments/assets/390a3201-f491-4d18-828b-125939ca2eff)
![Screenshot 2024-09-15 201409](https://github.com/user-attachments/assets/e208d798-ba7f-4e83-84e7-b3ff3a81a5f5)
![Screenshot 2024-09-15 201511](https://github.com/user-attachments/assets/356064b8-78f0-4cae-854a-3c3b44788c1b)
