# [Dialectal and low-resource speech translation: Bhojpuri to Hindi@IWSLT2025](https://iwslt.org/2025/low-resource)

# Introduction

Bhojpuri belongs to the Indo-Aryan language group which has the ISO code ``bho``. It is dominantly spoken in India’s western part of Bihar, the north-western part of Jharkhand, and the Purvanchal region of Uttar Pradesh. As per the 2011 Census of India, it has around 50.58 million speakers. Bhojpuri is spoken not just in India but also in other countries such as Nepal, Trinidad, Mauritius, Guyana, Suriname, and Fiji. Since Bhojpuri was considered a dialect of Hindi for a long time, it did not attract much attention from linguists and hence remains among the many lesser-known and less-resourced languages of India.

IWSLT participants may obtain the [Bhojpuri-Hindi speech translation data](https://github.com/panlingua/iwslt2025_bho-hi) without any cost. This corpus consists of 23 hours of audio speech data from the [news domain](https://newsonair.gov.in/) and stories and the translations into Hindi text.

## Structure of the ` Shared Task data`:
```
iwslt2025_bho-hi/
├─ iwslt2024_bho-hi/
│  	├─ train/
│     	    └─ stamped.tsv
│     	    └─ txt/
│        	└─ train.hi
│     	    └─ wav/
│  	├─ dev/
│     	    └─ stamped.tsv
│     	    └─ txt/
│               └─ dev.hi
│           └─ wav/
│  	├─ test/
│     	    └─ stamped.tsv
│     	    └─ wav/ 
├─ test/
├─ LICENSE.md
├─ README.md
   
```
**The data statistics are presented below:
-----------------------------------------------------
```
│ Language	        | Total_audios ( Total_Hours) | Total_translated_Sentences/   │
│                       │                             │    Total_translated_Segements │ 
│ Bhojpuri-Hindi (train) │      10171 (approx 19.88)  │          10171                 │
│ Bhojpuri-Hindi (dev)   │      1056 (approx 2.07)    │          1056                  │
│ Bhojpuri-Hindi (test-2024)  │      693 (approx  0.82)    │  -                              │
```
<p>We point participants to additional Bhojpuri audio data (with transcriptions), parallel and monolingual corpora from here:</p>

<ul>
  <li><a href="https://github.com/Open-Speech-EkStep/ULCA-asr-dataset-corpus">ULCA-asr-dataset-corpus</a></li>
  <li><a href="https://github.com/Open-Speech-EkStep/vakyansh-models#wav2vec2-based-models">Bhojpuri-wav2vec2 based model</a></li>
  <li><a href="https://github.com/shashwatup9k/bho-resources">Bhojpuri Language Technological Resources (BHLTR)</a></li>
</ul>

* NB: If you use [this dataset](https://storage.googleapis.com/test_public_bucket/external/labelled/Bhojpuri_newsonair_aligned_external_1_08-03-2022_07-36.zip) for your experiment, you may exclude [the following audio files](https://drive.google.com/file/d/1lGOwJ3B3ZJx3ehYEWck9Atx3cSwMpfbQ/view?usp=drive_link) from the dataset due to overlap.

# License
Please see the [LICENSE](https://github.com/panlingua/iwslt2025_bho-hi/blob/main/LICENSE.md) file.

# Acknowledgments
We would like to thank [Panlingua Language Processing LLP](http://panlingua.co.in/) for providing Bhojpuri-Hindi speech translation data. We would also like to thank [Science Foundation Ireland (SFI)](https://www.sfi.ie/) [(grant number SFI/12/RC/2289_ P2 Insight _ 2)](https://www.insight-centre.org/) 

## References
<pre>
@inproceedings{ahmad-etal-2024-findings,
    title = "{FINDINGS} {OF} {THE} {IWSLT} 2024 {EVALUATION} {CAMPAIGN}",
    author = {Ahmad, Ibrahim Said  and
      Anastasopoulos, Antonios  and
      Bojar, Ond{\v{r}}ej  and
      Borg, Claudia  and
      Carpuat, Marine  and
      Cattoni, Roldano  and
      Cettolo, Mauro  and
      Chen, William  and
      Dong, Qianqian  and
      Federico, Marcello  and
      Haddow, Barry  and
      Javorsk{\'y}, D{\'a}vid  and
      Krubi{\'n}ski, Mateusz  and
      Kim Lam, Tsz  and
      Ma, Xutai  and
      Mathur, Prashant  and
      Matusov, Evgeny  and
      Maurya, Chandresh  and
      McCrae, John  and
      Murray, Kenton  and
      Nakamura, Satoshi  and
      Negri, Matteo  and
      Niehues, Jan  and
      Niu, Xing  and
      Ojha, Atul Kr.  and
      Ortega, John  and
      Papi, Sara  and
      Pol{\'a}k, Peter  and
      Posp{\'\i}{\v{s}}il, Adam  and
      Pecina, Pavel  and
      Salesky, Elizabeth  and
      Sethiya, Nivedita  and
      Sarkar, Balaram  and
      Shi, Jiatong  and
      Sikasote, Claytone  and
      Sperber, Matthias  and
      St{\"u}ker, Sebastian  and
      Sudoh, Katsuhito  and
      Thompson, Brian  and
      Waibel, Alex  and
      Watanabe, Shinji  and
      Wilken, Patrick  and
      Zem{\'a}nek, Petr  and
      Zevallos, Rodolfo},
    editor = "Salesky, Elizabeth  and
      Federico, Marcello  and
      Carpuat, Marine",
    booktitle = "Proceedings of the 21st International Conference on Spoken Language Translation (IWSLT 2024)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand (in-person and online)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.iwslt-1.1",
    pages = "1--59",
    abstract = "This paper reports on the shared tasks organized by the 21st IWSLT Conference. The shared tasks address 7 scientific challenges in spoken language translation: simultaneous and offline translation, automatic subtitling and dubbing, speech-to-speech translation, dialect and low-resource speech translation, and Indic languages. The shared tasks attracted 17 teams whose submissions are documented in 27 system papers. The growing interest towards spoken language translation is also witnessed by the constantly increasing number of shared task organizers and contributors to the overview paper, almost evenly distributed across industry and academia.",
}
</pre>
<pre>
=== Machine-readable metadata (DO NOT REMOVE!) =====================================================
Data available since: Bhojpuri-Hindi Speech Translation Shared Task@IWSLT-2025
License: CC BY-NC-SA 4.0
=======
Includes text/audio: yes
Shared Task Organisers: Ojha, Atul Kr.; McCrae, John P.
Contact: atulkumar.ojha@insight-centre.org or shashwatup9k@gmail.com, info@panlingua.co.in
Contributor/&copy;holder: Panlingua Languague Processing LLP, India and Insight Centre for Data Analytics, Data Science Institue, University of Galway, Ireland
=======================================================================================================
</pre>

