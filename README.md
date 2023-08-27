# VoiceBank-2023
VoiceBank-2023 is the speech corpus designed to construct personalized Mandarin text-to-speech (TTS) systems. 

## Authors
* Speech and Multimedia Signal Processing Laboratory (SMSPLab), National Taipei University (NTPU), Taiwan
   * Prof. Chen-Yu Chiang (corresponding author), cychiang@mail.ntpu.edu.tw
   * Jia-Jyu SU, Pang-Chen LIAO, Yen-Ting LIN, Wu-Hao LI, and Pin-Han LIN
* AcoustInTek Co., Ltd., Taiwan
   * Cheng-Che KAO, Wei-Cheng CHEN, Jen-Chieh CHIANG, and Wen-Yang CHANG
* National Yang Ming Chiao Tung University (NYCU), Taiwan
   * Guan-Ting LIOU

## Design of the VoiceBank-2023
The VoiceBank-2023 corpus was designed to have two parts with eight sub-corpora:
* Part 1 - VoiceBanking (sub-corpora 1 and 2):
    * Sub-corpus 1: covers all Mandarin initial and final types
    * Sub-corpus 2: enlarge sample size for voice-banking

* Part 2- Common Phrases (sub-corpora 3 to 8)
   * Sub-corpora 3 to 8: comprised of 1 to $\geq 6$-character phrases to enrich the communicative functions
 
## Brief Statistics of the VoiceBank-2023 corpus
* \# of speakers: 111
   * 39 ALS patients + 63 voice donors + 9 unknowns
   * 47 females + 64 males
* \# of Utterances: 12,875
   * 7,625 (Part-1, VoiceBanking) + 5,250 (Part-2, Common Phrases)
* Total Duration: 29.78 hours
   * 28.18 hours (Part-1:VoiceBanking) + 1.60 hours (Part-2: Common Phrase)
* \# of Syllables: 360,586
   * 342,486 (Part-1:VoiceBanking) + 18,100 (Part-2: Common Phrase)


## Specification for the VoiceBank-2023 corpus 

|||
|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Corpus Name                                        | VoiceBank-2023 (URL: https://github.com/VoiceBank-NTPU-TW/VoiceBank-2023)                                                                   |
| Language                                           | mostly Taiwanese Mandarin                                                                                                                   |
| Text/Prompt materials                              | 1) Part-1 (VoiceBanking): 133 short paragraphs<br>2) Part-2 (Common Phrases): 556 common phrases                                          |
| Speaking Style                                     | 1) read speech for  Part-1 (VoiceBanking)<br>2) spontaneous like for Part-2 (Common Phrases)                                              |
| Uses                                               | 1) personalized TTS, 2) assessments of dysarthria, voice quality (jitter/shimmer), and sound quality (regarding recording)                  |
| # of Speakers (speaker types, gender, dysarthria degree) | 111(all) <br>= 39(ALS patients) + 63(voice donors) + 9(unknowns) <br>= 47(female) + 64(male) <br>= 86(degree 1: high speech intelligibility) + 11(degree 2) + 12(degree 3) + 2(degree 4: low speech intelligibility)
| # of Utterances (prompt type, gender, speaker type, dysarthria degree)|12,875(all) <br>= 7,625(Part-1, VoiceBanking) + 5,250(Part-2, Common Phrases) <br>= 5,677(female) + 7,198(male) <br>= 8,876(patient) + 3,875(donor) + 124(unknown) <br>= 8,760/2,246/1,849/20(degree 1/2/3/4)
| Total Duration (hours)                             | 29.78(all) <br>= 28.18(Part-1:VoiceBanking) + 1.60(Part-2: Common Phrase) <br>= 12.47(female) + 17.31(male) <br>= 17.66(patients) + 11.78(donors) + 0.34(unknowns) <br>= 19.37/5.74/4.58/0.09(degree 1/2/3/4)|
| Duration for each Speaker (minutes)                          |Part-1 (VoiceBanking): 15.37±10.97<br>Part-2 (Common Phrases): 5.99±5.34
| \# of Syllables                                    | 360,586(all) <br>= 342,486(Part-1:VoiceBanking) + 18,100(Part-2: Common Phrase) <br>= 153,396(female) + 207,190(male)<br>= 185,401(patients) + 170,387(donors) + 4,798(unknowns) <br>= 270,805/55,490/33,835/456(degree 1/2/3/4)|
| Utterance Length in Syllable                       | Part-1 (VoiceBanking): 44.13±9.03<br>Part-2 (Common Phrases): 3.30± 0.54<br>(utterance-wise mean±standard deviation)                    |
| Utterance Length in Second                         | Part-1 (VoiceBanking): 13.16±4.87<br>Part-2 (Common Phrases): 1.08±0.32 <br>(utterance-wise mean±standard deviation)                  |
| Waveform Encoding                                  | linear PCM, 48kHz sample rate, 16-bit resolution, mono channel                                                                              |
| Microphone/Recording Environment                   | mostly USB quality microphone/mostly home or office                                                                                         |
| Files for each Utterance                           | 1) *.TextGrid: time alignments for phonetic (initial/final), syllabic (tone), and word (part of speech and punctuation marks)<br>2) *.txt: raw text file in UTF-8<br>3) *.wav: WAVE file




## Samples
Here, we provide four zipped files of the corpus samples for four speakers with dysarthria degrees 1, 2, 3, and 4. Note that the waveforms provided have been pitch- and speed-shifted by some signal processing methods to remove speaker identities without destroying the naturalness of the speech. 
1. [download dysarthria degree 1 (fluent speech without speech impairment)](https://drive.google.com/file/d/1mlp1V1lHa8eXAuVkplAgGGvhuA4kCLB7/view?usp=drive_link)
2. [download dysarthria degree 2 (disfluent in prosody)](https://drive.google.com/file/d/1KFTy3F74Qaed6fzn-X3OD68f8qOvlOma/view?usp=drive_link)
3. [download dysarthria degree 3 (light dysarthria but high speech intelligibility)](https://drive.google.com/file/d/1eMBj8C6jnpvNJ6wTG79QhTWHzflVVZvb/view?usp=drive_link)
4. [download dysarthria degree 4 (dysarthria and low speech intelligibility)](https://drive.google.com/file/d/13A-W9azsL0DZ1b-2nia7bV-ZXN2JrrdB/view?usp=drive_link)


## Download Full VoiceBank-2023 Corpus
The VoiceBank-2023 is available by request for non-commercial use. Please email Prof. Chen-Yu Chiang, NTPU, Taiwan, for the request: cychiang@mail.ntpu.edu.tw

## Acknowledgment
We thank the 61 voice donors for banking their voices in the Asia-Pacific Medical Students' Symposium (APMSS) 2022, hosted by the NTU College of Medicine, Taiwan. We also thank Prof. Jing-Yi, Jeng, NKNU, Taiwan, for providing Mandarin common phrases as the prompts on the VoiceBanking website, Prof. Sin-Horng Chen and Prof. Yih-Ru Wang of NYCU, Taiwan, for providing Treebank-SR corpus and the word tokenizer and POS tagger.
