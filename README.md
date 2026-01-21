# voice-conversion-
🎙️ Voice Conversion using GANs
📌 Project Overview

This project implements a Voice Conversion system using Generative Adversarial Networks (GANs). The goal is to transform a source speaker’s voice into a target speaker’s voice without changing the linguistic content, while preserving naturalness and audio quality.

The pipeline includes audio preprocessing, feature extraction, GAN-based model training, and audio reconstruction using PyTorch and audio processing libraries.

🚀 Features

Audio preprocessing using Librosa
Mel-spectrogram and waveform visualization
Tensor-based dataset preparation
GAN architecture for voice conversion
Generator & Discriminator models implemented in PyTorch
End-to-end training workflow
Audio playback for qualitative evaluation
🛠️ Technologies & Libraries Used
Python 3
PyTorch / TorchAudio
Librosa
NumPy & Pandas
Matplotlib
SoundFile
IPython Display

📂 Project Structure
.
├── voice conversion.ipynb
├── metadata.csv
├── processed_tensors/
│ ├── audio_tensors.pt
│ └── spectrograms.pt
├── samples/
│ ├── source_audio.wav
│ └── converted_audio.wav
└── README.md

⚙️ Installation & Setup

Clone the repository
bash
git clone https://github.com/your-username/voice-conversion-gan.git
cd voice-conversion-gan

Install required dependencies
bash
pip install librosa soundfile matplotlib torch torchaudio pandas numpy

3.Open the notebook
bash
jupyter notebook "voice conversion.ipynb"

👤 Author

Hamd Zahid
AI / Machine Learning Engineer
Focused on Deep Learning, GANs, and Speech Processing

📜 License

This project is for educational and research purposes.
You may modify and use it with proper attribution.
