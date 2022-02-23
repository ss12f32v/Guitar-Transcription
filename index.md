This is the demo page for the paper **Towards Automatic Transcription of Polyphonic Electric Guitar Music: A new Dataset and A Multi-loss Transformer Model**

## Abstract
In this paper, we propose a new dataset named EGDB, that con-tains transcriptions of the electric guitar performance of 240 tab-latures rendered with different tones. Moreover, we benchmark theperformance of two well-known transcription models proposed orig-inally for the piano on this dataset, along with a multi-loss Trans-former model that we newly propose. Our evaluation on this dataset and a separate set of real-world recordings demonstrate the influenceof timbre on the accuracy of guitar sheet transcription, the potentialof using multiple losses for Transformers, as well as the room forfurther improvement for this task.


### Training Data Sample
Audio are sampled from training split with different timbre in each column.

|   |DI|Marshall|Fender-twins|Mesa|
|1.|<audio src="Guitar_Transcription_sample/Training/0701_3_c_DI.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_marshall.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_ft.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_mesa.wav" controls="" preload=""></audio>|
|2.|<audio src="Guitar_Transcription_sample/Training/0503_1_a_DI.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0503_1_a_marshall.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0503_1_a_ft.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0503_1_a_mesa.wav" controls="" preload=""></audio>|



### Realistic Data Transcription

|Source|Proposed model|
|<audio src="Guitar_Transcription_sample/RealData/clip1.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip1.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip2.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip2.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip3.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip3.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip4.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip4.wav" controls="" preload=""></audio>|
|<audio src="Guitar_Transcription_sample/RealData/clip5.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/RealDataTranscription/clip5.wav" controls="" preload=""></audio>|




### Dataset
<a href="https://drive.google.com/drive/folders/1ZEy5dytEDquxyf_WYDhKgadSCgPsq_tD?usp=sharing">Google Drive Link</a>

### Contact 
Yu-Hua Chen f08946011@ntu.edu.tw
