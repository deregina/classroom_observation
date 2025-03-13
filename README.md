# Empowering Rural Education: AI-powered Classroom Observation  
  
### :ledger: Introduction  
Texas has the largest number of rural students in the U.S., with 20% of campuses located in rural areas.  However, rural schools face significant challenges in teacher recruitment, retention and professional development of teachers. This challenge negatively impacts course quality, especially in STEM fields. Despite these challenges, research on rural education and its evaluation remains limited.  
  
This study explores the potential of **machine learning models to observe classroom instruction and provide valuable feedback to teachers.**  
Additionally, it introduces **a platform where educators can upload classroom videos to receive both transcripts and Pedagogical Observation Protocol (POP; Lara-Alecio & Parker, 1994) predictions, enhancing their ability to assess and improve teaching practices.**

-----

### :video_camera: Demo Video
https://github.com/user-attachments/assets/05726360-8db7-43df-8b78-072ba047b296
  
### :computer: Model
- **Whisper**: a speech recognition model (Radford et al., 2022)
- **BERT**: a pre-trained transformer model for natural language processing (Radford et al., 2019)
- **Transfer learning on the BERT model to predict each category of POP coding**
  
### 📑 Dataset
- Classroom recordings of science lessons from 110 sessions across 97 rural schools

### 📊 Results  
The classification models were evaluated by comparing their predictions to the human-coded POP labels. 

|   | Activity Structure | Curriculum | ESL Strategy | Language (student) | Language (teacher) | Language Content | Mode | Physical Group |
|     :---:      | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
| F1 score       | 0.415 | **0.979** | 0.491 | **0.692** | **0.907** | **0.851** | 0.426 | **0.666**
| Top-1 Accuracy | 0.439 | 0.986 | 0.692 | 0.990 | 0.995 | 0.941 | 0.677 | 0.809
| Top-2 Accuracy | 0.600 | 0.997 | 0.692 | 0.990 | 0.995 | 0.941 | 0.677 | 0.809
  
  
### :ledger: Conclusion  
AI classroom observation technology could support rural schools by enabling real-time monitoring of teaching practices and providing reliable, valid, and timely feedback. Through a platform providing classroom transcripts and POP predictions, this has the potential to enhance educational quality and support continuous professional development for teachers in rural areas facing resource limitations.

### :ledger: Acknowledgements  
This work was supported by funding from Virtually-Infused Collaborations for Teaching and Learning Opportunities for Rural Youth: Implementation and Evaluation of Online and Face-to-Face Delivery in High-Needs Schools (Project VICTORY S411B200055), funded by Education Innovation and Research, U.S. Department of Education.
