This is the demo page for the paper **Towards Automatic Transcription of Polyphonic Electric Guitar Music: A new Dataset and A Multi-loss Transformer Model**

## Abstract
The guitar is widely used in various musical genres and is one of the most accessible instruments people can play. However, research on guitar signal processing, such as automatic guitar transcription, has not drawn much attention in recent years, possibly due to the scarce of relevant labeled datasets. In this paper, we propose a new dataset named StratocasterDB, that contains annotations of the electric guitar performance of 240 tablatures rendered with different tones. Moreover, we benchmark the performance of two well-known transcription models proposed originally for the piano on this  dataset, along with a multi-loss Transformer model that we newly propose. Our evaluation on this dataset and a separate set of real-world recordings demonstrate the influence of timbre on the accuracy of guitar transcription, the potential of using multiple losses for Transformers, as well as the room for improvement for this task.

### Realistic Data Transcription

Test
### Training Data Sample
Audio are sampled from training split with different timbre in each column.

|   |DI|Marshall|Fender-twins|Mesa|
|1.|<audio src="Guitar_Transcription_sample/Training/0701_3_c_DI.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_marshall.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_ft.wav" controls="" preload=""></audio>|<audio src="Guitar_Transcription_sample/Training/0701_3_c_mesa.wav" controls="" preload=""></audio>|


<!-- ### Demo Video
This video recording is a guitarist from our team playing a generated tab which is generated from scratch.
<iframe width="800" height="500" src="https://www.youtube.com/embed/yccH6kvinq0">
</iframe> -->

### Contact 
Yu-Hua Chen f08946011@ntu.edu.tw
