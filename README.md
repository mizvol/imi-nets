# Fake news in social media. Network perspective
IMI project studying fake news exposure in Switzerland (in French, German, and Italian).

In this project, we focus on the networks to understand how fake news are spreaded. We study user networks and filter bubbles (the effect when users are trapped in a community (like in a bubble), which prevents them from being exposed to alternative opinions). 

You can click on the links below to explore the network view of the data we extracted from social media.

## 1. Twitter
Here, we extract networks of Twitter accounts spreading information about controvercial topics. 

* [General controvercial topics](https://mizvol.github.io/imi-nets/network/)
* [Conspiracy](https://mizvol.github.io/imi-nets/network-twitter-conspiracy)

## 2. Youtube*
Here, we study various Youtube networks. We have two lists of videos. One contains videos about controvercial topics. We call them sources of information. The other has videos that were identified as fake by an expert. 

First, we extract networks of **videos, users, and channels**. Two **videos** are connected if Youtube recommends watching one video after another. Two **channels** are connected if they feature each other or share a video. Two **users** are connected if they interact in the comment section.

### 2.1 Sources of information

#### 2.1.2 Climate change
<details><summary>Seed videos</summary>
  [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/R6eywXdssMw/0.jpg)](https://www.youtube.com/watch?v=R6eywXdssMw)
https://www.youtube.com/watch?v=R6eywXdssMw
https://www.youtube.com/watch?v=T4LVXCCmIKA
https://www.youtube.com/watch?v=iK3G8wqqp_k
https://www.youtube.com/watch?v=K01MnnOV-u4
https://www.youtube.com/watch?v=szho74EKGiM
https://www.youtube.com/watch?v=q3DM5TZ3FG4
https://www.youtube.com/watch?v=tPjHLRYZiHM
https://www.youtube.com/watch?v=OQBcrKqyHJI
https://www.youtube.com/watch?v=eytaVwARSmU
https://www.youtube.com/watch?v=TpbZYwH0X90
https://www.youtube.com/watch?v=KGdVCs5E8vE
https://www.youtube.com/watch?v=YX_RW5iYJcQ
https://www.youtube.com/watch?v=PLeVCOn7khk
https://www.youtube.com/watch?v=fS5HhcbyjKc
https://www.youtube.com/watch?v=W9ktHsL_dzE
https://www.youtube.com/watch?v=zBLTDscToOo
</details>

* [Video recommendation network](https://mizvol.github.io/imi-nets/youtube/youtube-diffuseurs-climate/)
* [Featured channels network](https://mizvol.github.io/imi-nets/youtube/youtube-channels-diffuseurs-climate/)
* [Users comment network](https://mizvol.github.io/imi-nets/youtube/youtube-users-comments-climate-sources/index.html)


### 2.2 Potential fake news channels

#### 2.2.2 Climate change. Fake news
<details><summary>Seed videos</summary>
https://www.youtube.com/watch?v=zBLTDscToOo
https://www.youtube.com/watch?v=I-Du-AqQTQU
https://www.youtube.com/watch?v=y3MYKWEPnus
https://www.youtube.com/watch?v=QppDqoF-ixk
https://www.youtube.com/watch?v=IkiI7wkm33Q
</details>

* [Video recommendation network](https://mizvol.github.io/imi-nets/youtube/youtube-videos-climate-fake/)
* [Featured channels network](https://mizvol.github.io/imi-nets/youtube/youtube-channels-climate-fake/)
* [Users comment network](https://mizvol.github.io/imi-nets/youtube/youtube-users-comments-climate-fake/)

#### 2.2.1 Chemtrails. Fake news
These videos are not very popular, so very few users comment on them. Therefore, the network is very small and doesn't bring any interesting insights. We don't extract users network for this topic.

<details><summary>Seed videos</summary>
https://www.youtube.com/watch?v=EdLHtJzxCQE
https://www.youtube.com/watch?v=4DmcsETVzKs
https://www.youtube.com/watch?v=IeXL--VBlYw
https://www.youtube.com/watch?v=0R-C3O4OwhY
https://www.youtube.com/watch?v=8MzshxsVxUg
https://www.youtube.com/watch?v=quWrSkTCEvc
https://www.youtube.com/watch?v=Q7BzNBfX3fU
https://www.youtube.com/watch?v=UOhJt72t7YI
https://www.youtube.com/watch?v=9hAULB7Qsac
</details>

* [Video recommendation network](https://mizvol.github.io/imi-nets/youtube/youtube-videos-haarp/)
* [Featured channels network](https://mizvol.github.io/imi-nets/youtube/youtube-channels-haarp/)

**Youtube data is collected using [Youtube Data Tools](https://github.com/bernorieder/YouTube-Data-Tools) by [Bernhard Rieder](http://thepoliticsofsystems.net/about/)*
