# VoiceBank-2023



## Specification for the VoiceBank-2023 corpus 



|                                                   |                                                                                                                                             |
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



## VoiceBank-2023 語料規格表


|                                                   |                                                                                                                                             |
|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| 語料庫名稱                                        | VoiceBank-2023 (URL: https://github.com/VoiceBank-NTPU-TW/VoiceBank-2023)                                                                   |
| 語言                                          | 國語                                                                                                                   |
| 文本/提示詞                             | 1) 第一部分(VoiceBanking): 133 短段落<br>2) 第二部分(常用片語)：556 常用片語                                          |
| 語調風格                                     | 1) 第一部分(VoiceBanking)：敘事語調<br>2) 第二部分(常用片語)：語助詞                                              |
| 用途                                              | 1) 個人化 TTS, 2) 評估構音障礙等級,  聲音品質(抖動/顫動)，以及音質(錄音環境)                  |
| # 語者 (語者類別, 性別, 構音障礙程度) | 111(總計) <br>= 39(ALS 患者) + 63(聲音捐贈者) + 9(未知)<br> = 47(女性) + 64(男性) <br>= 86(等級一：高語音可懂度) + 11(等級二) + 12(等級三) + 2(等級四:：低語音可懂度)
| # 語料 (語料分類, 性別, 語者類別, 構音障礙程度)|12,875(總計) <br>= 7,625(第一部分：VoiceBanking) + 5,250(第二部分：常用片語) <br>= 5,677(女性) + 7,198(男性) <br>= 8,876(ALS 患者) + 3,875(聲音捐贈者) + 124(未知) <br>= 8,760/2,246/1,849/20(等級 1/2/3/4)
| 語料庫總時長 (小時)                             | 29.78(all) <br>=  28.18(第一部分：VoiceBanking) + 1.60(第二部分：常用片語) <br>= 12.47(女性) + 17.31(男性) <br>= 17.66(ALS 患者) + 11.78(聲音捐贈者) + 0.34(未知) <br>= 19.37/5.74/4.58/0.09(等級 1/2/3/4)|
| 語者平均貢獻時長 (分鐘)                          |第一部分(VoiceBanking)：15.37±10.97<br>第二部分(常用片語)：5.99±5.34
| \# 字數                                    | 360,586(all) <br>= 342,486(第一部分：VoiceBanking) + 18,100(第二部分：常用片語) <br>= 153,396(女性) + 207,190(男性)<br>= 185,401(ALS 患者) + 170,387(聲音捐贈者) + 4,798(未知) <br>= 270,805/55,490/33,835/456(等級 1/2/3/4)|
| 單句語料字數                       | 第一部分(VoiceBanking): 44.13±9.03<br>第二部分(常用片語)：3.30± 0.54<br>(語句為單位的平均值±標準偏差)                  |
| 單句語料秒數                      | 第一部分(VoiceBanking)： 13.16±4.87<br>第二部分(常用片語)：1.08±0.32<br>(語句為單位的平均值±標準偏差)                   |
| 語音編碼方式                                  | 線性 PCM，48kHz 采樣率，16位元解析度，單聲道                                                                    |
| 麥克風/錄音環境                   | 主要使用USB麥克風/大部分在家或辦公室錄製                                                                                         |
| 語料檔案格式                           | 1) *.TextGrid: 根據音素切割語料，標上時間戳記(開頭/結尾)，韻律(聲調)，和詞語(詞性和標點符號)<br>2) *.txt: UTF-8編碼的原始文本文件 <br>3) *.wav: WAVE音頻文件




## Samples
### Phase-2, speakerid=019, degree of the speech impairment=1


## Download
The VoiceBank-2023 is available by request for non-commercial use. Please email to Prof. Chen-Yu Chiang, NTPU, Taiwan, for the request: cychiang@mail.ntpu.edu.tw
