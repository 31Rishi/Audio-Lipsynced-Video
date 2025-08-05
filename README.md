🎥 Automated Lip Syncing for Chatbots and Virtual Assistants

This project integrates state-of-the-art tools to generate talking virtual avatars from plain text. It uses **Bark AI** for text-to-speech generation, **MoviePy** for turning static images into video, and **Wav2Lip** for precise lip sync, producing hyper-realistic speech videos for use in virtual assistants and chatbots.

📌 Key Features
- Convert input text to expressive, multilingual speech using **Bark AI**
- Convert images into videos using **MoviePy**
- Synchronize lips in the video with speech using **Wav2Lip**
- Output: Talking avatar video with synchronized speech and mouth movement

🛠️ Tools & Technologies
- Python, Google Colab
- Bark AI (text-to-speech)
- Wav2Lip (lip sync model)
- MoviePy, NumPy, ffmpeg
- OpenCV, torch, torchvision

🧪 How to Run
> 🔗 [Open in Google Colab](https://colab.research.google.com/drive/1Vj8cJm7lOSDBPAXtmnTj-mphdZtASTfc?usp=sharing)

1. Upload image (face)
2. Provide input text
3. Bark converts text to speech
4. MoviePy builds image + audio into video
5. Wav2Lip syncs lip movements with generated speech
6. Download the final MP4

📁 Project Structure
- `Wav2Lip_LipSyncing_Avatar.ipynb`: Main code (Colab notebook)
- `demo_output/`: Sample results

📚 Research Paper
This project is part of our published paper:
> Shah, R., Garg, D., Chaudhari, N., Goel, P., & Sheikh, T. (2024). *Automated Lip Syncing for Chatbots and Virtual Assistants*. In **IEEE ICUIS 2024**. 

📌 Authors
- Rishi Shah
- Dweepna Garg
- Niasarg Chaudhari
- Parth Goel
- Tanvi Sheikh

📃 License
This project is for academic and research purposes only. Check original [Wav2Lip license](https://github.com/Rudrabha/Wav2Lip).

