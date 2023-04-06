---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Research Fellow at the Department of Electrical and Computer Engineering (ECE), National University of Singapore (NUS). Prior to that, I have received a Ph.D. degree from the National University of Singapore, supervised by Prof. [Haizhou Li](https://colips.org/~eleliha/) (IEEE Fellow) and Prof. [Shuzhi Sam Ge](https://cde.nus.edu.sg/ece/staff/ge-shuzhi-sam/) (IEEE Fellow). During my PhD studies, I  was a visiting research scholar at National Institute of Informatics (Japan), supervised by Prof. [Junichi Yamagishi](https://researchmap.jp/read0205283?lang=en). I also studied at the Speech Processing Courses Summer School at the University of Crete, supervised by Prof. [Yannis Stylianou](https://www.csd.uoc.gr/CSD/index.jsp?custom=yannis_stylianou&lang=en) (IEEE Fellow). I received a B.Sc degree from Nanjing University, Nanjing, China in 2017.

My research interest includes automatic lyrics transcription, speech recognition, speech-to-singing conversion, singing information processing, music information retrieval and multi-modal processing. I have published more than ten papers in leading journals and conferences, including IEEE/ACM Transaction on Audio, Speech and Language Processing (TALSP), Speech Communications, IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), INTERSPEECH, IEEE APSIPA ASC, Speaker Odyssey, SMC and IEEE ICOT.

# 📜 Research Area
<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Speech Processing </font>: <BR>&nbsp;&nbsp; Automatic Speech Recognition；Speech-to-Singing Conversion; Voice Conversion; Speech Synthesis</td>
    <td style="border: none;"> <font color="#0b5394"> Singing Processing </font>: <BR>&nbsp;&nbsp; Speech-to-Singing Conversion; Singing Voice Conversion; Automatic lyrics transcription of Solo-singing; Lyrics-to-Audio Alignment</td>
    <td style="border: none;"> <font color="#0b5394"> Music Information Retrieval </font>: <BR>&nbsp;&nbsp; Automatic lyrics transcription of Polyphonic Music; Automatic Chord Transcription; Music Source Separation; Automatic Musical Genre Recognition</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none;"> <font color="#0b5394"> Multi-modal Processing </font>: <BR>&nbsp;&nbsp; Audio-visual active speaker detection </td>
    <td style="border: none;"> <font color="#0b5394"> Self-supervised Learning </font>: <BR>&nbsp;&nbsp; Self-supervised speech processing; Self-supervised Language processing </td>
  </tr>
</table>

# 💻 Research Experiences
- *2022.11 - Present*, Research Fellow, National University of Singapore (NUS), Singapore.
- *2022.07 - 2022.08*, Research Scholar, National Institute of Informatics, Japan.
- *2019.07*, Research Scholar, University of Crete, Greece.
- *2018.11 - 2021.12*, Research Engineer, National University of Singapore (NUS), Singapore.
- *2018.01 - 2018.11*, Research Asistant, National University of Singapore (NUS), Singapore.

# 📖 Educations
- *2017.08 - 2022.10*, Ph.D. in Electrical and Computer Engineering, National University of Singapore (NUS), Singapore.
- *2013.09 - 2017.07*, B.Eng. in Electronic Information Science and Technology, Nanjing University, Nanjing, China.


# 🔥 News
- *2023*: &nbsp;🎉🎉 Two papers have been accepted by ICASSP 2023!
- *2020*: &nbsp;🎉🎉 Won first place for two tasks in Automatic Lyrics-to-Audio Alignment Task in Music Information Retreval Evaluation eXchange International Benchmarking Competition 2020. Check it in [NUS ECE news]().
- *2019*: &nbsp;🎉🎉 Received Best Poster Award Runner Up Prize at 4th Workshop for Young Female Researchers in INTERSPEECH, Graz, Austria. Check it in [NUS ECE news]().


# 📝 Publications 
-- **Journal Papers** --
- **Xiaoxue Gao**, Chitralekha Gupta, Haizhou Li, [PoLyScriber: Integrated Training of Extractor and Lyrics Transcriber for Polyphonic Music](https://arxiv.org/pdf/2207.07336.pdf), submitted to TALSP, 2023.
- **Xiaoxue Gao**, Chitralekha Gupta, Haizhou Li, [Automatic Lyrics Transcription of Polyphonic Music with Lyrics-Chords Multi-Task Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9833328), TALSP, 2022.
- Bidisha Sharma, **Xiaoxue Gao**, Karthika Vijayan, Xiaohai Tian and Haizhou Li, [NHSS: A Speech and Singing Parallel Database](https://arxiv.org/pdf/2012.00337.pdf), Speech Communication, 2021.


-- **Conference Papers** --
- **Xiaoxue Gao**, Xianghu Yue, Haizhou Li, [Self-Transriber: Few-shot Lyrics Transcription with Self-training](https://arxiv.org/pdf/2211.10152.pdf), ICASSP, 2023.
- Xianghu Yue, **Xiaoxue Gao<sup>`*`</sup>**, Haizhou Li, [token2vec: A Joint Self-Supervised Pre-training Framework Using Unpaired Speech and Text](https://arxiv.org/pdf/2211.10152.pdf), ICASSP, 2023.
- **Xiaoxue Gao**, Chitralekha Gupta, Haizhou Li, [Genre-conditioned Acoustic Models for Automatic Lyrics Transcription of Polyphonic Music](https://arxiv.org/pdf/2204.03307.pdf), ICASSP, 2022.
- **Xiaoxue Gao**, Chitralekha Gupta, Haizhou Li, [Music-robust Automatic Lyrics Transcription of Polyphonic Music](https://arxiv.org/pdf/2204.03306.pdf), SMC, 2022.
- **Xiaoxue Gao**, Xiaohai Tian, Rohan Kumar Das, Yi Zhou and Haizhou Li, [Personalized Singing Voice Generation Using WaveRNN](https://www.researchgate.net/profile/Gao-Xiaoxue/publication/341120657_Personalized_Singing_Voice_Generation_Using_WaveRNN/links/5eafe41492851cb2677310c3/Personalized-Singing-Voice-Generation-Using-WaveRNN.pdf), Speaker Odyssey, 2020.
- **Xiaoxue Gao**, Xiaohai Tian, Rohan Kumar Das, Yi Zhou and Haizhou Li, [Speaker-independent Spectral Mapping for Speech-to-Singing Conversion](https://d1wqtxts1xzle7.cloudfront.net/82715109/200-libre.pdf?1648314311=&response-content-disposition=inline%3B+filename%3DSpeaker_independent_Spectral_Mapping_for.pdf&Expires=1680773502&Signature=fXioJt8xbXCq~ZZ1Gr~T8TFJ1f4oau0XgWjk8kEneKtCAi634GEp~~giCwOkcKJetrh1cesPZt1Aga-d9KEegslWcYxgEdMOxsitE1xd~~Vaxy6rkFBFYirCd5nzpj64Ny456rqnMDKuYnrtl~2FGqn0LZw7flnMIY8BAwEZ-FoO5SflAlyM4QHjNmW~TvkQK0hXkP2JxjwGXWkvOW24fGk3LbeVgOc02VKs72DiciO3Tmex6MEt--t~MC9H6D1HA-RhAWBM8pdJ8E99dilu2Lgg2GH0WgmeEbG~~mmGq7mu2ZkkqPqqqy7LM79rqYKL6olDrryblFpmW3Ux6ViLPw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA), IEEE APSIPA ASC, 2019.
- Chitralekha Gupta, Karthika Vijayan, Bidisha Sharma, **Xiaoxue Gao** and Haizhou Li, [NUS Speak-to-Sing: A Web Platform for Personalized Speech-to-Singing Conversion](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/8041.pdf), INTERSPEECH, 2019.
- Karthika Vijayan, **Xiaoxue Gao** and Haizhou Li, [Analysis of Speech and Singing Signals for Temporal Alignment](http://www.apsipa.org/proceedings/2018/pdfs/0001893.pdf),IEEE APSIPA ASC 2018
- **Xiaoxue Gao**, Berrak Sisman, Rohan Kumar Das and Karthika Vijayan, [NUS-HLT Spoken Lyrics and Singing (SLS) Corpus](https://www.researchgate.net/profile/Berrak-Sisman/publication/328214772_NUS-HLT_Spoken_Lyrics_and_Singing_SLS_Corpus/links/5bda9a38a6fdcc3a8db5091b/NUS-HLT-Spoken-Lyrics-and-Singing-SLS-Corpus.pdf), IEEE ICOT, 2018




# 🎖 Honors and Awards
- *2020* **Ranked first** in Automatic Lyrics-to-Audio Alignment Task in Music Information Retreval Evaluation eXchange International Benchmarking Competition 2020.
- *2020* **Ranked first** in Automatic Lyrics Transcription Task in Music Information Retreval Evaluation eXchange International Benchmarking Competition 2020.
- *2019* **Best Poster Award Runner Up Prize**, “Speech-to-Singing Conversion and Synthesis” at 4th Workshop for Young Female Researchers in INTERSPEECH, Graz, Austria.
- *2019* **ISCA Grants**,“Average Modeling for Spectral Mapping in Speech-to-Singing Conversion” at 2019 Speech Processing Courses in Crete Conversational Speech Synthesis: from design to evaluation, University of Crete, Heraklion Crete, Greece.
- *2016* **Meritorious Winner** (Top 8% winner), American Mathematical Contest in Modeling.
- *2015* **National Second Prize**, National Undergraduate Electronic Design Contest.




# 💬 Talks
- *2022.08*, Automatic Lyrics Transcription of Polyphonic Music, National Institute of Informatics, Japan.
- *2022.06*, Music-robust Automatic Lyrics Transcription of Polyphonic Music, SMC 2022, France (virtual).
- *2022.05*, Genre-conditioned Acoustic Models for Automatic Lyrics Transcription of Polyphonic Music, ICASSP, Singapore.
- *2019.11*, Speaker-independent Spectral Mapping for Speech-to-Singing Conversion, IEEE APSIPA ASC, Lanzhou, China.
- *2018.10*, NUS-HLT Spoken Lyrics and Singing (SLS) Corpus, IEEE ICOT, Bali, Indonesia.



# 💻 Internships and Summer School
- *2022.07 - 2022.08*, National Institute of Informatics, Japan.
- *2019.07*, Research Scholar at the Speech Processing Courses Summer School, University of Crete, Heraklion Crete, Greece.

