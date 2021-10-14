This is the demo page for the paper [Towards Automatic Transcription of Polyphonic Electric Guitar Music: A new Dataset and A Multi-loss Transformer Model]

## Abstract
The guitar is widely used in various musical genres and is one of the most accessible instruments people can play. However, research on guitar signal processing, such as automatic guitar transcription, has not drawn much attention in recent years, possibly due to the scarce of relevant labeled datasets. In this paper, we propose a new dataset named StratocasterDB, that contains annotations of the electric guitar performance of 240 tablatures rendered with different tones. Moreover, we benchmark the performance of two well-known transcription models proposed originally for the piano on this  dataset, along with a multi-loss Transformer model that we newly propose. Our evaluation on this dataset and a separate set of real-world recordings demonstrate the influence of timbre on the accuracy of guitar transcription, the potential of using multiple losses for Transformers, as well as the room for improvement for this task.

### Realistic Data Transcription


### Training Data Sample
<!-- Audio in the same row share identical first 4 bars prompt. ***No grooving*** and ***Hard grooving***  model are asked to generate 16-bar continuations based on the prompt input. -->

<!-- |   |Real data|No grooving|Hard grooving| -->
<!-- |1.|<audio src="result/real data/0.wav" controls="" preload=""></audio>|<audio src="result/no grooving/0.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/0.wav" controls="" preload=""></audio>|
|2.|<audio src="result/real data/1.wav" controls="" preload=""></audio>|<audio src="result/no grooving/1.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/1.wav" controls="" preload=""></audio>|
|3.|<audio src="result/real data/2.wav" controls="" preload=""></audio>|<audio src="result/no grooving/2.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/2.wav" controls="" preload=""></audio>|
|4.|<audio src="result/real data/3.wav" controls="" preload=""></audio>|<audio src="result/no grooving/3.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/3.wav" controls="" preload=""></audio>|
|5.|<audio src="result/real data/4.wav" controls="" preload=""></audio>|<audio src="result/no grooving/4.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/4.wav" controls="" preload=""></audio>| -->

<!-- ### Demo Video
This video recording is a guitarist from our team playing a generated tab which is generated from scratch.
<iframe width="800" height="500" src="https://www.youtube.com/embed/yccH6kvinq0">
</iframe> -->

### Contact 
Yu-Hua Chen f08946011@ntu.edu.tw
