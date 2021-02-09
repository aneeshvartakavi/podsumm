# Audio Summarization For Podcasts

_Aneesh Vartakavi, Amanmeet Garg, Zafar Rafii_, Gracenote

This page contains audio and visual examples from our paper titled, *Audio Summarization for Podcasts*.

> We propose a novel system for automatically generating audio summaries for podcasts, allowing listeners to have quick previews of podcast episodes. The proposed system first transcribes the audio from a podcast using automatic speech recognition (ASR), then summarizes the transcript using automatic extractive summarization, and finally returns the audio associated with the text summary. Motivated by a lack of datasets for this task, we created our own by transcribing the audio from various podcasts and summarizing the transcripts using a manual annotation tool. Using these text summaries, we fine-tuned a recent Transformer-based summarization model to specifically handle podcast summaries. Our system achieves ROUGE-(1/2/L) F-scores of 0.63/0.53/0.63, respectively, showing good performance for podcast summarization.

---
### Example 1

![Figure 1](https://drive.google.com/file/d/1UKXgwQGNfSlUbv_gm34NTbd1TDMwXFpw/view?usp=sharing)
#### Audio Links
[Original](https://play.podtrac.com/npr-510310/edge1.pod.npr.org/anon.npr-podcasts/podcast/npr/nprpolitics/2020/01/20200130_nprpolitics_20200130_nprpolitics-ca318b72-e2a9-42dd-9b98-70028b39a35b.mp3?awCollectionId=510310&awEpisodeId=801452169&orgId=1&topicId=1014&d=911&p=510310&story=801452169&t=podcast&e=801452169&size=14545583&ft=pod&f=510310) |
[PreSumm (No FT)](./audio/PodSumm_1_no_ft.mp3?raw=true) |
[PreSumm (FT + Aug)](https://drive.google.com/file/d/1U7lBU7QxDaksKja3H4sONAzzFTKnLopb/view?usp=sharing)

---
### Example 2

![Figure 2](./images/PodSumm_fig2.jpg?raw=true)
#### Audio Links
[Original]() |
[PreSumm (No FT)](./audio/PodSumm_2_no_ft.mp3?raw=true) |
[PreSumm (FT + Aug)](./audio/PodSumm_2_ft.mp3?raw=true)

---
Gracenote, the Gracenote logo and logotype are either a registered trademark or a trademark of Gracenote, Inc. in the United States and/or other countries. © 2000-present. Gracenote, Inc. All rights reserved.  
