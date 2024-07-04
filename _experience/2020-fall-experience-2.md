---
title: "Huawei India RnD - Data Science Intern (July 2020)"
collection: experience
type: "Data Science Intern"
permalink: /experience/2020-fall-experience-2
venue: "Data Science Intern"
location: "Bengaluru, India (Remote)"
---

Huawei Technologies India is the largest overseas software development center of Huawei, a leading global information and communications technology (ICT) solutions provider. Established in the year 1999 in Bengaluru, Huawei Technologies India is engaged in component / platform / product development aligned with Huawei’s global product development strategy, roadmap, architecture & solutions.

* **Speech Language Detection:**
  - **Objective:** Develop a machine learning model to detect language from speech utterances for European languages.
  - **Actions:** 
    - Identified the need to transfer domain knowledge from speech to vision, leveraging extensive computer vision literature on multi-label classification.
    - Utilized mel-spectrogram images as effective speech representations for language detection.
    - Trained CNN models like InceptionV3, DenseNet201, and VGG16 on speech samples from open-source datasets such as LibriSpeech and CommonVoice.
  - **Results:** 
    - The InceptionV3-based model achieved a 97% classification accuracy for popular European languages, including English, Italian, and Spanish.

* **Automatic Speech Recognition:**
  - **Objective:** Develop a deep neural network-based approach for Speech-to-Text transcription in European languages, focusing on high performance in low-resource languages with limited data availability.
  - **Actions:**
    - Trained the Jasper Network with Connectionist Temporal Classification (CTC) for English ASR.
    - Applied transfer learning principles to extend training to Spanish, a low-resource language, using shared language tokens.
  - **Results:**
    - Achieved a Word Error Rate (WER) of 19.78% for Spanish ASR, a competitive benchmark for ASR models in 2020.

* **Reducing Error Rates with Post-Processing & Application to Music Transcription:**
  - **Objective:** Experiment with text processing techniques to correct transcription spellings and improve WER. Investigate the application of trained ASR models to music lyric transcription.
  - **Actions:**
    - Integrated spelling correction models like DeepPavlov and Enchant to enhance English ASR accuracy.
    - Utilized the Spleeter library to isolate vocals from music videos, followed by ASR.
  - **Results:**
    - Implemented text processing techniques resulting in a 7% relative improvement in English ASR.
    - Identified challenges in applying ASR models to the music domain, noting difficulties due to background sounds and irregular enunciations for musical effect.

---
